# Site da Dra. Iara Castro - Nutricionista

## Descrição
Site profissional desenvolvido para a nutricionista Dra. Iara Castro, inspirado no design moderno e elegante do site nataliamuniz.com.br. O site foi criado para melhorar a presença online e visibilidade no Google.

## Características do Site

### Design
- **Estilo**: Moderno, clean e profissional
- **Cores**: Paleta harmoniosa com verde (#6B8E5A) como cor principal, tons neutros e acentos dourados
- **Tipografia**: Combinação de Playfair Display (títulos) e Inter (texto)
- **Layout**: Responsivo e otimizado para dispositivos móveis

### Seções
1. **Header**: Logo, menu de navegação e botão CTA "Agendar Consulta"
2. **Hero**: Apresentação principal com foto da profissional
3. **Sobre**: Informações sobre formação e experiência
4. **Serviços**: 6 cards com os principais serviços oferecidos
5. **E-book**: Seção para download gratuito do e-book
6. **Contato**: Formulário de contato e informações
7. **Footer**: Links úteis e informações adicionais
8. **WhatsApp**: Botão flutuante fixo no canto inferior direito

### Funcionalidades
- ✅ Design responsivo (mobile-first)
- ✅ Navegação suave entre seções
- ✅ Formulário de contato integrado com WhatsApp
- ✅ **Botão flutuante do WhatsApp** (canto inferior direito)
- ✅ **Seção dedicada para e-book gratuito**
- ✅ Animações e efeitos hover
- ✅ Otimização para SEO
- ✅ Carregamento rápido
- ✅ Menu hambúrguer para mobile

## Estrutura de Arquivos
```
site_iara_castro/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # JavaScript para interatividade
├── assets/
│   └── images/
│       ├── nutricionista_profissional.jpg
│       ├── alimentacao_saudavel.jpg
│       └── icones_nutricao.jpg
└── README.md           # Este arquivo
```

## Como Usar

### 1. Hospedagem
Para colocar o site no ar, você pode usar qualquer serviço de hospedagem:
- **Netlify** (recomendado para sites estáticos)
- **Vercel**
- **GitHub Pages**
- **Hostinger**
- **GoDaddy**

### 2. Domínio
O site foi desenvolvido pensando no domínio **iaracastro.com.br** que você já possui.

### 3. Personalização
Para personalizar o site com as informações reais da Dra. Iara Castro:

#### Informações de Contato (arquivo `index.html`):
- Substitua `(11) 99999-9999` pelo telefone real
- Substitua `contato@iaracastro.com.br` pelo e-mail real
- Atualize a localização se necessário
- Adicione o número do CRN real no footer

#### Foto da Profissional:
- Substitua `assets/images/nutricionista_profissional.jpg` por uma foto real da Dra. Iara Castro
- Mantenha o formato circular (a imagem será cortada automaticamente)
- Resolução recomendada: 400x400px ou maior

#### WhatsApp (arquivo `script.js`):
- Na linha 47, substitua `5511999999999` pelo número real do WhatsApp
- Formato: código do país + DDD + número (sem espaços ou caracteres especiais)

#### Redes Sociais:
- Atualize os links das redes sociais no footer
- Adicione os perfis reais do Instagram, Facebook e LinkedIn

### 4. SEO e Google
O site já está otimizado para SEO com:
- Meta tags apropriadas
- Estrutura semântica HTML5
- Títulos hierárquicos
- Descrições relevantes
- Palavras-chave relacionadas à nutrição

Para melhorar ainda mais a visibilidade:
1. Cadastre o site no Google Search Console
2. Crie uma conta no Google Meu Negócio
3. Adicione o site ao Google Analytics
4. Publique conteúdo regularmente (blog)

## Tecnologias Utilizadas
- **HTML5**: Estrutura semântica
- **CSS3**: Estilos modernos com Flexbox e Grid
- **JavaScript**: Interatividade e animações
- **Font Awesome**: Ícones
- **Google Fonts**: Tipografia (Playfair Display + Inter)

## Suporte
O site foi desenvolvido seguindo as melhores práticas de desenvolvimento web e está pronto para uso. Todas as funcionalidades foram testadas e estão funcionando corretamente.

## Próximos Passos
1. Personalizar com informações reais
2. Adicionar foto profissional da Dra. Iara Castro
3. Configurar hospedagem
4. Apontar domínio iaracastro.com.br
5. Configurar Google Analytics e Search Console
6. Testar formulário de contato
7. Divulgar nas redes sociais

---

**Desenvolvido com ❤️ para a Dra. Iara Castro**



## Novas Funcionalidades Adicionadas

### 1. Botão Flutuante do WhatsApp
- **Localização**: Canto inferior direito da tela
- **Funcionalidade**: Abre conversa direta no WhatsApp
- **Animação**: Efeito pulsante para chamar atenção
- **Responsivo**: Adapta-se a diferentes tamanhos de tela
- **Personalização**: Substitua o número `5511999999999` no código pelo número real

### 2. Seção E-book
- **Localização**: Entre Serviços e Contato
- **Design**: Fundo gradiente verde com mockup do e-book
- **Funcionalidade**: Botão que redireciona para WhatsApp
- **Benefícios**: Lista com 3 principais vantagens do e-book
- **Personalização**: Substitua pelo arquivo PDF real do e-book

### Como Personalizar o E-book:

1. **Adicionar arquivo PDF real**:
   - Coloque o arquivo PDF na pasta `assets/`
   - Atualize a função `downloadEbook()` no `script.js`
   - Exemplo: `window.open('assets/ebook-nutricao.pdf', '_blank');`

2. **Personalizar conteúdo**:
   - Edite o título e descrição no HTML
   - Atualize os benefícios listados
   - Modifique as cores se necessário

### Como Personalizar o WhatsApp:

1. **Número do WhatsApp**:
   - Arquivo: `index.html` (linha 265) e `script.js` (linha 49 e 137)
   - Formato: `55` + `DDD` + `número` (sem espaços)
   - Exemplo: `5511987654321`

2. **Mensagem padrão**:
   - Personalize as mensagens automáticas
   - Diferentes mensagens para formulário e e-book

