# ha-store

Everything I maintain for Home Assistant, in one list.

HACS has no notion of a repository of repositories: one repo is one integration, and there's no "store of stores" to install. So this is the next best thing. Each link below adds that repo to HACS as a custom repository in one click, through [My Home Assistant](https://my.home-assistant.io/). Add the ones you want, then download them from the HACS panel as usual.

## Integrations

| | What it does | |
|---|---|---|
| **[Access Control (RBAC)](https://github.com/FezVrasta/ha-rbac)** | Role-based access control. Guests see the lights, kids get their own dashboard, nobody sees where your phone is. | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=ha-rbac&category=integration) |
| **[Growatt Datalogger](https://github.com/FezVrasta/growatt-datalogger)** | Local replacement for the Growatt cloud server. Integration plus a standalone library. | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=growatt-datalogger&category=integration) |
| **[C.A.F.E.](https://github.com/FezVrasta/cafe-hass)** | The "third way" for Home Assistant automations. | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=cafe-hass&category=integration) |
| **[Ducted HVAC](https://github.com/FezVrasta/ducted-hvac)** | Zoned ducted HVAC, one climate entity per zone. | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=ducted-hvac&category=integration) |
| **[ISEO Argo BLE](https://github.com/FezVrasta/iseo-argo-ble)** | ISEO Argo Bluetooth smart locks, local only. | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=iseo-argo-ble&category=integration) |
| **[Nespresso Smart](https://github.com/FezVrasta/ha-nespresso-smart)** | Local Bluetooth control of Nespresso Vertuo machines (Pop, Pop+, Next, Lattissima, Creatista). Unofficial. | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=ha-nespresso-smart&category=integration) |
| **[Trakt Scrobbler](https://github.com/FezVrasta/ha-trakt-scrobbler)** | Scrobbles your media players to Trakt. Works out the exact episode from the player's thumbnail, so it handles the Apple TV. | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=ha-trakt-scrobbler&category=integration) |
| **[AI Subscription Assist](https://github.com/FezVrasta/ai-subscription-assist)** | Use a Claude subscription as a conversation agent and a speech-to-text engine. No API key. | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=ai-subscription-assist&category=integration) |
| **[UnipolSai Unibox](https://github.com/FezVrasta/ha-unipolsai)** | The Unipol Unibox telematics box: car position, trips, battery. | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=ha-unipolsai&category=integration) |
| **[Enable Banking](https://github.com/FezVrasta/ha-enablebanking)** | PSD2 bank balances. Fork with security, privacy and correctness fixes, plus a test suite. | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=ha-enablebanking&category=integration) |
| **[EON Energia Italia](https://github.com/FezVrasta/eon-energia-italia-hass)** | Electricity consumption from EON Energia (Italy). | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=eon-energia-italia-hass&category=integration) |

## Cards

| | What it does | |
|---|---|---|
| **[M3 Cards](https://github.com/FezVrasta/m3-cards)** | 38 Material 3 cards, built natively with Lit. No button-card, no card-mod. | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=m3-cards&category=plugin) |
| **[Quick Popup](https://github.com/FezVrasta/ha-quick-popup)** | Popups and bottom sheets for dashboards. The browser_mod.popup feature, frontend only. | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=ha-quick-popup&category=plugin) |
| **[Glass Thermostat Card](https://github.com/FezVrasta/glass-thermostat-card)** | Liquid glass thermostat. | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=glass-thermostat-card&category=plugin) |
| **[Swipe Card Lite](https://github.com/FezVrasta/swipe-card-lite)** | Lightweight swipe carousel. | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=swipe-card-lite&category=plugin) |
| **[Pull Down Card](https://github.com/FezVrasta/pull-down-card)** | iOS-style pull-down drawer. | [Add to HACS](https://my.home-assistant.io/redirect/hacs_repository/?owner=FezVrasta&repository=pull-down-card&category=plugin) |

## Adding one by hand

If the My Home Assistant links don't work for you: HACS panel, three dots top right, **Custom repositories**, paste the GitHub URL, pick **Integration** or **Dashboard** as the category.

## repositories.json

The same list in machine-readable form, if you want to script it:

```bash
curl -s https://raw.githubusercontent.com/FezVrasta/ha-store/main/repositories.json
```
