# SEV Gestão & Sistemas

ERP que evoluiu para uma plataforma SaaS multi-empresa, cobrada por assinatura.

🔗 **Site em produção:** [sevgestaoesistemas.com.br](https://sevgestaoesistemas.com.br)

## Sobre o projeto

O SEV é um sistema de gestão empresarial (ERP) desenvolvido do zero, oferecido hoje como SaaS para múltiplas empresas clientes, cada uma com seus próprios dados isolados e seguros.

## Stack técnica

- **Backend:** Node.js + Fastify
- **Banco de dados:** PostgreSQL (via Supabase)
- **Frontend:** HTML, CSS, JavaScript
- **Infraestrutura:** Render (backend), GitHub Pages (site institucional), Cloudflare (proxy, SSL, proteção)
- **Versionamento:** Git

## Principais funcionalidades

- 🏢 **Multi-empresa** com isolamento de dados via Row Level Security (RLS) no PostgreSQL
- 🔌 **API de integração** para clientes (modelo push), cobrindo Vendas e Estoque, com autenticação por chave de API e controle de escopos
- 🔒 **Segurança de infraestrutura**: proxy e WAF via Cloudflare, Worker para validação de IP real, rate limiting por empresa e global
- 📋 **Auditoria**: logs de login e ações relevantes (vendas, produtos, configurações, equipe, integrações)
- 💳 **Sistema de assinaturas** com planos mensal, trimestral e anual
- 📄 **Conformidade legal**: Termos de Uso e Política de Privacidade adequados à LGPD

## Capturas de tela

**Painel principal** — visão geral do negócio, receita, pedidos e estoque em tempo real

<img width="1863" height="923" alt="Captura de tela 2026-08-10 223357" src="https://github.com/user-attachments/assets/351f2101-76e9-4d73-9c02-9f92f860e0ac" />


**Financeiro** — controle de receitas, despesas e importação automática de XML de NF-e

<img width="1856" height="922" alt="Captura de tela 2026-08-10 223410" src="https://github.com/user-attachments/assets/38b0b13e-6064-4f5d-8c67-ed061f309cb8" />


**Vendas** — cadastro de clientes e registro de pedidos com baixa automática de estoque

<img width="1863" height="924" alt="Captura de tela 2026-08-10 223420" src="https://github.com/user-attachments/assets/be183c5b-1203-4feb-80c7-decb8c91174e" />


**Estoque** — cadastro de produtos e alertas de reposição

<img width="1871" height="922" alt="Captura de tela 2026-08-10 223435" src="https://github.com/user-attachments/assets/fb79dd30-6c28-4cc3-a15d-3f7d0353936d" />


## Sobre o código-fonte

O repositório de código está privado, pois contém configurações e dados de clientes reais em produção. Este repositório serve como apresentação técnica do projeto.

---

📫 Contato: [LinkedIn](https://www.linkedin.com/in/miguel-lima-barros-671714327)<img width="1871" height="922" alt="Captura de tela 2026-08-10 223435" src="https://github.com/user-attachments/assets/c7e7a5b6-d7b6-4f8a-bfd7-04a25a27f52b" />


