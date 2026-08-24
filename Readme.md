---
permalink: /
layout: default
title: Mokupuni Hawaiʻi — one shared, trusted map
description: >-
  Mokunet holds the islands of Hawaiʻi as one shared, trusted map, organized by
  their 33 traditional moku — and serves that map to people and to software
  alike: feature services, dashboards, and the platform API.
---

# Mokupuni Hawaiʻi — one shared, trusted map

**Mokunet** holds the islands of Hawaiʻi as one shared, trusted map, organized
by their 33 traditional moku — so the people caring for a place today, and the
future leaders training to coordinate that care next, can see their moku and
their kuleana (their role, and where they stand) and act on it.

From any moku you can find the lands and waters that belong to it, the projects
and programs under way from planning to outcome, and the producers and partners
working there. (Assembled from 18 authoritative state and federal datasets.)

The map is not only something to look at — it is something to build on. This
repository is Mokunet's public service directory: the short list of the
surfaces where the shared map is served — to people, and to the software that
partners bring.

## Where to go

- **[mokunet.org](https://mokunet.org)** — the network's public home: moku
  stewardship, community, roles, and how to join.
- **[Moku Data Governance Hub](https://hawaii.mokunet.us)** — the platform app:
  data governance and management for Hawaiʻi's moku, with records grounded in
  place and access scoped to your kuleana.
- **[Research Commons](https://github.com/Aina-Design-Corp/mokulearner-research)** —
  community data intake: screened, qualified datasets contributed in the open.
- **[Mokunet on ArcGIS Online](https://mokunet.maps.arcgis.com/home/index.html)** —
  the network's geospatial service surface: the shared map's layers, published
  as feature services, and the dashboards assembled from them (how those prove
  the pipeline is described below).

## The service surfaces — for partners and developers

Everything the map shows a person, the network can serve to software. That is
this repository's subject: Mokunet's role as the service layer of the network.

- **Geospatial feature services** — the shared map's layers are published on
  [Mokunet's ArcGIS Online organization](https://mokunet.maps.arcgis.com/home/index.html)
  in the format Hawaiʻi's public agencies already work in. The dashboards and
  web maps there are the reference UI, assembled from the feature services
  alone — no custom software in between — so a working dashboard is live proof
  that the layer pipeline serves an integration exactly as it serves the eye.
- **Platform API** — [`hawaii.mokunet.us/api`](https://hawaii.mokunet.us/api):
  the Moku Data Governance Hub's interface for records grounded in place, with
  access scoped to kuleana — your role, and where you stand.
- **The pattern in practice** — the
  [Green Fee transparency demonstration](https://kuleana.ainadesign.org) shows
  how a public portal builds on this separation: a registry-driven site whose
  project records point to their authoritative map and dashboard destinations
  instead of replacing them. Official systems stay authoritative; services
  resolve each place against them. We honor the official lines; we don't
  redraw them.

**Stage, honestly:** the shared map and its layers are being tested; open
access for partners and developers is being built. Nothing here is presented
as further along than it is.

---

Stewarded by [Āina Design Corp](https://ainadesign.org). Some parts of the
network are still being built; [mokunet.org](https://mokunet.org) keeps the
honest list of what works today and what is on the way.
