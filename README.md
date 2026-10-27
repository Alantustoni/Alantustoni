<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1d4ed8,100:06b6d4&height=200&section=header&text=Alan%20Tustoni&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Constru%C3%A7%C3%A3o%20r%C3%A1pida%20com%20IA%20%7C%20Pagamentos%20%7C%20Python&descAlignY=60&descSize=20" width="100%"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=800&color=22D3EE&center=true&vCenter=true&width=900&height=50&lines=Construo+software+com+IA+e+coloco+em+produ%C3%A7%C3%A3o;Ferramentas+minhas+rodam+todo+dia+num+financeiro+real;CNAB240%2C+SISPAG%2C+Pix+e+concilia%C3%A7%C3%A3o+por+dentro;Python+%C2%B7+TypeScript+%C2%B7+automa%C3%A7%C3%A3o+%C2%B7+ADS+UNICID" alt="Typing SVG" /></a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-alantustoni-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alantustoni)
[![GitHub](https://img.shields.io/badge/GitHub-Alantustoni-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Alantustoni)
![Location](https://img.shields.io/badge/S%C3%A3o%20Paulo-Brasil-16a34a?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

---

## 🧭 Sobre mim

**Dev em pagamentos · Python · Automação · IA**

Construo software para o backoffice financeiro: ferramentas em Python que leem, validam e conciliam arquivos bancários — CNAB240, SISPAG, DDA, Pix — e que rodam todos os dias num setor de contas a pagar real. **4 projetos em produção**, **312 testes automatizados**, CI em todos.

**Automatizei o meu próprio trabalho:** cinco anos operando contas a pagar me ensinaram na prática o que quebra um arquivo de 240 posições, o que o banco rejeita e onde a conciliação do ERP falha. É essa regra de negócio que transformo em código.

Uso IA (Claude Code e Codex) como ferramenta de engenharia — especifico, gero, testo, anonimizo e publico — e documento quando um projeto não entrega o que promete: o screener de cripto abaixo tem uma auditoria pública concluindo que a estratégia não tinha edge.

🎓 Análise e Desenvolvimento de Sistemas (UNICID) — formatura prevista para 2027.

```python
alan = {
    "construo_com":  ["Claude Code", "Codex", "Lovable", "n8n"],
    "linguagens":    ["Python", "TypeScript", "SQL"],
    "dominio":       ["CNAB240", "SISPAG", "Pix", "DDA", "conciliação", "ERP"],
    "em_producao":   4,   # 3 no financeiro onde trabalho + 1 screener 24/7 no Railway
    "em_construcao": "processiq-core",
    "testes":        312, # pytest + node --test, todos no CI
    "proximo_passo": "transformar isso em produto",
}
```

---

## 🚀 Em produção

Código real, com testes e CI. Dados dos repositórios financeiros são sintéticos.

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🏦 Contas a Pagar Suite</h3>
      <p align="center">
        <a href="https://github.com/Alantustoni/contas-a-pagar-suite"><img src="https://img.shields.io/badge/repo-contas--a--pagar--suite-1d4ed8?style=flat-square&logo=github" /></a>
        <a href="https://github.com/Alantustoni/contas-a-pagar-suite/actions/workflows/tests.yml"><img src="https://github.com/Alantustoni/contas-a-pagar-suite/actions/workflows/tests.yml/badge.svg" /></a>
      </p>
      <p>App desktop de contas a pagar: junta e valida <b>.RET CNAB240</b> (Itaú → Bradesco, trailers recalculados), combina retornos <b>SISPAG</b>, cruza <b>DDA × banco</b> e concilia <b>remessa ERP × banco</b> em 3 passadas. Substituiu 5 executáveis antigos. <b>106 testes.</b></p>
      <p align="center"><code>Python</code> <code>CustomTkinter</code> <code>pandas</code></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🧾 cnab240-tools</h3>
      <p align="center">
        <a href="https://github.com/Alantustoni/cnab240-tools"><img src="https://img.shields.io/badge/repo-cnab240--tools-1d4ed8?style=flat-square&logo=github" /></a>
        <a href="https://github.com/Alantustoni/cnab240-tools/actions/workflows/tests.yml"><img src="https://github.com/Alantustoni/cnab240-tools/actions/workflows/tests.yml/badge.svg" /></a>
      </p>
      <p>Biblioteca Python, <b>só stdlib</b>, extraída da suíte: leitura e fusão de .RET, segmento G, fator de vencimento do código de barras, retorno SISPAG. Vem com <code>examples/demo.py</code> que gera arquivos sintéticos. <b>44 testes</b>, CI Ubuntu + Windows.</p>
      <p align="center"><code>Python</code> <code>pytest</code> <code>wheel</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">📬 email-nota-excel</h3>
      <p align="center">
        <a href="https://github.com/Alantustoni/email-nota-excel"><img src="https://img.shields.io/badge/repo-email--nota--excel-1d4ed8?style=flat-square&logo=github" /></a>
        <a href="https://github.com/Alantustoni/email-nota-excel/actions/workflows/tests.yml"><img src="https://github.com/Alantustoni/email-nota-excel/actions/workflows/tests.yml/badge.svg" /></a>
      </p>
      <p><b>Office Script + Power Automate</b>: a cada e-mail de Compras, lê as tabelas do corpo e registra as notas fiscais no Excel. Idempotente por ID, alerta duplicidade sem bloquear, protege contra injeção de fórmula. Em produção desde set/2026: <b>1.081 registros de 122 e-mails no primeiro mês, sem digitação</b>. <b>19 testes.</b></p>
      <p align="center"><code>TypeScript</code> <code>Node</code> <code>Power Automate</code></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">📈 2A Crypto Screener</h3>
      <p align="center">
        <a href="https://github.com/Alantustoni/crypto-screener"><img src="https://img.shields.io/badge/repo-crypto--screener-1d4ed8?style=flat-square&logo=github" /></a>
        <a href="https://github.com/Alantustoni/crypto-screener/actions/workflows/tests.yml"><img src="https://github.com/Alantustoni/crypto-screener/actions/workflows/tests.yml/badge.svg" /></a>
      </p>
      <p>Screener dos 100 pares mais líquidos da Binance: 15 indicadores, score por par, alertas no Telegram, dashboard FastAPI, auto-calibração e backtest. <b>55 commits em 6 semanas.</b> A <a href="https://github.com/Alantustoni/crypto-screener/blob/main/AUDITORIA_E_EDGE_2A.md">auditoria</a> com dados reais e custos concluiu: sem edge, não operar. <b>53 testes.</b></p>
      <p align="center"><code>Python</code> <code>FastAPI</code> <code>PostgreSQL</code> <code>Railway</code></p>
    </td>
  </tr>
</table>

---

## 🔨 Em construção

<table>
  <tr>
    <td valign="top">
      <h3>🧩 processiq-core</h3>
      <p>
        <a href="https://github.com/Alantustoni/processiq-core"><img src="https://img.shields.io/badge/repo-processiq--core-1d4ed8?style=flat-square&logo=github" /></a>
        <a href="https://github.com/Alantustoni/processiq-core/actions/workflows/tests.yml"><img src="https://github.com/Alantustoni/processiq-core/actions/workflows/tests.yml/badge.svg" /></a>
      </p>
      <p>Motor de análise de planilhas de contas a pagar para pequenas empresas: lê o Excel/CSV que a empresa já usa, reconhece as colunas por sinônimo e aponta NF duplicada, fornecedor cadastrado duas vezes (por raiz de CNPJ ou nome parecido), vencidos, valor fora do padrão e CNPJ inválido — e sugere qual cadastro manter ao unificar fornecedores. Motor puro + API FastAPI em camadas separadas (o motor não sabe que a API existe), Swagger, Dockerfile, relatório Excel com linhas marcadas. Construído em público. <b>90 testes</b>, CI Ubuntu + Windows.</p>
      <p><code>Python</code> <code>FastAPI</code> <code>Pydantic</code> <code>pytest</code> <code>Docker</code></p>
    </td>
  </tr>
</table>

---

## 🧪 Protótipos e experimentos

| Projeto | O que é | Como foi feito |
|---|---|---|
| [**ReForma**](https://github.com/Alantustoni/reforma-site) · [site](https://reforma-site-production.up.railway.app) | Plataforma de doação de sobras de material de construção (coordeno o projeto na faculdade) | HTML/CSS/JS, deploy no Railway |
| [**ProcessIQ**](https://github.com/Alantustoni/processiq) · [demo](https://processiq-insightful.lovable.app) | SaaS que transforma planilhas de contas a pagar de pequenas empresas em alertas | Protótipo de UI com Lovable; o motor real está em [processiq-core](https://github.com/Alantustoni/processiq-core) |
| [**BossFit**](https://github.com/Alantustoni/bossfit) | Gerador de treino adaptativo com progressão de carga e coach com IA | Lovable + Supabase + Edge Function com LLM |
| Cliente WebSocket de odds ao vivo | Leitura de feeds em tempo real por engenharia reversa (DevTools) + alertas no Telegram | Python, n8n — ainda não publicado |

---

## 🛠️ Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,ts,js,nodejs,postgres,mysql,react,tailwind,html,css,git,github,githubactions,vscode&perline=7" alt="stack" />
</div>

<br/>

<div align="center">

| Domínio financeiro | O que eu faço com isso |
|---|---|
| **CNAB240** | Leitura, geração, fusão e validação de remessa/retorno; recálculo de trailers; diagnóstico de rejeição |
| **SISPAG (Itaú)** | Combinação de retornos, lotes, segmentos A/B/J |
| **Boleto / DDA** | Vencimento pelo fator do código de barras, cruzamento DDA × agendamentos |
| **Conciliação** | Remessa ERP × extrato × retorno em passadas (exato → janela → fuzzy) |

</div>

---

## 📈 Atividade

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Alantustoni&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=22d3ee&icon_color=22d3ee&text_color=c9d1d9&locale=pt-br" height="165" alt="stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com?user=Alantustoni&theme=tokyonight&hide_border=true&background=0d1117&ring=22d3ee&fire=f59e0b&currStreakLabel=22d3ee&locale=pt_BR" height="165" alt="streak" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Alantustoni&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=22d3ee&text_color=c9d1d9&langs_count=6&locale=pt-br" height="165" alt="linguagens" />
</div>

<br/>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Alantustoni/Alantustoni/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Alantustoni/Alantustoni/output/github-contribution-grid-snake.svg" />
    <img alt="snake das contribuições" src="https://raw.githubusercontent.com/Alantustoni/Alantustoni/output/github-contribution-grid-snake.svg" />
  </picture>
</div>

---

<div align="center">

### 💬 Vamos conversar?

Se você trabalha com **fintech, ERP, automação financeira ou produtos construídos com IA**, me chama no [LinkedIn](https://www.linkedin.com/in/alantustoni).

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:1d4ed8,100:0f172a&height=120&section=footer" width="100%"/>

</div>
