# Sistema Bancário 🏦

Um sistema bancário simples implementado em Python que simula operações bancárias básicas.

## 📋 Índice
- [Funcionalidades](#funcionalidades)
- [Requisitos](#requisitos)
- [Instalação](#instalação)
- [Como Usar](#como-usar)
- [Regras do Sistema](#regras-do-sistema)
- [Estrutura do Projeto](#estrutura-do-projeto)

## ⚡ Funcionalidades

- **Depósito**: Adicione dinheiro à sua conta
- **Saque**: Retire dinheiro respeitando os limites
- **Extrato**: Visualize seu histórico de transações
- **Criar Conta**: Crie uma nova conta bancária
- **Listar Contas**: Visualize todas as contas cadastradas
- **Novo Usuário**: Cadastre um novo cliente

## 🔧 Requisitos

- Python 3.x
- Sistema Operacional: Windows, Linux ou macOS

## 📥 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/sistema-bancario.git
```

2. Entre no diretório do projeto:
```bash
cd sistema-bancario
```

## 🚀 Como Usar

1. Execute o arquivo principal:
```bash
python main.py
```

2. Use o menu interativo para:
   - Digite `d` para Depositar
   - Digite `s` para Sacar
   - Digite `e` para ver o Extrato
   - Digite `q` para Sair

## 📌 Regras do Sistema

### Depósitos
- ✅ Aceita apenas valores positivos
- ✅ Não há limite de valor para depósito

### Saques
- ⚠️ Limite de R$ 500,00 por saque
- ⚠️ Máximo de 3 saques diários
- ❌ Não permite saque se saldo insuficiente

### Contas
- 🔑 Número único para cada conta
- 👥 Um cliente pode ter múltiplas contas
- 📝 Necessário CPF e endereço para cadastro

## 🗂️ Estrutura do Projeto

```
sistema-bancario/
│
├── main.py           # Arquivo principal do sistema
├── README.md         # Documentação do projeto
```

## 👥 Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/AmazingFeature`)
3. Faça o Commit de suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Faça o Push para a Branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.