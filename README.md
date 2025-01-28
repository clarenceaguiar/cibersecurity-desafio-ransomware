# Desafio Ransomware do curso de Cybersecurity do Santander com a DIO

Na pasta [arquivos_desafio_ransomware](./arquivos_desafio_ransomware/) se encontram os arquivos criados para resolução do desafio testado via terminal do Kali Linux, seguindo os comandos abaixo.

No diretório onde se encontram os arquivos:

| **Comandos** | **Objetivo** |
|:---: |:---: |
| ls | listar os arquivos do diretório |
| nano teste.txt | visualizar o conteúdo do arquivo não criptografado |
| python encripter.py | criptografar o arquivo `teste.txt` |
| ls | listar novamente os arquivos verificando que o arquivo `teste.txt` se tornou o arquivo `teste.txt.ransomwaretroll` |
| nano teste.txt.ransomwaretroll | visualizar o conteúdo do arquivo criptografado |
| python decrypter.py | descriptografar o arquivo `teste.txt.ransomwaretroll` |
| ls | listar mais uma vez os arquivos verificando que o arquivo `teste.txt.ransomwaretroll` se tornou novamente o arquivo `teste.txt` |
| nano teste.txt | visualizar o conteúdo do arquivo descriptografado |