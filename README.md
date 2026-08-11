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

## Sobre o código-fonte

O repositório de código está privado, pois contém configurações e dados de clientes reais em produção. Este repositório serve como apresentação técnica do projeto.

---

📫 Contato: [LinkedIn](https://www.linkedin.com/in/miguel-lima-barros-671714327)
