# Guia de Navegação - JFN Calhas

## Mapa de Links e Navegação

### 🏠 Página Inicial (index.html)

**Links disponíveis:**
- Logo (clicável) → index.html (recarrega a página)
- Barra de Navegação:
  - **Produtos** → `produtos.html`
  - **Nossos Serviços** → `servicos.html`
  - **Fale Conosco** → `contato.html`

---

### 🛍️ Página de Produtos (produtos.html)

**Links disponíveis:**
- Logo (clicável) → `index.html`
- Barra de Navegação:
  - **Produtos** → `produtos.html` (página atual - ativa)
  - **Nossos Serviços** → `servicos.html`
  - **Fale Conosco** → `contato.html`
- Footer:
  - Home → `index.html`
  - Produtos → `produtos.html`
  - Serviços → `servicos.html`
  - Contato → `contato.html`

**Funcionalidades:**
- Carrinho de compras
- Sistema de filtros
- Busca de produtos

---

### 🔧 Página de Serviços (servicos.html)

**Links disponíveis:**
- Logo (clicável) → `index.html`
- Barra de Navegação:
  - **Produtos** → `produtos.html`
  - **Nossos Serviços** → `servicos.html` (página atual - ativa)
  - **Fale Conosco** → `contato.html`
- Botão CTA: **Solicitar Orçamento** → `contato.html`
- Footer:
  - Home → `index.html`
  - Produtos → `produtos.html`
  - Serviços → `servicos.html`
  - Contato → `contato.html`

**Serviços Destacados:**
1. Instalação de Calhas
2. Instalação de Coifas
3. Pintura Eletrostática
4. Manutenção Preventiva
5. Orçamento no Local
6. Entrega e Logística

---

### 📞 Página de Contato (contato.html)

**Links disponíveis:**
- Logo (clicável) → `index.html`
- Barra de Navegação:
  - **Produtos** → `produtos.html`
  - **Nossos Serviços** → `servicos.html`
  - **Fale Conosco** → `contato.html` (página atual - ativa)
- Links de Contato:
  - Telefone → tel: link
  - WhatsApp → wa.me link (abre WhatsApp)
  - Email → mailto: link
- Mapa → Google Maps integrado
- Footer:
  - Home → `index.html`
  - Produtos → `produtos.html`
  - Serviços → `servicos.html`
  - Contato → `contato.html`

**Formulário de Contato com campos:**
- Nome
- Email
- Telefone
- Assunto (dropdown)
- Mensagem

---

## Estrutura Visual de Navegação

```
┌─────────────────────────────────────────┐
│  Logo (Clicável) → index.html           │
├─────────────────────────────────────────┤
│     ┌──────────────────────────────┐    │
│     │ Produtos │ Serviços │ Contato │    │
│     │ (Links para página relativa) │    │
│     └──────────────────────────────┘    │
└─────────────────────────────────────────┘

        Conteúdo da Página

┌─────────────────────────────────────────┐
│ Footer com Links de Navegação           │
│ Home | Produtos | Serviços | Contato    │
│ Telefone | Email | Redes Sociais        │
└─────────────────────────────────────────┘
```

---

## Fluxo Recomendado de Navegação

### Cenário 1: Cliente quer conhecer produtos
```
index.html 
  ↓ (clica "Produtos")
produtos.html 
  ↓ (visualiza itens)
  ↓ (adiciona ao carrinho)
contato.html (via footer para finalizar pedido)
```

### Cenário 2: Cliente quer saber sobre serviços
```
index.html 
  ↓ (clica "Nossos Serviços")
servicos.html 
  ↓ (lê informações)
  ↓ (clica "Solicitar Orçamento")
contato.html
```

### Cenário 3: Cliente quer fazer contato direto
```
index.html 
  ↓ (clica "Fale Conosco")
contato.html 
  ↓ (preenche formulário ou clica WhatsApp)
  ✓ Mensagem enviada
```

---

## URLs Completas

| Página | URL | Descrição |
|--------|-----|-----------|
| Home | `index.html` | Página inicial |
| Produtos | `produtos.html` | Catálogo de produtos |
| Serviços | `servicos.html` | Informações sobre serviços |
| Contato | `contato.html` | Formulário e informações |

---

## Dicas de Navegação

1. **Logo sempre leva para Home** - Clique no logo "JFN Calhas" para voltar à página inicial de qualquer página
2. **Barra de Categorias** - Use a barra superior para navegar entre as 3 seções principais
3. **Footer** - Disponível em toda página para acesso rápido a todas as seções
4. **Links Contextuais** - Botões como "Solicitar Orçamento" levam diretamente para contato
5. **Redes Sociais** - Links para redes sociais no footer

---

## Elementos Interativos

✓ Carrinho de compras (em produtos)
✓ Filtros de produtos (em produtos)
✓ Busca de produtos (barra de busca global)
✓ Formulário de contato (em contato)
✓ Links WhatsApp e telefone
✓ Mapa interativo

---

*Última atualização: 23 de abril de 2026*
