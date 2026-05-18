# Aesthetic Rabello — Sistema de Gestão para Estética Automotiva

Sistema web desenvolvido para gerenciamento de uma empresa de estética automotiva, com foco em reservas, calendário, dashboard financeiro e controle de gastos.

## Sobre o projeto

O **Aesthetic Rabello** é um sistema de gestão criado para facilitar o controle diário de atendimentos em uma estética automotiva.

O projeto foi desenvolvido utilizando:

* HTML
* CSS
* JavaScript
* Firebase Firestore
* Chart.js
* Vercel

O sistema funciona totalmente online e em tempo real através da integração com o Firebase.

---

# Funcionalidades

## Reservas

* Cadastro de clientes
* Cadastro de veículos
* Agendamento de horários
* Controle de serviços
* Controle de valores
* Exclusão de reservas
* Atualização em tempo real

## Calendário

* Visualização mensal
* Navegação entre meses
* Exibição das reservas por dia
* Detalhamento dos atendimentos

## Dashboard

* Receita mensal
* Quantidade de atendimentos
* Controle de gastos
* Lucro líquido
* Gráficos dinâmicos

## Gastos

* Cadastro de despesas
* Categorias de gastos
* Controle financeiro
* Exclusão de despesas

---

# Tecnologias utilizadas

## Frontend

* HTML5
* CSS3
* JavaScript ES Modules

## Banco de dados

* Firebase Firestore

## Bibliotecas

* Chart.js

## Hospedagem

* Vercel

---

# Estrutura do sistema

```txt
Usuário acessa o site
↓
HTML cria a estrutura
↓
CSS aplica o design
↓
JavaScript executa a lógica
↓
Firebase salva e sincroniza os dados
↓
Dashboard e calendário atualizam em tempo real
```

---

# Firebase

O sistema utiliza o Firestore Database para:

* armazenar reservas
* armazenar gastos
* atualizar dados em tempo real
* sincronizar informações automaticamente

## Collections utilizadas

### reservas

```txt
nome
telefone
modelo
tipo
data
hora
servico
valor
```

### gastos

```txt
desc
cat
valor
data
```

---

# Funcionalidade em tempo real

O projeto utiliza:

```javascript
onSnapshot()
```

para atualização automática da interface sem necessidade de recarregar a página.

---

# Deploy

O sistema foi publicado utilizando:

* Vercel

## Link do projeto

[https://aesthetic-rabello.vercel.app/](https://aesthetic-rabello.vercel.app/)

---

# Objetivo do projeto

O objetivo do sistema é profissionalizar o gerenciamento de uma estética automotiva através de:

* automação de reservas
* controle financeiro
* organização de atendimentos
* visualização de métricas
* gerenciamento online

---

# Melhorias futuras

* Sistema de login/admin
* Geração automática de PDF
* Integração com WhatsApp
* Bloqueio automático de horários
* Painel mobile profissional
* Exportação de dados
* Backup automático
* Notificações
* Painel administrativo avançado

---

# Aprendizados durante o desenvolvimento

Durante o desenvolvimento deste projeto foram estudados conceitos como:

* integração com Firebase
* Firestore Database
* JavaScript moderno
* manipulação de DOM
* eventos
* banco de dados em tempo real
* deploy na Vercel
* criação de dashboards
* gráficos com Chart.js
* arquitetura frontend

---

# Autor

Marcelo Alves

Projeto desenvolvido para estudos e evolução prática em desenvolvimento web.

