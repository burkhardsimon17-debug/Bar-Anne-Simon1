# 🍸 Bar Luxe - Menu Interactif

Une page web minimaliste et luxe pour afficher le menu des boissons d'un bar avec filtrage par catégorie.

## 🚀 Déploiement en direct

Ce site est déployé sur GitHub Pages.

**🔗 Accédez au site:** https://burkhardsimon17-debug.github.io/Bar-Anne-Simon1/

## 📋 Source des données

Les données des boissons sont chargées **automatiquement** depuis votre Google Sheet en CSV:

**Google Sheet:** https://docs.google.com/spreadsheets/d/14WJ0G3f5frHAuu_1nt84rzOG8_ElEVEPudZHZgd0Dnw

### Structure du CSV requis:
```
Nom,Catégorie,Stock,Image
Mojito Classique,Cocktail,10,https://...
Heineken,Bière,25,https://...
```

**Colonnes attendues:**
- **Nom**: Nom de la boisson
- **Catégorie**: Cocktail, Bière, Vin, Spiritueux, Soft
- **Stock**: Quantité disponible (0 = rupture)
- **Image**: URL de l'image (accessible en ligne)

## ✨ Fonctionnalités

✅ **Filtrage par catégorie** - Boutons interactifs  
✅ **Statut de disponibilité** - "✓ Disponible" ou "✕ Rupture"  
✅ **Design minimaliste luxe** - Fond noir, typographie élégante  
✅ **Chargement dynamique** - Données en temps réel depuis Google Sheets  
✅ **Responsive** - Adapté à tous les appareils  
✅ **Gestion des erreurs** - Images de remplacement  

## 🎯 Comment utiliser

1. **Modifiez votre Google Sheet** avec vos boissons et stock
2. **Cliquez sur les filtres** pour naviguer par catégorie
3. **La page se met à jour automatiquement!** 🔄

## 🛠️ Technologies

- HTML5
- CSS3
- JavaScript vanilla
- Google Sheets (CSV export)

## 📝 Notes

- Les boissons avec **stock = 0** affichent "✕ Rupture"
- Les images doivent être accessibles publiquement
- La mise à jour du Google Sheet se reflète automatiquement sur le site

---

**Créé avec ❤️ pour Bar Anne-Simon**
