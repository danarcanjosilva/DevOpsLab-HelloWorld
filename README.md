# ⚙️ DevOpsLab — Pipeline DevOps com Python

Aplicação web desenvolvida em **Python** como projeto prático da **Trilha DevOps da 4Linux**, com o objetivo de demonstrar o ciclo de uma **Pipeline DevOps**, incluindo desenvolvimento, versionamento, testes, integração contínua e preparação para deploy.

## 🚀 Sobre o projeto

O projeto utiliza uma aplicação web simples como base para demonstrar conceitos fundamentais de **DevOps e CI/CD**.

A ideia é mostrar como o código pode passar por um fluxo automatizado desde o desenvolvimento até etapas de **testes e integração contínua**, utilizando ferramentas de automação.

Este projeto é especialmente útil para demonstrar conhecimentos em:

* DevOps
* CI/CD
* Integração Contínua
* Automação
* Testes automatizados
* Versionamento de código
* Desenvolvimento Python
* Deploy de aplicações

## 🛠️ Tecnologias utilizadas

* **Python**
* **Flask**
* **HTML**
* **Sass**
* **Git**
* **GitHub**
* **Travis CI**
* **WSGI**
* **Automação de testes**

## 📂 Estrutura do projeto

```text
DevOpsLab-HelloWorld/
│
├── static/
│   └── Arquivos estáticos da aplicação
│
├── templates/
│   └── Templates HTML
│
├── app.py
│   └── Aplicação Python/Flask
│
├── test.py
│   └── Testes automatizados
│
├── application.wsgi
│   └── Configuração WSGI
│
├── requirements.txt
│   └── Dependências Python
│
├── runtime.txt
│   └── Versão/runtime do Python
│
├── Procfile
│   └── Configuração para execução/deploy
│
├── .travis.yml
│   └── Configuração da Pipeline CI
│
└── README.md
```

## 🔄 Pipeline DevOps

O projeto foi estruturado para demonstrar um fluxo básico de integração contínua:

```text
Desenvolvimento
      ↓
     Git
      ↓
    GitHub
      ↓
 Travis CI
      ↓
Testes automatizados
      ↓
 Build / Integração
      ↓
 Deploy
```

Esse fluxo demonstra um dos princípios fundamentais de **DevOps**: automatizar etapas do ciclo de desenvolvimento para aumentar a confiabilidade e reduzir tarefas manuais.

## 🧪 Testes

O projeto possui testes automatizados através do arquivo:

```text
test.py
```

Os testes podem ser executados utilizando o ambiente Python configurado para o projeto.

## ⚙️ Instalação

### Pré-requisitos

Para executar o projeto localmente, é necessário possuir:

* Python
* Git
* Pip

### 1. Clone o repositório

```bash
git clone https://github.com/danarcanjosilva/DevOpsLab-HelloWorld.git
```

Entre na pasta:

```bash
cd DevOpsLab-HelloWorld
```

### 2. Crie um ambiente virtual

Linux/macOS:

```bash
python3 -m venv venv
source venv/bin/activate
```

Windows:

```powershell
python -m venv venv
venv\Scripts\activate
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Execute a aplicação

```bash
python app.py
```

Depois, acesse a aplicação pelo endereço informado pelo servidor Flask.

## 🔧 Integração Contínua

O arquivo:

```text
.travis.yml
```

contém as configurações utilizadas para demonstrar a integração do projeto com o **Travis CI**.

A pipeline pode ser utilizada para automatizar etapas como:

* Instalação das dependências
* Execução dos testes
* Validação do código
* Integração contínua

## 📚 Objetivo de aprendizado

Este projeto foi desenvolvido para colocar em prática conceitos relacionados ao ciclo de vida de uma aplicação dentro de uma cultura **DevOps**.

Entre os principais conhecimentos trabalhados estão:

* Controle de versão com Git
* GitHub
* Integração contínua
* Automação
* Testes
* Python
* Flask
* Configuração de ambientes
* WSGI
* Estrutura de aplicações web
* Pipeline de desenvolvimento
* Conceitos de CI/CD

## 🎓 Formação

Projeto relacionado à **Trilha DevOps da 4Linux**.

O repositório original pode ser encontrado no projeto da 4Linux.

## 👨‍💻 Autor

**Daniel Arcanjo da Silva**

Desenvolvedor Full Stack | Python | C#/.NET | Java | Angular | Node.js | Machine Learning | Inteligência Artificial | DevOps

### 🔗 Links

* GitHub: https://github.com/danarcanjosilva
* Repositórios: https://github.com/danarcanjosilva?tab=repositories
* Projeto: https://github.com/danarcanjosilva/DevOpsLab-HelloWorld

---

⭐ Se este projeto foi útil para você, considere deixar uma estrela no repositório.
