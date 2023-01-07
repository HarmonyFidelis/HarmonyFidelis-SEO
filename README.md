# HarmonyFidelis-SEO

## <ins>Qu'est ce que le référencment SEO / référencement naturel ?</ins>

```texte
Le référencement est l'action de référencer, c'est-à-dire mentionner quelque chose ou y faire référence.
Dans me domaine du web cela consiste donc à se rendre le plus visible possible via des sites qui on déja une grande visibilité.

Exemple :

- Google [Moteur de recherche USA]
- Baidu [Moteur de recherche CHINESE]
- Yandex [Moteur de recherche RUSSIA]
- Youtube [Plateforme de diffusion]
- Facebook [Social Media]
- Twitter [Social Media]
- Instagram [Social Media]
- Wikipedia [Encyclopédie]
- Amazon [E-Commerce]
- Aliexpress [E-Commerce]
- Prestashop [E-Commerce]
```

## TABLES DES MATIERES

---
<a id="referencmentSEO"></a><details><summary>Table des matieres</summary>

- [SEO : Comment optimisé référencement SEO / référencement naturel ?](#referencmentSEO)
- [SEO : Existe t-il des outils pour le référence SEO / référencement naturel ?](#toolSEO)
- [Google : Comment étre référencer sur Google ?](#googleSEO)
  - [Google : Google - Exploration, Indexation et Diffusion](#googleFonctionnement)
  - [Google : Google - Exigences techniques](#googleTechnique)
  - [Google : Google - Règles générale, Bonnes et Mauvaise Pratique](#googleRegles)

</details>

---

## SEO

---
<a id="referencmentSEO"></a><details><summary>Comment optimisé référencement SEO / référencement naturel ?
</summary>

### <ins>Comment optimisé référencement SEO / référencement naturel ?

```texte
Il y a pas de secret pour cela il faut regardez les différents outils et critéres que ces derniers proposent.
En effet, il existe des outils pour les développeurs ou le référenceurs pour optimisé leurs référencement.

Exemple :

- Google [GoogleSearchConsole, GoogleTagManager, GoogleAnalytics, ...]
- Baidu [Licence, Reglementation, OnePage, ...]
- YouTube [Keywords, Backlinks, ...]
- Facebook [OpenGraph, Backlinks, ...]
```

</details>

---

<a id="referencmentSEO"></a><details><summary>Existe t-il des outils pour le référence SEO / référencement naturel ?</summary>

### <ins>Existe t-il des outils pour le référence SEO / référencement naturel ?

```texte
En plus, des outils fournis par chaque site référenceur. Il existe des outils de suivis et d'analyse de site qui vous permetront d'optimiser votre référence.

GENERAL
- Semrush
- Hootsuite

GOOGLE 
- GoogleInspectionTool 
```

</details>

---

## GOOGLE

<a id="googleSEO" style="text-align: center;"></a><details><summary>Google - Comment étre référencer sur Google ?
</summary>

### <ins>Google - Comment étre référencer sur Google ?

```texte
Google est  le site le plus visité au monde, il doit son nombre de visiteur à la qualité des robots, données renvoyer à l'utilisateur et ces services(GoogleSearch, GoogleMaps, GoogleLens, GoogleEmploi, GoogleTravel, ...)

Pour optimiser notre référencement sur Google il faut suivre des directives et utilisé un certain nombre de services(GoogleTagManager, GoogleSearchConsole, ...).

Directives : https://developers.google.com/search/docs?hl=fr
```

---

<a id="googleFonctionnement"></a>

### <ins>Google - Exploration, Indexation et Diffusion

```texte
Google fonctionne en fesant appel à des robots qui va explorer régulierement le web et rechercher des pages à indexer.

L'exploration : Google télécharge des textes, des images et différent type de contenu par le biais de robot
l'indexation : Google Analyse les textes et les autres contenus puis les stockent.
Diffusion : Lorsque qu'un internaute fait une recherche sur le site google, il affiche les resultats les plus pertinent.
Pour voir site des pages du nom de domaine soit référencer site:wikipedia.org
```

---

<a id="googleTechnique"></a>

### <ins>Google - Exigences techniques

```texte
Les exigences techniques couvrent l'ensemble des pré-requis pour que notre page apparaise ou non sur Google.

INDEXABLE
- Le contenu doit être publique.
- Le contenu ne doit pas nécessité une connection. ( un robot ne se connecte pas )
- Le contenu ne doit pas avoir du contenu en double. ( un robot n'aime pas les plagiats)
- Le contenu doit etre utile, cela ne sert à rien d'écrire des phrases vide de sens dans le but de garnir l'article.
- Il doit etre un fichier indexable (voir la liste ci-dessous)
NON-INDEXABLE
- Le contenu inutile doit etre supprimer.
- Le données sensible doivent être privé, mis dans un repertoire sur le serveur avec mot de passe et ne doit pas être indexer. (nom, prenom, adresse, n°, ...)
- Bloquer l'indexation des images peut importante.
```

Pour ne pas indexer une page dans le head de cette page utiliser la balise meta

```code
<head>
  <meta name="robots" content="noindex">
</head>
```

Pour ne pas indexer des images créer un fichier robot.txt à la racine.

```robots.txt
User-agent: Googlebot-Image

<!-- N'indexe pas les images suivante -->
Disallow: /images/monimage1.jpg
Disallow: /images/monimage2.jpg

<!-- N'indexe pas les images ayant pour prefix model_picture_ et suffix .jpg -->
Disallow: /images/model_picture_*.jpg

<!-- N'indexe pas les images ayant pour extension .gif -->
Disallow: /images/*.gif$ 
```

Liste des extension de fichier pouvant faire l'objet d'une indexation

```text
  - Adobe Portable Document Format (.pdf)
  - Adobe PostScript (.ps)
  - Google Earth (.kml, .kmz)
  - GPS eXchange Format (.gpx)
  - Hancom Hanword (.hwp)
  - HTML (.htm, .html, autres extensions de fichier)
  - Microsoft Excel (.xls, .xlsx)
  - Microsoft PowerPoint (.ppt, .pptx)
  - Microsoft Word (.doc, .docx)
  - Présentation OpenOffice (.odp)
  - Feuille de calcul OpenOffice (.ods)
  - Texte OpenOffice (.odt)
  - Texte mis en forme (.rtf)
  - Scalable Vector Graphics (.svg)
  - TeX/LaTeX (.tex)
  - Texte (.txt, .text et autres extensions de fichiers), y compris le code source dans les langages de programmation courants :
  - Code source Basic (.bas)
  - Code source C/C++ (.c, .cc, .cpp, .cxx, .h, .hpp)
  - Code source C# (.cs)
  - Code source Java (.java)
  - Code source Perl (.pl)
  - Code source Python (.py)
  - Wireless Markup Language (.wml, .wap)
  - XML (.xml)
```

</details>

---

<a id="googleSEO" style="text-align: center;"></a><details><summary>Google - Règles générale, Bonnes et Mauvaise Pratique !
</summary>

<a id="googleRegles"></a>

### <ins>Google - Règles générale, Bonnes et Mauvaise Pratique

##### Règles générale

<https://support.google.com/websearch/answer/10622781?hl=fr>

##### Mauvaise Pratique

- Techniques de dissimulation (cloaking)
  - Consiste à présenter au robot une page différente de celle présenté à utilisateur.
- Satellites
  - Consiste à créer des pages contenant des recherche spécifique et qui renvois vers une page de destination finale.
- Contenu piraté
  - Un contenu piraté désigne tout contenu placé sans autorisation sur un site qui présente des failles de sécurité.
    - Injection de code : Personne mettant du code non autorisé directement dans le site ou dans des iframes
    - Injection de page : Personne ajoutant des spams sur une page
    - Injection de contenu : Personne ajoutant du liens ou texte cachè
    - Redirection : Personne voulant rediger les internaute vers une autre page.
- Texte et liens cachés
  - Dissimulation de contenu dans le seul but de manipuler les robots, mais invisible à l'oeil.
    - Texte blanc sur fond blanc
    - Texte caché derrière une image
    - Code CSS utilisé pour positionner du texte en dehors de l'écran
    - Taille de police ou opacité définie sur 0
    - Lien appliqué à un seul caractère de petite taille
    - Certain sont autorisé comme Accordéon, Diaporama, Info-bulle, Texte accessible uniquement aux lecteurs d'écran.
- Accumulation de mots clés
  - Consiste à remplir la page de mot clès hors contexte ou trop souvent répété.
- Liens toxiques
  - Liens achetés ou vendus à des fins de classement.
  - Échanges de liens de manière excessive
  - Utilisation de programmes pour créer des liens vers votre site
  - Lien imposé dans le cadre de conditions
  - Liens textuels
  - Publireportages : rémunération est perçue contre des articles contenant des liens produit
  - Liens vers des annuaires
  - Liens riches en mots clés
  - Liens largement distribués dans le footer ou header
  - Commentaires sur les forums incluant des liens
  - Pour tout les liens commercial utilisé la balise
    - `<a rel="sponsored" href="VOTRE_URL">Keyword</a>`
- Trafic généré automatiquement
  - BOT  
- Logiciels et Fonctionnalités trompeuses
  - Logiciel Malveillant
  - Fonctionnalité visant à faire croire au personne, qui est en réalité fausse
- Contenu détourné
  - Utilisation de mot cléf de site réputé.
- Contenu généré automatiquement
  - Mot cléf
  - traduction sans verification
  - Texte
  - Scraping
  - Assemblage ou combinaison de contenus issus de différentes pages Web
- Pages de site affilié sans valeur ajoutée
  - Site partangant la même structure avec un contenue casiment identique ou légement modifié
- Spam généré par l'utilisateur
- Suppression de contenu pour des raisons juridiques
- Suppression abusive d'informations personnelles
- Escroqueries et fraudes

### Google - Bonnes pratiques

Les bonnes pratiques sont la pour amélioré  le référence du site et des services proposaient.

- Création de contenu
  - Créer des données utiles
  - Exhaustive
  - Reformulé si c'est un ensemble d'information pris aillieur
  - Clair, l'utilisateur doit comprendre rapidement ou il arrive
  - Créer du contenue qui créer la confiance chez l'utilisateur
  - Sans faute
  - Responsive
- Créer des titres de page uniques et précis
  - `<head><title>Brandon's Baseball Cards - Buy Cards, Baseball News, Card Prices</title></head>`
  - courts, mais descriptifs
- Utiliser la balise meta description
  - `<head><meta name="description" content="Brandon's Baseball Cards provides a large selection of vintage and modern baseball cards for sale."></head>`
  - Utilisé des phrases plutot que de simple mot cléf
  - Clair et en rapport avec la page
- Utilisez des titres structuré, clair et court dans votre contenue
  - <h1>Votre titre</h1> [Trés Important][Unique]
  - <h2>Votre titre</h2> [Important]
  - <h3>Votre titre</h3> [Peut important]
  - <em>Italique</em> [Mot important]
  - <strong>Gras</strong> [Mot important]
- Utilisez les balises structurés
  - Les balises structurés permette d'enrichir le resulstat de recherche avec des avis, prix, horaire, lieu, etc.
  - Liste des structure : <https://developers.google.com/search/docs/appearance/structured-data/search-gallery>
  - Permet de tester votre code: <https://search.google.com/test/rich-results>
  - GoogleSearchConsole:
    - Générer graçe à l'outil google <https://www.google.com/webmasters/data-highlighter/sources?hl=fr>
    - Statistique sur les données structurés <https://support.google.com/webmasters/answer/7552505?hl=fr>
- Organiser l'arborescence/URL de votre site
  - <https://www.example.com/RunningShoes/Womens.htm?size=8#info>
  - Lorsque vous ajoutez votre site Web à la Search Console, nous vous recommandons d'ajouter à la fois les versions http:// et https://, ainsi que les versions avec et sans "www".
  - <https://lh3.googleusercontent.com/FkXf1NMLRBDRD0-82WWHYCu7_nHxCzkUaMDFDAuGiFRYIrtgO3wqSJdtSFhpnyu3yeE=w314>
  - Utiliser un fil d'ariane
  - Créez un fichier sitemap XML
  - Créer une page 404 qui permet la redirecction vers l'accueil ou autre page du site
  - L'url doit être le plus descriptif et court possible `https://www.brandonsbaseballcards.com/article/ten-rarest-baseball-cards.html`
  - ne pas créer plusieurs url qui renvois vers la même page
- Optimiser votre contenu
  - Le contenu de qualité et le facteur le plus important pour le référencemet
  - La répetutation par le bouche à oreille, newsletter ou mediasocial conribue à cela
  - Commprendre ce que veut votre audience à l'aide des mot clef
    - Rapport et statistique  <https://support.google.com/webmasters/answer/7576553?hl=fr>
    - Server vous de google KeywordsPlanner et GoogleTrend pour comprendre ce que les internaute recherche
- Identité & Confiance
  - Ajouter votre etablissement à google business <https://www.google.com/business/?hl=fr>
  - Mettre des publicité de maniere qu'elle ne gêne pas la navigation
- Utilisez les liens judicieusement
  - <a rel="sponsored" href="VOTRE_URL">Keyword</a>
  - descriptif, cour et clair en rapport avec le contenu
  - différencier le liens du texte
  - Utilisé l'encrage pour aidé à la navigation
  - <a href="https://www.example.com" rel="nofollow">Site à ne pas suivre ou à associez à votre page</a>
  - Si une personne ajoute un lien dans un commentaire mettre nofollow à ces lien
- Optimiser vos images
  - Utiliser les éléments HTML <img> ou <picture>
  - Utilisez loading="lazy" pour optimisez le chargement des pages
  - Utilisez alt pour fournir une description décrivant cette image
  - Utilisez un nom cour de fichier décrivant l'image
  - SiteMap pour vos images
  - Utiliser les formats d'image JPEG, GIF, PNG, BMP et WebP(le plus optimisé)
- Faire un site responsive
  - <https://web.dev/learn/design/>
  - Diffusion dynamique du code en fonction du user-agent
  - Url distincte
  - Utilisé meta name="viewport"
  - contenu identique
  - Tool mobile google <https://search.google.com/test/mobile-friendly?hl=fr>
- Social media
  - Evitez de promouvoir tout vos contenus
  - N'acheter pas des liens
  <details>
