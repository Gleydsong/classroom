# 📦 Webpack Classroom

Projeto de estudos sobre **Module Bundlers** utilizando Webpack 5, desenvolvido para aprender e dominar as configurações essenciais de um bundler moderno.

## 🎯 Sobre o Projeto

Este projeto foi criado com o objetivo de explorar e entender como funcionam os module bundlers, especialmente o Webpack. Através de uma configuração do zero, implementei diversos loaders, plugins e otimizações que são fundamentais no desenvolvimento web moderno.

## 🚀 Tecnologias Utilizadas

- **Webpack 5** - Module bundler
- **Babel** - Transpilador JavaScript (ES6+ → ES5)
- **Webpack Dev Server** - Servidor de desenvolvimento com hot reload
- **HTML Webpack Plugin** - Geração automática de HTML
- **CSS Loader & Style Loader** - Processamento de CSS
- **HTML Minimizer** - Otimização de HTML

## 📁 Estrutura do Projeto

```
classroom/
├── src/
│   ├── js/
│   │   ├── index.js         # Entry point da aplicação
│   │   └── components.js    # Componentes reutilizáveis
│   ├── CSS/
│   │   └── styles.css       # Estilos da aplicação
│   └── index.html           # Template HTML
├── dist/                    # Arquivos compilados (gerado automaticamente)
├── webpack.config.js        # Configuração do Webpack
└── package.json
```

## ⚙️ Configurações Implementadas

### 🔧 Webpack Config

- **Entry Point**: Configurado para iniciar em `src/js/index.js`
- **Output**: Bundle gerado em `dist/main.js`
- **Mode**: Development (com source maps)
- **Watch Mode**: Recompilação automática ao salvar arquivos

### 🎨 Loaders

- **babel-loader**: Transpilação de código JavaScript moderno
- **css-loader**: Resolução de imports CSS
- **style-loader**: Injeção de CSS no DOM

### 🔌 Plugins

- **HTMLWebpackPlugin**: Geração automática do HTML com injeção dos bundles
- **HTML Minimizer**: Otimização e minificação de HTML

### 🌐 Dev Server

- Porta: `3000`
- Static files servidos da pasta `dist`
- Hot Module Replacement (HMR)

## 🛠️ Como Usar

### Pré-requisitos

- Node.js instalado (versão 14+)
- npm ou yarn

### Instalação

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/webpack-classroom.git

# Entre na pasta do projeto
cd webpack-classroom

# Instale as dependências
npm install
```

### Comandos Disponíveis

```bash
# Modo desenvolvimento com servidor local
npm run dev

# Build de produção
npm run build
```

### Acessando a Aplicação

Após executar `npm run dev`, acesse:
```
http://localhost:3000
```

## 💡 O que Aprendi

- Como configurar o Webpack do zero
- Diferença entre loaders e plugins
- Configuração de transpilação com Babel
- Processamento de diferentes tipos de assets (JS, CSS)
- Otimização de bundles
- Configuração de ambiente de desenvolvimento
- Module resolution e dependency management

## 📚 Recursos Úteis

- [Documentação Oficial do Webpack](https://webpack.js.org/)
- [Babel Documentation](https://babeljs.io/)
- [Webpack Dev Server](https://webpack.js.org/configuration/dev-server/)

## 🤝 Contribuições

Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias!

## 📝 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar e modificar como desejar.

---

⭐ Se este projeto te ajudou de alguma forma, considere dar uma estrela!

**Desenvolvido com 💙 durante meus estudos sobre Module Bundlers**

