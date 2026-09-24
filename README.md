# Antunes OS — Internal Business Management MVP

> Operação simples, informação organizada · Simple operations, organized information

O **Antunes OS** é um software interno criado para centralizar a operação da Antunes Digital desde o início da empresa. O objetivo é construir processos claros antes do crescimento da equipe e evoluir o sistema conforme surgirem necessidades reais.

**English summary:** A local-first internal operations dashboard for managing clients, sales opportunities, projects, tasks, notes and business partners.

## Status

`Early MVP / Local-first prototype`

Nesta versão, os dados ficam armazenados no navegador do dispositivo. O projeto ainda não utiliza banco de dados remoto nem autenticação de usuários.

## Módulos · Core modules

- **Clients** — cadastro e situação dos clientes;
- **Opportunities** — pipeline comercial e valor estimado;
- **Projects** — acompanhamento dos projetos em andamento;
- **Tasks** — tarefas, prazos e conclusão;
- **Notes** — decisões, aprendizados e DNA da empresa;
- **Partners** — rede de colaboradores e especialistas por projeto.

## Objetivos do produto

- centralizar informações que normalmente ficariam espalhadas;
- documentar processos desde a fase inicial da empresa;
- facilitar a entrada futura de parceiros e colaboradores;
- transformar aprendizados comerciais em dados estruturados;
- servir como laboratório para futuras soluções da Antunes Digital.

## Stack

- `HTML5`
- `CSS3`
- `JavaScript`
- `LocalStorage`
- Responsive Dashboard
- Local-first architecture

## Executar localmente · Run locally

Abra `dist/index.html` no navegador ou sirva a pasta `dist` com um servidor HTTP local.

## Estrutura atual

```text
dist/
├── assets/
├── index.html
├── script.js
└── styles.css
```

## Limitações atuais · Current limitations

- dados disponíveis somente no navegador utilizado;
- ausência de login e controle de acesso;
- sem sincronização entre dispositivos;
- sem backups automáticos;
- dados demonstrativos usados apenas para validar a interface.

## Roadmap

- [x] Dashboard e indicadores iniciais
- [x] Clientes, oportunidades, projetos e tarefas
- [x] Notas e parceiros
- [x] Persistência local para prototipagem
- [ ] Autenticação e perfis de acesso
- [ ] Banco de dados PostgreSQL/Supabase
- [ ] Entrada automática das solicitações do site
- [ ] Histórico de atividades e responsáveis
- [ ] Arquivos, propostas e documentos
- [ ] Relatórios operacionais e comerciais
- [ ] Backups e boas práticas de segurança

## Autoria · Ownership

Projeto pessoal idealizado, dirigido e desenvolvido por **Gabriel Antunes**.

- Product design and business requirements
- Process modeling
- Interface and workflow decisions
- Front-end development
- AI-assisted development workflow with Codex

## Keywords

`Internal Tool` · `CRM` · `Project Management` · `Sales Pipeline` · `Local-first` · `JavaScript` · `Business Operations` · `AI-assisted Development`

---

O Antunes OS não é apresentado como um produto final. Ele documenta a evolução real de uma operação e de um desenvolvedor em formação.
