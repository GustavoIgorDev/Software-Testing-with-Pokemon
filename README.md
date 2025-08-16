# 🚀 Testes de Software: A Jornada do QA para Capturar Todos os Bugs!

Olá! Seja bem vindo a este repositório onde falarei sobre os tipos de teste de software, mas falarei deles de uma forma diferente, tentei fazer referências a um universo que gosto muito, que é o de Pokémon. O objetivo é fazer qualquer um entender sobre o assunto, mas deixar ainda mais interessante para os entusiastas dos jogos e da obra Pokémon!

Deixando bem claro que comecei meus estudos na área de qualidade faz pouco tempo, então caso eu esteja errado sobre alguma informação ou você ache que faltou falar sobre algo, pode entrar em contato comigo no LinkedIn ou por aqui mesmo! ([🔗 Meu LinkedIn](https://www.linkedin.com/in/gustavo-silva-b2687727a))

Vamos falar dos tipos de testes como se fossem técnicas de treinamento para seu time de devs e QAs serem tão incríveis quanto um time de lendários no level 100!

## 🔍 Caixa Preta vs. Caixa Branca: O Duelo Pokémon!
**Caixa Preta (Black Box):** É como ser um treinador novato tentando descobrir o que um Pokémon desconhecido faz – testamos tudo o que for possível sem ver o código, só pelos resultados! (Feito geralmente pelo QA)

**Caixa Branca (White Box):** Aqui viramos algo como um professor Pokémon – analisamos o código diretamente pra ver se tá tudo certo, como se estivessemos estudando o DNA de um Pokémon novo. (Feito pelo Dev, mas as vezes pelo QA também)

*(Sim, tem a Caixa Cinza também, que é tipo um Ditto – junta os dois!)*

## 🎮 Os Tipos de Testes (e Quem É o Treinador Responsável)

### 1️⃣ Testes Unitários – O Treino Básico no Laboratório do Professor, quando enfrentamos Blue pela primeira vez!
**O que é?** Treinar um Pokémon de cada vez, ou seja, testar cada função do código separadamente.

**Tipo:** Caixa Branca (o Dev é o cientista que conhece todos os IVs).

**Quem faz?** Dev (usando ferramentas como JUnit e pytest).

### 2️⃣ Testes Funcionais – A Batalha no Ginásio Pokémon
**O que é?** Ver se o sistema faz o que prometeu, tipo quando você ensina um golpe novo ao seu Charizard e testa logo em seguida para ver se funciona exatamente como na descrição!

**Tipo:** Caixa Preta (o QA não precisa saber como o ataque é programado).

**Quem faz?** QA (com ataques especiais como Selenium e Cypres ou até mesmo manualmente                                    ).

### 3️⃣ Testes de Integração – A Equipe Rocket trabalhando em conjunto!
**O que é?** Será que o Meowth (front-end), Jessie (back-end) e James (banco de dados) conseguem fazer algo direito juntos? Ou seja, é basicamente quando testamos se o conjunto da obra funciona com tudo conectado.

**Tipo:** Caixa Cinza (meio dev, meio QA).

**Quem faz?** Dev ou QA (usando Postman por exemplo).

### 4️⃣ Testes Regressivos – O Zubat que Aparece em Toda Caverna
**O que é?** Sabe aquele bug chato que sempre volta depois de uma atualizaçã? Testes regressivos servem basicamente para retestar tudo que já foi testado antes, isso após uma nova atualização no sistema. Mas por quê? Para garantir que a atualização não fez bugs antigos retornarem ou novos surgirem.

**Tipo:** Caixa Preta (o QA usa automação como um Repelente Supremo).

**Quem faz?** QA (porque alguém tem que lidar com esses bugs malditos).

### 5️⃣ Testes Exploratórios – Explorando a Caverna de Diglett Sem Mapa
**O que é?** É tipo entrar no Safari Zone pela primeira vez – explorar o sistema sem script pra achar bugs, geralmente usado quando um sistema já foi implementado sem ser testado antes ou não tem documentação de testes!

**Tipo:** Caixa Preta (QA literalmente sai na sua jornada Pokémon atrás de bugs).

**Quem faz?** QA (e precisa de senso de investigação igual ao Detetive Pikachu).

### 6️⃣ Testes de Usabilidade – O PC do centro Pokémon que todos sabem usar
**O que é?** Garantir que o sistema seja tão intuitivo quanto o sistema de PC dos Pokémon.

**Tipo:** Caixa Preta (foco no jogador/usuário).

**Quem faz?** UX/QA.

### 7️⃣ Testes de Stress/Carga – A Batalha Contra 100 Magikarps
**O que é?** Jogar 1000 treinadores contra um servidor pra ver se ele vence a batalha ou não, é basicamente testar os limites do sistema o estressando com uma quantidade bem maior de usuários que a comum.

**Tipo:** Caixa Preta (testamos por fora).

**Quem faz?** QA/DevOps (com JMeter como Master Ball da performance).

## 🎯 Por Que Isso Importa?
Porque ninguém quer um jogo (ou sistema) que:

- Trava igual os jogos antigos de Pokémon quando bugam
- Tem mais bugs que uma floresta
- É confuso como o sistema de EVs/IVs sem guia

**Devs e QAs são como Pikachu e Ash:**

- Devs garantem que o código funcione nos bastidores
- QAs garantem que a experiência do jogador seja épica!

<br>

## 🌎 English Version

<br>

# 🚀 Software Testing: The QA's Journey to Catch All Bugs!

Hello! Welcome to this repository where I'll talk about software testing types in a different way - using references from a universe I love: Pokémon. The goal is to make the subject understandable for everyone while making it extra interesting for Pokémon enthusiasts!

Just to be clear, I recently started studying quality assurance, so if I got anything wrong or missed something, feel free to contact me on LinkedIn or here! ([🔗 My LinkedIn](https://www.linkedin.com/in/gustavo-silva-b2687727a))

Let's talk about testing types as if they were training techniques to make your dev and QA teams as powerful as a team of level 100 legendaries!

## 🔍 Black Box vs. White Box: The Pokémon Battle!
**Black Box:** Like being a rookie trainer trying to figure out what an unknown Pokémon does - we test everything possible without seeing the code, just the results! (Usually done by QA)

**White Box:** Here we become like a Pokémon professor - we analyze the code directly to check if everything's correct, like studying a new Pokémon's DNA. (Done by Dev, but sometimes by QA too)

*(Yes, there's also Gray Box, which is like a Ditto - combines both!)*

## 🎮 The Testing Types (and Who's the Responsible Trainer)

### 1️⃣ Unit Tests - The Basic Training at the Professor's Lab (when we first battle Blue!)
**What is it?** Training one Pokémon at a time - testing each code function separately.

**Type:** White Box (the Dev is the scientist who knows all the IVs).

**Who does it?** Dev (using tools like JUnit and pytest).

### 2️⃣ Functional Tests - The Gym Battle
**What is it?** Verifying if the system does what it promises, like when you teach a new move to your Charizard and immediately test if it works exactly as described!

**Type:** Black Box (QA doesn't need to know how the attack is programmed).

**Who does it?** QA (with special attacks like Selenium and Cypress, or even manually).

### 3️⃣ Integration Tests - Team Rocket Working Together!
**What is it?** Checking if Meowth (front-end), Jessie (back-end), and James (database) can actually work together properly. Basically testing if everything works when connected.

**Type:** Gray Box (half dev, half QA).

**Who does it?** Dev or QA (using Postman for example).

### 4️⃣ Regression Tests - The Zubat That Appears in Every Cave
**What is it?** You know that annoying bug that always comes back after an update? Regression tests retest everything that was tested before after system updates. Why? To ensure updates don't bring back old bugs or create new ones.

**Type:** Black Box (QA uses automation like a Super Repel).

**Who does it?** QA (because someone has to deal with those darn bugs).

### 5️⃣ Exploratory Tests - Exploring Diglett Cave Without a Map
**What is it?** It's like entering the Safari Zone for the first time - exploring the system without scripts to find bugs, usually used when a system was implemented without prior testing or lacks test documentation!

**Type:** Black Box (QA literally embarks on a Pokémon journey hunting bugs).

**Who does it?** QA (needing investigation skills like Detective Pikachu).

### 6️⃣ Usability Tests - The Pokémon Center PC Everyone Can Use
**What is it?** Ensuring the system is as intuitive as the Pokémon PC system.

**Type:** Black Box (focus on the player/user).

**Who does it?** UX/QA.

### 7️⃣ Stress/Load Tests - The Battle Against 100 Magikarps
**What is it?** Throwing 1000 trainers at a server to see if it can handle the battle - basically testing system limits by stressing it with way more users than normal.

**Type:** Black Box (we test from the outside).

**Who does it?** QA/DevOps (with JMeter as the performance Master Ball).

## 🎯 Why Does This Matter?
Because nobody wants a game (or system) that:
- Crashes like old Pokémon games when they glitch
- Has more bugs than a forest
- Is as confusing as the EV/IV system without a guide

**Devs and QAs are like Pikachu and Ash:**
- Devs ensure the code works behind the scenes
- QAs ensure the player experience is epic!
