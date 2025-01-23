# 🖨️ Printf - Recriando a Função printf em C

![Printf](https://img.shields.io/badge/Language-C-blue) ![Makefile](https://img.shields.io/badge/Tool-Makefile-yellow) ![Norminette](https://img.shields.io/badge/Style-Norminette-green)

O projeto **Printf** desafia os estudantes a implementar sua própria versão da função `printf` da biblioteca padrão de C. Esse exercício é essencial para compreender o formato de saída, manipulação de parâmetros variáveis e conversão de tipos, preparando os alunos para projetos mais avançados.

---

## 📋 Objetivo do Projeto

🔹 Criar uma **implementação personalizada** da função `printf`.  
🔹 Aprofundar o entendimento sobre **manipulação de strings** e **saída formatada** em C.  
🔹 Trabalhar com conceitos avançados, como **descritores de arquivo** e **variáveis estáticas**.

---

## 📚 Conceitos Principais

- 🧵 **Manipulação de Strings**: formatação, análise e modificação de cadeias de caracteres.
- 🔄 **Conversão de Tipos**: lidar com diferentes tipos de dados e sua apresentação na saída.
- 📜 **Formato de Saída**: recriação de especificadores de formato (`%d`, `%s`, `%x`, etc.).
- 📂 **File Descriptors**: gerenciar saídas para diferentes descritores, como stdout e stderr.
- 📌 **Variáveis Estáticas**: armazenamento eficiente de dados persistentes durante a execução.

---

## 🛠️ Ferramentas e Padrões

| Ferramenta/Padrão      | Descrição                                               |
|-------------------------|-------------------------------------------------------|
| **GIT**                | Controle de versão para acompanhar o desenvolvimento do projeto. |
| **Makefile**           | Automação da compilação e gerenciamento de dependências. |
| **Norminette**         | Garantia de conformidade com os padrões de estilo da 42. |

---
## ✨ Funcionalidades Implementadas

A implementação personalizada do `ft_printf` inclui as seguintes funcionalidades:

### 🔤 Especificadores de Formato
- `%c` → Exibe um único caractere.  
- `%s` → Exibe uma string.  
- `%p` → Exibe um ponteiro no formato hexadecimal.  
- `%d` / `%i` → Exibe um número inteiro decimal com sinal.  
- `%u` → Exibe um número inteiro decimal sem sinal.  
- `%x` → Exibe um número hexadecimal em minúsculo.  
- `%X` → Exibe um número hexadecimal em maiúsculo.

### 🛠️ Funcionalidades Técnicas
- **Gerenciamento de Parâmetros Variáveis**: Uso de `stdarg.h` para manipular listas de argumentos de forma dinâmica com `va_list`.  
- **Saída Formatada**: Construção de strings personalizadas para diferentes especificadores de formato.  
- **Descritores de Arquivos (File Descriptors)**: Suporte para direcionar a saída para diferentes descritores, como `stdout` ou `stderr`.  
- **Manuseio de Erros**: Tratamento de erros em casos como ponteiros nulos ou argumentos inválidos.  
- **Eficiência na Saída**: Uso otimizado de buffers para melhorar a performance da saída formatada.

---

Estas funcionalidades foram cuidadosamente implementadas para refletir o comportamento do `printf` padrão, respeitando as limitações e especificações do projeto. 🚀
