# Introduction

<!-- TODO -->
Programa para contar a quantidade de linhas de comentários, linhas vazias e linhas de código de um arquivo do tipo C/C++/H/HPP. O programa recebe um diretório ou um único arquivo e exibe os dados daquele diretório/arquivo. Se executado com um diretório, também é apresentada uma soma de todos os arquivos analisados.

# Author(s)

<!-- TODO -->

William Campos Silva - camposwilliam23@gmail.com
Carlos Eduardo Miranda da Silva - cems2002@outlook.com

# Compiling and Runnig

<!-- TODO -->
Compilador utilizado: MinGW

Para compilar, se dirigir até o diretório com o arquivo e executar:

g++ -o sloc sloc.cpp

Para executar (ainda dentro do diretório):

sloc caminho-do-diretório/arquivo

Exemplo: C:\Users\Carlos\Desktop\programas\Estudo\C++\projeto_SLOC  // para executar o programa em um diretório

         C:\Users\Carlos\Desktop\programas\Estudo\C++\projeto_SLOC\exemplo.cpp  // para executar o programa em um único arquivo
