// Função para a contagem de palavras em uma frase
func contarPalavras(texto: String) -> Int {

  // Divide a string de entrada 'texto' em substrings,
  // usando " " como delimitador e armazena em 'palavras'.
  let palavras = texto.split(separator: " ")

  // Retorna o número de palavras (subtrings) presentes no texto.
  return palavras.count
}

// Solicita ao usuário que digite a frase
print("Digite a frase que você quer usar: ")

// readLine() retorna uma string opcional,
// ou seja, se o usuário não digitar nada ou pressionar Enter,
// o readLine() retornará um nil e o operador ?? fornece uma string vazia ("") como valor padrão.
// Isso garante que textoContar sempre tenha um valor válido.
let textoContar = readLine() ?? "" // Lê a entrada do usuário.

// Chama a função usando 'textoContar' como argumento e 
// armazena o total de palavras na constante.
let totalPalavras = contarPalavras(texto: textoContar)

print("Total de palavras: \(totalPalavras).")
