# Especificação de Layout - Cantinho dos Sonhos

Este documento detalha a construção visual da página, integrando a copy aprovada com os princípios de design de alta conversão e o efeito parallax solicitado.

---

## Seção 1: Hero (Sono de Qualidade Agora)

### Arquetipo e Constraints
- **Arquetipo:** Split Vertical (50/50) com Bleed Right
- **Constraints:** Imagem Parallax, Badge Overlap, Headline Full Width
- **Justificativa:** Cria uma entrada limpa e impactante, destacando o produto e a entrega imediata com profundidade visual.

### Conteudo
- **Headline:** O colchão ideal com entrega acelerada.
- **Subheadline:** Durma melhor hoje mesmo! Descubra grandes marcas com condições a partir de 10x de R$ 89 sem juros.
- **CTA:** Garantir Melhor Sono
- **Badge:** Receba Hoje Mesmo - Entrega super rápida!
- **Endereço:** Av. Pres. Getúlio Vargas, 2324

### Layout
- **Estrutura:** Grid 2 colunas (Mobile: 1 coluna).
- **Herança Visual:** Manter o alinhamento à esquerda para textos e imagem sangrando à direita.
- **Hero Visual:** Imagem ocupa 100% da altura da seção no desktop.

### Tipografia
- **Headline:** `Plus Jakarta Sans`, 800 weight, `clamp(2.8rem, 4vw, 4rem)`, line-height 1.1, letter-spacing -0.02em.
- **Subheadline:** `Inter`, 400 weight, `1.2rem`, line-height 1.6, color `#7A7A7A`.

### Cores
- **Primária:** `#B30000` (Botões e Destaques).
- **Badge:** Fundo `#FFFFFF`, borda esquerda `#FFE600`.
- **Texto:** `#222222`.

### Elementos Visuais
- **Efeito Parallax:** A imagem do colchão deve ter um movimento sutil (speed: 0.15) no sentido oposto ao scroll, criando profundidade.
- **Badge:** Box shadow suave `0 20px 40px rgba(0, 0, 0, 0.1)`.

### Animacoes
- **Parallax:** Scroll-linked na imagem principal.
- **Pulse:** No indicador "Loja Número 1".
- **Sem animação de entrada** (Conforme regra do projeto).

---

## Seção 2: Por que escolher o Cantinho dos Sonhos?

### Arquetipo e Constraints
- **Arquetipo:** Bento Box
- **Constraints:** Hover Lift, Stagger, Glassmorphism Cards
- **Justificativa:** Organiza os benefícios de forma moderna e não linear, fugindo do grid de 3 colunas tradicional.

### Conteudo
- **Título:** A Melhor Loja de Alvorada e Região
- **Benefício 1:** Preço Imbatível (10x de R$ 99 sem juros).
- **Benefício 2:** Entrega Ultra Rápida (Dependendo do horário, entregamos no mesmo dia).
- **Benefício 3:** Variedade Premium (As melhores marcas do mercado).

### Layout
- **Bento Grid:** 4 células. 
  - Célula 1 (Larga): Título + Subtítulo.
  - Célula 2 (Alta): Preço Imbatível.
  - Célula 3 (Padrão): Entrega Ultra Rápida.
  - Célula 4 (Padrão): Variedade Premium.
- **Gap:** 24px. Padding seção: 120px 0.

### Tipografia
- **Título Seção:** `Plus Jakarta Sans`, 700, `clamp(2rem, 3.5vw, 3rem)`.
- **Cards Header:** `Plus Jakarta Sans`, 600, `1.4rem`.

### Cores
- **Fundo Seção:** `#E6E6E6`.
- **Cards:** White Glass (`#FFFFFF` com opacity 0.9 e backdrop-filter blur 10px).
- **Destaque:** Borda de 1px sólida `#FFFFFF`.

### Animacoes
- **AOS:** `fade-up` com stagger de 100ms entre as células.
- **Hover:** `translateY(-8px)` + Shadow expansion.

---

## Seção 3: Festival de Colchões e Acessórios

### Arquetipo e Constraints
- **Arquetipo:** Modular
- **Constraints:** Hover Glow, Image Overlay, Perspective Carousel
- **Justificativa:** Exibe os produtos de forma tátil e elegante, destacando a variedade.

### Conteudo
- **Título:** Tudo para o Seu Quarto
- **Itens:** Colchões de Molas, Box e Baú, Cabeceiras.
- **CTA:** VER MODELOS NO WHATSAPP

### Layout
- **Estrutura:** Grid Modular com imagens grandes e texto sobreposto na base com gradiente.
- **Aspect Ratio:** Imagens 4:5 para verticalidade premium.

### Cores
- **Overlays:** Gradiente linear `rgba(0,0,0,0) 0%` para `rgba(0,0,0,0.8) 100%`.
- **Texto:** White `#FFFFFF`.

### Interatividade
- **Hover Glow:** Ao passar o mouse, uma borda de luz sutil `#FFE600` deve percorrer o card.
- **Botão CTA:** Sticky no canto inferior direito para mobile após scroll nesta seção.

---

## Seção 4: Localização

### Arquetipo e Constraints
- **Arquetipo:** Split Diagonal
- **Constraints:** Fixed Element, Skewed Section, Text Outline
- **Justificativa:** Quebra a monotonia do scroll com uma transição diagonal forte.

### Conteudo
- **Título:** Venha nos Visitar
- **Endereço:** Av. Presidente Getúlio Vargas, 2324 – Alvorada/RS
- **Texto:** Tem dúvidas de qual é o melhor modelo? Venha testar na nossa loja!

### Layout
- **Divisão:** 40% Texto / 60% Mapa.
- **Divisor:** Diagonal de 5 graus cortando a seção.
- **Mapa:** Elemento fixo que revela conforme o scroll "limpa" a área.

### Tipografia
- **Título Outline:** Stroke 1px primário, sem preenchimento, transformando-se em sólido no scroll.

### Animacoes
- **Parallax Background:** Textura de mapa estilizada movendo-se lentamente ao fundo.

---

## Seção 5: CTA Final (Fechamento)

### Arquetipo e Constraints
- **Arquetipo:** Single Focus
- **Constraints:** Neon Colors, Pulse Loop, High Contrast
- **Justificativa:** Foco absoluto na conversão final com urgência.

### Conteudo
- **Título:** Nós Temos o Colchão Ideal Para o Seu Sono
- **Subheadline:** Fale agora mesmo com nossos vendedores e garanta as melhores promoções.
- **CTA:** FAZER ORÇAMENTO NO WHATSAPP

### Layout
- **Centralizado:** Altura 60vh.
- **Container Narrow:** Max-width 800px.

### Cores
- **Fundo:** Dark `#222222`.
- **Botão:** Neon Red Effect (Shadow com spread generoso na cor primária).

### Animacoes
- **Pulse Loop:** O botão CTA respira suavemente.
- **Floating Shapes:** Elementos circulares borrados `#B30000` flutuando ao fundo em movimento aleatório.
