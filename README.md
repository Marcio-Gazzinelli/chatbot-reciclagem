# Chatbot de Reciclagem

## 1 Descrição do Projeto
O **Chatbot de Reciclagem** é uma aplicação educativa que auxilia usuários a descartar corretamente diferentes tipos de resíduos e adotar práticas sustentáveis no dia a dia.  
O projeto contribui com a **ODS 12 – Consumo e Produção Responsáveis**, promovendo conscientização ambiental e redução de impactos negativos do lixo no meio ambiente.

---

## 2 Objetivo do Projeto
Fornecer um **meio interativo** para informar usuários sobre:

- ✅ Descarte correto de pilhas, garrafas, eletrônicos, plásticos, vidros e outros resíduos;  
- ✅ Práticas de reciclagem e reutilização de materiais;  
- ✅ Pontos de coleta e alternativas de reaproveitamento.

---

## 3 Problema que será resolvido
Muitas pessoas **não sabem como separar e descartar corretamente os resíduos**, causando:  

- ⚠️ Aumento do lixo em locais inadequados;  
- ⚠️ Contaminação ambiental;  
- ⚠️ Desperdício de materiais recicláveis.

O chatbot fornecerá respostas claras e práticas, tornando o descarte e a reciclagem mais acessíveis.

---

## 4 Tipo de Solução
- **Software interativo:** chatbot baseado em regras e base de dados pré-definida;  
- **Funcionalidade principal:** responder dúvidas sobre descarte de resíduos e práticas de reciclagem.

---

## 5 Os Requisitos Do Projeto

### Requisitos Funcionais
O chatbot deverá:

1. Responder perguntas sobre descarte correto de diferentes tipos de resíduos (plásticos, vidro, pilhas/baterias, eletrônicos, papel, orgânicos, etc.).  
2. Fornecer instruções claras e didáticas sobre como reciclar ou descartar corretamente cada tipo de resíduo.  
3. Sugerir alternativas de reutilização e reaproveitamento de materiais sempre que possível.  
4. Responder perguntas frequentes (FAQ) previamente cadastradas na base de dados.  
5. Permitir interação via texto, oferecendo respostas para perguntas pré cadastradas  
6. Consultar uma base de dados estruturada de perguntas e respostas para gerar as respostas ao usuário.  

### Requisitos Não Funcionais
O chatbot deverá:

1. Ter tempo de resposta rápido (≤ 10 segundos) para interação com o usuário.  
2. Ser intuitivo e fácil de usar, mesmo para pessoas sem experiência em tecnologia.  
3. Possuir base de dados fácil de atualizar e manter, permitindo inclusão de novas perguntas e respostas.  
4. Ser compatível com diferentes dispositivos.  
5. Documentação clara e organizada no repositório GitHub, para fácil entendimento e manutenção.  
6. Ser seguro, sem armazenar informações pessoais sensíveis dos usuários.
   
---

## 6 Diagrama de Caso de Uso
-
            +-------------------+
            |    Usuário        |
            +-------------------+
                    |
                    | Faz pergunta sobre reciclagem
                    v
            +-------------------+
            |   Chatbot         |
            +-------------------+
            | - Recebe pergunta |
            | - Consulta base   |
            | - Responde        |
            +-------------------+
                    |
                    v
          +---------------------+
          | Base de Dados/FAQ   |
          +---------------------+

Ator principal: Usuário

Sistema: Chatbot de reciclagem

Fluxo principal: Usuário pergunta → Chatbot consulta base → Chatbot responde

---

## [Ir Para o GitHub Projects](https://github.com/users/Marcio-Gazzinelli/projects/1/views/1)
