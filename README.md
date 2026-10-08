<p align="center">
  <img src="assets/banner.svg" alt="excanear — Segurança ofensiva e engenharia de baixo nível" width="100%">
</p>

<p align="center">
  <sub><code>Segurança ofensiva e engenharia de baixo nível — eu construo a ferramenta, não só a prova de conceito.</code></sub>
</p>

<p align="center">
  <img src="assets/identity.svg" alt="CyberSecurity · Red Team · DFIR · Reverse Engineering · Low-Level · Software Engineering" width="100%">
</p>

&nbsp;

**Security researcher e engenheiro de baixo nível.** Trabalho em segurança ofensiva, engenharia reversa e forense digital — e construo as ferramentas que sustentam esse trabalho. O interesse não para na prova de conceito: desce até o binário, o kernel e o protocolo, sempre respondendo à mesma pergunta — *como isso funciona por baixo?*

&nbsp;

## Perímetro

<sub>Cinco frentes, um perímetro. Onde a segurança ofensiva encontra a engenharia de sistemas.</sub>

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
      <td align="center"><sub><code>01</code></sub></td>
      <td width="26%"><a href="https://github.com/excanear/OWASP-Bypass"><b>OWASP&nbsp;Bypass</b></a><br><sub><code>Python</code></sub></td>
      <td>Engine autônomo de exploração web. <b>106 de 107</b> desafios do OWASP Juice Shop resolvidos de ponta a ponta.</td>
    </tr>
    <tr>
      <td align="center"><sub><code>02</code></sub></td>
      <td><a href="https://github.com/excanear/Web-Application-Reconnaissance-Investigation-Platform"><b>Web&nbsp;Recon&nbsp;Platform</b></a><br><sub><code>Python</code></sub></td>
      <td>CLI de reconhecimento ofensivo: fingerprint real de tecnologia e versão, correlacionado a CVEs via NVD.</td>
    </tr>
    <tr>
      <td align="center"><sub><code>03</code></sub></td>
      <td><a href="https://github.com/excanear/devkit"><b>DEVKIT</b></a><br><sub><code>Assembly</code></sub></td>
      <td>Toolkit de terminal escrito em <b>100% Assembly x86-64</b> — estático, sem uma única dependência.</td>
    </tr>
    <tr>
      <td align="center"><sub><code>04</code></sub></td>
      <td><a href="https://github.com/excanear/OSIRIS---Operational-System-Intelligence-Response-Investigation-System"><b>OSIRIS</b></a><br><sub><code>Rust</code></sub></td>
      <td>Operational System Intelligence &amp; Response — inteligência operacional e investigação de sistema.</td>
    </tr>
    <tr>
      <td align="center"><sub><code>05</code></sub></td>
      <td><a href="https://github.com/excanear/Network-Kernel-Driver"><b>Network&nbsp;Kernel&nbsp;Driver</b></a><br><sub><code>Rust</code></sub></td>
      <td>Driver de rede em nível de kernel — interceptação e inspeção abaixo do userspace.</td>
    </tr>
    <tr>
      <td align="center"><sub><code>06</code></sub></td>
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

<img src="assets/divider.svg" alt="" width="100%">

## Em foco

Direção atual da pesquisa e do tooling — do userspace ao kernel.

- **Rust para segurança de sistemas** — [OSIRIS](https://github.com/excanear/OSIRIS---Operational-System-Intelligence-Response-Investigation-System) (inteligência e resposta operacional) e [Network&nbsp;Kernel&nbsp;Driver](https://github.com/excanear/Network-Kernel-Driver), levando tooling confiável para perto do kernel.
- **Inteligência de vulnerabilidades em escala** — [CVEs&nbsp;Enterprise&nbsp;System](https://github.com/excanear/CVEs-Enterprise-System): correlação e gestão de CVE como sistema, não como script.
- **Criptografia de baixo nível** — [Sistema de Criptografia Avançada](https://github.com/excanear/Sistema-de-Criptografia-e-Descriptografia-Avancada-Open-Source) implementado em Assembly, para entender a primitiva, não só usá-la.

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

## Ética operacional

> Ferramentas e pesquisa publicadas aqui existem para uso autorizado, estudo e para fortalecer a defesa. Conhecimento ofensivo serve para elevar a proteção — nunca para violá-la.

&nbsp;

<p align="center">
  <a href="https://www.escanearcplx.com"><img src="assets/colofao.svg" alt="O conhecimento ofensivo existe para fortalecer a defesa, não para violá-la. — escanearcplx.com" width="100%"></a>
</p>

<p align="center">
  <sub><a href="https://www.escanearcplx.com"><code>escanearcplx.com</code></a></sub>
</p>
