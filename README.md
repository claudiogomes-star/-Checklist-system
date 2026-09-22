# PATBO — Conversor de Aviamentos & Checklist (EXP-AVI-001)

Sistema autônomo (HTML/CSS/JS puro) para conversão de relatórios de Pré-Fase da Millennium NetWork Ltda em Checklists de Envio de Aviamentos oficiais da **PatBO**.

---

## 🌟 Principais Recursos

- **100% Standalone**: Não requer Node.js, npm, terminal ou servidores locais. Basta abrir o arquivo `index.html` em qualquer navegador.
- **Leitura Automática de PDF**: Processamento local no cliente via PDF.js, sem envio de dados para servidores externos.
- **Detecção Inteligente de Páginas**:
  - **1 Página**: Documentos de até 16 itens de matéria-prima são ajustados milimetricamente em uma única página A4.
  - **2 Páginas**: Listas maiores de 16 itens são paginadas automaticamente com cabeçalho de continuação na página 2 e blocos de assinatura ao final.
- **Edição em Tempo Real**: Clique em qualquer campo do documento diretamente na tela para realizar correções antes da impressão.
- **Exportação Dupla**:
  - **Imprimir / Salvar**: Visualização de impressão nativa formatada para folha A4 com `@media print`.
  - **Baixar PDF**: Geração instantânea de arquivo `.pdf` vetorial via jsPDF.

---

## 🚀 Como Iniciar

1. Abra a pasta `aviamento-checklist`.
2. Dê duplo clique em `index.html` (ou `index-standalone.html`).
3. Clique em **"Acessar Sistema"**.
4. Faça upload do seu PDF ou clique em **"Carregar Exemplo"** para testar imediatamente com a OP 284342.
