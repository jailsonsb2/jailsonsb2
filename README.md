# Olá, eu sou o Jailson Bezerra! 👋

### Engenheiro Eletricista | Arquiteto de Software | Data & IoT

> 🌎 **EN:** Electrical Engineer and software architect. I build end-to-end systems that connect hardware to the cloud — IoT telemetry, real-time radio streaming APIs, AI multi-agent automation and mobile apps. Creator of one of the first open-source "now playing" metadata APIs for web radio players — a response format that was widely copied and today underpins third-party radio systems around the world (80+ ⭐ across the player family, now with synchronized YouTube clip mode).

Sou Engenheiro Eletricista com sólida bagagem em eletrônica, experiência no setor público e gestão estratégica de telecomunicações. Uno engenharia de hardware e desenvolvimento de software para projetar ecossistemas de dados, automações assíncronas de missão crítica, arquiteturas multi-agentes de IA (LLMs) e soluções de IoT de ponta a ponta.

Criei e publiquei em código aberto uma das primeiras APIs de metadados "now playing" para rádios online — o formato de resposta que desenhei foi amplamente reutilizado pela comunidade e hoje serve de base para players e sistemas de rádio de terceiros em vários países. Como desenvolvedor independente e fundador da **JBCAST - App Dev**, construo e gerencio plataformas completas que unem backends estáveis, integrações de mídia, aplicativos mobile e soluções de mobilidade urbana inteligente com forte impacto no Distrito Federal.

---

## 🛠️ Tecnologias & Stack Tecnológica

- **Backend & Engenharia de Dados:** Python, SQL, PHP, Node.js, RabbitMQ (Mensageria assíncrona), Selenium (Web Scraping Avançado), InfluxDB (Time-series)
- **Inteligência Artificial & NLP:** Google Gemini API (Arquiteturas Multi-Agentes / ReAct), Processamento de Linguagem Natural (NLP/spaCy), Engenharia de Prompts Estruturada, Pandas
- **Especialidades Web & Mídia:** WordPress, Elementor, AJAX, APIs RESTful, Streaming/Radio Players, Integração em Tempo Real
- **Mobile & Observabilidade:** Android App Development (Java/Kotlin/PWAs), Grafana, Power BI, Qlik Sense (Painéis analíticos e monitoramento de infraestrutura/NOC)
- **Hardware & IoT:** Sistemas Embarcados (ESP32, ESP8266), Protocolos de Comunicação (MQTT), Sensores de Energia (PZEM-004T), Hardware e Interfaciamento Elétrico

---

## 🚀 Projetos em Destaque

### 🚌 [DF Bus - Horários de Ônibus DF](https://play.google.com/store/apps/details?id=com.jbcast.dfbus)
*Aplicativo mobile independente e plataforma de mobilidade urbana ativa no Distrito Federal.*
- **Arquitetura & Engenharia:** Backend otimizado para consumo, tratamento e pipelines de APIs governamentais e dados brutos de telemetria/GPS em tempo real (Semob-DF).
- **IA Agêntica:** Integração avançada com LLMs (Gemini API) para permitir consultas de rotas e horários complexos via linguagem natural.
- **UX & Resiliência:** Arquitetura focada em privacidade, "Modo Soneca" baseado em geofencing e distribuição multiplataforma via PWA estável.

### 📻 [Radioplayer & Ecossistema de Mídia (JBCAST)](https://github.com/jailsonsb2/Radioplayer_api)
*Soluções de backend e streaming voltadas para o ecossistema de rádio digital e aplicativos móveis.* — **[demo ao vivo](https://radio.jailson.es/)** · **[docs da API + testador](https://jailsonsb2.github.io/now-playing-api/)**
- **Destaque Técnico:** API de metadados em **PHP + Redis** (worker assíncrono, cache na borda e **Server-Sent Events**) alimentando players web e móveis em tempo real, com enriquecimento via iTunes/Spotify/Deezer **e resolução do clipe no YouTube** — os players exibem o vídeo da música **sincronizado com a rádio**.
- **Open Source:** Família de players com adoção real da comunidade (80+ ⭐) — [RadioPlayer](https://github.com/jailsonsb2/RadioPlayer) (30★), [Radioplayer_api](https://github.com/jailsonsb2/Radioplayer_api) (25★), [RadioPlayer-ZenoRadio](https://github.com/jailsonsb2/RadioPlayer-ZenoRadio) (21★) e o [bottom_radioplayer](https://github.com/jailsonsb2/bottom_radioplayer) — componente de rodapé em que **o áudio não para enquanto o visitante navega pelo site** (navegação seamless).
- **Origem do formato:** a primeira versão pública desta API ([RadioplayerAPI](https://github.com/jailsonsb2/RadioplayerAPI), jun/2024 — preservada como registro histórico) foi amplamente reutilizada pela comunidade; o mesmo formato de resposta aparece hoje em sistemas de rádio de terceiros em vários países. A [documentação pública](https://github.com/jailsonsb2/now-playing-api) define o contrato atual (incluindo `youtubeId` e o princípio "o ICY é lei").
- **Distribuição Mobile:** Publicação e gerenciamento de aplicações nativas e híbridas para **Android**, garantindo alta disponibilidade de streaming e interfaces responsivas construídas com **WordPress e Elementor**.

### 🤖 Enterprise NOC Agent (AI-Driven Automation)
*Sistema multi-agente assíncrono para triagem e diagnóstico automatizado de infraestrutura.*
- **Destaque Técnico:** Orquestração baseada em filas com **RabbitMQ** e workers de automação em **Python/Selenium** para capturar, categorizar e diagnosticar alarmes de conectividade.
- **Análise & Inteligência:** Redução drástica do tempo de resposta (MTTR) em ambientes de Telecom por meio de triagem automatizada com LLMs e fallbacks seguros de execução.

### ⚡ [Smart IoT Energy Monitor](https://github.com/jailsonsb2/monitoramento-iot)
*Sistema embarcado de ponta a ponta para monitoramento analítico de eficiência energética.*
- **Hardware & Edge:** Integração de microcontroladores (ESP32/ESP8266) com sensores analíticos **PZEM-004T** para coleta e processamento na ponta de métricas elétricas reais.
- **Data Pipeline & Observabilidade:** Telemetria estruturada via protocolo **MQTT** com persistência em banco de dados de séries temporais (**InfluxDB**) e dashboards analíticos em tempo real via **Grafana**.

### ⚖️ [Participa-DF-Lite](https://github.com/jailsonsb2/Participa-DF-Lite)
*Solução GovTech ágil focada em transparência pública e conformidade de dados.*
- **Destaque Técnico:** Pipelines de dados em Python usando expressões regulares avançadas (Regex) e técnicas de NLP (`spaCy`) para extração automatizada de metadados, higienização de strings e anonimização de dados sensíveis em conformidade com a **LGPD**.

---

## 📊 Estatísticas do GitHub

<!-- Instância comunitária do github-readme-stats (a oficial vive em rate-limit).
     Se a imagem parar de carregar: faça deploy gratuito do github-readme-stats
     na sua conta Vercel (https://github.com/anuraghazra/github-readme-stats#deploy-on-your-own)
     e troque o domínio abaixo pelo seu. -->
<p align="left">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=jailsonsb2&show_icons=true&theme=tokyonight&include_all_commits=true" alt="Estatísticas do GitHub de Jailson" width="400" />
</p>

### 📈 Histórico de Contribuições
<p align="left">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=jailsonsb2&theme=tokyonight&area=true" alt="Gráfico de Atividade de Jailson" width="100%" />
</p>

---

## 📫 Vamos nos conectar?

- **LinkedIn:** [linkedin.com/in/jailsonsb](https://linkedin.com/in/jailsonsb)
- **E-mail Profissional:** [contato@jailson.es](mailto:contato@jailson.es)
- **Rádio demo (player + API ao vivo):** [radio.jailson.es](https://radio.jailson.es/)
- **Portfólio Backend / Dev Entity:** JBCAST - App Dev
