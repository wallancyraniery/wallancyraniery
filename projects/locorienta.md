# LocOrienta — plataforma SaaS para locadoras de veículos

**Produto da Improve · Implantação piloto · Código-fonte privado**

[Conhecer a página pública](https://locacao-carros.vercel.app) · [Voltar ao perfil](../README.md)

## O problema

Pequenas locadoras precisam apresentar seus veículos, manter informações da frota organizadas e atender pessoas interessadas sem depender de controles dispersos.

A **LocOrienta** reúne uma vitrine pública própria para cada locadora e uma **Central privada** para a operação inicial.

## O que o produto já oferece

| Área | Entrega |
| --- | --- |
| Primeiro acesso | Convite individual, senha definida pelo próprio responsável e ativação administrativa |
| Organização | Onboarding da locadora e atualização de dados institucionais pelo proprietário |
| Frota | Cadastro e acompanhamento de veículos, valores, estados operacionais e fotografias |
| Vitrine pública | Página da locadora identificada por endereço próprio, com publicação e despublicação controladas |
| Interessados | Formulário público para manifestação de interesse e acompanhamento na Central |
| Proteção de dados | Autorização por organização, políticas no banco de dados e separação entre dados públicos e privados |

### Jornada do responsável

```mermaid
flowchart LR
    A[Convite individual] --> B[Definição de senha]
    B --> C[Ativação administrativa]
    C --> D[Novo login]
    D --> E[Cadastro da locadora]
    E --> F[Frota e fotos]
    F --> G[Preparação da vitrine]
```

**Estado da implantação:** o fluxo de convite, senha, ativação, novo login, cadastro da locadora e acesso à Central foi validado em ambiente hospedado com identidade sintética. O primeiro cliente real recebeu o convite e está iniciando seu processo de entrada; isso **não** significa que já opere comercialmente a plataforma.

## Engenharia e tecnologias

| Camada | Tecnologias e práticas |
| --- | --- |
| Aplicação | Next.js, React e TypeScript |
| Backend e persistência | PostgreSQL, Supabase e Drizzle ORM |
| Qualidade | Validação de entrada, testes automatizados, integração PostgreSQL, lint e typecheck |
| Operação | Docker para desenvolvimento, GitHub Actions e Vercel |
| Segurança | Autenticação, isolamento entre locadoras, controle de permissões e políticas de acesso no banco |

### Decisões que orientam o desenvolvimento

O desenvolvimento prioriza delimitação do domínio de cada locadora, permissões explícitas, evolução por checkpoints, validação de fluxos reais e prevenção de alterações não autorizadas em ambientes remotos.

A entrada no piloto é **assistida**. Não existe cadastro público irrestrito para novas locadoras.

## Limites do estágio atual

A LocOrienta **não oferece ainda uma operação comercial completa de reservas ou pagamentos**. Manifestação de interesse não equivale a reserva confirmada. Funcionalidades e fluxos seguem evoluindo conforme a implantação e o retorno dos usuários.

O [site público](https://locacao-carros.vercel.app) apresenta a proposta do produto. A Central exige uma conta autorizada.

> **Código privado por decisão de produto e segurança.** Esta apresentação explica o escopo e as competências técnicas sem disponibilizar credenciais, arquivos internos, infraestrutura sensível ou dados de clientes.

## Meu papel

Participo da construção da LocOrienta conectando **decisões de produto, desenvolvimento de software, arquitetura, segurança, testes e implantação** na Improve.

Tenho interesse em oportunidades de desenvolvimento **backend e full-stack**, projetos sob medida e parcerias para criar soluções úteis para operações reais.

[LinkedIn](https://www.linkedin.com/in/wallancyraniery/) · [Perfil no GitHub](https://github.com/wallancyraniery)
