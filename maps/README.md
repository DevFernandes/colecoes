# ✔️ Desafio coleções sets e array

function getAdmins(map) {  -- Declara nome da função
    let admins = [];
    for([key, value] of map) {  ---- chave e valor
        if (value === 'Admin') {     --- Admin ( Somente os administradores )
            admins.push(key);   -- Push na key (Admin)
        }
    }
    return admins;   -- retorno ao push do valor
}   

const usuarios = new Map(); -- usuarios

usuarios.set('Luiz', 'Admin');
usuarios.set('Stephany', 'Admin');
usuarios.set('Jorge', 'User');
usuarios.set('Natália', 'Admin');

console.log(getAdmins(usuarios));   -- console log dos getadmins / usuarios

🗃️ Repositório feito para atividade prática
