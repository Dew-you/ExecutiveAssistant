# Holy Trinity

The three brands below are **always connected**. They are run as one system — content, commerce, and community feed each other, and each one is built to generate income for the group. Wherever one brand acts, the other two are considered.

> **Canonical direction (always true):** Everything forwards to **`allnaturalextract.com`** (the Shopify store). **WordPress is disconnected and no longer used.** **`naturalextract.net` is email-only** (e.g. dew@ / support@naturalextract.net) and forwards to allnaturalextract.com — nothing else comes from the `.net` domain. "The site"/"the store" = allnaturalextract.com (Shopify).

## The Mission

**Own the menopause decade-and-a-half.** Our niche is the **20 years between ages 40 and 60** — for **both men and women**.

- Every man has a woman in his life in some way, and every woman will go through this stage. So these are **our business years**.
- We serve this window three ways:
  1. **Education** — teaching people what is happening to their bodies and lives in these years.
  2. **Medication** — natural products and remedies to get through it.
  3. **Art / artful ways of enduring** — content, story, and community that make the years livable, not just survivable.
- We bring in **experts** to speak to these 20 years, and we feature **young and old** voices to reach **all groups**.

That is the mission: dominate this niche across the full 40–60 span.

## The Three Brands

All three brands consolidate to the single web home **allnaturalextract.com (Shopify)**. The old WordPress sites are disconnected; the brands live on as personas + YouTube/social + Shopify.

| Brand | Web home | Persona | Role in the Trinity |
|---|---|---|---|
| **Natural Extracts** | allnaturalextract.com (Shopify) | — | Commerce / **Medication** (natural products & remedies) |
| **Her Natural Edge** | allnaturalextract.com (Shopify) · hernaturaledge.com WordPress *disconnected* | Valerie | **Education** (teaching the 40–60 transition) |
| **Stand In Her Corner** | allnaturalextract.com (Shopify) · standinhercorner.com WordPress *disconnected* | Jordan | Community / **Art** (story, content, endurance) |

> Pillar-to-brand mapping above is the working alignment — confirm or adjust and this file gets updated.

## Live Connection Status

Last checked: **2026-09-01** (from a Claude Code remote/cloud session, via claude.ai connectors).

### ✅ Connected & verified

| Service | Account / Detail | Serves |
|---|---|---|
| Shopify | "Natural Extract" store · allnaturalextract.com · Basic · USD/EDT | Natural Extracts (commerce) |
| Gmail | dew@naturalextract.net | All brands (support, ops) |
| Google Drive | dew@naturalextract.net | All brands (assets, video) |
| Google Calendar | dew@naturalextract.net | All brands (scheduling) |
| Blotato | dew@naturalextract.net · 4,250 credits | All brands (social scheduling) |
| VidIQ | 74 credits (0 renewable, resets Sep 21) | All brands (YouTube) |
| Autoclips | 50,880 credits · enterprise | All brands (video) |
| Figma | handle DEW · dew@naturalextract.net · Starter (View) | All brands (design) |
| Gamma | connected | All brands (decks/docs) |
| Slack | auth works (no channels matched a test search — verify workspace) | All brands (ops) |

### YouTube channels (VidIQ, authorized as dew@naturalextract.net)

| Channel | Subs | Views | Videos | Trinity brand? |
|---|---|---|---|---|
| **Stand In Her Corner** (Jordan) | 16 | 11,246 | 211 | ✅ Yes |
| **KitchenLore** (food history) | 106 | 22,626 | 169 | ❌ Separate brand |

⚠️ No YouTube channel is authorized for **Natural Extracts** or **Her Natural Edge (Valerie)** — if they exist, link them to this VidIQ account.

### Websites

Everything forwards to **allnaturalextract.com (Shopify)** — that is the only live web property to manage.

| Domain | Role | Status |
|---|---|---|
| allnaturalextract.com | Shopify store — the web home for all brands | ✅ Connected (via Shopify) |
| naturalextract.net | **Email only** (dew@/support@); forwards to allnaturalextract.com | Email-only, no site |
| hernaturaledge.com | Valerie companion app (Bolt.new) — "meet Valerie" links only; WordPress gone | ✅ App domain (managed via Bolt.new, not a connector) |
| standinhercorner.com | Jordan companion app (Bolt.new) — "meet Jordan" links only; WordPress gone | ✅ App domain (managed via Bolt.new, not a connector) |

(Direct web browsing of these domains is blocked by the remote session's egress proxy, but management of the live store runs through the Shopify connector.)

### ⚠️ Needs attention

| Service | Issue | Fix |
|---|---|---|
| Microsoft 365 | Signed in as **tech@earthweb.llc** — intentional; for SharePoint/other business functions (coming later), separate from company email | No action — company email stays Gmail on naturalextract.net |
| Stripe | Connector present but **not authorized**; OAuth **cannot be completed from a remote/cloud session** | You reconnect it in claude.ai → Settings → Connectors, then I re-verify |

> WordPress connectors are intentionally **disconnected** — not a gap to fix.

## Agents

| Agent | File | Scope |
|---|---|---|
| **Entendre** — Marketing | `.claude/agents/entendre.md` | All marketing across the three brands; hands off commerce/ops, legal, finance, engineering, personal correspondence |
| Executive Assistant | *(not yet defined)* | Don's desk: calendar, inbox, correspondence, legal/finance routing |
| Operations | *(not yet defined)* | Store ops: stock, pricing, suppliers, theme + Bolt.new app code |

## Notes / Limitations

- The **Chrome extension ("Claude in Chrome") is not available in a remote/cloud session** — it only works in a local Claude Code session connected to your own browser. All connections above run through claude.ai connectors, which is the correct path for remote work.
- To bring a currently-off service online, re-authorize it in claude.ai settings (e.g. Stripe), then re-run this check. WordPress is deliberately disconnected and should stay off.
