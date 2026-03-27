# Diagnóstico ELO — Mel Figueiredo

> O espelho estratégico que revela o que está desalinhando seu negócio.

![Método ELO](https://img.shields.io/badge/Método-ELO-7B2D3B?style=for-the-badge&labelColor=2C2426)
![Status](https://img.shields.io/badge/Status-Produção-6B8F71?style=for-the-badge)
![License](https://img.shields.io/badge/Licença-Proprietária-C9A96E?style=for-the-badge)

---

## Sobre

O **Diagnóstico ELO** é uma ferramenta interativa de autodiagnóstico para empreendedoras, desenvolvida para o **Método ELO** da mentora **Mel Figueiredo**.

Através de 15 perguntas distribuídas em 3 pilares — **Essência**, **Liderança** e **Organização** — a ferramenta identifica qual pilar está desalinhado no negócio da participante, entrega um resultado visual com barras de pontuação e direciona para a mentoria *Essência da Liderança*.

## Estrutura do Método ELO

| Pilar | Significado | O que mede |
|-------|------------|------------|
| **E** — Essência | Sua verdade como raiz | Autenticidade, identidade do negócio, conexão pessoal |
| **L** — Liderança | Sua presença como direção | Posicionamento, tomada de decisão, coragem |
| **O** — Organização | Sua clareza como sustentação | Prioridade, estrutura, consistência de execução |

## Funcionalidades

- **Questionário interativo** — 15 perguntas com escala Likert (1-5), clicável
- **Cálculo automático** — soma por pilar com barras animadas de resultado
- **Diagnóstico personalizado** — identifica pilar mais forte e mais fraco
- **Conteúdo editorial** — cada pilar com descrição, estados (forte/fraco), pensamentos comuns, exercício prático e nota da mentoria
- **Seção de pausa/respiração** — elemento de conexão emocional antes do conteúdo
- **CTA para mentoria** — botão direto para WhatsApp
- **Animações de scroll** — elementos aparecem suavemente conforme a navegação
- **100% responsivo** — desktop, tablet e mobile
- **Imagens embutidas** — base64 inline, zero dependência externa

## Stack

- HTML5 semântico
- CSS3 (custom properties, grid, flexbox, animations)
- JavaScript vanilla (IntersectionObserver, DOM manipulation)
- Google Fonts (Cormorant Garamond + Raleway)
- Arquivo único — sem build, sem dependências, sem framework

## Deploy

O projeto é um arquivo `index.html` autocontido. Para publicar via GitHub Pages:

1. Crie um repositório (ex: `diagnostico-elo`)
2. Faça upload do `index.html` na branch `main`
3. Vá em **Settings → Pages → Source** e selecione `main` / `/ (root)`
4. O site estará disponível em `https://seuusuario.github.io/diagnostico-elo/`

## Configuração

### WhatsApp

No CTA final, substitua `SEUNUMERO` pelo número real com código do país:

```html
<a href="https://wa.me/5569XXXXXXXXX?text=QUERO%20MENTORIA" ...>
```

### Domínio personalizado (opcional)

Para usar um domínio próprio:

1. Crie um arquivo `CNAME` na raiz com o domínio (ex: `diagnostico.melfigueiredo.com.br`)
2. Configure o DNS com um registro CNAME apontando para `seuusuario.github.io`

## Paleta de cores

| Cor | Hex | Uso |
|-----|-----|-----|
| Marsala | `#7B2D3B` | Cor principal, títulos, destaques |
| Marsala Deep | `#5C1F2B` | Fundos escuros, gradientes |
| Gold | `#C9A96E` | Acentos, ornamentos, labels |
| Cream | `#FBF7F0` | Fundo principal |
| Charcoal | `#2C2426` | Textos escuros, hero |
| Green | `#6B8F71` | Indicador "pilar forte" |

## Tipografia

- **Display/títulos:** Cormorant Garamond (300, 400, 500, 600, 700)
- **Corpo/labels:** Raleway (300, 400, 500, 600)

---

**Desenvolvido por [GrupoPasdiora](https://github.com/grupopasdiora)** — Tecnologia e automação com IA para negócios.
