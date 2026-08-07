# 💰 Finança+

Aplicativo web de **organização financeira pessoal e acompanhamento de investimentos**. Funciona 100% no navegador, sem servidor e sem cadastro — seus dados ficam **apenas no seu dispositivo**.

🔗 **Acesse:** `https://SEU-USUARIO.github.io/financas/` *(troque pelo seu link após publicar)*

---

## ✨ Funcionalidades

- 📊 **Dashboard** com saldo, receitas, despesas e **patrimônio total** (saldo + investimentos), com seletor de mês
- 💸 **Transações** — receitas e despesas, com categorias, filtros e **exclusão em massa**
- 🔁 **Recorrências** — modelos automáticos (ex: salário) que geram lançamentos pendentes para você aprovar, com data de término opcional e histórico de valores
- 💳 **Cartões e contas** — múltiplos cartões/contas com limite e filtro por perfil
- 🎯 **Orçamento** — metas por categoria com gráfico gasto × meta (mês a mês)
- 📈 **Investimentos** — carteira com preço médio × atual, alocação por classe (padrão B3) e **exclusão em massa**
- 📥 **Importação** de extratos e faturas (**PDF, CSV, OFX**) e de carteira da **B3** (Excel/PDF)
- 🎨 **3 layouts** (Clássico, Fintech, Tecnológico) + modo claro/escuro
- 👁️ **Modo privacidade** para ocultar valores ao mostrar a tela
- 💾 **Backup** completo (exportar/importar) e opção de limpar tudo

---

## 🔒 Privacidade

Este app **não envia seus dados para lugar nenhum**. Tudo é salvo localmente no navegador (via IndexedDB). Se você compartilhar o link, cada pessoa terá seus próprios dados no próprio dispositivo — ninguém vê os dados do outro.

> Para levar seus dados de um dispositivo/navegador a outro, use **Configurações → Exportar/Importar backup**.

---

## 🛠️ Tecnologias

- HTML, CSS e JavaScript puro (arquivo único `index.html`)
- [Chart.js](https://www.chartjs.org/) — gráficos
- [PDF.js](https://mozilla.github.io/pdf.js/) — leitura de PDFs
- [SheetJS](https://sheetjs.com/) — leitura de Excel
- **IndexedDB** — armazenamento local

> As bibliotecas de gráficos, PDF e Excel são carregadas via internet, então a importação de arquivos precisa de conexão. O restante funciona offline.

---

## 🚀 Como usar

1. Acesse o link do app
2. Cadastre suas **contas e cartões**
3. Adicione transações manualmente ou **importe** seu extrato/fatura
4. Acompanhe tudo no **Dashboard**

Feito com ❤️ para organização financeira pessoal.
