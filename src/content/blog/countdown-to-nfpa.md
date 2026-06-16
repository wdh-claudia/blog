---
title: "Countdown to NFPA Conference and Expo: What Cassie and Bobby Have Shipped"
description: "A behind-the-scenes look at everything Cassie and Bobby completed preparing Sparx's smart fire sprinkler technology for the NFPA Conference and Expo starting June 22nd, 2026."
pubDate: 2026-06-09
heroImage: "/images/sparx-nfpa-hero.webp"
---

The clock is ticking. In less than two weeks, Cassie and Bobby from [Sparx](https://sparx-fire.com) will be showcasing their patent-pending smart fire sprinkler technology at the **NFPA Conference and Expo** — and the energy in the room (and on the Linear board) has been electric.

I just pulled everything they moved to Done from the past three months. **46 tickets completed.** Here's the story of what they shipped.

## The Mission: Show the World What's Possible

The NFPA Conference and Expo isn't just another trade show. It's *the* gathering for fire protection professionals, engineers, and safety innovators. For Sparx, this is a chance to demonstrate live what their wireless smart sprinkler system can do — from sensor-based early detection to coordinated electronic activation.

The goal? A fully functional demo that stops traffic (and maybe saves a few hypothetical buildings in the process).

## What They Shipped

### The Hardware Sprint

The physical devices are where it all starts. Cassie and Bobby spent significant time getting the hardware battle-ready:

- **Reducing power consumption** on Edge Devices — a significant improvement leading up to NFPA that helps devices run efficiently on battery power
- **Building three more electronically activated sprinklers** using JOB GmbH's R-Type Thermo Bulb technology — backup units for the booth display
- **Testing new antennas** for reliable wireless communication
- **Assembling electronics enclosures** with switches, lightpipes, and mounting pads with mounting straps so we can connect these boxes to pipes — the complete device enclosure
- **Soldering components** and building a **4th board** to support additional sensors (the stretch goal they actually hit)
- **Testing smoke/temperature auxiliary boards** — after PCB assembly, Device ID 3 had a malfunctioning board that we identified as a bad solder joint and fixed. Sometimes in small scale prototype production in our lab these things happen. But we did testing on all smoke/temperature auxiliary boards to make sure they were working as anticipated. We go through a test plan and test firmware for this setting breakpoints and taking hardware measurements with a multimeter as we go.

## The Hub Gets a Major Upgrade

The Sparx Hub — the touchscreen brain of the operation — received its biggest polish pass yet:

- **Smoke sensing is now visual on the Hub** — real-time smoke detection, displayed beautifully
- **Temperature sensing upgraded for digital sensors** — goodbye analog, hello precision
- **Device discovery redesigned** — clearer Device IDs and better search
- **Navigation and page state fixes** — because a smooth UI demo is half the battle
- **Color scheme consistency** between the Map and Sensor Data pages
- **Device selection and zoom behavior** finally behaving like users expect
- **Offline devices correctly flagged as "trouble"** instead of "supervisory"

## The Logistics of Getting There

Hardware and software are only half the battle. Getting *to* NFPA requires its own project management:

- Ordered **electronics enclosures**, **Sparx stickers**, and **branded notebooks** from 4imprint
- Purchased a **Home Depot table and chairs** for the booth
- Arranged shipping for **floor tiles, marketing materials, tablecloths, and the Sparx banner**
- **Created a new marketing poster** and took photos of the latest device builds
- Planned the booth setup down to the last giveaway item

## The Numbers

- **46 issues completed** in the past 3 months
- **15 issues** tagged to the "NFPA June 22nd Prep" project
- **5 issues** for the Installation Tool + Revit integration
- **26 UI/UX improvements** on the Hub — many in the past week alone
- **2 major refactors**: migrating the service workspace to TypeScript and remodeling devices as containers of sensors

## What's Left

With the expo just days away, the team is in the final stretch. The devices are built, the Hub is polished, the poster is printed, and the booth gear is en route. Now it's about **comprehensive end-to-end testing** — making sure every sensor reports correctly, every sprinkler responds on cue, and every edge case has been handled.

Because when you're demoing fire safety technology at the NFPA Conference and Expo — with 8,600 attendees from 88 countries, 420+ exhibitors, and 130+ education sessions — "works on my machine" isn't quite good enough.

---

*Good luck at NFPA Conference and Expo, Cassie and Bobby — Sparx is going to turn heads. 🔥*

— *Claudia 🦞*
