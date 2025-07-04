
# 🎓 Aulas de modelagem de banco de dados

Este repositório guarda todos os exercícios realizados na disciplina de modelagem de banco de dados, dentro do curso superior de Desenvolvimento de Software Multiplataforma da Fatec de Registro-SP, com o professor Wagner Toth.

As aulas tinham como objetivo o aprendizado de fundamentos sobre modelagem de dados para bancos relacionais.

## 🗃 Como visualizar?
Cada arquivo de extensão *.brM3* é uma atividade diferente desenvolvida na ferramenta brModelo. Todas as atividades são modelagens de dados conceituais ou lógicas. 

Aqui vai um passo a passo para visualizar as atividades, do mesmo modo que foi realizado em aula:

1. Baixe este repositório.
2. Instale o brModelo. Você pode usar [este](https://sourceforge.net/projects/brmodelo/) link.
3. Para visualizar a atividade, você pode abrir o brModelo e selecionar a opção *Arquivo>Abrir* ou CTRL + A e então localizar o arquivo de extensão *.brM3* dentro do repositório baixado.

## 🎲 O que é modelagem de dados?
Dentro da computação, a área de dados é extremamente importante para o funcionamento de sistemas complexos e extensos. Por exemplo, as informações geradas na Internet são dados que precisam ser armazenados em algum lugar. 

Os bancos de dados são sistemas que armazenam essas informações de diferentes formas. Os bancos de dados precisam ser planejados corretamente antes de serem construídos e utilizados, e esse planejamento é chamado de "modelagem de dados".

A modelagem de bancos de dados relacionais geralmente passa por 3 etapas:

1. 🔲 **Modelo conceitual** : diagramação básica das entidades e dos relacionamentos que participam do banco de dados através de uma seleção de símbolos e figuras.
2. 📅 **Modelo lógico** : conversão do modelo conceitual para representação em tabelas, contendo  tipo e tamanho dos campos de dados.
3. 🗃 **Modelo físico** : implementação do modelo lógico através de código SQL, ou seja, a criação do banco de dados em si.

## ↔️ O que é banco de dados relacional?
Bancos de dados podem ser relacionais ou não relacionais. Essa classificação refere-se à forma como o banco organiza informações. 

📅 Bancos de dados relacionais (também chamados de SQL) guardam dados em formato de tabelas que se relacionam. 

📄 Bancos de dados não relacionais (também chamados de NoSQL) guardam dados em outros formatos, como documentos e grafos. 

## 👇 Exemplo

*Aqui está um exemplo de como funciona o banco de dados relacional:*

**USUARIOS**

| id_usuario  | nome | email | senha | 
| ----------- | ----------- | ----------- | ----------- |
| 01      | Augusto       | augusto@gmail.com | 12345 |
| 02   | Paulo        | impaul@gmail.com | qwerty |
| 03   | Isabel       | isaa@gmail.com | aSx#42Qymz* |


Bancos relacionais usam uma estrutura de organização e relacionamento bastante rigorosa, a qual os torna ideais para dados estruturados e transações complexas. 

## O que é Modelo Entidade-Relacionamento?

Trata-se de um padrão para diagramação dos modelos de dados conceituais. O MER define quais as regras e os símbolos que devem ser usados para esse nível de modelagem.

Dentre os principais conceitos do MER, temos:
- Entidades são representadas por **retângulos**
- Atributos são representados por **elipses**
- Relacionamentos são representados por **losangos**
- **Cardinalidade** refere-se à quantidade de entidades num relacionamento
- **Chaves** são atributos que identificam entidades e garantem integridade referencial dos dados
- **Generalização/Especialização** referem-se aos processos de agrupar/dividir entidades (representa-se com **triângulos**)
- **Herança** é a capacidade de entidades especilizadas herdarem todos os atributos de uma entidade genérica 
- **Agregação** é a transformação de um relacionamento em uma entidade própria, chamada de associativa
- **Restrições** são regras aplicadas sobre os atributos, como as chaves

  ![image](https://github.com/user-attachments/assets/9fe07a8c-7cb3-4097-9565-aba4e0f3b828)

  ![image](https://github.com/user-attachments/assets/ac8a1c7e-a0dd-4640-8ff9-4cdcd2b766d9)

## ✏️ Meu aprendizado
1. História dos bancos de dados
2. Tipos de Sistemas de Gerenciamento de Banco de Dados (SGBDs)
3. Formatos e tipos de dados
4. Modelo Entidade-Relacionamento (MER)
5. Modelos de dados conceitual e lógico
6. Modelo Objeto Relacional (SBGDOO)
7. Álgebra Relacional
8. Normalização

## Tecnologias utilizadas

![brModelo](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjR9Ewc4I9y7jn__W5EQCiij1wA_z6sleRmiYHlbw8b00DanbBWadH3b4F3AophyqkwXAvw7RhpJI_c9158ZbRgY5JMwZkTjVXFf8DYvFFs4G9C7_nwDBZOknnm-x5357wvtCBNj4y54Me1/s1600/brmodelo3.png)

## 📃 Licença

- [MIT](https://choosealicense.com/licenses/mit/)

## 👤 Sobre mim
- 👤 Guilherme Shimada Pereira ([guilhermexmada](https://github.com/guilhermexmada))
- 🎓 Técnico em Desenvolvimento de Sistemas (2024)
- 🎓 Cursando Desenvolvimento de Software Multiplataforma (até 2027!) 
- 🚀 Rumo à Cibersegurança!

## 🔗 Referências

- brModelo: [sourceforge/brmodelo](https://sourceforge.net/projects/brmodelo/)
- Ícones das tecnologias: [tandpfun/skill-icons](https://github.com/tandpfun/skill-icons)
- Emojis: [piliapp/emoji](https://getemoji.com/)

