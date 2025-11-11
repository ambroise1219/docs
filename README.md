# ONO Backend API Documentation

Documentation complète de l'API ONO Backend construite avec Mintlify.

## 🚀 À propos

Cette documentation couvre l'API ONO Backend, une solution modulaire en Rust qui alimente l'ensemble de la plateforme ONO. Elle fournit des services pour plusieurs domaines d'activité :

- **Food** - Restaurants et commandes alimentaires
- **Delivery** - Système de livraison complet
- **Groceries** - Épicerie en ligne
- **Pharmacy** - Pharmacies et services médicaux
- **Social** - Réseau social de type TikTok
- **Pulse** - Temps réel via gRPC, WebSocket et SSE

## 📦 Développement local

Pour prévisualiser la documentation localement, installez la [CLI Mintlify](https://www.npmjs.com/package/mintlify) :

```bash
npm i -g mintlify
```

Lancez le serveur de développement à la racine de la documentation (où se trouve `docs.json`) :

```bash
mintlify dev
```

Accédez à la prévisualisation locale sur `http://localhost:3000`.

## 🔄 Publication des modifications

Les modifications sont déployées automatiquement en production après un push sur la branche `main`.

## 🛠️ Dépannage

- **L'environnement de dev ne démarre pas** : Exécutez `mintlify update` pour avoir la dernière version de la CLI.
- **Une page charge en 404** : Assurez-vous d'être dans un dossier avec un `docs.json` valide.

## 📚 Resources

- [Documentation Mintlify](https://mintlify.com/docs)
- [Dépôt ONO Backend](https://github.com/ono/ono-backend)
- [Support ONO](mailto:support@ono.app)
