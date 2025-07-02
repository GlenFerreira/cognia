# Monorepo Cognia

Este repositório segue a estrutura de monorepo para facilitar a organização de múltiplos apps e serviços.

## Estrutura

```
/
├── apps/
│   └── web/           # Site institucional (estático)
│       ├── index.html
│       ├── styles.css
│       ├── script.js
│       ├── logo.jpg
│       └── README.md
├── package.json       # (opcional, para gerenciar dependências globais)
└── README.md          # Este arquivo
```

## Como rodar localmente

1. Entre na pasta do site:
   ```bash
   cd apps/web
   ```
2. Abra o arquivo `index.html` no navegador.

## Deploy no Render (Static Site)

1. No Render, crie um novo serviço do tipo **Static Site**.
2. Configure:
   - **Root Directory:** `apps/web`
   - **Build Command:** (deixe em branco)
   - **Publish Directory:** `apps/web`
3. Salve e aguarde o deploy.

Pronto! O site estará disponível na URL fornecida pelo Render.

---

Para adicionar outros apps (ex: backend, API, admin), crie novas pastas dentro de `apps/`.

# NeuroTech - Site da Startup de IA Médica

## 📋 Sobre o Projeto

Site profissional desenvolvido para a NeuroTech, uma startup brasileira especializada em Inteligência Artificial para diagnóstico médico. A plataforma utiliza redes neurais convolucionais para análise de imagens de ressonância magnética cerebral, focando na detecção precoce da Doença de Parkinson.

## 🚀 Tecnologias Utilizadas

- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Estilos modernos com Flexbox e Grid
- **JavaScript ES6+** - Interatividade e animações
- **Font Awesome** - Ícones profissionais
- **Google Fonts** - Tipografia Inter

## 🎨 Características do Design

### Design System
- **Cores Principais:**
  - Azul: `#2563eb` (Primário)
  - Roxo: `#667eea` (Gradiente)
  - Amarelo: `#fbbf24` (Destaque)
  - Verde: `#10b981` (Sucesso)

### Responsividade
- Design mobile-first
- Breakpoints: 480px, 768px, 1200px
- Menu hamburger para dispositivos móveis

### Animações
- Efeito de digitação no título principal
- Animação de contadores nas estatísticas
- Parallax suave no hero
- Animações de entrada no scroll
- Efeitos hover nos cards

## 📁 Estrutura do Projeto

```
NeuroTech/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # JavaScript interativo
└── README.md          # Documentação
```

## 🏗️ Seções do Site

### 1. Header/Navegação
- Logo da NeuroTech
- Menu de navegação responsivo
- Header transparente com blur

### 2. Hero Section
- Título principal com efeito de digitação
- Descrição da empresa
- Botões de call-to-action
- Animação do cérebro com rede neural

### 3. Sobre (About)
- Missão da empresa
- Estatísticas animadas
- Visualização de ressonância magnética

### 4. Tecnologia
- Cards explicativos das tecnologias
- Ícones representativos
- Efeitos hover

### 5. Benefícios
- Lista de vantagens da solução
- Ícones coloridos
- Layout em grid responsivo

### 6. Call-to-Action
- Seção de conversão
- Botão de contato

### 7. Contato
- Informações de contato
- Formulário funcional
- Validação de campos

### 8. Footer
- Links rápidos
- Redes sociais
- Informações da empresa

## 🎯 Funcionalidades

### Interatividade
- Navegação suave entre seções
- Menu mobile funcional
- Formulário de contato com validação
- Animações de scroll
- Tooltips informativos

### Performance
- Otimizações para mobile
- Animações reduzidas em dispositivos móveis
- Carregamento eficiente de fontes

### Acessibilidade
- Estrutura HTML semântica
- Contraste adequado
- Navegação por teclado
- Textos alternativos

## 🚀 Como Executar

1. **Clone ou baixe os arquivos**
2. **Abra o `index.html` em um navegador**
3. **Ou use um servidor local:**
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js
   npx serve .
   
   # PHP
   php -S localhost:8000
   ```

## 📱 Compatibilidade

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile (iOS/Android)

## 🎨 Personalização

### Cores
Edite as variáveis CSS no arquivo `styles.css`:
```css
:root {
  --primary-color: #2563eb;
  --secondary-color: #667eea;
  --accent-color: #fbbf24;
  --success-color: #10b981;
}
```

### Conteúdo
- Atualize textos no `index.html`
- Modifique estatísticas na seção About
- Altere informações de contato

### Animações
- Ajuste velocidades no `script.js`
- Modifique efeitos no CSS
- Personalize transições

## 📊 SEO e Meta Tags

O site inclui:
- Meta tags otimizadas
- Título descritivo
- Estrutura semântica
- URLs amigáveis
- Open Graph tags (pode ser expandido)

## 🔧 Próximas Melhorias

- [ ] Integração com backend
- [ ] Blog/Notícias
- [ ] Área de login
- [ ] Dashboard de demonstração
- [ ] Chat online
- [ ] Analytics
- [ ] PWA (Progressive Web App)

## 📞 Contato

Para dúvidas sobre o projeto:
- Email: contato@neurotech.com.br
- Telefone: +55 (11) 99999-9999

---

**Desenvolvido com ❤️ para revolucionar a medicina através da IA** 