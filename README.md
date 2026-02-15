# coordination-map-v1
Prototype pour PU-AMI
Nutrition Cluster Coordination Cockpit

Benishangul-Gumuz – Pilot Prototype

1. Purpose

This prototype provides a lightweight, read-only visualization layer built on existing 4W data to improve the efficiency and clarity of Nutrition Cluster meetings.

It does not replace ActivityInfo or official 4W reporting systems.
It is designed solely to support faster collective decision-making during coordination meetings.

2. What This Tool Is — and Is Not
✔ What it is

A meeting support interface

A visual layer built on validated 4W exports

A read-only dashboard for coverage, freshness, and geographic gaps

A pilot to test whether meetings become more decision-focused

✖ What it is not

Not a parallel reporting system

Not a replacement for ActivityInfo

Not a performance ranking tool

Not a public-facing publication platform

Not a data collection mechanism

No additional reporting burden is created for partners.

3. Operational Workflow

The tool follows the standard cluster data governance chain:

NGO → Draft 4W → Validation (Cluster IM) → Published dataset → Coordination Cockpit → Cluster meeting

The cockpit only consumes validated data.
No data editing is possible within the interface.

4. Modules
A. Monthly Timeline View

Filter by reporting month

Visual comparison across months

Quick understanding of reporting dynamics

B. Geographic View (Woreda Level)

Number of interventions per woreda

Actor visibility

Rapid identification of low-coverage areas

C. Update Freshness Indicator

Displays last reporting date per organization

Based on collectively agreed thresholds

No public ranking or naming-and-shaming

Purpose: support collective accountability and preparedness before meetings.

5. Data Source

Source: Standard 4W export (ActivityInfo / Excel consolidation)

Format: Published CSV (Google Sheets or equivalent export)

Structured fields only

No additional data required from partners

Data Sensitivity

This prototype:

Does not store personal data

Does not publish sensitive site-level information

Does not host external datasets

Does not redistribute data outside cluster validation

Any external publication requires explicit cluster approval.

6. Hosting & Technical Structure

Static HTML interface (no backend server required)

Built using:

Leaflet (map rendering)

Chart.js (visual summaries)

PapaParse (CSV parsing)

Can run via GitHub Pages or local environment

Read-only by design

Offline fallback version can be implemented if required.

7. Governance & Ownership

Data ownership remains with the Cluster.

Validation responsibility remains with Cluster IM / IMO.

Code is open and transferable.

No proprietary lock-in.

The tool can be fully handed over to the Cluster IM if validated after pilot phase.

8. Pilot Scope (4–6 Weeks)

Evaluation indicators may include:

Time spent interpreting data during meetings

Speed of gap identification

% of partners updating within agreed threshold

Perception of clarity (partner feedback)

Objective: test whether meetings shift from data reading to decision-making.

9. Current Status

Prototype – Version 1
Developed as a pilot support tool for cluster discussion.

10. Contact

For pilot feedback or technical questions, contact the Cluster IM focal point or project lead.
