---
layout: app
app: couloir
lang: fr
alt: /en/couloir/
permalink: /couloir/
---

## Les règles en une minute

<div class="rules-grid" markdown="0">
  <div class="rule-card">
    <span class="rule-number">1</span>
    <h3>Le but</h3>
    <p>Chaque joueur part du milieu de son bord d'un plateau de 9 × 9 cases. Le premier qui atteint n'importe quelle case du bord opposé gagne.</p>
  </div>
  <div class="rule-card">
    <span class="rule-number">2</span>
    <h3>À votre tour</h3>
    <p>Une seule action : avancer votre pion d'une case (en avant, en arrière, à gauche ou à droite), <em>ou</em> poser un mur.</p>
  </div>
  <div class="rule-card">
    <span class="rule-number">3</span>
    <h3>Les murs</h3>
    <p>Chacun dispose de 10 murs, longs de deux cases. Ils se posent entre les cases pour rallonger le chemin adverse, sans se chevaucher ni se croiser.</p>
  </div>
  <div class="rule-card">
    <span class="rule-number">4</span>
    <h3>Le saut</h3>
    <p>Face à face, vous sautez par-dessus le pion adverse. Si un mur ou le bord bloque ce saut, vous passez en diagonale, à côté de lui.</p>
  </div>
  <div class="rule-card rule-card-gold">
    <span class="rule-number">★</span>
    <h3>La règle d'or</h3>
    <p>Interdit d'enfermer un joueur : il doit toujours lui rester au moins un chemin vers son arrivée. Couloir vérifie chaque mur pour vous.</p>
  </div>
</div>

## Six façons de jouer

- **Contre l'ordinateur** — gratuit. Quatre niveaux, de Facile à Expert : l'Expert calcule de nombreux coups à l'avance.
- **Face à face** — à deux sur le même iPhone, iPad ou Mac. Le mode table retourne le panneau de votre adversaire vers lui.
- **En ligne** — partout, en Wi‑Fi ou en 4G/5G. L'un crée un code à 8 chiffres valable 2 minutes, l'autre le saisit.
- **Partie classée** — des adversaires du monde entier, à votre niveau, et des médailles à gagner.
- **À proximité** — chacun sur son appareil, en Wi‑Fi ou en Bluetooth, sans internet ni compte.
- **SharePlay** — pendant un appel FaceTime, même à l'autre bout du monde.

Le jeu contre l'ordinateur et le fait de rejoindre une partie à proximité sont gratuits. Tout le reste du jeu à deux se débloque par un **achat unique de 2,99 €**, partagé avec votre famille.

## Les médailles des parties classées

Chaque joueur a une **cote**, calculée comme le classement Elo des échecs : elle part de 1 000 points, une victoire contre plus fort que soi rapporte beaucoup, une défaite contre plus faible coûte cher. La cote donne votre médaille :

<div class="medal-grid" markdown="0">
  <div class="medal medal-bronze"><span class="medal-coin" aria-hidden="true"></span><strong>Bronze</strong><span>départ</span></div>
  <div class="medal medal-silver"><span class="medal-coin" aria-hidden="true"></span><strong>Argent</strong><span>dès 1 100 points</span></div>
  <div class="medal medal-gold"><span class="medal-coin" aria-hidden="true"></span><strong>Or</strong><span>dès 1 300 points</span></div>
  <div class="medal medal-platinum"><span class="medal-coin" aria-hidden="true"></span><strong>Platine</strong><span>dès 1 500 points</span></div>
  <div class="medal medal-diamond"><span class="medal-coin" aria-hidden="true"></span><strong>Diamant</strong><span>dès 1 700 points</span></div>
  <div class="medal medal-master"><span class="medal-coin" aria-hidden="true"></span><strong>Maître</strong><span>dès 1 900 points</span></div>
  <div class="medal medal-grandmaster"><span class="medal-coin" aria-hidden="true"></span><strong>Grand maître</strong><span>dès 2 100 points</span></div>
</div>

Le matchmaking cherche d'abord un adversaire de votre médaille, puis des médailles voisines après 20 secondes, puis tous les joueurs. Quitter une partie classée en cours compte comme une défaite. Votre cote est enregistrée dans Game Center : vous la retrouvez sur tous vos appareils, avec le classement mondial.

## Développé en Swift, pour les appareils Apple

Couloir est une app native, écrite entièrement en **Swift 6** et **SwiftUI**, sans moteur de jeu ni bibliothèque tierce. Un seul projet produit l'app pour l'iPhone, l'iPad et le Mac, avec une interface qui s'adapte à chaque écran, du plus petit iPhone au grand écran du Mac.

<div class="tech-grid" markdown="0">
  <div class="tech"><strong>SwiftUI &amp; Observation</strong><span>Interface, animations, thèmes clairs et sombres, réduction des animations.</span></div>
  <div class="tech"><strong>Moteur de jeu maison</strong><span>Plateau en « bitboards » 64 bits et recherche de chemin (BFS) en moins d'une microseconde.</span></div>
  <div class="tech"><strong>Intelligence artificielle</strong><span>Recherche negamax alpha-bêta à approfondissement itératif, calculée hors du fil principal.</span></div>
  <div class="tech"><strong>MultipeerConnectivity</strong><span>Parties à proximité en Wi‑Fi ou Bluetooth, sans serveur.</span></div>
  <div class="tech"><strong>GroupActivities</strong><span>SharePlay pendant les appels FaceTime.</span></div>
  <div class="tech"><strong>GameKit</strong><span>Parties en ligne avec un code, matchmaking classé par médailles, classements et succès Game Center — sans aucun serveur.</span></div>
  <div class="tech"><strong>StoreKit 2</strong><span>Achat intégré unique, restauration et Partage familial.</span></div>
  <div class="tech"><strong>WidgetKit &amp; ActivityKit</strong><span>Widgets, activité en direct sur l'écran verrouillé et dans la Dynamic Island.</span></div>
</div>

Sans publicité, sans pistage, sans collecte de données : [politique de confidentialité]({{ '/couloir/privacy/' | relative_url }}). Une question ? Rendez-vous sur la page d'[assistance]({{ '/couloir/support/' | relative_url }}).
