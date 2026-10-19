# Portfólio de Cibersegurança

Olá! Seja bem-vindo(a) ao meu repositório de portfólio em Cibersegurança.

---

## Sobre Mim

Atualmente, estou me especializando através de uma Pós-Graduação em Red Team, combinando fundamentação teórica sólida com treinamento prático diário em ambientes e simuladores corporativos.
Sou apaixonada por Cibersegurança e venho me especializando em análise de vulnerabilidades web, teste de invasão (pentest) e boas práticas de AppSec. 

Tenho me dedicado à resolução prática de laboratórios na **PortSwigger**, **HackTheBox** e **TryHackMe**, documentando vetores de ataque, testes de conceito (PoC) e estratégias de remediação.

**Carta de Apresentação:** https://github.com/hackradtsec/hackradtsec

---

## Tipos de Vulnerabilidades Praticadas

### Broken Access Control (Controle de Acesso)
Práticas focadas na identificação de falhas de autorização e elevação de privilégios no lado do servidor e do cliente:
* **Navegação Forçada (*Forced Browsing*):** Acesso a painéis administrativos ocultos ou sem autenticação através da análise de arquivos de configuração públicos (como `robots.txt`).
* **Vazamento de Informações no Lado do Cliente (*Client-Side Leakage*):** Descoberta de rotas e endpoints administrativos ocultos/imprevisíveis diretamente no código-fonte JavaScript enviado ao navegador.
* **Manipulação de Parâmetros e Estado da Sessão (*Parameter Tampering*):** Elevação vertical de privilégios via alteração direta de atributos e cookies de controle (como `Admin=true`) mantidos de forma insegura no cliente.

### SQL Injection (Injeção de SQL)
Práticas voltadas para a exploração de consultas ao banco de dados não sanitizadas:
* **Bypass de Autenticação (*Login Bypass*):** Anulação da verificação de senha em formulários de login através da manipulação da lógica SQL e uso de caracteres de comentário (como `administrator'--`) em entradas concatenadas diretamente nas queries.

---

## Ferramentas

* **Ferramentas:** Burp Suite (Interceptação e edição de requisições HTTP), Browser DevTools (Inspeção de DOM, Cookies e Storage), Git e GitHub.

---

## Estrutura Padrão dos Relatórios

Cada relatório neste repositório segue a estrutura de documentação profissional utilizada em auditorias e testes de invasão:
1. **Diagnóstico da Vulnerabilidade:** Explicação teórica do problema.
2. **Passo a Passo da Exploração (PoC):** Vetor de ataque e reprodução técnica.
3. **Impacto no Negócio:** Riscos reais à aplicação e aos dados.
4. **Remediação:** Como corrigir o código seguindo boas práticas de desenvolvimento seguro.

---
