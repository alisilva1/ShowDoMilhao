# ShowDoMilhao

# Desafio Java - REST API - Movie Challenge

### Épico: 

> A CHALLENGE INC é uma empresa responsável por criar aplicativos de mídia e está estudando desenvolver um novo aplicativo para que seus usuários possam trocar informações sobre os filmes que assistiram e sobre os que ainda desejam assistir. A idéia é obter informações completa dos filmes de fontes públicas como o IMDB, porém sem comentários e sem spoilers. O usuário pode criar listas de desejos e sobre estas pode filtrar por gênero, ator, diretor e etc. Também será possível avaliar com notas de 5 a 10, aplicar 1 a 5 estrelas para os filmes e adicionar comentários. Ele pode adicionar, atualizar e remover sua nota, quantidade de estrelas e comentários, mas não pode repetir os mesmos comentários por filme. Ele pode escolher se sua avaliação será pública ou privada, o mesmo vale para suas listas. Ah! O legal é que ele pode criar grupos de discussão de qualquer tipo, por exemplo, para falar da atuação de um ator, de um cena ou etc. Esses grupos podem ser público ou privados, sendo privados é necessário passar a lista dos usuários que vão participar. Um outro recurso interessante é o "Me ajuda a assistir" que nada mais é que um usuário pedindo publicamente indicações de um filme, por exemplo, "me ajude a ver um bom filme sobre a viagem ao espaço", as pessoas podem apenas indicar filmes, compartilhando sua nota e estrelas, mas não pode comentar _(para evitar spolier, claro!)_ Bom! É isso! Mãos a obra, pois esta é apenas a versão beta. 


Escolha uma das API abaixo para obter informações do filmes:

- http://www.omdbapi.com/
- https://www.themoviedb.org/documentation/api

#### Atenção:

1. Atente para os itens obrigatórios do desafio e os diferenciais
2. Não utilize soluções low-code ou API Prontas. Você precisa construir do zero e em Java
3. Utilize qualquer framework e/ou bibliotecas de sua peferência
2. Não precisa enviar Pull Request para a master ou expor a API Publicamente. Apenas documente em MD como executar e no Swagger o que cada operação fornece
3. Não crie frontend, você será avaliado apenas pelos recursos e operações da sua API
4. Realize quantos commits for necessário na sua branch e sinalize ao responsável pela sua avaliação qual o commit que dá o desafio como pronto
5. **Entregue o desafio em uma branch deste repositório. Não mova o desafio para um novo repositório pessoal**

#### Sobre a pontuação:

Para ser aprovado é necessário atingir a **pontuação mínima de 7 pontos** de um total de 10 pontos composto por: 
- **7,5** = Soma das notas máximas dos itens obrigatórios
- **1** = Tirar nota maior que zero em todos os itens obrigatórios 
- **1,5** = Cobrir todos os requisitos do épico

Além disso os **itens diferenciais para o desafio** possibilita ao candidato obter mais pontos e pode ajudar a compensar algum item obrigatório que não foi bem implementado. Por isso é importante considerá-los mesmo não sendo obrigatórios. Fica a dica! :)


### Obrigatório para o desafio _(Isso bem aplicado te aprova)_:


| Item  | Descrição| Peso  | Pontuação |
| ----- | -------- | ----- | --------- |
1  | Criar testes unitário para o seu código (Mínimo de 80% de cobertura) | 1 | 2 |
2  | Documentar API, respeitando o OpenAPI + Swagger | 1 | 2 |
3  | Criar markdown (MD) na branch, explicando como executar e testar a API | 0,5 | 1 |
4  | Utilizar um banco de dados de sua preferência. Qualquer tipo (SQL ou NoSQL) | 0,75 | 1 |
5  | Consumir a API TMDb ou OMDb para obter informações dos filmes _(URLs acima)_ | 1 | 1,5 |
6  | Aplicar as validações e regras de negócio para que sua API seja consistente | 0,75 | 1 |

### Diferenciais para o desafio _(Isso bem aplicado te coloca a frente de outros candidados)_:

| Item  | Descrição| Pontuação |
| ----- | -------- | ----- | 
1 | Aplicar todos os princípios do S.O.L.I.D e explicar em comentários no código onde se aplicam | 1 | 
2 | Criar um teste de contrato com Postman ou outro | 0,5 |
3 | Fornecer algum recurso da API que vá além dos básico para atendimento do desafio | 0,5 |
4 | Aplicar cache para sua API | 0,75 |
5 | Utilizar Docker e/ou Docker Compose | 1 | 
6 | Proteger a API com algum método de autenticação e/ou autorização. Pode ser apenas um API Key! | 0,75 |

### **ATENÇÃO: Será considerado o COMO implementa a solução. O simples fato de implementar não garante a pontuação total. Portanto, neste desafio será avaliado o seu grau de conhecimento em:

- GIT
- Solução aplicada
- Codificação em Java EE 
- Criação, documentação e Best Practice em APIs REST
- POO, Best Practice, Design Patterns e S.O.L.I.D principles aplicado em Java


**Boa sorte e lembre-se: DRY, YAGNI e KISS!**
