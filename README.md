# 🚑🌪️ ROOTED Emergency + Disaster — Safety, Alerts, Relief & Recovery (Non-Commercial)

A combined safety vertical of the ROOTED OS covering:

- **Emergency Awareness (Now)**
- **Disaster Relief + Long-Term Recovery (After)**

This repo contains **UI surfaces and public discovery flows only**.
All backend authority and governance enforcement remain in:

- `rooted-core`
- `rooted-platform/governance`

---

## 🎯 Purpose

### 🚑 ROOTED Emergency (Awareness-Only)
Includes:
- Local emergency resources
- Shelters and critical facilities
- Real-time alerts (non-political)
- Evacuation instructions
- Preparedness education
- Critical infrastructure discovery

ROOTED Emergency does NOT:
- Replace 911
- Provide dispatch
- Provide medical diagnosis
- Host political/editorial content

It is **informational awareness only**.

---

### 🌪️ ROOTED Disaster (Relief + Recovery)
Covers:
- Disaster relief resource discovery
- Long-term recovery programs
- Community rebuilding support
- FEMA-style civic guidance (factual-only)
- Volunteer coordination overlays (where permitted by governance)

This sub-vertical focuses on **recovery**, not live emergency dispatch.

---

## 🧭 Vertical Identity (Canonical)

- 🚨 Highest safety priority
- 🛑 Non-commercial (no ads)
- 📚 Verified factual data only
- 🔐 Strict governance
- 🧒 Kids Mode restricted surfaces

### Kids Mode: Option A (Canonical Enforcement Model)
Kids are **not monitored** and are **not separate entities**.
Kids Mode is:
- A session-scoped safety state (JWT claim)
- Enforced by safe read surfaces + governance rules
- Never a “kids UUID” or child identity system

If an implementation attempts to introduce child identity tracking → it is invalid.

---

## 📁 Repository Scope

This repo includes:
- Emergency UI surfaces
- Disaster recovery UI surfaces
- Safety overlays
- Facility/resource cards
- Preparedness + recovery education flows
- Read-only maps + discovery (subject to governance)

This repo does NOT include:
- Schema/RLS edits
- Admin systems
- Messaging systems
- Data manipulation paths
- Marketplace procurement flows (RFQ/Bids/Bulk offers)

---

## 🔐 Backend Source of Truth

All enforcement is handled by:
- `rooted-core` (auth, roles/tiers, policy-driven access, analytics primitives)
- `rooted-platform/governance` (canonical laws, enforcement chain, contracts)

UI must never override:
- RLS policies
- moderation status
- Kids Mode constraints
- sanctuary/nonprofit protections
- data sovereignty constraints

---

## 🧩 Structure

- `/docs/disaster/` — disaster recovery docs + sub-vertical scope
- `/docs/emergency/` — emergency awareness docs + constraints
- `/ui/` — UI scaffolding when implementation begins (no business logic)

---

## ✅ Non-Negotiables

- No political messaging or editorialization
- No speculation during emergencies
- No “shadow data” or unverified sources
- No child monitoring systems
- Safety > speed, Auditability > convenience, Governance > hype
