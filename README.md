# 💸 Primeiro App de Finanças Pessoais com Vibe Coding utilizando o Lovable

Objetivo é aprender com o curso da DIO a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 🎯 Desafio

Problema: Muitas pessoas não conseguem manter um controle financeiro porque os aplicativos exigem muita entrada de dados manual, e a criação de orçamentos é vista como algo tedioso. 

Precisamos de uma solução que permita **controlar as finanças por meio de uma conversa simples**, com **agentes de IA** capazes de criar **planos de economia personalizados e automatizados**. Você deve utilizar as ideias de **Vibe Coding** e **MVP (Produto Mínimo Viável)** para desenvolver o **conceito de um aplicativo** que resolva o problema citado.

> [!IMPORTANT]
> Você **não precisa construir o código**! O foco está em **usar a IA como sua parceira criativa**, transformando boas ideias e prompts em conceitos funcionais que simulam um produto real.

## 🪄 Etapas do Desafio

### 1. Saber o que Pedir é a Chave! Otimize seus Prompts!

Antes de pedir para a IA "criar um app", é importante definir com clareza o que você quer construir e por quê. Para isso, você vai criar um **PRD (Product Requirements Document)** simplificado, uma especificação que serve como _briefing_ para a IA entender sua ideia.

Um bom PRD deve descrever o problema, quem será beneficiado, as principais funcionalidades e o que você espera que a IA entregue. Use o modelo abaixo como ponto de partida e adapte conforme o seu estilo:

```txt
# 📄 PRD – App de Organização de Finanças Pessoais via Chat

## 1. Contexto
Criar um aplicativo de **organização financeira pessoal** que funcione por meio de conversas naturais.  
O usuário interage com um **chat** para registrar despesas e receitas, que são automaticamente classificadas e exibidas em um painel simples.  
Neste primeiro momento, o app será baseado em uma **página web**.

---

## 2. Problema
- Apps de finanças atuais exigem **entrada manual extensa** (formulários, planilhas).  
- Pouca personalização e experiência engessada.  
- Usuários iniciantes acabam desistindo por falta de praticidade.  

**Solução proposta:**  
Um app que usa **linguagem natural** para registrar transações e fornece **dicas automáticas de economia**, tornando o processo leve e acessível.

---

## 3. Público-Alvo
- Pessoas que querem começar a organizar suas finanças sem complicação.  
- Usuários iniciantes em controle financeiro.  
- Jovens adultos e profissionais que buscam praticidade.

---

## 4. Funcionalidades-Chave (MVP)
1. **Página de Login e Cadastro**  
   - Usuário pode criar conta com e-mail e senha.  
   - Login simples para acessar suas carteiras e dados.  

2. **Chat de Registro de Transações**  
   - Usuário digita: “Gastei 50 reais no mercado” → sistema registra como despesa, categoria “Alimentação”.  
   - “Recebi 200 reais de freelas” → sistema registra como receita.  

3. **Classificação Automática**  
   - Tags sugeridas com base na linguagem natural (ex: mercado → alimentação, Uber → transporte).  

4. **Dashboard Simples**  
   - Balanço financeiro com:  
     - Receita (verde)  
     - Despesa (vermelho)  
   - **Toda despesa ou receita lançada deve aparecer automaticamente no dashboard.**  
   - Gráfico ou lista resumida.  

5. **Extrato Filtrável**  
   - Usuário pode pedir: “Mostrar despesas de alimentação” ou “Receitas do mês”.  

6. **Carteiras Individuais e Compartilhadas**  
   - Duas carteiras iniciais: **Pessoal** e **Casa**.  
   - Usuário escolhe via chat ou botão rápido em qual carteira lançar a transação.  
   - Dashboard mostra saldo e balanço **separado por carteira**.  
   - **Carteira da Casa Compartilhada**:  
     - Apenas despesas.  
     - Cada despesa registrada deve mostrar o **nome do usuário logado** que lançou.  
   - Futuramente: criação de carteiras adicionais e compartilhamento entre múltiplos usuários.

---

## 5. Funcionalidades Futuras (não no MVP, mas planejadas)
- **Agente Financeiro**: dicas de economia personalizadas.  
- **Alertas inteligentes**: “Você gastou 20% a mais em transporte este mês”.  
- **Integração com bancos/cartões** para importação automática.  
- **Carteira compartilhada completa** (com receitas e múltiplos usuários).  

---

## 6. Entregáveis do MVP
- **Principais telas**:  
  - Tela de login/cadastro.  
  - Tela de chat (entrada de dados).  
  - Dashboard simples (saldo, receitas, despesas).  
  - Tela de extrato filtrável.  
  - Visualização separada por carteira (Pessoal e Casa).  
  - Registro de despesas da casa com nome do usuário logado.  

- **Recursos necessários**:  
  - Autenticação básica (login/cadastro).  
  - Processamento de linguagem natural (para interpretar entradas).  
  - Banco de dados simples (armazenar transações e usuários).  
  - Interface básica (chat + dashboard).  

- **Validação inicial**:  
  - Testar com 5–10 usuários iniciantes.  
  - Observar se conseguem registrar transações sem esforço.  
  - Verificar se todas as transações aparecem corretamente no dashboard.  
  - Coletar feedback sobre clareza do dashboard e utilidade do extrato.  

---

## 7. Design Universal ✨
A solução deve ser construída com base em **Design Universal**, garantindo que:  
- O aplicativo seja **intuitivo e acessível** para iniciantes e usuários experientes.  
- Interfaces com **contraste adequado, fontes legíveis e navegação simples**.  
- Compatibilidade com **recursos de acessibilidade** (ex: leitores de tela, legendas, comandos de voz).  
- Dashboard visual e direto, com cores e ícones que facilitem a compreensão.  

---

## 8. Sugestões para MVP
- **Começar pequeno**: login/cadastro + chat + dashboard + extrato + carteiras básicas.  
- **Evitar complexidade inicial**: não incluir integração bancária ou IA avançada logo de cara.  
- **Iterar rápido**: após validar, adicionar o “Agente Financeiro” com dicas simples (ex: “Você gastou muito em alimentação este mês”).  

---

## 9. Mini Wireframe Textual

**Tela de Login/Cadastro**  
- Campos: e-mail, senha.  
- Botão: [Entrar] [Cadastrar].  

**Tela de Chat**  
- Campo de entrada: “Gastei 100 reais no supermercado [Casa]”  
- Sistema entende: despesa, categoria alimentação, carteira da casa.  
- Sugestão de tags rápidas: [Pessoal] [Casa]  

**Tela de Dashboard**  
- Seção “Carteira Pessoal”: saldo, receitas, despesas.  
- Seção “Carteira da Casa”: saldo, despesas (com nome do usuário que lançou).  
- **Todas as transações (despesas e receitas) aparecem automaticamente aqui.**  
- Cores contrastantes (verde para receita, vermelho para despesa).  

**Tela de Extrato**  
- Filtros: por categoria, por período, por carteira.  
- Lista clara e legível, com ícones simples.  

```

Depois de preencher o modelo, use o Copilot Web para revisar e melhorar o seu prompt antes de ir ao Lovable. A ideia é lapidar o texto até que ele fique claro, direto e reflita exatamente a sua intenção.

> [!TIP]
> Pense no PRD/Prompt como “o briefing que a IA precisa para entender sua vibe”. Portanto, quanto mais claro e intencional for o texto, mais próximas do ideal serão as respostas da IA.

### 2. Explorando o Lovable na Prática

Com seu PRD pronto e revisado, é hora de colocar a IA em ação. Abra o Lovable, cole seu prompt completo e peça o plano inicial do MVP do seu aplicativo. Como o plano gratuito limita você a 5 interações por dia, seja estratégico:
- Faça perguntas diretas e construtivas, como “crie o fluxo de telas com base nas funcionalidades listadas” ou “gere uma versão resumida do plano de MVP”;
- Priorize clareza nas instruções para aproveitar ao máximo cada resposta;

Durante essa etapa, você pode orientar a IA para três entregas principais:
1. Agente Financeiro: defina o comportamento e o tom de voz de um consultor financeiro pessoal, alinhado ao público e objetivo do app.
2. Fluxo de Telas: peça à IA para gerar o fluxo conceitual de telas com base nas funcionalidades descritas no PRD, simulando a interação por conversa.
3. Plano de MVP: solicite um resumo das 5 funcionalidades principais, dos recursos necessários e um plano de validação inicial (como medir se o app cumpre seu propósito).

> [!TIP]
> Se preferir, você pode fazer tudo com o **Copilot**. O importante é exercitar a habilidade de transformar intenções em instruções claras e testar os limites da IA como parceira criativa.

### 3. Entregando o Desafio na DIO

Finalize seu projeto criando um **repositório no GitHub** (pode ser um **fork** deste).  
No README do seu repositório, inclua:

- Seu **prompt final** (PRD);  
- Prints ou pequenos vídeos das interações com a IA;  
- Um resumo do que o seu **App de Finanças Pessoais** faz;  
- Uma breve **reflexão sobre o processo**:
  - O que funcionou bem?  
  - O que não funcionou como o esperado?  
  - O que aprendeu sobre conversar com IAs?

> [!TIP]
> Publique seu repositório e compartilhe o link na plataforma da DIO! Sua entrega é a prova de que você domina o raciocínio de Vibe Coding, mesmo sem escrever uma única linha de código.

## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.


## Prints do APP
<img width="1365" height="732" alt="image" src="https://github.com/user-attachments/assets/735db93a-ba32-4d26-a10b-4a6cdfb4d5c1" />

<img width="1339" height="725" alt="image" src="https://github.com/user-attachments/assets/23869791-e6b8-4fe3-a9cf-bd50bdb70617" />

<img width="1364" height="725" alt="image" src="https://github.com/user-attachments/assets/fa807543-8dc1-4b04-ad49-49619b16d1e8" />

<img width="1354" height="722" alt="image" src="https://github.com/user-attachments/assets/1aeadfbf-c557-4fae-bb46-cc1abd50ca56" />




