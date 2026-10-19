# Portfólio de Cibersegurança

Olá! Seja bem-vindo(a) ao meu repositório de portfólio em Cibersegurança.

---

## Sobre Mim

Atualmente, estou me especializando através de uma Pós-Graduação em Red Team, combinando fundamentação teórica sólida com treinamento prático diário em ambientes e simuladores corporativos.
Sou apaixonada por Cibersegurança e venho me especializando em análise de vulnerabilidades web, teste de invasão (pentest) e boas práticas de AppSec. 

Tenho me dedicado à resolução prática de laboratórios na **PortSwigger**, **HackTheBox** e **TryHackMe**, documentando vetores de ataque, testes de conceito (PoC) e estratégias de remediação.

**Carta de Apresentação:** https://github.com/hackradtsec/hackradtsec

---

## Foco e Competências

- **OWASP Top 10:** Broken Access Control (BAC) e SQL Injection (SQLi)
- **Análise Técnica:** Interceptação e análise de tráfego HTTP/HTTPS, inspeção *client-side* (DevTools/DOM), manipulação de cookies/parâmetros de sessão e bypass de autenticação.
- **Ferramentas Utilizadas:** Burp Suite, Browser DevTools, Git e GitHub.

---

## Relatórios de Laboratórios (PortSwigger)

### Access Control (Controle de Acesso)

* 📄 **[Unprotected Admin Functionality](./laboratorios/access-control/LabPortSwingger1.md)**
  * **Vulnerabilidade:** Acesso direto a painel administrativo desprotegido exposto publicamente via arquivo `robots.txt`.
  * **Conceito:** Falha de controle de acesso por navegação forçada (*Forced Browsing*).

* 📄 **[Unprotected Admin Functionality with Unpredictable URL](./laboratorios/access-control/LabPortSwingger2.md)**
  * **Vulnerabilidade:** Exposição de rota administrativa imprevisível no código-fonte JavaScript no lado do cliente (*client-side leakage*).
  * **Conceito:** Ineficácia do uso de "Segurança por Obscuridade" sem validação no servidor.

* 📄 **[User Role Controlled by Request Parameter](./laboratorios/access-control/LabPortSwingger4.md)**
  * **Vulnerabilidade:** Elevação de privilégio vertical via manipulação direta de atributo/cookie de controle (`Admin=true`).
  * **Conceito:** Confiança indevida no lado do cliente (*client-side state management*) para controle de acesso.

---

### SQL Injection (Injeção de SQL)

* 📄 **[SQL Injection Allowing Login Bypass](./laboratorios/sql-injection/LabPortSwingger3.md)**
  * **Vulnerabilidade:** Bypass do mecanismo de autenticação via injeção de SQL no campo de nome de usuário (`username`).
  * **Conceito:** Manipulação da lógica da consulta e anulação da verificação de senha usando comentários SQL (`administrator'--`).

---

## Estrutura Padrão dos Relatórios

Cada relatório neste repositório segue a estrutura de documentação profissional utilizada em auditorias e testes de invasão:
1. **Diagnóstico da Vulnerabilidade:** Explicação teórica do problema.
2. **Passo a Passo da Exploração (PoC):** Vetor de ataque e reprodução técnica.
3. **Impacto no Negócio:** Riscos reais à aplicação e aos dados.
4. **Remediação:** Como corrigir o código seguindo boas práticas de desenvolvimento seguro.

---
