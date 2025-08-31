# Feetzy – Next.js App

MVP marketing + catalogue + soumissions partenaires (email via Resend).

## Démarrer en local
```bash
npm i
npm run dev
```

## Variables d'environnement (Vercel)
- RESEND_API_KEY = (clé Resend)
- RESEND_FROM = "Feetzy <noreply@votre-domaine>"
- FEETZY_ADMIN_EMAIL = "votre.email@domaine.com"

## Déploiement
1. Poussez ce repo sur GitHub.
2. Importez sur Vercel.
3. Ajoutez les variables d'environnement ci-dessus.
4. Déployez.

## Workflow publication expériences
- Les partenaires soumettent via /partners.
- Vous recevez un email.
- Pour publier : copier le bloc JSON dans `data/experiences.json`, commiter et déployer.
