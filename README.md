# 🧪 Projeto de Testes – Urban Lunch (Automatizados e Funcionais)

## 📌 Descrição e Objetivo

Este projeto tem como objetivo validar as funcionalidades do aplicativo **Urban Lunch**, que permite combinar pratos de diferentes restaurantes em um único pedido. Os testes foram realizados de forma manual e automatizada, cobrindo Web, API e Mobile (Android), com foco em garantir estabilidade, usabilidade e qualidade nas entregas.

## 🧰 Stack Utilizada

- **Selenium WebDriver** – automação de testes Web
- **Pytest** – estrutura de testes em Python
- **Postman** – testes de API REST
- **Android Studio** – testes exploratórios em dispositivos Android
- **Jira** – registro e rastreamento de bugs

## 🚀 Como Rodar os Testes

1. Clone o repositório:
   ```bash
   git clone https://github.com/danielasilva3251/urban-lunch-tests.git
   cd urban-lunch-tests
2. Instale as dependências:
pip install -r requirements.txt

3. Execute os testes automatizados:
pytest --headed --browser chrome

Versão recomendada: Python 3.11+, ChromeDriver 120+, Pytest 7+

## Estrutura de pastas:

```urban-lunch-tests/
│
├── pages/               # Objetos de página (POM)
│   ├── login_page.py
│   ├── menu_page.py
│   └── checkout_page.py
│
├── test_cases/          # Casos de teste automatizados
│   ├── test_login.py
│   ├── test_menu_selection.py
│   └── test_checkout_flow.py
│
├── fixtures/            # Dados e configurações reutilizáveis
│   └── user_data.json
│
├── reports/             # Evidências e logs de execução
│   ├── screenshots/
│   └── test_report.html
│
├── conftest.py          # Configurações globais do Pytest
└── requirements.txt     # Dependências do projeto

```

Evidências
Prints e gravações disponíveis na pasta /reports/screenshots

Relatórios de bugs simulados no Jira: 🔗 Issues anonimizadas – Projeto PQ4

📊 Resultados
✅ +40 casos de teste executados

🐞 +15 bugs identificados e documentados com evidências

📌 Checklist dividido por requisitos funcionais

🔍 1 área cinzenta identificada e registrada

👩‍💻 Autora
**Daniela Silva** 
📧 danielasilva3251@gmail.com  
📱 +55 11 99336-5375  
🔗 [LinkedIn](https://www.linkedin.com/in/daniela-silva-b1a544275)  
💻 [GitHub](https://github.com/danielasilva3251)  
📂 [Portfólio de Testes](https://danielasilva3251.atlassian.net/jira/software/c/projects/PQ4/issues?jql=project%20%3D%20%22PQ4%22%20ORDER%20BY%20created%20DESC)

