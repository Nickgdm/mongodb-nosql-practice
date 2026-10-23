# Exercícios MongoDB — Consultas NoSQL

Projeto educacional para praticar consultas e operações de pesquisa no MongoDB usando conjuntos de dados de estudantes e professores.

## Objetivos
- Filtrar e ordenar documentos.
- Pesquisar valores com expressões regulares.
- Projetar campos específicos.
- Agrupar e contabilizar documentos com agregações.

## Tecnologias
- MongoDB
- JavaScript para consultas
- Arquivos JSON para dados de exemplo

## Pré-requisitos
- MongoDB instalado ou acesso a uma instância MongoDB.
- Mongo Shell (`mongosh`) ou ferramenta compatível.

## Como executar
1. Inicie ou acesse sua instância MongoDB.
2. Importe os arquivos JSON para coleções adequadas ou use-os como referência para inserir os documentos.
3. Abra `queries-mongodb.js` e execute as consultas no contexto do banco e das coleções esperadas.
4. Confira os resultados e adapte nomes de banco/coleção conforme a configuração local.

## Estrutura do projeto
```text
atividade-NoSQL/
├── estudantes.json
├── professores.json
├── queries-mongodb.js
└── README.md
```

## Desafios práticos
O exercício trabalha ordenação, filtros por curso, nota e cargo, pesquisa textual, seleção de campos e agregação para contabilizar estudantes por curso.

## Boas práticas adotadas
- Separação entre dados de exemplo e consultas.
- Uso de conjuntos JSON para facilitar a reprodução do exercício.
- Consultas organizadas por objetivo.

## 📚 Aprendizados
A atividade permitiu praticar consultas NoSQL com MongoDB, incluindo filtros, ordenação, expressões regulares, projeção de campos e pipelines de agregação. Também reforçou a importância de entender a estrutura dos documentos e validar os resultados das consultas.

## Considerações finais
Este repositório contém material de estudo. Os nomes do banco e das coleções devem corresponder ao contexto usado nas consultas durante a execução.

---

## 🎓 Formação
Atividade desenvolvida durante a formação profissionalizante em **Quality Assurance (QA) pela EBAC — Escola Britânica de Artes Criativas e Tecnologia**.