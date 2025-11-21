# Nikel — Controle Financeiro
Aplicação desenvolvida durante o **Codaí 2.0 – Front-End**, focada em prática de HTML, CSS, JavaScript e manipulação de dados no navegador usando **LocalStorage**.  
O projeto simula um gerenciador simples de finanças pessoais, permitindo registrar entradas, saídas e visualizar o saldo total.

---

## Funcionalidades

### Autenticação
- Criação de conta (simulada com LocalStorage)  
- Login com validação  
- Opção *“Manter conectado”*

### Controle Financeiro
- Adicionar lançamentos de **entrada** e **saída**
- Listagem completa dos lançamentos
- Cálculo automático de:
  - Total recebido  
  - Total gasto  
  - Saldo atual  

### Interface e Usabilidade
- Layout responsivo com **Bootstrap 5**
- Ícones via **Bootstrap Icons**
- Estrutura moderna e intuitiva

---

## Estrutura do Projeto

```
/
├── index.html          # Tela de login
├── home.html           # Tela principal com saldo e lançamentos resumidos
├── transactions.html   # Listagem completa de transações
│
├── css/
│   └── styles.css      # Estilos da aplicação
│
├── js/
│   ├── index.js        # Lógica de login/criação de conta
│   ├── home.js         # Manipulação da Home e cálculos
│   └── transactions.js # CRUD de lançamentos
│
└── assets/
    ├── images/         # Logos e ilustrações
```

---

## Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript Vanilla**
- **Bootstrap 5**
- **Bootstrap Icons**
- **LocalStorage**

---

## Como executar o projeto

1. **Baixe o repositório**
   ```
   git clone https://github.com/Lucas12310/nikel.git
   ```

2. **Abra o arquivo `index.html`** diretamente no navegador  
   — Não é necessário servidor local.

3. **Crie uma conta** e comece a utilizar o app normalmente.

---

## Aprendizados do Curso

Durante o desenvolvimento, foram praticados conceitos como:

- Manipulação do DOM  
- Manipulação de formulários  
- Eventos no JavaScript  
- Armazenamento no LocalStorage  
- Organização de código front-end  
- Componentização simples com HTML + Bootstrap  
- Uso de modais, tabelas e ícones  

---

## Evoluções Futuras

- Edição e exclusão de lançamentos  
- Dashboard com gráficos  
- Autenticação real via API  
- Tema dark/light

---

## Autor

Projeto desenvolvido durante o **Codaí 2.0 – Growdev** por:

**Lucas Fernandes**
