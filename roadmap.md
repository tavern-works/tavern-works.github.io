---
title: Roadmap
order: 2
---

# Outline

- [Product Tiers](#product-tiers)

  - [Local](#local)
  - [Legacy](#legacy)
  - [Live](#live)

- [Development Roadmap](#development-roadmap)

- [Financial Transparency](#financial-transparency)
  - [Actual Costs](#actual-costs)
  - [Developer Support](#developer-support)

# Product Tiers

The ultimate goal of this project is to produce three tiers of the Tavern virtual tabletop (VTT):

## Local

**Price**: **_Free_** (donations accepted)

The **Local** tier will give you access to all of the VTT features: map editing, Tavern's unique dynamic lighting engine, system integrations, etc. The only limitation is that all of the data is stored in your browser, which means you can't easily sync it between computers, and it's possible that the data could be lost if you clear your browser storage.

## Legacy

**Price**: [Actual Costs](#actual-costs) + no more than $2/month of [Developer Support](#developer-support)

The **Legacy** tier will provide everything **Local** provides, but with the addition of syncing of your games so you can move them between computers and not worry about losing anything between sessions. The exact number of games per user and the amount of asset storage space is still to be determined, but each user will likely get at least 2 games and a comfortable amount of space.

## Live

**Price**: [Actual Costs](#actual-costs) + no more than $4/month of [Developer Support](#developer-support)

The **Live** tier will provide everything **Legacy** provides, but with the addition of hosted server support so you can play with your friends online. Only one person will need to pay for a subscription for any given game.

---

# Development Roadmap

I intend to deploy the tiers in the order above. I'll provide more detail about the tasks I'm currently working on in the [Discord](https://discord.gg/SkjzZVKe2m), but at a high level, here are the tasks I still need to complete for each tier:

## Local

- [ ] Add ability to upload maps (including grid detection)
- [ ] Add tools for drawing rooms/platforms (i.e., the existing hard-coded functionality)
- [ ] Add tools for irregular walls/floors
- [ ] Save created maps in local storage
- [ ] Save character updates, token positions, etc., in local storage

## Legacy

- [ ] Create a user database
- [ ] Create admin and user pages to manage stored data
- [ ] Save and restore game state to/from server storage

## Live

- [ ] Create a server management infrastructure
- [ ] Update admin pages to track server-side content
- [ ] <span>Convert existing [service worker](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)-based state updates to remote state updates</span>

## SRD 5.1

There are also a few tasks I need to complete before any of the tiers are useful for running SRD 5.1 sessions:

- [ ] Add lead character creation flow for SRD 5.1 (also includes being able to level characters up)
- [ ] Add ability to create custom equipment items, including magic items
- [ ] Add system support for higher-level character abilities
- [ ] Add more spells, and the ability to add custom spells

Beyond this, there are a lot of features I _want_ to add, but I also want to prioritize getting the core functionality ready for people to try.

---

# Financial Transparency

Once a paid subscription tier launches, I will provide monthly accounting of the financials of providing the subscription services. This will help me adjust pricing for the subscription tiers by showing two important numbers:

## Actual Costs

Actual costs are how much I have to spend to keep the site running for a given tier. That means that for the **Legacy** tier, it mostly consists of the file storage and database server required to track users and their game content, and for the **Live** tier, it will also add the cost of running servers to support multiple concurrent users. This cost will then be divided out over the number of users at that tier. I care a lot about performance and efficiency, so I will do my best to keep the server overhead as low as I can and pass on the savings to you.

## Developer Support

In short, this is my salary for developing this product. I haven't set a firm number for this yet, but it will be enough to support me and my family at a level commensurate with my professional experience (but well under the most I've made at big tech companies).

This will also be divided out over the paid tiers, but I've put a cap on the amount, which means that it won't cost the first users too much, even though that means it will take longer for me to recoup my initial costs. I will also subtract any donations from the **Local** tier before computing the rest, in the event that I'm able to hit my target.
