# HTML Tag Escaper

Este é um programa simples em Node.js para escapar caracteres especiais HTML em um arquivo de texto.

## Funcionalidades

- **escapeHtmlFile(inputFilePath, outputFilePath)**: Esta função recebe o caminho do arquivo de entrada e o caminho do arquivo de saída. Ela lê o conteúdo do arquivo de entrada, escapa os caracteres especiais HTML e escreve o conteúdo escapado no arquivo de saída.

- **espaceHtmlSpecialCharacters(text)**: Esta função recebe um texto como entrada e escapa os caracteres especiais HTML, como `<`, `>`, e `&`.

- **askFilePath(question)**: Esta função solicita ao usuário o caminho de um arquivo.

- **userInteraction()**: Esta função lida com a interação do usuário. Se nenhum argumento for passado na linha de comando, ele solicitará os caminhos do arquivo de entrada e saída ao usuário. 

- **run()**: Esta função verifica se os argumentos foram passados na linha de comando. Se sim, executa a função `escapeHtmlFile()` com os caminhos fornecidos. Caso contrário, solicita a interação do usuário para fornecer os caminhos dos arquivos.

## Utilização

Para utilizar este programa, execute-o a partir da linha de comando, fornecendo os caminhos dos arquivos de entrada e saída: node html-escaper.js <caminho_do_arquivo_de_entrada> <caminho_do_arquivo_de_saída>


Se nenhum argumento for fornecido, o programa solicitará os caminhos dos arquivos interativamente.

## Exemplo

node html-escaper.js input.txt output.txt


