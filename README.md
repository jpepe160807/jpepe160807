<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,55:7A0019,100:FF3355&height=170&section=header&text=Jo%C3%A3o%20Pedro%20Ribeiro&fontSize=40&fontColor=FFFFFF&fontAlignY=42&desc=Defesa%20Cibern%C3%A9tica%20%C2%B7%20AppSec%20%C2%B7%20Python&descSize=17&descColor=FFD6DC&descAlignY=68&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=19&pause=1400&color=FF3355&center=true&vCenter=true&width=560&lines=Explorar+a+falha.+Escrever+a+corre%C3%A7%C3%A3o.;Defesa+Cibern%C3%A9tica+%40+FIAP;Python+%E2%80%A2+AppSec+%E2%80%A2+An%C3%A1lise+de+logs;Procurando+est%C3%A1gio+em+seguran%C3%A7a" alt="Explorar a falha. Escrever a correção." />

<a href="https://www.linkedin.com/in/jo%C3%A3o-pedro-s-ribeiro-2ba201304"><img src="https://img.shields.io/badge/LinkedIn-7A0019?style=for-the-badge" /></a> <a href="mailto:joaopedrosribeiro08@gmail.com"><img src="https://img.shields.io/badge/E--mail-7A0019?style=for-the-badge&logo=gmail&logoColor=white" /></a> <img src="https://img.shields.io/badge/%E2%97%8F_Aberto_a_est%C3%A1gio-FF3355?style=for-the-badge" />

</div>

<br>

## `[01]` quem sou

Estudante de **Defesa Cibernética na FIAP**, buscando **estágio em segurança da informação** (SOC, AppSec ou análise de vulnerabilidades).

Gosto de entender como um ataque funciona por dentro e depois escrever o código que o impede. Hoje estudo principalmente **segurança de aplicações web**, **análise de logs** e **automação com Python**.

<br>

## `[02]` ataque × defesa

<table>
<tr>
<th width="50%">⚔️ O que eu exploro</th>
<th width="50%">🛡️ Como eu corrijo</th>
</tr>
<tr>
<td>SQL injection numa busca com query concatenada</td>
<td>Query parametrizada</td>
</tr>
<tr>
<td>XSS refletido numa página de perfil</td>
<td>Escape da entrada e headers de segurança (CSP)</td>
</tr>
<tr>
<td>Rota de DELETE sem autenticação</td>
<td>Chave de API obrigatória, 401/403 e rate limiting</td>
</tr>
<tr>
<td>Prompt injection escondida dentro de um log</td>
<td>Delimitadores, resposta em formato rígido e regras como piso</td>
</tr>
<tr>
<td>Arquivo <code>.pkl</code> adulterado que executa código ao abrir</td>
<td>Conferir o SHA-256 antes de carregar (OWASP A08)</td>
</tr>
</table>

<br>

## `[03]` projetos

### 🧨 [App vulnerável × app seguro](https://github.com/jpepe160807/cp2-coding-for-security/tree/main/ex10)
![Python](https://img.shields.io/badge/Python-1a1f27?style=flat-square&logo=python&logoColor=FF3355)
![Flask](https://img.shields.io/badge/Flask-1a1f27?style=flat-square&logo=flask&logoColor=FF3355)
![MySQL](https://img.shields.io/badge/MySQL-1a1f27?style=flat-square&logo=mysql&logoColor=FF3355)

Aplicação Flask com 8 falhas do OWASP Top 10, um script de exploit que ataca cada uma, uma [auditoria](https://github.com/jpepe160807/cp2-coding-for-security/blob/main/ex10/auditoria.md) com impacto e correção e a versão endurecida, contra a qual o mesmo exploit falha.

### 🧠 [Classificador de logs à prova de prompt injection](https://github.com/jpepe160807/cp3-coding-for-security)
![Python](https://img.shields.io/badge/Python-1a1f27?style=flat-square&logo=python&logoColor=FF3355)
![LLM](https://img.shields.io/badge/LLM-1a1f27?style=flat-square&logo=openai&logoColor=FF3355)

Classifica eventos de `auth.log` e logs web como NORMAL, SUSPEITO ou CRÍTICO. Mostra um classificador ingênuo sendo enganado por uma ordem escondida no log e a versão protegida, que não deixa o modelo rebaixar o que as regras já marcaram como grave.

### 🛰️ [Ferramentas de threat intel](https://github.com/jpepe160807/cp3-coding-for-security)
![Python](https://img.shields.io/badge/Python-1a1f27?style=flat-square&logo=python&logoColor=FF3355)
![REST](https://img.shields.io/badge/APIs_REST-1a1f27?style=flat-square&logo=fastapi&logoColor=FF3355)

Consulta de CVEs na API do NVD (CVSS e severidade) e enriquecimento de IPs com cache e backoff quando a API limita as requisições.

<br>

## `[04]` stack

<div align="center">

<img src="https://skillicons.dev/icons?i=py,flask,mysql,mongodb,docker,linux,git&theme=dark&perline=7" />

</div>

<br>

## `[05]` in english

Cyber Defense student at FIAP (Brazil), looking for an **information security internship**. I build and break web apps (OWASP Top 10), analyze logs and automate security tasks in Python. Highlights: a vulnerable vs. hardened Flask app with its exploit and audit, and an LLM log classifier hardened against prompt injection.

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=slice&color=0:FF3355,45:7A0019,100:0D1117&height=110&section=footer&reversal=true&rotate=6" width="100%"/>

</div>
