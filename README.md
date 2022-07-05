# Projeto upskCGD 
### Preparação estágio NTTDATA

## Indíce

1. [Objetivos](#Objetivos)
2. [Tecnologias](#Tecnologias)
3. [Descrição](#Descrição)


## Objetivos

Utilizar todas as tecnologias presentes nas ferramentas de formação disponibilizadas pela NTT DATA num único projeto em grupo para consolidar conceitos e praticar. O projeto irá consistir em desevolver uma webapp que diponibiliza serviços SOAP e consome serviços REST do petAPI. A webapp vai servir de intermediário e o objeto é abstrair o utilizar da "complexidade" da comunicação com o servidor do petAPI.

## Tecnologias 

Tecnologias ou frameworks com que ambicionamos trabalhar neste projeto.

1. Java 1.8
2. Spring Web
3. ThymeLeaf
4. JPA Repositories
5. H2 Database
6. JavaScript
7. HTML
8. CSS
9. Jquery
10. REST
11. SOAP

## Descrição

A webapp vai correr localmente. Vai ter três url aceites: 

"/" - index <br />
"/criar" - criação de pets <br />
"/consulta" - consulta e edição de pets conhecidos <br />

Os id's dos pets criado dentro da aplicação vão se guardados na H2 Database, sempre que for necessário construir os pets ou ler id's é preciso aceder à base de dados, nunca guardamos os Pet criados, em contrapartida as Category e Tag criada vão ter que estar gravadas em memória. 

Index - vai apresentar dados estatiscos, por exemplo: nome mais comum, categoria mais comum, etc

Criar - menu de criação de pets, categories e tags

Consulta - permite a consulta e edição dos pets, categories e tags selecionados

(...)
