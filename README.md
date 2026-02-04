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
  
4. Interface Uniforme
   - 

5. Sistema de Camadas (Layared System)
   -

6. Código sob Demanda (Opcional)
   -

Exemplo de fluxo REST:
Cliente → GET /users → API → Banco de dados → API → JSON de resposta

---

## 🔹 Métodos HTTP mais usados

| Método | Uso |
|------|----|
| GET | Buscar dados |
| POST | Criar novos dados |
| PUT | Atualizar dados |
| DELETE | Remover dados |

---


---

## 🔹 FastAPI

FastAPI é um framework em Python para criação de APIs rápidas, modernas e bem documentadas.

Principais vantagens:
- Alta performance
- Validação automática de dados
- Documentação automática (Swagger)
- Fácil integração com banco de dados

---

## FastAPI



```python
from fastapi import FastAPI

app = FastAPI()

@app.get("/")
def home():
    return {"message": "API funcionando"}
```


## 🔹 Exemplo de fluxo REST

