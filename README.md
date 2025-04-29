# 🐍 Fase 1 — Fundamentos de Python

**Objetivo da fase:**  
Dominar os conceitos básicos da linguagem Python para criar scripts simples e adquirir raciocínio lógico de programação.

---

## 1. Introdução ao Python e Ambiente

- **📘 O que estudar:**  
  [Curso Python para Iniciantes - Aula 1 (Hashtag Treinamentos)]([https://www.youtube.com/watch?v=S9uPNppGsGo](https://www.youtube.com/playlist?list=PLHz_AreHm4dlKP6QQCekuIPky1CiwmdI6))

- **📌 Por que isso é importante:**  
  Aprender a instalar o Python e executar o primeiro código é o primeiro passo para se tornar um programador. Sem isso, você não conseguirá testar nem evoluir.

- **✅ O que você vai aprender:**  
  - Instalar Python
  - Usar o terminal/IDLE
  - Rodar scripts `.py`

- **🧪 Exercício:**  
  Crie um script chamado `inicio.py` que imprime:
  ```
  Alva, aqui vamos nós!
  ```

---

## 2. Tipos de Variáveis (int, float, str, bool)

- **📘 O que estudar:**  
  [Tipos de Dados em Python (W3Schools)](https://www.w3schools.com/python/python_datatypes.asp)

- **📌 Por que isso é importante:**  
  Toda informação em um sistema precisa ser representada como tipo de dado. Saber diferenciar texto, número e booleano é essencial para manipular dados corretamente.

- **✅ O que você vai aprender:**  
  - Criar e manipular variáveis
  - Identificar tipos de dados

- **🧪 Exercício:**  
  Escreva um programa que pergunta seu nome e idade, e imprime:  
  ```
  Olá, João! Você tem 25 anos.
  ```

---

## 3. Convenções de Estilo (PEP8 + Nomeação de Variáveis)

- **📘 O que estudar:**  
  [Guia PEP8 - Real Python](https://realpython.com/python-pep8/)

- **📌 Por que isso é importante:**  
  Código limpo e padronizado facilita leitura, manutenção e evita erros em times.

- **✅ O que você vai aprender:**  
  - Escrever variáveis com `snake_case`
  - Definir constantes com `UPPER_CASE`
  - Usar nomes significativos

- **🧪 Exercício:**  
  Refatore seu exercício anterior aplicando boas práticas:
  - `nome_usuario`, `idade_usuario` (snake_case)
  - `TAXA_CONVERSAO = 3.2` (constante em UPPER_CASE)

---

## 4. Listas e Dicionários

- **📘 O que estudar:**  
  [Listas e Dicionários em Python - Curso em Vídeo](https://www.youtube.com/watch?v=1YbTDcz0T-K)

- **📌 Por que isso é importante:**  
  A maioria dos dados em aplicativos é manipulada em coleções. Saber trabalhar com listas e dicionários é essencial para armazenar e acessar informações.

- **✅ O que você vai aprender:**  
  - Criar listas com vários elementos
  - Criar dicionários com chave-valor

- **🧪 Exercício:**  
  - Crie uma lista com 5 produtos favoritos  
  - Crie um dicionário com dados de um cliente:
    ```python
    cliente = {
        "nome": "Maria",
        "idade": 30,
        "email": "maria@exemplo.com"
    }
    ```

---

## 5. Condicionais (if, elif, else)

- **📘 O que estudar:**  
  [Python Conditions (if, elif, else) - W3Schools](https://www.w3schools.com/python/python_conditions.asp)

- **📌 Por que isso é importante:**  
  Permite que seu programa tome decisões com base em diferentes entradas.

- **✅ O que você vai aprender:**  
  - Escrever condições simples e compostas
  - Criar diferentes fluxos no programa

- **🧪 Exercício:**  
  Crie um programa que pergunte a idade e classifique:
  - Menor de idade (< 18)
  - Adulto (18-60)
  - Idoso (> 60)

---

## 6. Laços de Repetição (for, while)

- **📘 O que estudar:**  
  [Loops em Python - Curso em Vídeo](https://www.youtube.com/watch?v=K1zTOo8npIs&t=1423s)

- **📌 Por que isso é importante:**  
  Permite executar tarefas repetidamente sem reescrever o código.

- **✅ O que você vai aprender:**  
  - Repetir ações com `for` e `while`
  - Iterar sobre listas e faixas numéricas

- **🧪 Exercício:**  
  Crie um programa que receba 5 nomes e os armazene em uma lista.

---

## 7. Funções e Modularização

- **📘 O que estudar:**  
  [Funções em Python - Programação Dinâmica (YouTube)](https://www.youtube.com/watch?v=5gV6DlKPkKk)

- **📌 Por que isso é importante:**  
  Funções organizam seu código, evitam repetições e facilitam testes.

- **✅ O que você vai aprender:**  
  - Criar e chamar funções
  - Passar argumentos e retornar valores

- **🧪 Exercício:**  
  Crie uma função `saudacao(nome, idade)` que imprima:
  ```
  Seja bem-vindo, João! Você tem 25 anos.
  ```

---

## ✅ Checkpoint da Fase 1

**Projeto prático sugerido: Sistema de Cadastro de Clientes**

- Perguntar: nome, idade, email
- Armazenar cada cliente como dicionário
- Adicionar em uma lista de clientes
- Imprimir todos os cadastros
- Subir o projeto no GitHub

---

## 🔁 O que você aprendeu até aqui:

- Lógica básica de programação
- Uso de variáveis, listas e dicionários
- Estruturas de decisão e repetição
- Criação de funções reutilizáveis
- Estilo limpo de código (PEP8)

**Próximo passo:**  
Você agora pode aprender **Orientação a Objetos**, que vai te ajudar a modelar sistemas reais com mais clareza e flexibilidade!



# 🧱 Fase 2 — Orientação a Objetos e Design Patterns

**Objetivo da fase:**  
Aprender a modelar sistemas com classes e objetos, aplicando organização e reaproveitamento de código.

---

## 1. O que é Programação Orientada a Objetos (POO)

- **📘 O que estudar:**  
  [O que é POO - Curso em Vídeo](https://www.youtube.com/watch?v=Ejkb_YpuHWs)

- **📌 Por que isso é importante:**  
  POO ajuda a modelar o mundo real e torna o código mais estruturado.

- **✅ O que você vai aprender:**  
  - Diferença entre Procedural e Orientado a Objetos  
  - Conceitos de classe, objeto, atributo, método

- **🧪 Exercício:**  
  Criar classe `Pessoa` com atributos `nome`, `idade` e um método `apresentar()`.

---

## 2. Classes e Métodos em Python

- **📘 O que estudar:**  
  [POO em Python - Hashtag Programação](https://www.youtube.com/watch?v=-0X8mr6Q8Ew)

- **📌 Por que isso é importante:**  
  Classes são blocos principais na estrutura orientada a objetos.

- **✅ O que você vai aprender:**  
  - Criar classes, atributos, construtores e métodos

- **🧪 Exercício:**  
  Criar classe `Produto` com `nome`, `preco` e um método que aplica desconto.

---

## 3. Encapsulamento e Propriedades

- **📘 O que estudar:**  
  [Encapsulamento e @property - YouTube](https://www.youtube.com/watch?v=QJVT5iDYOxk)

- **📌 Por que isso é importante:**  
  Evita acesso direto a atributos sensíveis e permite validações.

- **✅ O que você vai aprender:**  
  - Modificadores públicos e privados  
  - Getters e Setters com `@property`

- **🧪 Exercício:**  
  Criar classe `ContaBancaria` com saldo privado e método de depósito com validação.

---

## 4. Herança e Polimorfismo

- **📘 O que estudar:**  
  [Herança e Polimorfismo - DevAprender](https://www.youtube.com/watch?v=RSl87lqOXDE)

- **📌 Por que isso é importante:**  
  Reutiliza código e permite comportamentos diferentes entre objetos relacionados.

- **✅ O que você vai aprender:**  
  - Criar classes que herdam de outras  
  - Sobrescrever métodos

- **🧪 Exercício:**  
  Criar `Funcionario` e `Gerente` onde `Gerente` herda de `Funcionario`, mas calcula bônus diferente.

---

## 5. Introdução a Design Patterns (Factory, Singleton)

- **📘 O que estudar:**  
  [Design Patterns em Python - Refactoring Guru](https://refactoring.guru/pt-br/design-patterns/python)

- **📌 Por que isso é importante:**  
  Ajuda a resolver problemas comuns com soluções reutilizáveis.

- **✅ O que você vai aprender:**  
  - Entender e aplicar padrões básicos

- **🧪 Exercício:**  
  Criar um Singleton para gerenciar uma configuração de sistema.

---

## ✅ Checkpoint da Fase 2

**Projeto prático: Sistema de contas bancárias**

- Criar `Cliente`, `ContaCorrente` e `ContaPoupanca`  
- Métodos para saque, depósito e extrato  
- Aplicar herança e encapsulamento  
- Subir o projeto no GitHub

# 🧩 Fase 3 — Django Básico: Admin, Templates e Views (4-5 semanas)

**Objetivo da fase:**  
Aprender a usar Django para criar sistemas web internos com cadastro, exibição e administração de dados via Django Admin e Templates.

---

## 1. O que é Django + Instalação e Estrutura

- **📘 O que estudar:**  
  [Tutorial oficial Django - Parte 1](https://docs.djangoproject.com/pt-br/5.0/intro/tutorial01/)

- **📌 Por que isso é importante:**  
  Django é o framework web que você usará para criar aplicações internas. Entender sua estrutura base é fundamental.

- **✅ O que você vai aprender:**  
  - Instalar Django  
  - Criar projeto e app  
  - Compreender a estrutura: settings, urls, apps, templates, static

- **🧪 Exercício:**  
  Criar projeto `sistema_alva` com app `clientes` e rodar localmente com página de boas-vindas.

---

## 2. Models: Criando e Migrando Tabelas

- **📘 O que estudar:**  
  [Modelos no Django - Documentação](https://docs.djangoproject.com/pt-br/5.0/topics/db/models/)

- **📌 Por que isso é importante:**  
  Models representam as tabelas do banco. Tudo no Django gira em torno do Model.

- **✅ O que você vai aprender:**  
  - Criar classes modelando dados  
  - Rodar `makemigrations` e `migrate`  
  - Usar `__str__` e campos úteis (CharField, DateField, etc.)

- **🧪 Exercício:**  
  Criar Model `Cliente` com `nome`, `email`, `cidade`, `data_cadastro`

---

## 3. Django Admin

- **📘 O que estudar:**  
  [Admin do Django - Documentação](https://docs.djangoproject.com/pt-br/5.0/ref/contrib/admin/)

- **📌 Por que isso é importante:**  
  O Admin do Django facilita o CRUD de dados internos e é uma das ferramentas mais poderosas da plataforma.

- **✅ O que você vai aprender:**  
  - Registrar models no Admin  
  - Personalizar lista e filtros  
  - Criar campos de leitura, ordenação e busca

- **🧪 Exercício:**  
  Ativar o Django Admin para `Cliente`, com busca por nome e filtro por cidade.

---

## 4. Views e URLs

- **📘 O que estudar:**  
  [Views e URLs no Django - Tutorial oficial](https://docs.djangoproject.com/pt-br/5.0/topics/http/views/)

- **📌 Por que isso é importante:**  
  Views são responsáveis por processar requisições e retornar respostas. URLs definem o roteamento.

- **✅ O que você vai aprender:**  
  - Criar `views.py` com function-based views  
  - Criar `urls.py` do app  
  - Conectar rotas no projeto

- **🧪 Exercício:**  
  Criar uma view que lista todos os clientes e renderiza um template.

---

## 5. Templates (HTML + Django Template Language)

- **📘 O que estudar:**  
  [Template Language - Documentação Oficial](https://docs.djangoproject.com/pt-br/5.0/topics/templates/)

- **📌 Por que isso é importante:**  
  Templates são usados para exibir dados de forma visual. Eles combinam HTML com lógica leve.

- **✅ O que você vai aprender:**  
  - Usar `for`, `if`, `extends` e `block`  
  - Organizar layout base (base.html)  
  - Exibir dados de um model na interface

- **🧪 Exercício:**  
  Criar `clientes.html` listando todos os clientes com nome e email.

---

## 6. Formulários Simples (Formulários HTML com POST)

- **📘 O que estudar:**  
  [Formulários em Views - Documentação Django](https://docs.djangoproject.com/pt-br/5.0/topics/forms/)

- **📌 Por que isso é importante:**  
  Permite que usuários enviem dados para o servidor (cadastros, edições).

- **✅ O que você vai aprender:**  
  - Criar formulário manual em HTML  
  - Processar dados no `POST` da view  
  - Salvar novos objetos no banco

- **🧪 Exercício:**  
  Criar página com formulário de cadastro de cliente (nome, email).

---

## ✅ Checkpoint da Fase 3

**Projeto prático: Cadastro completo com Django**

- Criar App `clientes`  
- Model: Cliente (nome, email, cidade, data_cadastro)  
- Admin com busca e filtro  
- Listagem via View e Template  
- Formulário de cadastro  
- Subir no GitHub

---

## 🔁 O que você aprendeu até aqui:

- Criar projetos Django do zero  
- Criar Models e migrar banco  
- Usar Django Admin para gerenciar dados  
- Renderizar dados com Templates  
- Criar rotas e Views  
- Processar formulários HTML

**Próximo passo:**  
Você agora pode aprender sobre **consumo de APIs externas com Python**, expandindo suas habilidades para integrações reais!

# 🌐 Fase 4 — Consumo de APIs com Python (2 semanas)

**Objetivo da fase:**  
Aprender a consumir APIs REST externas utilizando Python e a biblioteca `requests`, compreendendo requisições HTTP, tratamento de respostas e manipulação de dados JSON.

---

## 1. Conceitos Básicos de APIs REST

- **📘 O que estudar:**  
  - [Python and REST APIs: Interacting With Web Services – Real Python](https://realpython.com/api-integration-in-python/)
  - [Como consumir uma API utilizando Python – Revelo Community](https://community.revelo.com.br/como-consumir-uma-api-utilizando-python/)

- **📌 Por que isso é importante:**  
  Compreender o funcionamento de APIs REST é essencial para integrar aplicações com serviços externos, permitindo a troca de dados e funcionalidades.

- **✅ O que você vai aprender:**  
  - O que é uma API REST  
  - Métodos HTTP: GET, POST, PUT, DELETE  
  - Estrutura de endpoints e parâmetros  
  - Códigos de status HTTP

- **🧪 Exercício:**  
  - Pesquise e escolha uma API pública (ex: [PokeAPI](https://pokeapi.co/), [API do IBGE](https://servicodados.ibge.gov.br/api/docs/))  
  - Acesse a documentação e identifique um endpoint que retorne dados em JSON  
  - Faça uma requisição manual utilizando o navegador ou ferramentas como Postman para entender a resposta

---

## 2. Introdução à Biblioteca `requests`

- **📘 O que estudar:**  
  - [Python Requests Module – W3Schools](https://www.w3schools.com/python/module_requests.asp)
  - [Python Requests Tutorial – GeeksforGeeks](https://www.geeksforgeeks.org/python-requests-tutorial/)

- **📌 Por que isso é importante:**  
  A biblioteca `requests` simplifica o processo de realizar requisições HTTP em Python, sendo amplamente utilizada para consumir APIs.

- **✅ O que você vai aprender:**  
  - Instalar e importar a biblioteca `requests`  
  - Realizar requisições GET e POST  
  - Entender o objeto de resposta (`Response`)  
  - Acessar conteúdo, status e headers da resposta

- **🧪 Exercício:**  
  - Instale a biblioteca `requests` utilizando `pip`  
  - Faça uma requisição GET para o endpoint escolhido no exercício anterior  
  - Imprima o status code e o conteúdo da resposta

---

## 3. Manipulação de Dados JSON

- **📘 O que estudar:**  
  - [Working with JSON Data in Python – Real Python](https://realpython.com/python-json/)
  - [How to Use an API in Python – Dataquest](https://www.dataquest.io/blog/api-in-python/)

- **📌 Por que isso é importante:**  
  A maioria das APIs retorna dados no formato JSON. Saber manipular esse formato é crucial para extrair e utilizar as informações desejadas.

- **✅ O que você vai aprender:**  
  - Converter respostas JSON em dicionários Python  
  - Acessar e iterar sobre dados JSON  
  - Tratar erros e exceções durante o parsing

- **🧪 Exercício:**  
  - A partir da resposta JSON obtida anteriormente, extraia e imprima informações específicas (ex: nome de um Pokémon, população de uma cidade)  
  - Trate possíveis exceções que possam ocorrer durante o processo

---

## 4. Requisições com Parâmetros e Headers

- **📘 O que estudar:**  
  - [Quickstart – Requests Documentation](https://requests.readthedocs.io/en/master/user/quickstart/)
  - [Requests Library in Python – DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-get-started-with-the-requests-library-in-python)

- **📌 Por que isso é importante:**  
  Muitas APIs exigem parâmetros específicos e headers personalizados para retornar os dados corretos ou para autenticação.

- **✅ O que você vai aprender:**  
  - Adicionar parâmetros de query nas requisições  
  - Configurar headers personalizados  
  - Entender como enviar dados no corpo da requisição (POST)

- **🧪 Exercício:**  
  - Modifique a requisição anterior para incluir parâmetros de query (ex: filtrar resultados)  
  - Adicione headers personalizados, como `User-Agent`  
  - Realize uma requisição POST para um endpoint que aceite dados no corpo da requisição

---

## 5. Projeto Prático: Integração com API Externa

- **📘 O que estudar:**  
  - [Tutorial de como consumir a API do IBGE usando Django – GitHub](https://github.com/cannudo/consumo-api-django)

- **📌 Por que isso é importante:**  
  Consolidar o conhecimento adquirido aplicando-o em um projeto prático reforça o aprendizado e demonstra a utilidade real das habilidades desenvolvidas.

- **✅ O que você vai aprender:**  
  - Integrar uma API externa em uma aplicação Django  
  - Exibir dados dinâmicos obtidos via API  
  - Atualizar informações em tempo real

- **🧪 Exercício:**  
  - Crie uma aplicação Django que consuma dados de uma API pública  
  - Exiba as informações obtidas em um template HTML  
  - Implemente uma funcionalidade de busca ou filtro utilizando parâmetros de query

---

## ✅ Checkpoint da Fase 4

**Projeto final sugerido: Dashboard de Informações Públicas**

- Escolha uma API pública que forneça dados relevantes (ex: clima, localização, estatísticas)  
- Crie uma aplicação Django que consuma essa API  
- Exiba as informações em um dashboard interativo  
- Implemente funcionalidades adicionais, como busca, filtros ou gráficos  
- Suba o projeto no GitHub e compartilhe com a equipe

---

## 🔁 O que você aprendeu até aqui:

- Conceitos fundamentais de APIs REST  
- Utilização da biblioteca `requests` para realizar requisições HTTP  
- Manipulação de dados JSON em Python  
- Integração de APIs externas em aplicações Django

**Próximo passo:**  
Aprofundar-se no desenvolvimento de APIs com Django REST Framework, permitindo que suas aplicações não apenas consumam, mas também forneçam dados para outras aplicações e serviços.
