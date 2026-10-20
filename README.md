<div align="center">

<img src="assets/header.gif" width="100%" alt="banner pixel art: skyline de Recife à noite" />

<a href="https://github.com/lucasvfelinto">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1100&color=00E5FF&center=true&vCenter=true&width=700&lines=Eae%2C+sou+o+Lucas+%F0%9F%91%8B;LLM+em+produ%C3%A7%C3%A3o%2C+n%C3%A3o+em+demo;JSON+de+schema+fixo+%3E+prompt+bonito;Vim+de+redes%3A+debugar+%C3%A9+meu+primeiro+idioma" alt="Typing SVG" />
</a>

<br/><br/>

<img src="assets/globe.gif" height="380" alt="globo pixel art girando, Recife marcado" />
<br/>
<img src="assets/dev.gif" height="210" alt="avatar pixel art digitando" />

<br/><br/>

<a href="https://www.linkedin.com/in/lucasvfelinto/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="https://lucas-felinto-curriculo_2022.surge.sh/" target="_blank"><img src="https://img.shields.io/badge/-My%20WebSite-%23000000?style=for-the-badge&logo=website&logoColor=white&color=purple"></a>
<a href = "mailto: lucas.felinto.office@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
<a href="https://instagram.com/lucasvfelinto" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
<a href="https://bento.me/lucasvfelinto" target="_blank"><img src="https://img.shields.io/badge/-More%20About%20Me-0D1117?style=for-the-badge&logo=bento&logoColor=00E5FF"></a>

<br/><br/>
<img src="https://komarev.com/ghpvc/?username=lucasvfelinto&label=Visitantes&color=00E5FF&style=for-the-badge" />

</div>

## 🧠 whoami

```yaml
nome:    Lucas Felinto            # Recife, PE
cargo:   Engenheiro de Software | IA Specialist @GeoSistemas
faz:     sistemas que leem foto e PDF de engenharia e devolvem planilha conferida
stack:   Python (stdlib até onde der), React 19 + Vite, SQLite, APIs de LLM
estudo:  Pós em Eng. de Software com IA @ CESAR School (2026-27)
caminho: Redes/Infra → Java/Spring → Vue/Quasar → WordPress/n8n → IA
fora:    [PC, treino, vôlei, anime, autoconhecimento]
```

> 🔒 Meus melhores projetos são privados. O que está aqui é o que dá pra mostrar.

## 🔧 O que eu construo

- **IA aplicada (GeoSistemas):** pipelines que leem foto e PDF de engenharia com modelo de visão (Claude, GPT, Gemini), forçam a saída em JSON de schema fixo, validam e geram planilha e PDF. Modelo escolhido por medição contra gabarito, com cache pra não pagar a API em dobro. Back em Python (stdlib + SQLite), front em React + Vite.
- **LLMs no dia a dia:** RAG e MCP em uso diário, além de fine-tuning de modelos.
- **CRM e propostas automatizadas (Lunio):** plataforma de CRM com geração automática de propostas comerciais. Front em Vue.js, API em Python + Django.
- **Site e automação (Lunio):** reestruturei o `luniobr.com` em WordPress e liguei formulário, e-mail e marketing com n8n.
- **Back-end Java:** Spring Boot com Postgres e Docker no projeto Unimpact (Unicap Icam TECH), e modelagem de banco no FitDB.
- **Base de infra:** anos de redes e Windows Server. Eu sei onde a aplicação quebra por baixo.

## 🧱 Decisões de arquitetura (e o porquê)

| Decisão | Motivo |
|---|---|
| Backend em Python stdlib (`ThreadingHTTPServer`) + SQLite | Ambiente sem pip. Zero dependência de framework web. Migro pra FastAPI quando der. |
| React 19 + Vite 7, rotas por hash, CSS próprio com variáveis | Sem UI lib e sem servidor de rotas. Menos peça pra quebrar. |
| `pypdfium2` + numpy + Pillow | Rasteriza o PDF e pré-processa a imagem antes do modelo. |
| Servidor só em localhost, senha opcional, header `X-App` nos POSTs, CSP sem inline | Segurança básica por padrão, sem custo extra. |
| Chave da API em `.env`, nunca enviada ao front | O navegador não vê a chave. |

## ⚡ Stack

**Hoje**

<img src="https://skillicons.dev/icons?i=python,react,vite,ts,js,sqlite,git&theme=dark" />

**Antes**

<img src="https://skillicons.dev/icons?i=java,spring,django,vue,postgres,docker,html,css,mysql,mongodb&theme=dark" />

**IA & automação**

![Claude](https://img.shields.io/badge/Claude-Anthropic_API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/GPT-OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-Google-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-no_dia_a_dia-00E5FF?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-no_dia_a_dia-00E5FF?style=for-the-badge)
![Fine-tuning](https://img.shields.io/badge/Fine--tuning-LLMs-00E5FF?style=for-the-badge)
![n8n](https://img.shields.io/badge/n8n-automação-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

<details>
<summary><b>🧭 Trajetória, sem cortar o começo</b></summary>

- **2026 →** GeoSistemas: sistemas e automações com IA para engenheiros projetistas.
- **2025–26** Lunio: WordPress + n8n (formulários, e-mail, marketing), depois CRM e propostas automatizadas com Vue.js e Python/Django.
- **2024** Unicap Icam TECH (Unimpact): Java/Spring Boot, React, Postgres, Docker, Maven.
- **2021–24** Suporte e infra de TI: redes, Windows Server, Totvs, Google Workspace. É por isso que eu debugo de baixo pra cima.
- **2019** CESAR School: controle de presença com Python, C++ e Arduino.

</details>

## 📊 Provas de vida (só o que é público)

<div align="center">
<img height="170" src="https://github-readme-stats.vercel.app/api?username=lucasvfelinto&show_icons=true&hide_border=true&bg_color=0D1117&title_color=00E5FF&icon_color=00E5FF&text_color=C9D1D9" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lucasvfelinto&layout=compact&hide_border=true&bg_color=0D1117&title_color=00E5FF&text_color=C9D1D9" />
<br/>
<img src="https://streak-stats.demolab.com?user=lucasvfelinto&theme=dark&hide_border=true&background=0D1117&ring=00E5FF&fire=00E5FF&currStreakLabel=00E5FF" />
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lucasvfelinto/lucasvfelinto/output/github-snake-dark.svg" />
  <img alt="snake" src="https://raw.githubusercontent.com/lucasvfelinto/lucasvfelinto/output/github-snake.svg" />
</picture>

<div align="center">
<img src="assets/footer.gif" width="100%" alt="rodapé pixel art: mar à noite" />
</div>
