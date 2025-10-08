# Validador de Senhas em Python

## 📖 Sobre o Projeto

Este é um projeto acadêmico que consiste em uma API simples de validação de senhas, desenvolvida em Python. O objetivo é garantir que as senhas atendam a critérios de segurança específicos, utilizando boas práticas de desenvolvimento, como testes unitários e análise de cobertura de código.

## ✨ Funcionalidades

A função `validate_password` garante que uma senha siga as seguintes regras de negócio:

- **Comprimento Mínimo:** A senha deve ter no mínimo 8 caracteres.
- **Letra Maiúscula:** Deve conter pelo menos uma letra maiúscula (A-Z).
- **Letra Minúscula:** Deve conter pelo menos uma letra minúscula (a-z).
- **Número:** Deve conter pelo menos um número (0-9).
- **Sem Espaços:** Não pode conter nenhum espaço em branco.

Se qualquer uma dessas regras for violada, uma exceção customizada (`InvalidPasswordException`) é lançada com uma mensagem clara sobre o erro.

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python
- **Testes:** Pytest
- **Análise de Cobertura:** Pytest-Cov

## 🚀 Como Executar o Projeto

Siga os passos abaixo para configurar e rodar o projeto em sua máquina local.

### 1. Pré-requisitos

- Python 3.x
- `pip` (gerenciador de pacotes do Python)

### 2. Clone o Repositório

```bash
git clone <https://github.com/andresilvm/qa_p5_b.git>
```

### 3. Configure o Ambiente

```cmd
cd qa_p5_b
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
pytest --cov=src --cov-report term-missing --cov-report html
```

## Relatório

<img width="2410" height="716" alt="image" src="https://github.com/user-attachments/assets/12606a6d-bbfa-48ca-972c-71579bc986f4" />

