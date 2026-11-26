# Voidwink para Windows — download oficial

<p align="center"><img src="https://voidwink.vercel.app/og-image.png" alt="Voidwink" width="600"></p>

O **Voidwink** transforma lives da Kick, Twitch e YouTube em cortes verticais prontos para TikTok, Reels e Shorts — com título, legenda colada na fala e crédito do canal. Os cortes são feitos **no seu PC**, usando a sua placa de vídeo.

**Site oficial:** https://voidwink.vercel.app

## Baixar

➡️ **[Baixar o instalador mais recente](https://github.com/LCfoward1/voidwink-download/releases/latest/download/VoidwinkSetup.exe)**

Todas as versões, com o código de verificação (SHA-256) de cada arquivo, ficam em [Releases](https://github.com/LCfoward1/voidwink-download/releases).

## Requisitos

- Windows 10 ou 11 (64 bits)
- 8 GB de memória e uns 5 GB livres no disco
- Placa de vídeo NVIDIA recomendada (sem ela funciona, mas mais devagar)
- Uma conta do Voidwink — grátis, com 3 lives

## Instalação

1. Baixe o `VoidwinkSetup.exe` e abra.
2. Leia e aceite o contrato de uso. Tudo o que o programa precisa já vem junto.
3. Abra o Voidwink pelo atalho. Ele abre no seu navegador.

> O programa ainda não tem certificado de assinatura digital. Se o Windows mostrar **"O Windows protegeu o computador"**, clique em **Mais informações › Executar assim mesmo**. Baixe somente por este repositório ou pelo site oficial.

## Conferir o arquivo (opcional)

No PowerShell, na pasta do download:

```powershell
Get-FileHash .\VoidwinkSetup.exe -Algorithm SHA256
```

O resultado deve ser igual ao SHA-256 publicado na página da versão.

## Legal

- [Termos de Uso](https://voidwink.vercel.app/termos.html) · [Política de Privacidade](https://voidwink.vercel.app/privacidade.html) · [Licenças de código aberto](https://voidwink.vercel.app/licencas.html)
- Este repositório só distribui o instalador; o código do Voidwink não é público.
- O instalador inclui programas de código aberto (FFmpeg — GPL v3, Node.js, yt-dlp, Whisper, Real-ESRGAN), cada um sob a sua própria licença. Os textos completos e os endereços do código-fonte vão junto com o programa (`AVISOS-DE-TERCEIROS.txt` e pasta `licencas`).
- Kick, Twitch, YouTube, TikTok, Instagram, Windows e NVIDIA são marcas dos seus donos. O Voidwink não tem vínculo com essas empresas.

© 2026 Voidwink · Projeto independente mantido por Lucas Miguel Oliveira Calixto · Contato: voidwinksupport@gmail.com
