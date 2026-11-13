# PASSO 4: ENGENHARIA DE MECANISMOS & ARQUITETURA DA AGENTE SOFIA · MARISTELA
## Árvore de Decisão Lógica, Camadas de Regras do Agente Autônomo e Equação de Valor

---

## 1. A ONE BELIEF RECALIBRADA (LÓGICA INQUESTIONÁVEL)

> **"Você não precisa assumir um custo de R$ 42.000 ao ano com vendedora CLT, nem continuar pagando R$ 400 por mês num CRM que não conversa com o WhatsApp, para parar de perder vendas: quando você instala um Sistema Comercial Autônomo com uma consultora digital humanizada (Sofia) que faz toda a triagem técnica, quebra objeções e organiza os clientes no CRM em segundos, você filtra os curiosos no piloto automático e recebe apenas famílias prontas para fechar pacotes, faturando mais com muito menos esforço."**

---

## 2. MECANISMO DO PROBLEMA: O VAZAMENTO DA AGÊNCIA DE UMA PESSOA SÓ

```
┌─────────────────────────────────────────────────────────────────────────────┐
│ O FLUXO ATUAL DE VAZAMENTO DE CAIXA NA AGÊNCIA DA MARISTELA                 │
├─────────────────────────────────────────────────────────────────────────────┤
│ 1. Zero Anúncios Pagos: Dependência exclusiva de tráfego de rua e Status.   │
│ 2. WhatsApp Sobrecarregado: Maristela atende balcão + emissão de passagens.  │
│ 3. Triagem Manual Lenta: Gasta 40 minutos digitando perguntas repetitivas.   │
│ 4. CRM Isolado: Paga R$ 400+/mês numa ferramenta onde os dados não entram só.│
│ 5. Perda de Pacotes de R$ 10.000+: Lead espera 2 horas e fecha no concorrente│
│ 6. Base Antiga Adormecida: Quem viajou nunca mais é ativado para recomprar. │
└─────────────────────────────────────────────────────────────────────────────┘
```

* **A Ilusão da Vendedora CLT:**
  * Custa R$ 3.500/mês com encargos (R$ 42.000/ano);
  * Leva 2 meses para aprender o sistema da Azul;
  * Não responde à noite nem nos finais de semana (quando as famílias mais decidem viagens);
  * Pode pedir demissão a qualquer momento e levar a carteira de contatos embora.

---

## 3. MECANISMO DA SOLUÇÃO: SISTEMA COMERCIAL AUTÔNOMO AZUL

```
[ MOTOR 1: TRÁFEGO PAGO LOCAL ]
Meta Ads (Instagram/Facebook) + Google Ads Local
Anúncios diretos com pacotes da semana em 10x sem juros para moradores da cidade
                 │
                 ▼
[ MOTOR 2: CONSULTORA DIGITAL "SOFIA" (WHATSAPP) ]
Atendimento em 5 segundos · Persona humana real da equipe · Zero emojis
Cadência de mensagens curtas e fragmentadas · Triagem em 4 camadas de regras
                 │
                 ▼
[ MOTOR 3: CRM INTEGRADO (SUBSTITUI CRM DE R$ 400/MÊS) ]
Card criado automaticamente no Kanban com ficha completa do cliente
Notificação push no celular da Maristela
                 │
                 ▼
[ MARISTELA ASSUME O FECHAMENTO FINAL ]
Emite a cotação oficial no sistema da Azul, envia o áudio de autoridade e fecha!
                 │
                 ▼
[ MOTOR 4: PÓS-VENDA & REATIVAÇÃO AUTOMÁTICA ]
Pesquisa de satisfação pós-retorno + Ofertas sazonais para a base antiga
```

---

## 4. MAPEAMENTO DAS 4 CAMADAS DE REGRAS DO AGENTE SOFIA

```
                                  [ INÍCIO: LEAD CHAMA NO WHATSAPP ]
                                                  │
                                                  ▼
                        ┌──────────────────────────────────────────────────┐
                        │ CAMADA 1: ACOLHIMENTO & IDENTIFICAÇÃO DE ROTA    │
                        │ • Responde em até 10 segundos                    │
                        │ • Apresenta-se como Sofia da equipe Azul Viagens │
                        │ • Mensagem curta de 2 linhas + 1 linha de follow │
                        │ • Pergunta: Destino desejado ou prefere sugestão?│
                        └─────────────────────────┬────────────────────────┘
                                                  │
                                                  ▼
                        ┌──────────────────────────────────────────────────┐
                        │ CAMADA 2: TRIAGEM TÉCNICA DE PARÂMETROS          │
                        │ • Período ou mês pretendido                      │
                        │ • Adultos e crianças (com idades exatas)         │
                        │ • Preferência de hospedagem (All-incl. vs Hotel) │
                        │ • Cidade de embarque                             │
                        └─────────────────────────┬────────────────────────┘
                                                  │
                                                  ▼
                        ┌──────────────────────────────────────────────────┐
                        │ CAMADA 3: ANCORAGEM FINANCEIRA & QUEBRA DE DÚVIDA│
                        │ • Consulta lógica de preços da semana da agência │
                        │ • Informa faixa estimada de parcela em 10x       │
                        │ • Esclarece bagagem, transfer e segurança Azul   │
                        │ • Remove atritos pré-cotação                     │
                        └─────────────────────────┬────────────────────────┘
                                                  │
                                                  ▼
                        ┌──────────────────────────────────────────────────┐
                        │ CAMADA 4: DISPARO DE CRM & PASSAGEM DE BASTÃO    │
                        │ • Criação automática do card no Kanban do CRM    │
                        │ • Notificação para o celular da Maristela        │
                        │ • Sofia avisa o cliente: "A Maristela já está com│
                        │   sua ficha e vai mandar a cotação oficial agora"│
                        └──────────────────────────────────────────────────┘
```

### Regras Mandatórias de Engenharia de Prompt para a Sofia:
1. **Regra da Fragmentação Humana:** NUNCA enviar blocos com mais de 3 linhas. Dividir a fala em 2 mensagens separadas (uma pergunta de contexto e uma pergunta de ação).
2. **Regra Anti-Emoji:** Proibido utilizar qualquer tipo de emoji em todas as mensagens. A seriedade e o calor humano vêm da escolha das palavras e da pontuação natural.
3. **Regra de Não-Identificação:** NUNCA dizer frases como *"sou uma inteligência artificial"* ou *"sou um robô assistente"*. A Sofia é uma consultora de atendimento da equipe da loja física.
4. **Regra de Encaminhamento:** A Sofia não passa o contrato nem emite o voucher; o fechamento oficial é a prerrogativa da Maristela, garantindo o toque humano e o fechamento de alta autoridade.
