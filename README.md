# StoryFlow Quiz

Quiz interativo para diagnóstico de Stories do Instagram com sistema StoryFlow.

## 🚀 Como executar localmente

1. **Instalar dependências:**
   ```bash
   npm install
   ```

2. **Iniciar servidor local:**
   ```bash
   npm run dev
   ```

3. **Acessar:**
   - URL: http://localhost:3000
   - O navegador deve abrir automaticamente

## 📁 Estrutura do projeto

```
├── index.html              # Página principal
├── package.json            # Dependências e scripts
├── assets/
│   ├── css/               # Estilos CSS
│   ├── images/            # Imagens do quiz
│   │   ├── img-boneca01.png
│   │   ├── img-boneca02.png
│   │   ├── prova social 1.jpeg
│   │   └── prova social 2.jpeg
│   └── js/                # JavaScript
│       ├── app.js         # Lógica principal
│       ├── quiz-engine.js # Motor do quiz
│       ├── charts.js      # Gráficos
│       └── supabase-config.js # Configuração do banco
└── README.md
```

## 🎯 Funcionalidades

- ✅ Quiz interativo com 8 perguntas
- ✅ Diagnóstico personalizado
- ✅ Sistema de navegação SPA
- ✅ Gráficos de comparação
- ✅ Integração com Supabase
- ✅ Design responsivo
- ✅ Animações suaves

## 🛠️ Scripts disponíveis

- `npm run dev` - Inicia servidor de desenvolvimento (porta 3000)
- `npm start` - Inicia servidor de produção (porta 8080)
- `npm run build` - Build do projeto

## 📱 Tecnologias utilizadas

- **HTML5** - Estrutura
- **Tailwind CSS** - Estilização
- **JavaScript ES6+** - Lógica
- **Chart.js** - Gráficos
- **Supabase** - Banco de dados
- **http-server** - Servidor local

## 🎨 Personalização

Para personalizar o quiz, edite os arquivos:
- `assets/js/quiz-engine.js` - Perguntas e lógica
- `assets/js/app.js` - Interface e navegação
- `index.html` - Layout e conteúdo