# Painel 6 — v1.3 (IA online + Push)

## Rodar local
```bash
npm install
npm run dev
```

## Configurar IA (OpenAI direta)
- Endpoint: `https://api.openai.com/v1/chat/completions`
- Modelo: `gpt-5`
- API Key: cole sua `sk-...`

## Push Web (OneSignal)
1) Crie conta em https://onesignal.com e um App Web Push.
2) Em **Settings → Keys & IDs**, copie o **App ID**.
3) No app, em **Push Web**, cole o **OneSignal App ID** e clique **Ativar Push**.
4) No domínio publicado (Vercel), o SDK pedirá permissão de push. Aceite.

> Para Safari, configure também o **Safari Web ID** (opcional).
