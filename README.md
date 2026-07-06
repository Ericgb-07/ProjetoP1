# Análise de Coleção Pessoal (filmes, livros, músicas e derivados):
Grupo composto por Eric Gabriel, Emanuel Victor e Dayan Lucas

---

## 💻 Sobre o Projeto

Escolhemos um dos projetos sugeridos pelo professor, que consiste em um sistema interativo feito em Python para 
gerenciamento de um catálogo pessoal de entreterimento, utilizando persistência de dados local com arquivos JSON.
O sistema permite que o usuário gerencie seus filmes, livros, músicas e séries favoritas através de 
um menu interativo no terminal. Podendo, com isso, buscar as mídias já selecionadas e adicionar mídias novas, 
com os seus respectivios anos de lançamento, nota, gênero etc.

---

## ✨ Funcionalidades

O sistema conta com as seguintes opções:

1. Cadastrar: Adiciona novos itens validando a categoria (`Livro`, `Filme`, `Música`, `Série`),
aplicando formatação automática nos textos (Iniciais Maiúsculas) e salvando o ano de lançamento com suas notas.
2. Buscar: Permite pesquisar no catálogo utilizando 4 filtros diferentes:
   - Por Categoria;
   - Por Gênero;
   - Por Ano;
   - Por Nome.
3. Editar: Lista todos os itens cadastrados e possibilita a alteração completa de qualquer registro selecionado.
4. Apagar: Remove permanentemente um item do catálogo através da seleção do seu índice.
5. Sair: Encerra o programa com segurança.

---

## 🛠 Tecnologias Utilizadas

- Linguagem: Python.
- Biblioteca Nativa: `json` 
- Formatação de Arquivos: JSON (JavaScript Object Notation)

---

## 📂 Estrutura de Arquivos

O projeto necessita de apenas dois arquivos principais para rodar na mesma pasta:

```text
├── main.py          # Código-fonte principal com toda a lógica do menu e funções
└── catalogo.json    # Arquivo gerado automaticamente para salvar os dados salvos