<p align="center">
  <img src="assets/banner.svg" alt="excanear — Segurança ofensiva e engenharia de baixo nível" width="100%">
</p>

<p align="center">
  <sub><code>Segurança ofensiva e engenharia de baixo nível — eu construo a ferramenta, não só a prova de conceito.</code></sub>
</p>

&nbsp;

Pesquisa ofensiva, engenharia de baixo nível e investigação forense. O foco não é demonstrar uma vulnerabilidade — é entregar a ferramenta que a encontra, a explora e, no fim, fortalece a defesa. Cada projeto aqui começa de uma pergunta simples: *como isso funciona por baixo?*

&nbsp;

## Perímetro

<p align="center">
  <img src="assets/radar.svg" alt="Cinco frentes: 01 Offensive/Red Team — pentest, recon, CVE, fuzzing · 02 Application Security — OWASP, injeção, XSS, SSRF · 03 Reverse Engineering — malware, binário, firmware, DLL hijacking · 04 Forense/DFIR — memória, disco, rede, Android, incident response · 05 Baixo nível/Kernel — kernel, hypervisors, drivers, criptografia" width="100%">
</p>

<img src="assets/divider.svg" alt="" width="100%">

## Arsenal

> Seleção. O índice completo fica ao final.

<p align="center">
  <img src="assets/terminal.svg" alt="ls ~/arsenal: OWASP-Bypass (106/107 Juice Shop), Web-Recon-Platform, devkit (100% Assembly), OSIRIS, Network-Kernel-Driver, Sysinfo-Shell" width="100%">
</p>

<table>
  <tbody>
    <tr>
      <td width="30%"><a href="https://github.com/excanear/OWASP-Bypass"><b>OWASP&nbsp;Bypass</b></a><br><sub><code>Python</code></sub></td>
      <td>Engine autônomo de exploração web. <b>106 de 107</b> desafios do OWASP Juice Shop resolvidos de ponta a ponta.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/excanear/Web-Application-Reconnaissance-Investigation-Platform"><b>Web&nbsp;Recon&nbsp;Platform</b></a><br><sub><code>Python</code></sub></td>
      <td>CLI de reconhecimento ofensivo: fingerprint real de tecnologia e versão, correlacionado a CVEs via NVD.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/excanear/devkit"><b>DEVKIT</b></a><br><sub><code>Assembly</code></sub></td>
      <td>Toolkit de terminal escrito em <b>100% Assembly x86-64</b> — estático, sem uma única dependência.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/excanear/OSIRIS---Operational-System-Intelligence-Response-Investigation-System"><b>OSIRIS</b></a><br><sub><code>Rust</code></sub></td>
      <td>Operational System Intelligence &amp; Response — inteligência operacional e investigação de sistema.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/excanear/Network-Kernel-Driver"><b>Network&nbsp;Kernel&nbsp;Driver</b></a><br><sub><code>Rust</code></sub></td>
      <td>Driver de rede em nível de kernel — interceptação e inspeção abaixo do userspace.</td>
    </tr>
    <tr>
      <td><a href="https://github.com/excanear/Sysinfo-Shell"><b>Sysinfo&nbsp;Shell</b></a><br><sub><code>Shell</code></sub></td>
      <td>System info em shell POSIX puro, zero dependências: Linux, Windows, WSL, Git Bash e MSYS2.</td>
    </tr>
  </tbody>
</table>

<img src="assets/divider.svg" alt="" width="100%">

## Instrumentação

<table>
  <thead>
    <tr>
      <th align="left"><sub>LINGUAGENS</sub></th>
      <th align="left"><sub>OFENSIVO · REDE</sub></th>
      <th align="left"><sub>ENGENHARIA · WEB</sub></th>
    </tr>
  </thead>
  <tbody>
    <tr valign="top">
      <td><sub><code>Python</code> <code>C</code> <code>C++</code> <code>C#</code><br><code>Go</code> <code>Rust</code> <code>Java</code> <code>Assembly</code></sub></td>
      <td><sub><code>Nmap</code> <code>Wireshark</code> <code>Burp&nbsp;Suite</code><br><code>OWASP&nbsp;ZAP</code> <code>ffuf</code> <code>Gobuster</code><br><code>Metasploit</code> <code>Kali&nbsp;Linux</code></sub></td>
      <td><sub><code>Docker</code> <code>Linux</code> <code>Git</code><br><code>React</code> <code>Next.js</code> <code>TypeScript</code><br><code>Tailwind</code> <code>GSAP</code></sub></td>
    </tr>
  </tbody>
</table>

<details>
<summary><sub><b>Credenciais técnicas</b></sub></summary>

<br>

<sub>

| Emissor | Credencial |
|---|---|
| Cisco / IBSEC | Certified Ethical Hacker (CEH) |
| IBSEC | Certified Pentester |
| Cisco | Cybersecurity Defense Analyst |
| Palo Alto | Cloud Security Professional · SOC Professional |
| Fortinet | Network Security Expert 3 |
| Linux Foundation | Linux Kernel Development |
| Securiti AI | AI Security &amp; Governance |

</sub>

</details>

<details>
<summary><sub><b>Índice completo do arsenal</b></sub></summary>

<br>

<sub>

**Ofensivo · AppSec** — `CVEs-Enterprise-System` · `Escanearcpl-Exploit-Tools` · `Hacking-Framework` · `Fuzzer-Vuln` · `PortScan-CPLX` · `WebScan` · `Crawler-de-Subdominios` · `Scanner-de-Portas`

**Reverse · Baixo nível** — `DLL-Hijacking-System` · `HyperVisor-Open-Source` · `Project-REXA` · `Arquitetura-de-CPU` · `Network-Kernel-Driver`

**Forense · DFIR** — `android-forensics-suite` · `Ferramenta-de-Analise-Forense-de-Memoria-e-Rede` · `Ferramenta-de-chunked-file-carving` · `Raw-Disk-Viwer-CPLX`

**Criptografia** — `Sistema-de-Criptografia-e-Descriptografia-Avancada` · `Criptografia-AES` · `Gerador-de-Senhas-Hash`

</sub>

</details>

<img src="assets/divider.svg" alt="" width="100%">

&nbsp;

<p align="center">
  <a href="https://www.escanearcplx.com"><img src="assets/colofao.svg" alt="O conhecimento ofensivo existe para fortalecer a defesa, não para violá-la. — escanearcplx.com" width="100%"></a>
</p>
