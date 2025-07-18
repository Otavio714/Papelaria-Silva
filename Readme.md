# 🏪 Papelaria Silva - Site E-commerce

Um site moderno e responsivo para a Papelaria Silva, desenvolvido com HTML, CSS e JavaScript puro. O site oferece um catálogo de produtos, consulta de fretes e um painel administrativo completo.

## ✨ Funcionalidades Principais

### 🏠 **Página Inicial**
- Design moderno com gradiente colorido
- Logo da empresa com efeito gradiente
- Botões de navegação para Catálogo e Consulta de Fretes
- Elementos decorativos animados
- Layout totalmente responsivo

### 📦 **Catálogo de Produtos**
- **Grid responsivo** de produtos (1-4 colunas dependendo do tamanho da tela)
- **Sistema de busca** em tempo real por nome e descrição
- **Filtro por categorias** (cadernos, canetas, borrachas, etc.)
- **Cards de produtos** com:
  - Imagem do produto
  - Nome e descrição
  - Preço em destaque
  - Layout limpo sem botões de compra
- **Mensagem personalizada** quando nenhum produto é encontrado

### 🚚 **Sistema de Fretes**
- **Consulta por bairro** com busca em tempo real
- **Lista de zonas de entrega** com preços
- **Interface intuitiva** para consulta de valores
- **Mensagem personalizada** para bairros não cadastrados

### 🔍 **Sistema de Pesquisa Global**
- **Campo de pesquisa no header** (desktop e mobile)
- **Redirecionamento automático** para o catálogo
- **Aplicação automática** do termo pesquisado
- **Funciona com clique no ícone** ou tecla Enter

### 📱 **WhatsApp Integration**
- **Ícone do WhatsApp** no header (desktop e mobile)
- **Link configurável** para seu número
- **Mensagem pré-definida** personalizável
- **Abre em nova aba** sem sair do site
- **Cores e ícones oficiais** do WhatsApp

### 🔧 **Painel Administrativo**
- **Acesso por senha** (Ctrl + Shift + A)
- **Senha configurável** no código
- **Interface moderna** com abas

#### 📦 **Gerenciamento de Produtos**
- **Adicionar produtos** com formulário completo
- **Editar produtos** existentes
- **Remover produtos** com confirmação
- **Upload de imagens** por arquivo ou URL
- **Preview de imagens** em tempo real
- **Validação de campos** obrigatórios
- **Persistência em localStorage**

#### 🚚 **Gerenciamento de Fretes**
- **Adicionar zonas de entrega** com bairro e preço
- **Editar fretes** existentes
- **Remover zonas** com confirmação
- **Validação de dados** obrigatórios
- **Persistência em localStorage**

### 📱 **Responsividade Completa**
- **Mobile-first design**
- **Menu hambúrguer** para dispositivos móveis
- **Grid adaptativo** para diferentes tamanhos de tela
- **Navegação otimizada** para touch
- **Textos e botões** redimensionáveis

### 🎨 **Design e UX**
- **Tailwind CSS** para estilização moderna
- **Fonte Inter** para melhor legibilidade
- **Cores consistentes** (roxo como cor principal)
- **Animações suaves** e transições
- **Feedback visual** para interações
- **Toast notifications** para ações do usuário

## 🚀 **Como Usar**

### **Para Clientes:**
1. **Navegue** pelas páginas usando o menu
2. **Pesquise produtos** no campo de busca
3. **Filtre por categoria** no catálogo
4. **Consulte fretes** por bairro
5. **Clique no WhatsApp** para fazer pedidos

### **Para Administradores:**
1. **Pressione Ctrl + Shift + A** para acessar o painel
2. **Digite a senha** (padrão: `admin123`)
3. **Gerencie produtos** na aba "Produtos"
4. **Configure fretes** na aba "Fretes"
5. **Clique em "Sair"** para logout

## ⚙️ **Configurações**

### **Personalizar WhatsApp:**
```javascript
// No arquivo index.html, linha ~340
whatsappButton.href = 'https://wa.me/SEU_NUMERO?text=SUA_MENSAGEM';
```

### **Alterar Senha do Admin:**
```javascript
// No arquivo index.html, linha ~109
const ADMIN_PASSWORD = 'sua_nova_senha';
```

### **Adicionar Produtos:**
1. Acesse o painel administrativo
2. Clique em "Adicionar Produto"
3. Preencha: Nome, Preço, Categoria, Descrição
4. Adicione imagem por arquivo ou URL
5. Clique em "Adicionar"

### **Configurar Fretes:**
1. Acesse o painel administrativo
2. Vá para a aba "Fretes"
3. Clique em "Adicionar Frete"
4. Digite o bairro e valor
5. Clique em "Adicionar"

## 📁 **Estrutura do Projeto**

```
Papelaria Silva/
├── index.html          # Arquivo principal com todo o código
├── IMG/               # Pasta de imagens
│   ├── Logo.png       # Logo da empresa
│   └── ...            # Outras imagens
└── README.md          # Este arquivo
```

## 🛠️ **Tecnologias Utilizadas**

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização moderna
- **JavaScript ES6+** - Funcionalidades dinâmicas
- **Tailwind CSS** - Framework de estilos
- **localStorage** - Persistência de dados
- **Google Fonts** - Tipografia

## 📱 **Compatibilidade**

- ✅ **Chrome** (recomendado)
- ✅ **Firefox**
- ✅ **Safari**
- ✅ **Edge**
- ✅ **Mobile browsers**

## 🔒 **Segurança**

- **Senha administrativa** configurável
- **Validação de dados** em formulários
- **Sanitização** de inputs
- **Persistência local** segura

## 🎯 **Recursos Avançados**

- **Sistema de rotas** com hash navigation
- **Componentes reutilizáveis** em JavaScript
- **Gestão de estado** global
- **Modais responsivos** para formulários
- **Sistema de notificações** toast
- **Upload de imagens** com preview
- **Busca em tempo real** com debounce
- **Filtros dinâmicos** por categoria

## 📞 **Suporte**

Para dúvidas ou sugestões sobre o site da Papelaria Silva, entre em contato através do WhatsApp disponível no site.

---

**Desenvolvido com ❤️ para a Papelaria Silva**
