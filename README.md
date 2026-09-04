# Nutrialle Campo iOS

Base iOS do app Campo, separada da aplicação web em produção.

Origem: `norbertown02/nutrialle-campo` (branch `main`).

## Stack
- React + Vite
- Supabase
- Capacitor
- iOS / Xcode

## Fluxo local

```bash
npm install
npm run build
npx cap add ios
npx cap sync ios
npx cap open ios
```

No Xcode, selecione seu `Personal Team` em **Signing & Capabilities**, conecte o iPhone e execute o app.

> A aplicação web original permanece separada e não é alterada por este repositório.
