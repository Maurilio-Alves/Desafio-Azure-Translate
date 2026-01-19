# 🌍 Desafio de Projeto: Tradutor Multilíngue com Azure AI

Este projeto foi desenvolvido como parte do desafio prático sobre **Processamento de Linguagem Natural (NLP)** na trilha de Inteligência Artificial da DIO em parceria com a Microsoft.

## 📖 Sobre o Projeto
O objetivo deste desafio foi criar um tradutor automático utilizando os serviços de IA da Azure. O script desenvolvido é capaz de receber textos em Português e realizar a tradução simultânea para diversos idiomas, demonstrando o poder das APIs de tradução da Microsoft.

## 🛠️ Tecnologias e Serviços Utilizados
- **Azure AI Translator**: Serviço de nuvem para tradução de texto em tempo real.
- **Python**: Linguagem utilizada para integração com a API.
- **Biblioteca Requests**: Para gerenciar as chamadas de API via HTTP.
- **VS Code**: Ambiente de desenvolvimento.

## 🚀 Funcionalidades
- **Detecção Automática**: Identifica o idioma de entrada.
- **Tradução em Massa**: Traduz para Inglês e Espanhol em uma única chamada.
- **Segurança**: Estrutura preparada para uso de variáveis de ambiente.

## 📦 Como reproduzir o projeto
1. Tenha uma conta ativa no **Azure Portal**.
2. Crie um recurso de **Tradução (Translator)**.
3. Copie sua **Chave** e **Localização** (ex: eastus).
4. No arquivo `translator.py`, insira suas credenciais.
5. Instale as dependências: `pip install requests`
6. Execute o script: `python translator.py`

---
*Desenvolvido por Maurílio durante o curso de IA da Microsoft na DIO.*