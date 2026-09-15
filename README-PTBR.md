<div align="center">

<img src="./dcsemfundooriginal.png" width="150" alt="DC Foundry Digital" />

# Vitor Henrique Camillo

### Engenheiro de Software · Tech Lead · Full Stack · IA & LLMs

[English](./README.md) · **Português 🇧🇷**

Curitiba, Brasil · Aberto a oportunidades no Brasil, Portugal e União Europeia

[LinkedIn](https://linkedin.com/in/vitor-henrique-camillo) · [GitHub](https://github.com/Camillox2) · [Portfólio](https://dcfoundrydigital.com) · [E-mail](mailto:vitorcamilloh@gmail.com)

</div>

---

## Sobre mim

Sou **Engenheiro de Software**, formado pela **Universidade Positivo em julho de 2026**, e atualmente atuo como **Tech Lead & Desenvolvedor Full Stack na Vital Scheffer**.

Meu trabalho combina **liderança técnica, arquitetura, desenvolvimento full stack, integrações corporativas, automação e inteligência artificial aplicada**. Hoje lidero o desenvolvimento de sistemas que conectam comercial, fábrica, logística, financeiro, e-commerce e atendimento, além de gerenciar diretamente **2 estagiários de desenvolvimento**.

Gosto de construir produtos de ponta a ponta: entender o problema, desenhar a solução, implementar backend e frontend, integrar serviços, revisar código, publicar, observar em produção e evoluir o produto com o time.

---

## O que faço hoje

### Vital Scheffer — Tech Lead & Desenvolvedor Full Stack

**Liderança e processo**
- Gestão e acompanhamento técnico de **2 estagiários**
- Priorização de demandas, revisão de código e acompanhamento de entregas
- Uso de **Scrum, dailies e weeklies** no fluxo do time
- Uso de **Gemini** para revisão assistida de Pull Requests e análise de código, sempre com validação humana antes do merge

**MKI Hub**
- Integração entre **ERP OMIE** e **Shopee, Amazon, Mercado Livre e TikTok Shop**
- Sincronização de estoque e cruzamento de SKUs
- Detecção de anúncios divergentes
- Mapeamento de concorrentes
- Curva ABC e apoio à operação de e-commerce

**NextStep CRM**
- CRM corporativo com **ANA AI**, baseada em Gemini, para atendimento e qualificação de clientes
- KPIs e visão gerencial
- Módulos de PCP e Licitações
- Chat interno com ligações e compartilhamento de tela via **WebSockets**
- Painel de logística e cotação de fretes
- Contratos e checklists via **D4Sign**
- Conciliação de pagamentos e baixa de títulos no OMIE

**VitalOps**
- Ferramentas para a operação da fábrica
- Fluxos de de/para de códigos antigos para novos
- Movimentações automáticas de estoque no OMIE
- Visualização 3D de produtos
- Aprovação de projetos personalizados

Também desenvolvo e mantenho páginas institucionais e landing pages da empresa, incluindo **vitalscheffer.com.br**.

---

## Projeto em destaque — Keilinks Core 380M

### [Keilinks — LLM PT-BR autoral](https://github.com/Camillox2/Keilinks)

O **Keilinks Core 380M** é meu projeto de pesquisa e engenharia em modelos de linguagem locais. O modelo principal não é apenas um fine-tuning de um LLM pronto: a arquitetura Transformer é implementada no próprio projeto e os pesos são inicializados e treinados pelo pipeline do Keilinks.

- ~**380 milhões de parâmetros**
- Transformer decoder em **PyTorch**
- Vocabulário de **32.000 tokens**
- **24 camadas**, GQA, RoPE, RMSNorm, SwiGLU e QK-Norm
- Contexto de **8.192 tokens** e KV cache
- Pré-treinamento próprio + **SFT conversacional**
- Pipeline de dados com limpeza, deduplicação e proveniência
- **RAG local**, grounding e experimentos com memória
- Treino local em **RTX 5050 Laptop 8 GB**
- Otimizações com BF16/TF32, AdamW 8-bit, gradient checkpointing e `torch.compile`

Modelos externos podem ser utilizados como **teacher/critic** para auxiliar em parte dos dados sintéticos, mas não substituem os pesos do Keilinks Core.

---

## Experiência profissional

| Período | Empresa | Função |
|---|---|---|
| **Jun 2026 — Atual** | Vital Scheffer | **Tech Lead & Desenvolvedor Full Stack** |
| **Nov 2025 — Dez 2025** | DIXI Soluções | Desenvolvedor Full Stack |
| **Jun 2025 — Nov 2025** | Tecnoponto | Desenvolvedor Full Stack |
| **Jan 2025 — Jun 2025** | EVO Sistemas Inteligentes | Estagiário de Desenvolvimento |

> EVO Sistemas Inteligentes, Tecnoponto e DIXI Soluções fazem parte do mesmo grupo empresarial.

Na EVO, projetei e implementei o ecossistema de controle de ponto **IPM**, em Node.js e Java, responsável pelo gerenciamento dos registros de ponto de **8 prefeituras**. Também trabalhei com integração a hardware de reconhecimento facial, MySQL em tempo real, React Native, Java e Flutter.

Na Tecnoponto, assumi o ecossistema de controle de ponto end-to-end, desenvolvendo aplicativo React Native para iOS/Android, APIs Java, publicação na App Store e Google Play, além de evolução da plataforma web em Flutter.

Na DIXI, atuei na sustentação e evolução da plataforma principal, corrigi falhas críticas em produção e desenvolvi uma aplicação de estoque integrada ao **ERP OMIE** com React, Java e MySQL.

---

## Projetos selecionados

### [Grupo YR Hospitalar — Site Institucional + CRM](https://github.com/Camillox2/grupoyr)
Projeto comercial full stack para venda e locação de equipamentos hospitalares, com **React, Vite, Neon Serverless, Gemini, Vercel e Cloudflare**.

Site em produção: [site.grupoyrhospitalar.com.br](https://site.grupoyrhospitalar.com.br)

### Entre Fases
Aplicativo mobile de saúde feminina com **React Native, Java Spring Boot e Gemini AI**, cobrindo ciclo menstrual, gravidez e menopausa.

### [Dr. Adriano Camillo — Site Institucional](https://dradrianocamillo.com)
Site responsivo em React.js entregue como projeto freelance e publicado em produção.

### [CNHora — Landing Page](https://cnhora.com.br)
Landing page responsiva focada em conversão, desenvolvida com HTML, CSS e JavaScript.

### Sapphire Days
Visual novel publicada em Ren'Py, com múltiplas rotas, sistema de escolhas, trilha sonora original e versões para Windows, macOS e Linux.

---

## Stack técnica

**Frontend & Mobile**  
<kbd>React</kbd> <kbd>Next.js</kbd> <kbd>TypeScript</kbd> <kbd>JavaScript</kbd> <kbd>Tailwind CSS</kbd> <kbd>React Native</kbd> <kbd>Flutter</kbd>

**Backend & Integrações**  
<kbd>Node.js</kbd> <kbd>Java</kbd> <kbd>Spring Boot</kbd> <kbd>REST APIs</kbd> <kbd>WebSockets</kbd> <kbd>OMIE</kbd> <kbd>D4Sign</kbd>

**IA & Machine Learning**  
<kbd>Python</kbd> <kbd>PyTorch</kbd> <kbd>Transformers</kbd> <kbd>LLM Training</kbd> <kbd>SFT</kbd> <kbd>RAG</kbd> <kbd>Gemini</kbd> <kbd>Ollama</kbd>

**Dados, Cloud & DevOps**  
<kbd>PostgreSQL</kbd> <kbd>PostGIS</kbd> <kbd>MySQL</kbd> <kbd>SQLite</kbd> <kbd>Redis</kbd> <kbd>Docker</kbd> <kbd>AWS</kbd> <kbd>Git</kbd> <kbd>GitHub</kbd> <kbd>Vercel</kbd> <kbd>Cloudflare</kbd>

---

## Formação

**Bacharelado em Engenharia de Software**  
Universidade Positivo — Curitiba, PR  
**Concluído em julho de 2026**

---

## Certificações e desenvolvimento profissional

<details>
<summary><strong>Ver certificações</strong></summary>

### OpenAI
- Agents and Workflows — 2026

### Anthropic
- AI Fluency for Builders — 2026
- AI Fluency for Small Businesses — 2026
- Introduction to Subagents — 2026
- AI Capabilities and Limitations — 2026
- AI Fluency Framework & Foundations — 2026

### Google
- Agentes de IA Generativa — 2026
- Apps de IA Generativa — 2026
- IA Generativa: cenário atual — 2026
- IA Generativa: para além do chatbot — 2026
- IA Generativa: conceitos básicos — 2026

### NVIDIA
- Getting Started with AI on Jetson Nano — 2026

### AWS / Alura
- Preparação AWS Cloud Practitioner — Domínios 1 & 2 — 2026
- Preparação AWS Cloud Practitioner — Domínios 3 & 4 — 2026

### Cisco
- Inglês para TI 1 — nível técnico B2
- Segurança de Endpoint

### Outros destaques
- ExxonMobil Data & Analytics Day — Universidade Positivo
- Workshop de Liderança e Comunicação — Universidade Positivo
- Palestrante no VIASOFT Connect
- TCS CodeVita Season 12 Master Class

</details>

---

## Aberto a oportunidades

Tenho interesse em posições de:

**Full Stack Development** · **Backend Engineering** · **React / Next.js / Node.js** · **Java / Spring Boot** · **Python / IA / LLM Engineering** · **Software Engineering** · **Liderança técnica**, quando compatível com o nível esperado da vaga.

Aberto a **CLT, PJ, freelance, trabalho remoto e oportunidades internacionais**.

<div align="center">

### Software útil, automação que resolve problemas reais e IA aplicada com propósito.

[LinkedIn](https://linkedin.com/in/vitor-henrique-camillo) · [Portfólio](https://dcfoundrydigital.com) · [E-mail](mailto:vitorcamilloh@gmail.com)

</div>
