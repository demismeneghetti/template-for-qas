# Checklist de Atividades

## Problemas comuns

| **Item**                                                                         | **Para auto-revisão**    | **Para revisão do nomeado** |
| -------------------------------------------------------------------------------- | ------------------------ | --------------------------- |
| Os pacotes, namespaces e dependências estão em ordem?                            | <ul><li>- [x] </li></ul> | <ul><li>- [ ] </li></ul>    |
| A formatação e o estilo do código seguem os padrões da organização?              | <ul><li>- [x] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Você consegue entender o código sem que o codificador o explique?                | <ul><li>- [ ] </li></ul> | <ul><li>- [x] </li></ul>    |
| A alteração do código atinge o resultado desejado de forma simples e eficaz?     | <ul><li>- [ ] </li></ul> | <ul><li>- [x] </li></ul>    |
| Existem bons princípios de design de código que poderiam tornar o código melhor? | <ul><li>- [ ] </li></ul> | <ul><li>- [x] </li></ul>    |

<br/>

## Problemas de Performance

| **Item**                                                               | **Para auto-revisão**    | **Para revisão do nomeado** |
| ---------------------------------------------------------------------- | ------------------------ | --------------------------- |
| O novo código deve ter um perfil de desempenho?                        | <ul><li>- [x] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Existe algum código de registro ou depuração que deve ser removido?    | <ul><li>- [x] </li></ul> | <ul><li>- [ ] </li></ul>    |
| O cache é usado onde aplicável?                                        | <ul><li>- [ ] </li></ul> | <ul><li>- [x] </li></ul>    |
| A estrutura de dados correta está sendo usada para armazenar coleções? | <ul><li>- [ ] </li></ul> | <ul><li>- [x] </li></ul>    |

<br/>

## Problemas de Banco de Dados SQL

| **Item**                                                                     | **Para auto-revisão**    | **Para revisão do nomeado** |
| ---------------------------------------------------------------------------- | ------------------------ | --------------------------- |
| O tipo de dado mais eficiente é utilizado para os valores esperados?         | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| As consultas estão retornando dados desnecessários que podem ser eliminados? | <ul><li>- [ ] </li></ul> | <ul><li>- [x] </li></ul>    |
| Suas consultas estão protegidas em relação às injeções de SQL?               | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Uma procedure pode ser utilizada ao invés desse código?                      | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| A consulta SQL pode se beneficiar do tratamento de erros?                    | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| O desempenho pode ser melhorado pela indexação?                              | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |

<br/>

## Problemas de Segurança

| **Item**                                                                                             | **Para auto-revisão**    | **Para revisão do nomeado** |
| ---------------------------------------------------------------------------------------------------- | ------------------------ | --------------------------- |
| O código foi verificado em busca de secrets usando uma ferramenta apropriada?                        | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| As mensagens de erro fornecem muitas informações para invasores em potencial?                        | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| A entrada do usuário é validada?                                                                     | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Os dados do usuário, como senhas e informações de cartão de crédito, estão armazenados corretamente? | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| A autenticação e autorização são tratadas corretamente?                                              | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Os documentos XML são validados em relação a um esquema?                                             | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Os documentos JSON são validados em relação a um esquema?                                            | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |

<br/>

## Problemas com Testes

| **Item**                                                                             | **Para auto-revisão**    | **Para revisão do nomeado** |
| ------------------------------------------------------------------------------------ | ------------------------ | --------------------------- |
| Os testes estão bem documentados?                                                    | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Os testes cobrem todas as alterações do código?                                      | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Os testes realmente testam o que é suposto testar?                                   | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Os testes são isolados o suficiente para permitir encontrar facilmente os problemas? | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| A mudança no código afeta a maneira como os testes existentes funcionam?             | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Existem casos extremos que precisam ser cobertos?                                    | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |

<br/>

## Problemas de Legibilidade

| **Item**                                                                                               | **Para auto-revisão**    | **Para revisão do nomeado** |
| ------------------------------------------------------------------------------------------------------ | ------------------------ | --------------------------- |
| Variáveis, nomes de métodos ou classes podem ser renomeados para melhorar a legibilidade?              | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| A legibilidade do código pode ser melhorada dividindo os métodos em métodos menores?                   | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| É fácil acompanhar como as mudanças nos dados acontecem ao longo do tempo?                             | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Existem comentários desnecessários?                                                                    | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Um comentário deve explicar por que o código foi projetado da maneira que foi?                         | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Existe algum código comentado? Pode ser removido? Se não, há um comentário explicando por que está lá? | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |

<br/>

## Problemas no Tratamento de Erros

| **Item**                                                                    | **Para auto-revisão**    | **Para revisão do nomeado** |
| --------------------------------------------------------------------------- | ------------------------ | --------------------------- |
| Os erros cobrem adequadamente as situações esperadas?                       | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Existe um tratamento de erro geral para evitar uma falha completa?          | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Existem verificações de nulos quando apropriado?                            | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Os códigos de erro da web corretos são usados e interpretados?              | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| O usuário recebe mensagens de erro apropriadas, quando aplicável?           | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |
| Os erros são enviados aos usuários registrados com informações suficientes? | <ul><li>- [ ] </li></ul> | <ul><li>- [ ] </li></ul>    |

<br/>
