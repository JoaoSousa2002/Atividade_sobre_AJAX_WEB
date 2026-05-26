# Pesquisa AJAX
### Aluno: João Victor Sousa da Conceição

AJAX é uma técnica de desenvolvimento WEB onde um app WEB faz requisições HTTP de forma assíncrona, ou seja, atualizar uma parte da pagina sem precisar recarregar a pagina inteira

Tipos de requisição WEB:

- **Síncrono:** Eventos ocorrem ao mesmo tempo
- **Assíncrono**: Eventos ocorrem em tempos diferentes

Os metodos de AJAX são **XmlHttpRequest**, **fetch**, **Promises** e **async/await**

## XmlHttprequest

O XmlHttpRequest é o metodo mais antigo de requisição assincrona em HTTP, é um metodo bem mais verboso que os outros, sendo bastante problematico em requisições aninhadas alem de não retornar promisse nativamente.

## Promisses

Promisses são objetos que representam a conclusao ou falha de uma requisição assincrona, sendo a base dos metodos Fetch() e Async/Await

## Fetch API

Fetch API É uma evolução mais forte e flexível do XmlHttpRequest, por ser mais simples por exigir menos linhas, melhor tratamento de erro e baseado em promisses

## Async/Await

Async/Await tem uma sintaxe que permite escrever código assíncrono com aparência síncrona. Toda função async retorna uma Promise. O await pausa a execução da função até a Promise resolver, usando o try/catch

# Desempenho

| Metodo         | Desempenho                                                        | Facilidade                                                                 |
|-----------------|-------------------------------------------------------------------|------------------------------------------------------------------------------|
| XmlHttpRequest  | Muito rapido, Media de 3ms em 10 requisições                    | Dificil, Muito verboso e exige uma pesquisa maior                           |
| Async/Await     | Muito rapido, quase impercepitivel Media 190ms (10 requisições) | Facil                                                                       |
| Fetch           | Muito rapido, Media de 2ms em 10 requisições                    | Muito facil                                                                 |
| promisses       | x                                                                 | Não foi possivel usar o objeto promisses puro, sempre leva ao fetch() ou async/await |
