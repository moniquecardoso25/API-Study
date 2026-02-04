# Estudo sobre API REST com FastAPI

Este repositório com objetivo de demonstrar meus conhecimentos e estudos sobre **APIs**, **API REST**, **HTTP**, **FastAPI** e **integração com banco de dados SQL**, com exemplos simples e objetivos.

---

##  O que é uma API?

API (Application Programming Interface) é uma forma de sistemas diferentes se comunicarem entre si, segundo um conjunto um conjunto de definições e protocolos.  
Ela define **como pedir informações**, **como enviar dados** e **como receber respostas**, que possibilita a integração de serviços e a criação de aplicativos. 

Exemplo simples:  
Um front-end faz uma requisição → A API processa → Retorna dados em JSON (mais comum).

---

## O que é uma API REST?

API REST segue um conjunto de regras e diretrizes relacionados a criação de uma API, além de seguir 6 princípios de arquitetura REST que são:

1. Arquitetura Cliente-Servidor:
   - Separação entre cliente (consome os dados) e servidor (armazena e fornece os dados).
     
2. Stateless (Estado)
   - Cada requisição feita do cliente para o servidor deve conter toda a informação que o servidor precisa para entendimento e processamento da requisição.

3. Cachable (Cacheável)
   -  As respostas da API REST precisam ser cacheadas, indicando se ela pode ou não ser armazenadas em cache pelo cliente ou por um servidor de cache intermediário. Isso melhora a performance e reduz a carga do servidor.
     Feito através de cabeçalhos HTTP na resposta : 'Cache-Control' e 'Expires'.
  
4. 

---

## 🔹 Métodos HTTP mais usados

| Método | Uso |
|------|----|
| GET | Buscar dados |
| POST | Criar novos dados |
| PUT | Atualizar dados |
| DELETE | Remover dados |

---

## 🔹 Exemplo de fluxo REST

