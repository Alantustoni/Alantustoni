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

Eu uso IA como ferramenta de engenharia, não como atalho: especifico o problema, gero com **Claude Code, ChatGPT e Codex**, escrevo testes, anonimizo dados e publico. Foi assim que as três ferramentas abaixo nasceram — e elas rodam **todos os dias** no setor de contas a pagar onde trabalho.

O domínio é o que me diferencia: vivo dentro de **CNAB240**, remessas **SISPAG**, **Pix**, DDA e conciliação **ERP × banco**. Sei o que quebra um arquivo de 240 posições e o que um banco rejeita. Em paralelo, curso **Análise e Desenvolvimento de Sistemas (UNICID)**, formatura prevista para **2027**.

```python
alan = {
    "construo_com":  ["Claude Code", "ChatGPT", "Codex", "Lovable", "n8n"],
    "linguagens":    ["Python", "TypeScript", "SQL"],
    "dominio":       ["CNAB240", "SISPAG", "Pix", "DDA", "conciliação", "ERP"],
    "em_producao":   3,   # ferramentas em uso diário num financeiro real
    "testes":        165, # pytest + node --test, todos no CI
    "proximo_passo": "transformar isso em produto",
}
```

---

## 🚀 Em produção

Código real, com testes e CI, extraído das ferramentas que uso no trabalho. Todos os dados nos repositórios são sintéticos.

<table>
  <tr>
    <td width="34%" valign="top">
      <h3 align="center">🏦 Contas a Pagar Suite</h3>
      <p align="center">
        <a href="https://github.com/Alantustoni/contas-a-pagar-suite"><img src="https://img.shields.io/badge/repo-contas--a--pagar--suite-1d4ed8?style=flat-square&logo=github" /></a>
        <a href="https://github.com/Alantustoni/contas-a-pagar-suite/actions/workflows/tests.yml"><img src="https://github.com/Alantustoni/contas-a-pagar-suite/actions/workflows/tests.yml/badge.svg" /></a>
      </p>
      <p>App desktop de contas a pagar: junta e valida <b>.RET CNAB240</b> (Itaú → Bradesco, trailers recalculados), combina retornos <b>SISPAG</b>, cruza <b>DDA × banco</b> e concilia <b>remessa ERP × banco</b> em 3 passadas. Substituiu 5 executáveis antigos. <b>106 testes.</b></p>
      <p align="center"><code>Python</code> <code>CustomTkinter</code> <code>pandas</code></p>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">🧾 cnab240-tools</h3>
      <p align="center">
        <a href="https://github.com/Alantustoni/cnab240-tools"><img src="https://img.shields.io/badge/repo-cnab240--tools-1d4ed8?style=flat-square&logo=github" /></a>
        <a href="https://github.com/Alantustoni/cnab240-tools/actions/workflows/tests.yml"><img src="https://github.com/Alantustoni/cnab240-tools/actions/workflows/tests.yml/badge.svg" /></a>
      </p>
      <p>Biblioteca Python, <b>só stdlib</b>, extraída da suíte: leitura e fusão de .RET, segmento G, fator de vencimento do código de barras, retorno SISPAG. Vem com <code>examples/demo.py</code> que gera arquivos sintéticos. <b>44 testes</b>, CI Ubuntu + Windows.</p>
      <p align="center"><code>Python</code> <code>pytest</code> <code>wheel</code></p>
    </td>
    <td width="33%" valign="top">
      <h3 align="center">📬 email-nota-excel</h3>
      <p align="center">
        <a href="https://github.com/Alantustoni/email-nota-excel"><img src="https://img.shields.io/badge/repo-email--nota--excel-1d4ed8?style=flat-square&logo=github" /></a>
        <a href="https://github.com/Alantustoni/email-nota-excel/actions/workflows/tests.yml"><img src="https://github.com/Alantustoni/email-nota-excel/actions/workflows/tests.yml/badge.svg" /></a>
      </p>
      <p><b>Office Script + Power Automate</b>: a cada e-mail de Compras, lê as tabelas do corpo e registra as notas fiscais no Excel. Idempotente por ID, alerta duplicidade sem bloquear, protege contra injeção de fórmula. Em produção desde set/2026. <b>15 testes.</b></p>
      <p align="center"><code>TypeScript</code> <code>Node</code> <code>Power Automate</code></p>
    </td>
  </tr>
</table>

---

## 🧪 Protótipos e experimentos

| Projeto | O que é | Como foi feito |
|---|---|---|
| [**ReForma**](https://github.com/Alantustoni/reforma-site) · [site](https://reforma-site-production.up.railway.app) | Plataforma de doação de sobras de material de construção (coordeno o projeto na faculdade) | HTML/CSS/JS, deploy no Railway |
| [**ProcessIQ**](https://github.com/Alantustoni/processiq) · [demo](https://processiq-insightful.lovable.app) | SaaS que transforma planilhas de contas a pagar de pequenas empresas em alertas | Protótipo de UI com Lovable; motor de análise é o próximo passo |
| [**BossFit**](https://github.com/Alantustoni/bossfit) | Gerador de treino adaptativo com progressão de carga e coach com IA | Lovable + Supabase + Edge Function com LLM |
| Cliente WebSocket de odds ao vivo | Leitura de feeds em tempo real por engenharia reversa (DevTools) + alertas no Telegram | Python, n8n, Railway, API da Anthropic — ainda não publicado |

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
