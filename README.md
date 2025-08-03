# 🚀 Portfólio Pessoal - Desenvolvedor Front-end

Um portfólio moderno, responsivo e profissional criado com HTML, CSS e JavaScript puro. Perfeito para desenvolvedores front-end que querem mostrar seus projetos e serviços de forma impactante.

## ✨ Características

- **Design Moderno**: Interface limpa e profissional com animações suaves
- **Totalmente Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- **Performance Otimizada**: Carregamento rápido e animações fluidas
- **SEO Friendly**: Estrutura semântica e meta tags otimizadas
- **Acessível**: Seguindo as melhores práticas de acessibilidade
- **Fácil Personalização**: Código bem organizado e comentado

## 🎨 Seções Incluídas

- **Header Hero**: Apresentação impactante com call-to-action
- **Sobre Mim**: Descrição profissional e habilidades técnicas
- **Projetos**: Cards para exibir seus trabalhos com imagens e descrições
- **Serviços**: O que você oferece aos clientes
- **Depoimentos**: Testimonials de clientes satisfeitos
- **Contato**: Formulário funcional e informações de contato
- **Footer**: Links sociais e informações adicionais
- **WhatsApp Flutuante**: Botão fixo para contato direto

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilos modernos com CSS Grid e Flexbox
- **JavaScript ES6+**: Interatividade e funcionalidades dinâmicas
- **Font Awesome**: Ícones profissionais
- **Google Fonts**: Tipografia elegante (Inter)

## 📁 Estrutura do Projeto

```
port/
├── index.html          # Página principal
├── style.css           # Estilos CSS
├── script.js           # Funcionalidades JavaScript
└── README.md           # Este arquivo
```

## 🚀 Como Usar

### 1. Personalização Básica

#### Informações Pessoais
Edite o arquivo `index.html` e substitua:

```html
<!-- Seu nome -->
<h2>Seu Nome</h2>

<!-- Título do hero -->
<h1 class="hero-title">Desenvolvedor Front-end e Criador de Sites que Vendem</h1>

<!-- Descrição sobre você -->
<p>Sou um desenvolvedor front-end apaixonado por criar experiências digitais...</p>

<!-- Contato -->
<p>seuemail@exemplo.com</p>
<p>(11) 99999-9999</p>
```

#### WhatsApp
Atualize o link do WhatsApp no final do `index.html`:

```html
<a href="https://wa.me/5511999999999?text=Olá! Gostaria de conversar sobre um projeto web." class="whatsapp-btn" target="_blank">
```

### 2. Personalização de Projetos

Para adicionar seus projetos, edite a seção de projetos no `index.html`:

```html
<div class="projeto-card">
    <div class="projeto-image">
        <img src="caminho/para/sua/imagem.jpg" alt="Nome do Projeto">
    </div>
    <div class="projeto-content">
        <h3>Nome do Projeto</h3>
        <p>Descrição detalhada do projeto...</p>
        <div class="projeto-tech">
            <span>React</span>
            <span>Node.js</span>
        </div>
        <a href="link-do-projeto" class="btn btn-outline">Ver Projeto</a>
    </div>
</div>
```

### 3. Personalização de Cores

Edite as variáveis CSS no arquivo `style.css`:

```css
:root {
    --primary-color: #4F46E5;    /* Cor principal */
    --secondary-color: #10B981;  /* Cor secundária */
    --accent-color: #F59E0B;     /* Cor de destaque */
    /* ... outras cores */
}
```

### 4. Personalização de Serviços

Atualize a seção de serviços conforme suas especialidades:

```html
<div class="servico-card">
    <div class="servico-icon">
        <i class="fas fa-laptop-code"></i>
    </div>
    <h3>Seu Serviço</h3>
    <p>Descrição do serviço...</p>
    <ul class="servico-features">
        <li>Característica 1</li>
        <li>Característica 2</li>
    </ul>
</div>
```

## 🎯 Funcionalidades JavaScript

### Animações Automáticas
- **Scroll Animations**: Elementos aparecem conforme o scroll
- **Counter Animation**: Números das estatísticas animam
- **Typewriter Effect**: Efeito de digitação no título
- **Hover Effects**: Interações suaves nos cards

### Formulário de Contato
- **Validação em Tempo Real**: Verifica campos conforme o usuário digita
- **Notificações**: Feedback visual para o usuário
- **Simulação de Envio**: Demonstra o funcionamento (você precisará integrar com backend)

### Navegação
- **Menu Mobile**: Hamburger menu responsivo
- **Scroll Suave**: Navegação entre seções
- **Active States**: Indica seção atual no menu

## 📱 Responsividade

O site é totalmente responsivo com breakpoints em:
- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

## 🔧 Personalização Avançada

### Adicionando Novas Seções

1. Crie a estrutura HTML da nova seção
2. Adicione os estilos CSS correspondentes
3. Inclua o link no menu de navegação
4. Adicione animações JavaScript se necessário

### Integrando com Backend

Para o formulário de contato, substitua a simulação no `script.js`:

```javascript
// Substitua esta parte no script.js
fetch('/api/contact', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json',
    },
    body: JSON.stringify({
        name: name,
        email: email,
        subject: subject,
        message: message
    })
})
.then(response => response.json())
.then(data => {
    showNotification('Mensagem enviada com sucesso!', 'success');
})
.catch(error => {
    showNotification('Erro ao enviar mensagem.', 'error');
});
```

## 🚀 Deploy

### Opções de Hospedagem

1. **GitHub Pages** (Gratuito)
2. **Netlify** (Gratuito)
3. **Vercel** (Gratuito)
4. **Hostinger** (Pago)
5. **GoDaddy** (Pago)

### Deploy no GitHub Pages

1. Crie um repositório no GitHub
2. Faça upload dos arquivos
3. Vá em Settings > Pages
4. Selecione a branch main
5. Seu site estará disponível em `https://seuusuario.github.io/seurepositorio`

## 📈 SEO e Performance

### Meta Tags Incluídas
- Title otimizado
- Meta description
- Viewport para responsividade
- Charset UTF-8

### Otimizações de Performance
- CSS e JS minificados (recomendado para produção)
- Imagens otimizadas
- Lazy loading para imagens
- Animações otimizadas com CSS transforms

## 🎨 Paleta de Cores

- **Primária**: #4F46E5 (Azul/Índigo)
- **Secundária**: #10B981 (Verde)
- **Destaque**: #F59E0B (Laranja)
- **Texto**: #1F2937 (Cinza escuro)
- **Fundo**: #FFFFFF (Branco)

## 📞 Suporte

Se precisar de ajuda para personalizar ou implementar funcionalidades específicas, entre em contato!

## 📄 Licença

Este projeto é de uso livre. Sinta-se à vontade para modificar e usar em seus projetos pessoais e comerciais.

---

**Desenvolvido com ❤️ para a comunidade de desenvolvedores** 