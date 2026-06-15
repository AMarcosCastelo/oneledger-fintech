# OneLedger — Dashboard (Fintech)

Tela de **Dashboard** da fintech **OneLedger**, um consolidador de contas via **Open Finance**:
o usuário conecta vários bancos e vê saldo total, resumo do mês e últimas movimentações em um só lugar.

Atividade da **Fase 4 (View)** — FIAP / 1TDSOD. Recriação em **HTML + CSS + Tailwind CSS** de uma das
telas projetadas na Fase 2.

**🔗 Site publicado:** https://amarcoscastelo.github.io/oneledger-fintech/

## Como abrir

Basta abrir o arquivo **`index.html`** no navegador (duplo clique).
O CSS já vem compilado em `styles.css`, então **não precisa instalar nada** para visualizar.

## Tecnologias

- **HTML5** semântico (`header`, `nav`, `main`, `aside`, `section`, `article`)
- **CSS** em arquivo separado (`styles.css`)
- **Tailwind CSS v4** para layout e estilização
- **Design responsivo** (mobile-first com breakpoints `sm` / `lg`)
- Sem JavaScript

## Estrutura

```
oneledger-fintech/
├── index.html      # a tela (Dashboard)
├── styles.css      # CSS compilado do Tailwind (é este que o index.html usa)
├── src/
│   └── input.css   # fonte do Tailwind (tokens do design + @import)
├── package.json    # script de build do CSS
└── README.md
```

## Recompilar o CSS (opcional)

Só é necessário se você editar as classes no HTML ou os tokens em `src/input.css`:

```bash
npm install
npm run build      # gera styles.css a partir de src/input.css
```

## Identidade visual

- **Cor de marca:** roxo `#3629B7` (base no iBank UI Kit)
- **Tipografia:** Poppins (com fallback do sistema caso esteja offline)
- **Cores semânticas:** verde `#0F9D58` para entradas, vermelho `#FF4267` para saídas

## Autor

Antonio Marcos Castelo de Carvalho — RM 571858 — 1TDSOD
