# NutriBox Pro AI - Sistema Completo

Este é o projeto completo em **React + Vite + Tailwind CSS** para gestão clínica nutricional com Inteligência Artificial.

## 🚀 Como executar no computador

1. Certifique-se de ter o **Node.js** instalado (versão 18 ou superior).
2. Extraia o conteúdo deste arquivo `.zip` para uma pasta.
3. Abra o terminal na pasta e execute os comandos:

```bash
# 1. Instalar dependências
npm install

# 2. Iniciar o servidor de desenvolvimento
npm run dev
```

4. Acesse o link fornecido no terminal (geralmente `http://localhost:5173`).

## 📱 Como compilar para Android (.APK)

Caso queira gerar um aplicativo Android nativo:

```bash
# Instalar a CLI do Capacitor
npm install @capacitor/core @capacitor/cli @capacitor/android

# Inicializar o Capacitor
npx cap init NutriBoxPro com.nutribox.pro

# Gerar build do Vite
npm run build

# Adicionar plataforma Android
npx cap add android

# Abrir no Android Studio para gerar o APK
npx cap open android
```
