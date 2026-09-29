# Transpetro Estudo — App Android

App Android nativo que envolve a PWA de estudos.

## Como gerar o APK (10 min)

### Passo 1: Cria conta GitHub (se ainda não tem)
- Vai em https://github.com
- Clica "Sign up" — email, senha, username

### Passo 2: Cria repositório
- Clica no botão verde "New" (canto superior esquerdo)
- Nome: `transpetro-estudo`
- Deixa **público**
- **NÃO marca** "Add README" nem nada
- Clica "Create repository"

### Passo 3: Sobe os arquivos deste ZIP
- **Descompacta o ZIP** no teu PC
- Na página do repo, clica "**uploading an existing file**" (link no meio)
- **Arrasta a pasta descompactada inteira** pra dentro
- Espera terminar upload
- Rola pra baixo, escreve "primeiro commit" e clica "**Commit changes**"

### Passo 4: Aguarda o build automático
- Clica na aba "**Actions**" (topo)
- Vê um workflow "Build APK" com bola amarela (rodando)
- Espera ~5 minutos até virar bola verde ✓

### Passo 5: Baixa o APK
- Clica no workflow verde
- Rola até "Artifacts" no final
- Clica em "**transpetro-app-debug**" → baixa ZIP
- Descompacta → tem o arquivo `app-debug.apk`

### Passo 6: Instala no celular
- Manda o APK pro celular (WhatsApp, Drive, USB)
- No celular, ativa "**Instalar apps de fontes desconhecidas**" em Configurações → Segurança → Fontes desconhecidas
- Toca no APK → Instalar
- **Ícone azul "TR" aparece na gaveta de apps**
- Abre pelo ícone — app nativo, tela cheia, funciona offline

## Que este projeto faz

- App Android nativo (WebView) que carrega os arquivos de estudo
- Ícone próprio na gaveta de apps
- Voz TTS do sistema Android (Google TTS pt-BR)
- Funciona 100% offline após instalação
- Comportamento igual apps normais (fechar/abrir, back button, etc.)

## Se der erro no Actions
Me manda screenshot do log de erro que ajusto.
