# NEXUS SQUADS

> **12 Times de IA Especialistas. Direto no Seu Claude Code.**

Instale uma vez. Use em qualquer projeto. Para sempre.

---

## O Que São os Nexus Squads?

Os Nexus Squads são 12 times de agentes IA altamente especializados que se instalam globalmente no seu **Claude Code**. Cada squad traz os maiores especialistas do mundo no formato de agentes prontos para trabalhar — ativados com um único comando (`/`).

Quer copy que converte? Chame o Copy Master. Precisa de branding? O Brand Squad está pronto. Estratégia de negócio? Seu Advisory Board com Ray Dalio, Charlie Munger e Peter Thiel está disponível — agora.

---

## Os 12 Squads

| Squad | Agentes | Especialidade |
|-------|---------|---------------|
| **Advisory Board** | 11 | Conselho estratégico — Ray Dalio, Charlie Munger, Peter Thiel, Naval Ravikant... |
| **Brand Squad** | 15 | Branding e posicionamento — David Aaker, Marty Neumeier, Al Ries, Donald Miller... |
| **C-Level Squad** | 6 | Liderança executiva — CEO, CTO, CMO, COO, CIO, CAIO |
| **Claude Code Mastery** | 8 | Domínio do Claude Code — hooks, MCP, automações, worktrees |
| **Copy Master** | 23 | Copywriting lendário — Gary Halbert, David Ogilvy, Eugene Schwartz, Dan Kennedy... |
| **Copy Squad** | 23 | Copy Squad com frameworks adicionais de conversão |
| **Cybersecurity** | 15 | Segurança ofensiva e defensiva — pentest, recon, incident response |
| **Data Squad** | 7 | Analytics e growth — Sean Ellis, Avinash Kaushik, Peter Fader... |
| **Design Squad** | 8 | UX/UI e design systems — Brad Frost, Dan Mall, Dave Malouf... |
| **Hormozi Squad** | 16 | Negócios e escala — ofertas irresistíveis, pricing, funis |
| **Movement** | 7 | Construção de movimentos, manifestos e comunidades |
| **Storytelling** | 12 | Narrativa e pitch — Joseph Campbell, Nancy Duarte, Oren Klaff... |
| **Traffic Masters** | 16 | Tráfego pago — Molly Pittman, Ralph Burns, Tom Breeze, Pedro Sobral... |

---

## Instalação Rápida

### Pré-requisitos

- [Node.js 18+](https://nodejs.org)
- [Git](https://git-scm.com)
- [Claude Code](https://docs.anthropic.com/claude-code) — `npm install -g @anthropic-ai/claude-code`

### Passo 1 — Instalar o AIOS (base)

```bash
git clone https://github.com/SynkraAI/aios-core.git ~/aios-core
cd ~/aios-core && npm install && npm link
cp -r ~/aios-core/.claude/commands/AIOS ~/.claude/commands/AIOS
```

### Passo 2 — Instalar os Nexus Squads

```bash
git clone https://github.com/philipesells-oss/nexus-squads.git ~/nexus-squads
cp -r ~/nexus-squads/* ~/.claude/commands/
```

### Passo 3 — Verificar

Feche e abra o Claude Code. Digite `/` — seus 12 times aparecem.

---

## Guia de Instalação Completo (Do Zero)

Nunca usou o Claude Code? Não tem o Node.js instalado? O arquivo `guia-instalacao.html` cobre tudo:

- Instalação do Node.js (Mac / Windows / Linux)
- Instalação do Git
- Instalação do Claude Code
- Criação de conta + API key na Anthropic
- Instalação do AIOS
- Instalação dos Nexus Squads
- Verificação e primeiros comandos

---

## Como Usar

Todo comando segue o padrão: `/[squad]:[tipo]:[nome]`

```bash
# Copywriter lendário para sua landing page
/copy-master:agents:gary-halbert

# Branding e naming da sua marca
/brand-squad:tasks:generate-names

# Advisory Board para decisão estratégica
/advisory-board:agents:ray-dalio

# Análise de performance de tráfego
/traffic-masters:tasks:analyze-performance

# Criar design system completo
/design-squad:tasks:create-design-system

# Auditoria de segurança
/cybersecurity:tasks:assess-security

# Criar oferta irresistível
/hormozi-squad:tasks:create-offer
```

---

## Estrutura dos Squads

```
squad-name/
├── README.md           # Documentação do squad
├── squad.yaml          # Manifesto (agentes, tasks, workflows)
├── agents/             # Definições de agentes (persona, role, foco)
├── tasks/              # Tasks executáveis com inputs/outputs
├── checklists/         # Checklists de qualidade
├── config/             # Configurações
└── data/               # Frameworks e referências
```

---

## Licença

MIT — Use, modifique e distribua livremente.

---

**NEXUS SQUADS** — 12 Times de IA Especialistas para o Claude Code
