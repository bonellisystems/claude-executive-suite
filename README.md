# Claude Executive Suite

**28 C-Suite Executive Personas + 8 Business Legend Advisors for Claude Code**

Each executive persona is built from extensive research on the **world's top 25 leaders** in that role — synthesizing their decision frameworks, leadership philosophies, strategic postures, and operational expertise into actionable AI advisors.

The advisory board features **8 business legends** with their complete frameworks: Alex Hormozi, Grant Cardone, Seth Godin, Gary Vee, Jordan Belfort, Russell Brunson, Dan Kennedy, and Tony Robbins.

---

## Quick Start

### Install

```bash
claude install-plugin bonellisystems/claude-executive-suite
```

### Personalize (Optional but Recommended)

```
/exec:setup
```

This runs a setup wizard that asks about your business and generates a company context file. All executives will then tailor their advice to your specific company.

### Use

```
/exec:ceo                    # Consult the Chief Executive Officer
/exec:finance                # Consult the Chief Financial Officer
/exec:technology             # Consult the Chief Technology Officer
/board:hormozi               # Consult Alex Hormozi on offer engineering
/board:godin                 # Consult Seth Godin on positioning
/allhands                    # Round-table with all 36 advisors
```

---

## Available Executives (28)

| Command | Role | Focus Areas |
|---------|------|-------------|
| `/exec:ceo` | Chief Executive Officer | P&L ownership, strategy, capital allocation, growth, culture |
| `/exec:finance` | Chief Financial Officer | Financial planning, unit economics, cash management, investment |
| `/exec:technology` | Chief Technology Officer | Architecture, build vs buy, platform strategy, engineering culture |
| `/exec:operations` | Chief Operating Officer | Operations, service delivery, SLAs, capacity planning, process |
| `/exec:infosec` | Chief Information Security Officer | Security strategy, compliance, zero trust, risk management |
| `/exec:revenue` | Chief Revenue Officer | Pipeline, sales process, pricing, channel strategy, NRR |
| `/exec:information` | Chief Information Officer | Internal IT, vendor management, technology standardization |
| `/exec:marketing` | Chief Marketing Officer | Demand generation, content, SEO, brand, partner marketing |
| `/exec:medical` | Chief Medical Officer | Healthcare vertical, HIPAA, clinical workflows, medical devices |
| `/exec:commercial` | Chief Commercial Officer | Commercial strategy, partnerships, go-to-market, pricing |
| `/exec:compliance` | Chief Compliance Officer | Regulatory compliance, SOC 2, audits, risk management |
| `/exec:customer` | Chief Customer Officer | Retention, expansion, NRR, onboarding, customer advocacy |
| `/exec:data` | Chief Data Officer | Data strategy, governance, analytics, data-driven decisions |
| `/exec:digital` | Chief Digital Officer | Digital experience, CRM, client portals, automation |
| `/exec:product` | Chief Product Officer | Product vision, roadmap, user research, product-led growth |
| `/exec:people` | Chief People Officer | Culture, talent, employee experience, organizational health |
| `/exec:procurement` | Chief Procurement Officer | Vendor management, strategic sourcing, cost optimization |
| `/exec:strategy` | Chief Strategy Officer | Competitive strategy, M&A, scenario planning, market analysis |
| `/exec:sustainability` | Chief Sustainability Officer | ESG, green operations, sustainable practices |
| `/exec:transformation` | Chief Transformation Officer | Change management, organizational transformation, scaling |
| `/exec:innovation` | Chief Innovation Officer | R&D, emerging technology, innovation pipeline |
| `/exec:experience` | Chief Experience Officer | Customer + employee experience, journey mapping, UX |
| `/exec:admin` | Chief Administrative Officer | Governance, facilities, internal administration |
| `/exec:analytics` | Chief Analytics Officer | BI, predictive analytics, dashboards, data culture |
| `/exec:chief-of-staff` | Chief of Staff | Cross-functional coordination, special projects, CEO support |
| `/exec:hr` | Chief Human Resources Officer | HR operations, compensation, org design, compliance |
| `/exec:legal` | Chief Legal Officer | Contracts, IP protection, regulatory, employment law |
| `/exec:ai` | Chief AI Officer | AI strategy, responsible AI, ML applications, AI governance |

---

## Advisory Board (8)

| Command | Advisor | Expertise |
|---------|---------|-----------|
| `/board:hormozi` | Alex Hormozi | Offer engineering, value creation, pricing, $100M Offers |
| `/board:cardone` | Grant Cardone | 10X sales, pipeline volume, follow-up, closing |
| `/board:godin` | Seth Godin | Positioning, Purple Cow, smallest viable market, brand story |
| `/board:garyvee` | Gary Vee | Content strategy, personal brand, social media, volume |
| `/board:belfort` | Jordan Belfort | Straight Line System, sales psychology, tonality, closing |
| `/board:brunson` | Russell Brunson | Funnels, value ladder, webinars, email sequences |
| `/board:kennedy` | Dan Kennedy | Direct response, magnetic marketing, high-ticket positioning |
| `/board:robbins` | Tony Robbins | Peak performance, mindset, state management, raving fans |

---

## All-Hands Mode

```
/allhands
```

Get multi-perspective strategic analysis from all 36 advisors on any business decision. The round-table provides:

- **Executive consensus** — where the C-suite agrees
- **Executive tensions** — where roles disagree and why (e.g., CFO vs CRO on growth investment)
- **Board advisor input** — what the business legends would add
- **Synthesis** — recommended path with trade-offs and suggested deep-dives

---

## Company Personalization

By default, all personas provide **industry-agnostic advice** that works for any business.

To personalize for your company:

### Option 1: Setup Wizard (Recommended)

Run `/exec:setup` and answer 10-15 questions about your business. The wizard generates a `company-context.md` file that all personas read automatically.

### Option 2: Manual Template

Copy the template and fill it in:

```bash
# The template is at:
# plugins/exec/references/company-context-template.md
#
# Copy it to:
# plugins/exec/references/company-context.md
```

---

## Research Methodology

Each executive persona was built through extensive research on the **top 25 real-world leaders** in that specific role. This includes studying their:

- Published leadership philosophies and frameworks
- Decision-making approaches and mental models
- Strategic priorities and operational focuses
- Communication styles and management techniques
- Key metrics and success indicators

The result is **700+ real leaders** synthesized across 28 roles, creating personas that reflect the collective wisdom of the world's best executives — not generic AI advice.

The research data can be found in `Top_25_CLevel_Executives_by_Role.xlsx`.

---

## How Each Persona Works

When you invoke an executive (e.g., `/exec:ceo`), the AI adopts that persona completely:

- **Identity** — Background, core mission, and professional DNA
- **Strategic Posture** — How they think about the business and market
- **Voice & Tone** — How they communicate and lead
- **Decision Framework** — Filters for evaluating any decision
- **Guardrails** — Non-negotiable boundaries and principles
- **Key Metrics** — What they measure and optimize for
- **Anti-Patterns** — Common mistakes they avoid
- **Output Formats** — How they deliver recommendations and analysis

The persona stays in character throughout the conversation, providing advice as that executive would.

---

## Examples

**Strategic pricing decision:**
```
/exec:finance
"Should we raise our prices by 20% or keep them flat and focus on volume?"
```

**Go-to-market strategy:**
```
/exec:marketing
"We're launching a new product line. Help me design the GTM strategy."
```

**Offer engineering:**
```
/board:hormozi
"My consulting service is commoditized. Help me create an irresistible offer."
```

**Multi-perspective analysis:**
```
/allhands
"We're considering acquiring a competitor. What should we think about?"
```

---

## Contributing

We welcome contributions! Here's how you can help:

### Improve Existing Personas
- Found a framework that should be included? Open a PR with the addition.
- Notice advice that could be more actionable? Suggest improvements.

### Add New Personas
- Follow the existing SKILL.md structure (identity, strategic posture, decision framework, etc.)
- Research the top 25 real-world leaders in the role
- Ensure the persona is industry-agnostic (no company-specific details)

### Report Issues
- Open an issue for any persona that gives outdated or incorrect advice
- Report any remaining company-specific content that should be generic

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## License

MIT License. See [LICENSE](LICENSE) for details.

---

Built with research and care by [Bonelli Systems](https://github.com/bonellisystems).
