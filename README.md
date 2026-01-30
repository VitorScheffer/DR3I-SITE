# DR3I - Website

Website institucional estático da DR3I - Gestão de Drawback.

## Estrutura

```
DR3i-Site/
├── index.html          # Página principal
├── assets/             # Arquivos de mídia
│   ├── logo.png        # Logo horizontal da empresa
│   ├── icon.png        # Ícone/símbolo da marca
│   └── favicon.png     # Favicon do site
└── README.md           # Este arquivo
```

## Configuração

### Imagens Necessárias

Adicione os seguintes arquivos na pasta `assets/`:

1. **logo.png** - Logo horizontal da DR3I (usado na navegação e rodapé)
2. **icon.png** - Ícone/símbolo quadrado (usado na seção hero)
3. **favicon.png** - Favicon para a aba do navegador

### Personalização

#### Cores
As cores da marca estão definidas como variáveis CSS no início do arquivo `index.html`:

```css
--color-primary: #031B4E;    /* Azul escuro principal */
--color-secondary: #0A3FB0;  /* Azul médio */
--color-accent: #00AEF1;     /* Azul claro/ciano */
```

#### Contato
Atualize o link do WhatsApp na seção de contato:

```html
<a href="https://wa.me/5500000000000" ...>
```

Substitua `5500000000000` pelo número de telefone real (código do país + DDD + número, sem espaços ou caracteres especiais).

## Como usar

1. Clone ou baixe este repositório
2. Adicione as imagens na pasta `assets/`
3. Atualize as informações de contato conforme necessário
4. Abra o arquivo `index.html` em um navegador ou hospede em qualquer servidor web estático

## Hospedagem

Este é um site estático e pode ser hospedado em qualquer serviço, incluindo:

- GitHub Pages
- Netlify
- Vercel
- Amazon S3
- Qualquer servidor web tradicional

## Características

- ✅ Design responsivo (mobile-first)
- ✅ Animações suaves
- ✅ Menu mobile
- ✅ Scroll suave
- ✅ Abas interativas para serviços
- ✅ SEO básico configurado
- ✅ Performance otimizada (CSS inline, sem dependências externas além de fontes)

## Tecnologias

- HTML5
- CSS3 (com variáveis CSS)
- JavaScript vanilla
- Google Fonts (Inter)
