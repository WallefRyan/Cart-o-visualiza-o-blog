Perfeito, Wallef Ryan 😎 Vou criar um **STYLE.md** bem detalhado, explicando o CSS do seu projeto e as escolhas de estilo. Aqui está:

```markdown
# 🎨 Estilo do Cartão de Visualização do Blog

Este documento descreve os estilos aplicados ao cartão de visualização de artigo, desenvolvido em **HTML e CSS**.

---

## 🌈 Cores Utilizadas

- **Fundo da página:** `hsl(47, 88%, 63%)` (amarelo vibrante)
- **Fundo do cartão:** `white` (contraste limpo com a página)
- **Categoria (Learning):** `hsl(47, 88%, 63%)` (mesma cor do fundo da página)
- **Texto principal:** `hsl(0, 0%, 3%)` (quase preto)
- **Texto secundário (descrição):** `hsl(0, 0%, 42%)` (cinza médio)

---

## 🖋️ Tipografia

- **Fonte:** Figtree (via Google Fonts)  
- **Hierarquia de textos:**
  - `h5` → Categoria do artigo (negrito e destaque com fundo amarelo)
  - `h3` → Título do artigo (1.5em, negrito, cursor pointer)
  - `p` → Parágrafos (descrição do artigo e data, com tamanhos ajustados para leitura)

---

## 📐 Layout e Estrutura

- **Body**
  - `display: flex; align-items: center; justify-content: center;` → Centraliza o cartão vertical e horizontalmente
  - `min-height: 100vh;` → O cartão sempre ocupa a altura total da tela
  - `margin: 0; padding: 0;` → Remove margens e padding padrão

- **.container**
  - `width: 300px; padding: 20px;` → Largura fixa e espaçamento interno
  - `border-radius: 15px;` → Cantos arredondados
  - `box-shadow: 10px 8px 0px black;` → Sombra estilizada para efeito “recortado”  

- **.cabessalho img**
  - `width: 100%; border-radius: 10px;` → A imagem ocupa toda a largura e tem bordas arredondadas

---

## ✨ Efeitos e Interações

- **Título do artigo (`.section1 h3`)**
  - `transition: all 0.3s ease;` → Animação suave ao passar o mouse
  - `:hover { color: hsl(47, 88%, 63%); transform: scale(1.05); }` → Muda a cor e aumenta levemente

- **Parágrafos**
  - Textos de descrição (`.section p` e `.section1 p`) possuem `line-height` e `font-size` ajustados para melhor leitura

- **Footer**
  - `display: flex;` → Alinha avatar e nome do autor horizontalmente
  - Avatar com tamanho fixo `30px x 30px`
  - Nome do autor com espaçamento ajustado

---

## 📌 Observações

- O design é **minimalista**, com foco em legibilidade e destaque para o conteúdo principal.
- As cores e efeitos de hover podem ser facilmente ajustados para criar novas variações de cartões.

---

## 💡 Possíveis Melhorias

- Tornar o cartão totalmente **responsivo** para telas pequenas
- Adicionar **sombras suaves** nos textos para maior destaque
- Criar **temas alternativos** (modo escuro, cores diferentes)
```


