# 🌿 Against the Wild

> *Survival the way it was always meant to feel — real.*

**Against the Wild** is an immersive realism mod that transforms Minecraft survival into something that actually feels like fighting to stay alive. No magic shortcuts, no easy starts. The world is harsh, unforgiving, and beautiful — just like the real wilderness.

This mod is currently in **early ALPHA**. The foundation is here, but this is only the beginning.

---

## ⚠️ ALPHA WARNING

This mod is in active development. Expect rough edges, missing content and frequent updates. Features will be added, tweaked and expanded over time. **Your feedback shapes what this becomes.**

---

## 🌱 What's in the Alpha?

### 🌾 A Living Forest Floor

The world feels inhabited even before you arrive. Freshly explored chunks are scattered with:

- **Sticks** — fallen branches lying on the ground
- **Small Rocks** — loose pebbles on the dirt
- **Rocks** — heavier stones, more common near rivers and lakes
- **Flint** — rare sharp stones with only a **5% chance** to appear per chunk

Just **right-click** to pick them up. No mining, no breaking — you find them, you take them.

Ground items spawn differently depending on the environment:

- **Near water** — rocks and flint are more common along riverbanks and shorelines
- **Underwater** — small rocks, rocks and flint accumulate on riverbeds and lakebeds
- **In caves** — rocks and flint appear on cave floors, because that's where loose stone collects

---

### 🌿 Plant Fiber

Breaking **tall grass** or **short grass** has a **60% chance** to drop 1–2 **Plant Fiber**.

This is the first step toward crafting primitive tools and binding materials.

Combine plant fiber to craft **Primitive Rope** — the binding that holds your first weapons together.

---

### 🪨 Knapping — Stone Age Crafting

You can't just craft a knife with a crafting table and a dream. You need to work the stone first.

**Step 1 — Knap the flint:**
Place a **Flint** and a **Rock** anywhere in the crafting grid.
→ Yields **2× Flint Shard**. The Rock is **not consumed** — it acts as your hammerstone.

**Step 2 — Shape the edge:**
Place a **Flint Shard** and a **Rock** in the crafting grid.
→ Yields **1× Sharp Flint**. The Rock is **not consumed**.

This reflects how early humans actually made tools — striking one stone against another to shape a cutting edge.

---

### 🔪 Primitive Knife

Craft your first real weapon from what the land gives you.

**Recipe**:
```
[ Sharp Flint   ]
[ Stick         ]
[ Primitive Rope ]
```

**Stats:**
- **Attack Damage:** 4.5 *(weaker than a stone sword, but that's the point)*
- **Attack Speed:** faster than a sword *(a short knife swings quicker than a long blade)*
- **Durability:** 50 uses *(flint is sharp — but it chips and breaks)*

This is a tool of necessity, not power. Use it until you can make something better.

---

### 🏹 Primitive Spear

Your first ranged weapon. Longer reach, heavier swing — and you can throw it.

**Recipe**:
```
[ Sharp Flint   ]
[ Stick         ]
[ Stick         ]
[ Primitive Rope ]
```

**Stats:**
- **Attack Damage:** 6.0 *(hits harder than the knife, but swings slower)*
- **Attack Speed:** slower than a sword *(a spear needs room to swing)*
- **Durability:** 80 uses

**Throwing:**

Hold right-click to wind up the throw. The longer you hold, the faster it flies. Release to throw. A fully charged throw deals **7.5 damage** — more than a melee strike, because momentum matters. The spear will stick into whatever it hits — a block, a tree, an enemy. Walk up and right-click to retrieve it. The spear keeps its durability state when picked up, so don't throw a broken one.

---

### 🪓 Your Bare Hands Are Not a Tool

You cannot break **any wooden block** with your bare hands.

No more punching trees on day one. You need a proper tool — or you're not getting that wood.

- Breaking speed drops to nearly zero without a tool
- Attempting to break wood barehanded is **fully blocked** — no drops, no progress

This applies to every wood type in the game.

---

## 🎯 The Vision

**Against the Wild** is being built toward a full realistic survival overhaul. The goal is a Minecraft experience where every decision matters, every resource has weight, and the wilderness actually feels dangerous and alive.

Think real hunger. Real exhaustion. Real consequences. A world where a stick on the ground isn't just decoration — it's a resource you'll be glad you found.

This is just the first step.

---

## ⚙️ Technical Info

- **Minecraft 1.21.1** — Forge
- Ground items are persistent world entities, not random drops
- Spawning happens once per chunk, on first exploration only
- Spawn rates vary by biome type: surface, underwater, and underground each have their own logic
- Knapping recipes use a custom recipe type — the Rock is returned to your inventory after crafting
- Thrown spear is a persistent world entity — it sticks into blocks and can be retrieved by right-clicking
- Spear throw removes the item from inventory and returns it on pickup with correct durability
- Server-side logic, client-side rendering

---

## 🐛 Feedback & Bugs

This is Alpha — bugs are expected. Report them in the comments or on GitHub and help shape the direction of the mod.

---

Made with ❤️ by ZappyQ

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/Z8Z51UE2EQ)
