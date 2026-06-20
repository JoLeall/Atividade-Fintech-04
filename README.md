# 📸 JOVI SmartCapture

> Protótipo interativo de um sistema inteligente de câmera com 5 módulos integrados, desenvolvido como projeto acadêmico na disciplina de Design de Interface Inteligente.

---

## 💡 O que é

O **JOVI SmartCapture** é um ecossistema completo de captura, organização, edição, compartilhamento e análise de mídias — tudo com assistência de inteligência artificial. O protótipo simula a interface de um app de câmera inteligente para smartphones JOVI, com interações reais e feedback visual.

O layout segue o modelo **Split Screen**:
- **Painel Esquerdo** — Apresentação dinâmica com título, descrição e bullet points do módulo ativo.
- **Painel Direito** — Área interativa com simulações funcionais de cada módulo.

---

## 📦 Os 5 Módulos

| # | Módulo | Descrição |
|---|--------|-----------|
| 📷 | **Captura Inteligente** | Visor de câmera com grade de composição (regra dos terços), nível, controles de ISO/WB, modos foto/vídeo, e painel de assistente IA lateral com dicas de cena em tempo real. |
| 🖼️ | **Galeria Inteligente** | Galeria com filtros por tipo (fotos, vídeos), tags automáticas de IA, sugestões de álbuns, detecção de duplicatas, e cache inteligente para performance. |
| ✨ | **Editor Assistido** | Editor com 9 sliders de ajuste (exposição, contraste, saturação…) que aplicam filtros CSS reais na imagem. Inclui curva de tons interativa, zoom e 8 ferramentas profissionais. |
| 🔗 | **Compartilhamento Otimizado** | Seleção múltipla com carrossel, 9 plataformas de destino (Instagram, TikTok, WhatsApp…), toggles de privacidade, barra de progresso simulada e geração de link. |
| 📊 | **Analytics com Insights de IA** | Dashboard com métricas (views, likes, shares), gráfico de barras com troca de período (7D/30D/90D), insights da IA, melhores horários para postagem e hashtags sugeridas. |

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — Estrutura semântica com `<aside>`, `<main>`, `<nav>`, `<section>`
- **CSS3** — Estilos customizados em arquivo separado (`style.css`) com variáveis CSS, glassmorphism, animações e 4 breakpoints responsivos
- **Tailwind CSS (CDN)** — Carregado via `<script>` do CDN, complementando os estilos customizados

---

## 🚀 Como Executar

1. Baixe esta pasta.
2. Dê um **duplo clique** no arquivo `index.html`.
3. Pronto — abre direto no navegador, sem servidor necessário.


---

## 📂 Estrutura do Projeto

```
fintech-dashboard/
├── index.html       # Página principal com HTML
├── style.css        # Estilos customizados (variáveis, layouts, animações)
├── Jovi.pdf           # Fonte utilizada (Atividade 02 Fintech)
└── README.md          # Arquivo de documentação

---

## 🎓 Contexto Acadêmico

Este protótipo foi desenvolvido como entrega prática para a disciplina de **Design de Interface Inteligente**. O objetivo é demonstrar como a inteligência artificial pode ser integrada em cada etapa do fluxo fotográfico — desde a captura até a análise de performance nas redes sociais.

O projeto abrange os seguintes tópicos da proposta acadêmica:
- **Introdução** ao problema de complexidade das câmeras de smartphones
- **Objetivo** de simplificar o fluxo completo de captura-a-publicação
- **Solução Proposta** com os 5 módulos integrados
- **Impacto Esperado** na experiência do usuário



© 2026 JOVI SmartCapture — Projeto acadêmico. Todos os direitos reservados.
