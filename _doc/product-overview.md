# FlowTrack — Product Overview

## What It Is
FlowTrack is a warehouse operations dashboard built specifically for warehouse supervisors. It provides real-time visibility into the three critical phases of warehouse flow — inbound shipments, storage locations, and outbound orders — so supervisors can accelerate fulfillment and eliminate misplaced inventory. It replaces paper logs, radio chasing, and tribal knowledge with a single, authoritative command center.

## Users
- **Primary:** Warehouse supervisors managing daily receiving, storage, and shipping operations
- **Secondary:** Warehouse managers and logistics coordinators who need operational status at a glance

## Problem It Solves
Warehouse supervisors currently lose time and money to three compounding problems:

1. **Inbound chaos** — Shipments arrive with no pre-visibility. Docks clog, receiving slows, and teams scramble without a plan.
2. **Misplaced inventory** — Items get stored ad hoc in whatever space is available. Workers spend hours searching instead of picking.
3. **Stalled outbound orders** — Outbound orders halt when picks can't be located, causing late shipments, customer complaints, and costly re-work.

The root cause: supervisors have no single source of truth. They manage by radio calls, paper logs, and memory — reactive, not proactive.

## Core Features

1. **Inbound Shipment Tracker** — Log expected shipments before they arrive. Track status from expected arrival through dock assignment to confirmed receipt. Capture carrier details, expected quantities, and arrival windows.

2. **Storage Location Manager** — Assign every item to a specific zone, aisle, and bin. Instantly search and locate any inventory by SKU or storage slot. Maintain a full movement history so nothing disappears without a trace.

3. **Outbound Order Board** — Manage outbound orders end-to-end: generate pick lists, track packing status, flag blockers, and confirm dispatch. Every order's status is visible at a glance.

4. **Supervisor Dashboard** — A unified operational command view showing live counts of open inbounds, occupied storage locations, and pending outbound orders — with alerts flagging anything that needs immediate attention.

## Goals & Success Metrics
- Speed up fulfillment cycle time by eliminating status-chasing
- Eliminate misplaced inventory incidents through location assignment
- Give supervisors a single dashboard replacing spreadsheets, radios, and paper logs

## Positioning
FlowTrack is not a full WMS replacement — it is a focused supervisor tool: lean, fast, and built around the three operational moments that matter most (receive → store → ship). It sits above the warehouse floor as a command layer, giving supervisors clarity to act without digging through paper or pinging their team for status.

## Tone & Brand
- **Product name:** FlowTrack
- **Voice:** Direct, operational, no-nonsense. Built for people who need answers fast, not a polished enterprise demo.
- **Primary color:** Deep navy (#1A3B6E) — trust, reliability, authority
- **Accent color:** Vibrant orange (#F97316) — urgency, action, logistics energy
- **Supporting color:** Emerald green (#10B981) — confirmation, success states
- **Feel:** Command center. Calm but alert. Utility-first with professional polish.

## Scope
- Application type: Admin Dashboard / Operational SaaS
- Access: Web application — desktop or warehouse kiosk
- Roles: Warehouse Supervisor, Warehouse Manager, Admin
- Tech: Remix + Express, MongoDB, Tailwind + shadcn/ui

## Planned Next Features (Post-MVP)

1. **Outbound Order Dispatch Board** — A dedicated queue view for supervisors to review, prioritize, and confirm outbound orders before truck dispatch. Shows per-order status (pick pending, packed, ready), lets supervisors flag blockers, and confirms gate release. Reduces late shipments by giving supervisors explicit control of the final dispatch step.

2. **Inventory Alert System** — Proactive, rule-based notifications surfaced inside the supervisor dashboard. Alerts fire on low-stock thresholds, items with no confirmed storage location, overdue inbound shipments, and orders blocked because a pick location is empty. Replaces reactive radio chasing with structured, prioritized alert feeds.

3. **Shipment History & Audit Trail** — A searchable, filterable log of all inbound and outbound movements. Every status transition (expected → arrived → received, pick → packed → dispatched) is recorded with timestamp, actor, and details. Supports end-of-shift reviews, discrepancy investigations, and carrier performance tracking.
