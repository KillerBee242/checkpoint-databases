# checkpoint-databases

**Slide 1 : Page de titre**  
**Titre** : MongoDB vs. Bases de données SQL : Choisir le bon outil  
**Sous-titre** : Une analyse comparative pour les applications modernes  
**Visuel** : Icône d'écran divisé (logo MongoDB vs. diagramme de base de données SQL)  

---

**Slide 2 : Aperçu des bases de données SQL**  
**Titre** : SQL (Bases de données relationnelles)  
**Points clés** :  
- 🗄️ **Structure** : Tables avec schémas prédéfinis (lignes/colonnes)  
- 🔗 **Relations** : Clés étrangères, jointures, conformité ACID  
- 🔍 **Langage de requête** : SQL (Structured Query Language)  
- 💡 **Cas d'utilisation** : Systèmes bancaires, ERP, applications nécessitant des transactions complexes  
- ⚙️ **Exemples** : MySQL, PostgreSQL, Oracle  

**Visuel** : Diagramme de schéma de table avec relations.  

---

**Slide 3 : Aperçu de MongoDB**  
**Titre** : MongoDB (Base de données NoSQL orientée documents)  
**Points clés** :  
- 📄 **Structure** : Documents de type JSON avec schémas dynamiques  
- 🧩 **Flexibilité** : Données imbriquées, tableaux, support des données non structurées  
- 🚀 **Évolutivité** : Mise à l'échelle horizontale via le sharding  
- 🔥 **Cas d'utilisation** : Analytique en temps réel, IoT, gestion de contenu, applications en évolution rapide  
- ⚙️ **Fonctionnalités** : Pipeline d'agrégation, requêtes géospatiales  

**Visuel** : Exemple de document JSON avec champs imbriqués.  

---

**Slide 4 : Comparaison clé**  
**Titre** : MongoDB vs. SQL : Comparaison directe  
**Tableau comparatif** :  

| **Critère**        | **SQL**                     | **MongoDB**               |  
|----------------------|-----------------------------|---------------------------|  
| **Modèle de données** | Structuré (Tables)         | Flexible (Documents)      |  
| **Schéma**           | Rigide, prédéfini           | Dynamique, évolutif       |  
| **Évolutivité**      | Mise à l'échelle verticale  | Mise à l'échelle horizontale |  
| **Transactions**     | Garanties ACID multi-enregistrements | ACID mono-document (multi-document à partir de v4.0+) |  
| **Langage de requête** | SQL                         | Langage de requête MongoDB |  
| **Idéal pour**       | Jointures/transactions complexes | Données à haute vélocité/volume |  

**Visuel** : Graphique de balance des avantages/inconvénients.  

---

**Slide 5 : Quand choisir quoi ?**  
**Titre** : Guide de décision  
**Recommandations** :  
- ✅ **Choisissez SQL si** :  
  - Vos données sont hautement structurées  
  - Les transactions complexes sont critiques  
  - Vous avez besoin d'une intégrité stricte des données (ex. applications financières)  

- ✅ **Choisissez MongoDB si** :  
  - Votre schéma de données évolue fréquemment  
  - Vous avez besoin d'une mise à l'échelle horizontale  
  - Vous travaillez avec des données hiérarchiques/JSON (ex. réseaux sociaux, catalogues)  

**Visuel** : Organigramme de décision (Données structurées ? → SQL / Données non structurées et évolutives ? → MongoDB)  

---

**Astuce bonus** :  
Les solutions modernes utilisent souvent les deux !  
**Exemple** : SQL pour les données transactionnelles + MongoDB pour les logs d'activité utilisateur.  

**Visuel de clôture** : Icône Yin-Yang mélangeant les logos SQL/NoSQL.
