---
layout: app
app: couloir
lang: en
alt: /couloir/
permalink: /en/couloir/
---

## The rules in one minute

<div class="rules-grid" markdown="0">
  <div class="rule-card">
    <span class="rule-number">1</span>
    <h3>The goal</h3>
    <p>Each player starts in the middle of their edge of a 9 × 9 board. The first to reach any square of the opposite edge wins.</p>
  </div>
  <div class="rule-card">
    <span class="rule-number">2</span>
    <h3>On your turn</h3>
    <p>One action only: move your pawn one square (forward, backward, left or right), <em>or</em> place a wall.</p>
  </div>
  <div class="rule-card">
    <span class="rule-number">3</span>
    <h3>Walls</h3>
    <p>Each player has 10 walls, two squares long. They go between squares to lengthen your opponent's path, and can't overlap or cross.</p>
  </div>
  <div class="rule-card">
    <span class="rule-number">4</span>
    <h3>Jumping</h3>
    <p>Face to face, you jump over the other pawn. If a wall or the edge blocks that jump, you move diagonally beside it instead.</p>
  </div>
  <div class="rule-card rule-card-gold">
    <span class="rule-number">★</span>
    <h3>The golden rule</h3>
    <p>Never trap a player: there must always be at least one path to their goal. Couloir checks every wall for you.</p>
  </div>
</div>

## Six ways to play

- **Versus Computer** — free. Four levels, from Easy to Expert: the Expert thinks many moves ahead.
- **Head to Head** — two players on the same iPhone, iPad or Mac. Tabletop mode turns your opponent's panel to face them.
- **Online** — anywhere, over Wi‑Fi or 4G/5G. One player creates an 8‑digit code valid for 2 minutes, the other enters it.
- **Ranked Game** — opponents from around the world, at your level, and medals to earn.
- **Nearby** — each on their own device, over Wi‑Fi or Bluetooth, with no internet or account.
- **SharePlay** — during a FaceTime call, even on the other side of the world.

Playing the computer and joining a nearby game are free. Everything else in two-player mode is unlocked with a **one-time purchase**, shared with your family.

## Ranked medals

Every player has a **rating**, computed like the chess Elo rating: it starts at 1,000 points, beating a stronger player earns a lot, losing to a weaker one costs a lot. Your rating gives you your medal:

<div class="medal-grid" markdown="0">
  <div class="medal medal-bronze"><span class="medal-coin" aria-hidden="true"></span><strong>Bronze</strong><span>starting medal</span></div>
  <div class="medal medal-silver"><span class="medal-coin" aria-hidden="true"></span><strong>Silver</strong><span>from 1,100 points</span></div>
  <div class="medal medal-gold"><span class="medal-coin" aria-hidden="true"></span><strong>Gold</strong><span>from 1,300 points</span></div>
  <div class="medal medal-platinum"><span class="medal-coin" aria-hidden="true"></span><strong>Platinum</strong><span>from 1,500 points</span></div>
  <div class="medal medal-diamond"><span class="medal-coin" aria-hidden="true"></span><strong>Diamond</strong><span>from 1,700 points</span></div>
  <div class="medal medal-master"><span class="medal-coin" aria-hidden="true"></span><strong>Master</strong><span>from 1,900 points</span></div>
  <div class="medal medal-grandmaster"><span class="medal-coin" aria-hidden="true"></span><strong>Grandmaster</strong><span>from 2,100 points</span></div>
</div>

Matchmaking first looks for an opponent with your medal, then neighboring medals after 20 seconds, then all players. Leaving a ranked game in progress counts as a loss. Your rating is saved in Game Center: you'll find it on all your devices, along with the world leaderboard.

## Built in Swift, for Apple devices

Couloir is a native app written entirely in **Swift 6** and **SwiftUI**, with no game engine or third-party library. A single project builds the app for iPhone, iPad and Mac, with an interface that adapts to every screen, from the smallest iPhone to a large Mac display.

<div class="tech-grid" markdown="0">
  <div class="tech"><strong>SwiftUI &amp; Observation</strong><span>Interface, animations, light and dark themes, Dynamic Type and VoiceOver.</span></div>
  <div class="tech"><strong>Custom game engine</strong><span>64-bit bitboards and pathfinding (BFS) in under a microsecond.</span></div>
  <div class="tech"><strong>Artificial intelligence</strong><span>Negamax alpha-beta search with iterative deepening, computed off the main thread.</span></div>
  <div class="tech"><strong>MultipeerConnectivity</strong><span>Nearby games over Wi‑Fi or Bluetooth, with no server.</span></div>
  <div class="tech"><strong>GroupActivities</strong><span>SharePlay during FaceTime calls.</span></div>
  <div class="tech"><strong>GameKit</strong><span>Online games with a code, medal-based ranked matchmaking, Game Center leaderboards and achievements — with no server at all.</span></div>
  <div class="tech"><strong>StoreKit 2</strong><span>One-time in-app purchase, restore and Family Sharing.</span></div>
  <div class="tech"><strong>WidgetKit &amp; ActivityKit</strong><span>Widgets and a Live Activity on the Lock Screen and in the Dynamic Island.</span></div>
</div>

No ads, no tracking, no data collection: [privacy policy]({{ '/en/couloir/privacy/' | relative_url }}). A question? Visit the [support page]({{ '/en/couloir/support/' | relative_url }}).
