# ✔️ Desafio coleções sets

const meuArray = [30, 30, 40, 5, 223, 2049, 3034, 5]; -- Valores

function valoresUnicos(arr) {     Nome da função
    const mySet = new Set(arr);  Nome da constância

    return [...mySet];  -- Retorna o nome da constância 
}

console.log(valoresUnicos(meuArray));  -- Resultado da array // Apenas valores únicos sem repetir

🗃️ Repositório feito para atividade prática
