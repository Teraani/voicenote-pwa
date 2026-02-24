# VoiceNote AI — PWA

App para gravar, transcrever e resumir reuniões com IA.

## 📦 Arquivos

```
voicenote-pwa/
├── index.html       ← App principal
├── manifest.json    ← Configuração PWA
├── sw.js            ← Service Worker (offline)
└── icons/
    ├── icon-192.png ← Ícone para Android
    ├── icon-512.png ← Ícone para splash screen
    └── favicon.png  ← Ícone do browser
```

## 🚀 Como testar no celular

### Opção 1 — Netlify Drop (mais fácil, 2 minutos)
1. Acesse https://app.netlify.com/drop
2. Arraste a **pasta inteira** `voicenote-pwa` para a área de drop
3. Um link público será gerado (ex: `https://abc123.netlify.app`)
4. Abra esse link no celular

### Opção 2 — Vercel (também grátis)
1. Crie conta em https://vercel.com
2. Instale a CLI: `npm i -g vercel`
3. Na pasta do projeto: `vercel --prod`
4. Acesse o link gerado no celular

### Opção 3 — Servidor local na mesma rede Wi-Fi
```bash
cd voicenote-pwa
python3 -m http.server 8080
```
Acesse `http://SEU_IP_LOCAL:8080` no celular (mesmo Wi-Fi)

## 📲 Instalar como app no celular

### Android (Chrome)
1. Abra o link no Chrome
2. Menu (3 pontos) → "Adicionar à tela inicial"
3. Confirme → ícone aparece na tela inicial!

### iPhone (Safari)
1. Abra o link no Safari (obrigatório, não Chrome)
2. Botão de compartilhar (quadrado com seta)
3. "Adicionar à Tela de Início"
4. Confirme → ícone aparece!

## ✅ Funcionalidades

- 🎙️ Gravar áudio ao vivo com timer e waveform
- 📁 Upload de áudios (MP3, WAV, M4A, OGG)
- 📎 Anexar notas e documentos (TXT, PDF, DOCX)
- ✨ Resumo automático com pontos-chave e ações
- 🧠 Mapa mental visual da reunião
- 📝 Transcrição por falante com timestamps
- 🌐 Tradução (PT, EN, ES, FR, DE, JA)
- 🤖 Assistente com ações rápidas:
  - Redigir e-mail de resumo
  - Criar follow-up de tarefas
  - Gerar ata formal
  - Criar estrutura de slides
  - Identificar riscos
  - Preparar pauta da próxima reunião
- 📴 Funciona offline (Service Worker)
- 📲 Instalável como app nativo (PWA)
