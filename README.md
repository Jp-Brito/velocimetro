# Velocímetro GPS — PWA

Velocímetro para moto usando GPS do celular. Funciona offline depois da primeira abertura.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub (ex: `velocimetro`)
2. Faça upload de todos os arquivos desta pasta
3. Vá em **Settings → Pages → Branch: main → / (root) → Save**
4. Acesse `https://SEU_USUARIO.github.io/velocimetro/`

## Como instalar no iPhone como app

1. Abra o link no **Safari** (não funciona em outros navegadores no iOS)
2. Toque no botão de compartilhar (quadrado com seta)
3. Toque em **"Adicionar à Tela de Início"**
4. Confirme — o app aparece na tela inicial como qualquer outro app

## Dicas de uso

- A velocidade mínima só é registrada acima de 1,5 km/h (ignora quando está parado)
- O botão "Resetar máx / mín" zera os recordes sem parar o GPS
- Para a tela não apagar: **Ajustes → Tela e Brilho → Bloqueio Automático → Nunca**
- O app tenta ativar o Wake Lock automaticamente (iOS 16.4+)
- Funciona 100% offline após a primeira abertura (Service Worker faz cache dos arquivos)

## Arquivos

| Arquivo | Função |
|---|---|
| `index.html` | App principal |
| `manifest.json` | Configuração PWA (ícone, nome, cor) |
| `sw.js` | Service Worker — cache offline |
| `icon.svg` | Ícone do app |
# Velocimetro
