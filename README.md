
# 🖼️ Projeto de Processamento de Imagens em C

Este projeto foi desenvolvido como parte das atividades da disciplina de Laboratório de Computação na Universidade Federal do Maranhão (UFMA), sob orientação do Prof. Dr. Thales Levi Azevedo Valente.

## ✅ O que o projeto faz

Este programa realiza **processamento de imagens** em C, permitindo aplicar os seguintes filtros:

- 🌓 **Negativo**  
- ⚫ **Escala de Cinza**  
- 🌫️ **Blur (Desfoque)**  
- 🧭 **Sobel (Detecção de Bordas)**  

A imagem original é carregada a partir do disco, processada conforme a opção do usuário, e uma nova imagem com o filtro aplicado é salva automaticamente.

## 💡 Por que o projeto é útil

Este projeto é útil como **material didático** para estudantes de engenharia da computação que desejam aprender:

- Manipulação de imagens com C
- Uso de ponteiros e arrays unidimensionais para percorrer pixels
- Implementação prática de filtros clássicos de visão computacional
- Manipulação de bibliotecas externas (`stb_image` e `stb_image_write`)

## 🚀 Como começar a usar o projeto

1. **Prepare o ambiente**:
   - Um compilador C (como GCC)
   - A biblioteca `stb_image.h` e `stb_image_write.h` (já incluídas)

2. **Compile o código**:
   ```bash
   gcc nome_arquivo.c -o processamento -lm
   ```

3. **Edite o caminho da imagem** dentro do código:
   ```c
   char inputFile[100] = "C:\caminho\para\sua\imagem.jpg";
   ```

4. **Execute o programa**:
   ```bash
   ./processamento
   ```

6. **Escolha o filtro** desejado no menu interativo.

- 👨‍💻 **Pedro Luís de Souza**
- 👨‍🏫 **Orientador:** Prof. Dr. Thales Levi Azevedo Valente — UFMA
