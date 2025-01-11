# Descriptografar arquivo
Objetivo é descriptograr um arquivo para o arquivo se tornar legivel novamente.

### Ferramentas utilizadas:

- Kali Linux (https://www.kali.org/)
- Linguagem Python (https://www.python.org/)
- NANO (neste exemplo usaremos o NANO para construir e executar o código, mas podem usarem outras ferramentas como myCompiler, CMD etc. Já tem instalado no Kali) (https://medium.com/@habbema/tutorial-do-nano-3e6aec905213)

### Pontos Importantes:
 - Para descriptograr arquivo, precisa usar o mesmo padrão de criptor. Esse documento continuação do material: https://github.com/WanderBernardo/Python_Encrypt_File
 - Código construido aqui é um simples, pode ser melhorado automatizando a localização do arquivo, por exemplo.
 - Caso ao executar o codigo apresente o erro "ModuloNotFoundError: No modulo named 'pyaes'". Então, deve instalar a biblioteca: ``` pyaes ```.
   
       - sudo apt-get update && sudo apt-get upgrade
   
       - sudo apt install python3-pyaes

### Resumo:

 - Acesso o Terminal Emulator (CMD)
 - Iniciar NANO: nano
 - Construir o código para abrir o arquivo criptografado
 - Construir o código para chave de descriptografar
 - Construir o código para remover o arquivo criptografado
 - Construir o código para criar o arquivo descriptografado

### Detalhamento:

01 - Acesso o Terminal Emulator (CMD):
![image](https://github.com/user-attachments/assets/e8537deb-7a38-4b89-8e8e-60e1cfce7d2a)

02 - Para acessar o NANO apenas digitar ``` nano ``` na tela
![image](https://github.com/user-attachments/assets/2d647809-8d8a-4d24-9228-7febcd4cd626)

03 - Antes de iniciar a digitar o código precisamos importar duas bibliotecas para o codigo:

 - os    - é um conjunto de funções que permite interagir com o sistema operacional na maquina.
 
 - pyaes - é o algoritmo que será usado para cryptograr

Antes de iniciar a construir o código criei o arquivo com a instensão ``` .py ``` 

![image](https://github.com/user-attachments/assets/bd382476-db3f-409f-84e5-c5d626d3fafb)

04 - Construir o código para abrir o arquivo criptografado

![image](https://github.com/user-attachments/assets/c7e2eec0-09ab-4560-b9e1-be08b6ae2145)

05 - Construir o código para chave de descriptografar

![image](https://github.com/user-attachments/assets/5a0daaaf-250c-4841-b292-a6efe3841a9d)

06 - Construir o código para remover o arquivo criptografado

![image](https://github.com/user-attachments/assets/ada6d959-8352-4a11-a968-48517b928b73)

07 - Construir o código para criar o arquivo descriptografado

![image](https://github.com/user-attachments/assets/7cfa0037-10ad-41ee-bb45-fd4c543d963d)

08 - Salvar o código digitando: ``` Ctrl + o ``` para salvar e ``` Ctrl + x ``` para sair do editor de texto NANO. Para executar digite na tela de comando: ``` python nome do arquivo do codigo criado```, no nosso exemplo: codigo_encrypto.py

### Resultado

``` Antes ```

![image](https://github.com/user-attachments/assets/60904200-e1fe-4da2-b7e9-b1f106250b51)

``` Depois ```

![image](https://github.com/user-attachments/assets/4cc11580-2540-44a8-8677-10d7f6f5eff5)

### Arquivo com o código construindo no anexo: "decryter"






