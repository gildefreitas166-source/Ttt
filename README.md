# 📺 IPTV App

Aplicativo IPTV em React Native (Expo).  
Suporta listas M3U, categorias e player de vídeo.

## 🚀 Recursos
- Build automatizado com Expo EAS
- Upload automático para Mediafire
- Tema escuro/claro automático
- Busca de canais e filtro por categoria

## 🔗 Como pegar o APK
Quando o GitHub Actions terminar o workflow, no log você verá algo como:

```
✅ Baixe aqui: https://www.mediafire.com/file/XXXXXX/app.apk
```

Basta copiar esse link e compartilhar. 🎉

## ⚙️ Configuração
1. Configure os **Secrets** no repositório:
   - `EAS_TOKEN`
   - `MEDIAFIRE_KEY`
   - `MEDIAFIRE_USER`
   - `MEDIAFIRE_PASS`
2. Faça `git push` e aguarde o build.

Pronto! O APK estará disponível no Mediafire automaticamente.
