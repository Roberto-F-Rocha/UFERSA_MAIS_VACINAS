# UFERSA-VACINA

## Visão Geral

O projeto UFERSA-VACINA é um sistema desenvolvido em C para gerenciar o cadastro de vacinas e o registro de aplicação de vacinas em pessoas. Ele permite operações como adicionar, remover, listar, buscar e editar informações de vacinas, além de registrar a aplicação de vacinas em indivíduos e consultar o quantitativo de pessoas vacinadas com uma determinada vacina.

## Funcionalidades

- **Gestão de Vacinas:**
  - Adicionar novas vacinas (nome, lote, data de fabricação, validade).
  - Remover vacinas existentes.
  - Listar todas as vacinas cadastradas.
  - Buscar vacinas por nome e lote.
  - Editar informações de vacinas cadastradas.

- **Gestão de Pessoas Vacinadas:**
  - Registrar a aplicação de vacinas em pessoas, incluindo nome, documento (CPF/RG), idade, nome da vacina, dose e data de aplicação.
  - Consultar o número de pessoas vacinadas com uma vacina específica.

## Estrutura do Projeto

- `main.c`: Contém a lógica principal do programa, o menu de interação com o usuário e a inicialização dos arquivos de dados (`entrada.txt` para vacinas e `entrada_pessoa.txt` para pessoas).
- `vacina.h`: Define as estruturas de dados para as vacinas e declara as funções relacionadas à gestão de vacinas e menus.
- `vacina.c`: Implementa as funções de gestão de vacinas declaradas em `vacina.h`.
- `pessoa.c`: Define as estruturas de dados para o registro de pessoas vacinadas e implementa as funções de aplicação e consulta de vacinas em pessoas.

## Como Compilar e Executar

Para compilar o projeto, utilize um compilador C (como GCC) e os seguintes comandos no terminal:

```bash
gcc main.c vacina.c pessoa.c -o ufersa-vacina
```

Após a compilação, execute o programa:

```bash
./ufersa-vacina
```

O sistema criará automaticamente os arquivos `entrada.txt` e `entrada_pessoa.txt` se eles não existirem, que serão usados para armazenar os dados das vacinas e das pessoas vacinadas, respectivamente.

## Desenvolvedores

- Roberto Fernandes Rocha
- Vinicius Anacleto de Almeida

## Professora

- Dra. Rosana Cibely Batista Rego

## Instituição

- Universidade Federal Rural do Semi-árido (UFERSA)
