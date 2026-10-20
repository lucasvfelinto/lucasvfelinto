<div align="center">

<img src="assets/header.gif" width="100%" alt="Banner em pixel art: skyline de Recife à noite" />

<a href="https://github.com/lucasvfelinto">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1400&color=00E5FF&center=true&vCenter=true&width=760&lines=Engenharia+de+software+aplicada+a+LLMs;Sa%C3%ADda+estruturada%2C+valida%C3%A7%C3%A3o+e+avalia%C3%A7%C3%A3o+com+gabarito;RAG+%C2%B7+MCP+%C2%B7+agentes+%C2%B7+fine-tuning;Python+%C2%B7+React+%C2%B7+Django+%C2%B7+Vue.js" alt="Texto animado com as áreas de atuação" />
</a>

<br/><br/>

<img src="assets/globe.gif" height="380" alt="Globo em pixel art girando, com Recife marcada" />
<br/>
<img src="assets/dev.gif" height="210" alt="Avatar em pixel art digitando em um terminal" />

<br/><br/>

<a href="https://www.linkedin.com/in/lucasvfelinto/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="https://lucas-felinto-curriculo_2022.surge.sh/" target="_blank"><img src="https://img.shields.io/badge/-My%20WebSite-%23000000?style=for-the-badge&logo=website&logoColor=white&color=purple"></a>
<a href = "mailto: lucas.felinto.office@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
<a href="https://instagram.com/lucasvfelinto" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
<a href="https://bento.me/lucasvfelinto" target="_blank"><img src="https://img.shields.io/badge/-More%20About%20Me-0D1117?style=for-the-badge&logo=bento&logoColor=00E5FF"></a>

<br/><br/>
<img src="https://komarev.com/ghpvc/?username=lucasvfelinto&label=Visitas&color=00E5FF&style=for-the-badge" />

</div>

## Resumo

```yaml
nome:     Lucas Felinto
cargo:    Engenheiro de Software | IA Specialist @ GeoSistemas
local:    Recife, PE
foco:     sistemas com LLMs em produção: extração com modelos de visão, saída estruturada,
          RAG, MCP e fine-tuning
stack:    Python, TypeScript, React, Vue.js, Django, SQLite, PostgreSQL
formação: Ciência da Computação (UNICAP) · Pós em Engenharia de Software com IA (CESAR School, 2026–27)
```

Os sistemas em produção ficam em repositórios privados. O que segue descreve o que pode ser tornado público.

## Atuação

### Sistemas com LLMs · GeoSistemas

- **Extração de dados técnicos a partir de fotos e PDFs** com modelos de visão (Claude, GPT e Gemini): prompt com saída em JSON de schema fixo, validação estrita da resposta e rejeição de qualquer payload fora do schema.
- **Geração de artefatos:** planilhas `.xlsx` (openpyxl) e relatórios em PDF, com persistência em SQLite.
- **Seleção de modelo por benchmark:** comparação entre provedores sobre fotos reais com gabarito, medindo acurácia e custo por requisição. Cache de leituras elimina chamadas repetidas à API.
- **Reconciliação** da saída do sistema com as planilhas produzidas pela equipe, com métricas de acurácia, metas e retorno em horas.
- **Arquitetura híbrida em avaliação:** detector (YOLO) para localização e modelo de visão para leitura.
- **RAG, MCP e fine-tuning** em uso diário no desenvolvimento.

### Desenvolvimento web · Lunio

- **CRM com geração automatizada de propostas comerciais.** Front-end em Vue.js e API em Python/Django.
- **Reestruturação do `luniobr.com` em WordPress** e automações em n8n: formulários, e-mail e integrações de marketing.

### Back-end Java

- Spring Boot, PostgreSQL, Docker e Maven no projeto Unimpact (Unicap Icam TECH). Modelagem relacional no FitDB.

### Infraestrutura

- Redes, Windows Server, banco Totvs e Google Workspace (ABA Global Education e FINSOL México).

## Decisões de projeto: sistema de extração

| Camada | Escolha | Justificativa |
|---|---|---|
| Servidor | Python 3.11+, `ThreadingHTTPServer` da stdlib | Sem dependência de framework web: um único processo. |
| Persistência | SQLite | Arquivo único, sem serviço de banco para operar. |
| Documentos | `pypdfium2`, Pillow, numpy | Rasterização de PDF e pré-processamento da imagem antes da inferência. |
| Planilhas | openpyxl | Geração e comparação programática de `.xlsx`. |
| Front-end | React 19, Vite 7, roteamento por hash, CSS com variáveis | Roteamento client-side sem configuração de servidor. Tema centralizado, sem biblioteca de UI. |
| Segurança | Bind em localhost, senha opcional, header `X-App` obrigatório nos POSTs, CSP sem inline | Superfície de exposição mínima. O header customizado restringe os POSTs ao próprio front. |
| Segredos | Chave da API em `.env`, nunca enviada ao front | O segredo existe apenas no servidor. |
| Custo | Cache de leituras | Evita reprocessar a mesma imagem. |

## Stack

**Atual**

<img src="https://skillicons.dev/icons?i=python,react,vite,ts,js,sqlite,git&theme=dark" />

**Histórico**

<img src="https://skillicons.dev/icons?i=java,spring,django,vue,postgres,docker,html,css,mysql,mongodb&theme=dark" />

**IA e automação**

![Claude](https://img.shields.io/badge/Claude-Anthropic_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/GPT-OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-Google-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-00E5FF?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-00E5FF?style=for-the-badge)
![Fine-tuning](https://img.shields.io/badge/Fine--tuning-00E5FF?style=for-the-badge)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

<details>
<summary><b>Trajetória</b></summary>

- **2026–** GeoSistemas: Engenheiro de Software | IA Specialist. Sistemas e automações com IA para engenheiros projetistas.
- **2025–2026** Lunio: Desenvolvedor Web e depois Full Stack. WordPress e n8n; em seguida, CRM e propostas automatizadas (Vue.js, Python/Django).
- **2024** Unicap Icam TECH (Unimpact): estágio full stack com Java/Spring Boot, React, PostgreSQL, Docker e Maven.
- **2021–2024** Suporte e infraestrutura de TI: redes, Windows Server, Totvs e Google Workspace.
- **2019** CESAR School: estágio de desenvolvimento. Controle de presença com Python, C++ e Arduino.

</details>

## Atividade pública no GitHub

<div align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=lucasvfelinto&show_icons=true&hide_border=true&bg_color=0D1117&title_color=00E5FF&icon_color=00E5FF&text_color=C9D1D9" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lucasvfelinto&layout=compact&hide_border=true&bg_color=0D1117&title_color=00E5FF&text_color=C9D1D9" />
<br/>
<img src="https://streak-stats.demolab.com?user=lucasvfelinto&theme=dark&hide_border=true&background=0D1117&ring=00E5FF&fire=00E5FF&currStreakLabel=00E5FF" />
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lucasvfelinto/lucasvfelinto/output/github-snake-dark.svg" />
  <img alt="Gráfico de contribuições animado" src="https://raw.githubusercontent.com/lucasvfelinto/lucasvfelinto/output/github-snake.svg" />
</picture>

<div align="center">
<img src="assets/footer.gif" width="100%" alt="Rodapé em pixel art: mar à noite" />
</div>
