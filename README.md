# Secure by Design para Devs com IA

Checklist de cibersegurança criado para desenvolvedores que constroem aplicações com IA Generativa.

A adoção de LLMs no desenvolvimento de software criou uma nova superfície de ataque que a maioria dos times ainda não considera no ciclo de desenvolvimento. As mesmas APIs usadas para criar produtos inteligentes estão sendo exploradas para gerar phishing personalizado, realizar reconhecimento automatizado de alvos e injetar instruções maliciosas em sistemas de produção.

Este checklist traduz o que profissionais de Blue Team já observam no SOC em verificações práticas que qualquer dev pode aplicar antes de um deploy.

---

## O que este checklist cobre

**Exposição de dados** — o que você publica no GitHub, LinkedIn e Stack Overflow pode ser usado como input de reconhecimento por atacantes que automatizam a coleta com LLMs.

**Segurança da API de IA** — prompt injection, keys expostas no frontend, ausência de rate limiting e outputs de modelo não sanitizados são as vulnerabilidades mais exploradas em aplicações com IA em produção.

**Autenticação e controle de acesso** — spear phishing gerado por IA tem taxa de clique 3x maior que phishing genérico. Sem MFA e princípio do menor privilégio, uma credencial comprometida vira acesso total.

**Proteção contra ataques via IA** — deepfake de voz e vídeo já são usados em fraudes corporativas documentadas. Fine-tuning com dados reais de produção e ausência de testes de prompt injection são riscos diretos.

**Monitoramento e resposta** — sem logs de chamadas à API de IA e sem plano de resposta a incidentes, não há forense possível após um comprometimento.

---

## Para quem é

Desenvolvedores, engenheiros de software e times de produto que usam ou planejam usar IA Generativa — Gemini, OpenAI, Claude ou qualquer LLM — em aplicações reais.

Não exige experiência prévia em cibersegurança. Cada item traz uma explicação direta do risco e do que fazer.

---

## Autor

**Arthur Alves**  
Information Security Analyst · Santos Cyber Group  
[linkedin.com/in/euarthuralvess](https://linkedin.com/in/euarthuralvess) · [@euarthuralvess](https://instagram.com/euarthuralvess)
