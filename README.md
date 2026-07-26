# PTDAGY: Phase-Transmutation Directed Acyclic Graph Engine
**Repository:** `https://github.com/professordt/ptdagy.git`  
**Current Version:** `PTDAGY v2.5`  
**Focus Area:** West Hollywood Infrastructure Cascade & Cross-Domain Forensic Matrix  

---

## 📌 About The Project

**PTDAGY** (Phase-Transmutation Directed Acyclic Graph) is an open-source, non-hierarchical, multi-layered knowledge graph architecture. It integrates physical infrastructure telemetry, legal and regulatory records, acoustic/infrasound dynamics, and spatial coordinates into a unified, fact-checked investigative graph.

Rather than relying on top-down institutional narratives, PTDAGY maps ground reality from the bottom up—starting at the physical and geological layer (pipe metallurgy, soil saturation, standing wave frequencies, fault lines) and tracing upward to administrative logs, court filings, and municipal actions.

---

## 🏙️ Current Case Focus: The West Hollywood Corridor Cascade (July 2026)

This repository currently tracks the physical, hydraulic, and municipal events surrounding the July 2026 infrastructure failures in West Hollywood, California:

1. **July 16, 2026 (Sunset/Palm Rupture):** Catastrophic rupture of the 110-year-old, 36-inch riveted steel Sunset Trunk Line (installed 1916), releasing 17,000,000+ gallons of water, creating a sinkhole, and flooding subterranean structures down the Palm Avenue elevation gradient.
2. **July 23, 2026 (Santa Monica Blvd / Laurel Leak):** Secondary hydraulic surge and 6-inch water main valve failure 0.3 miles downhill on the 8200 block of Santa Monica Boulevard, flooding sidewalks outside Laurel Hardware (8218 SMB) and Farmacy Collective dba MedMen WeHo (8208 SMB).
3. **Regulatory & Receivership Mapping:** Cross-referencing physical flood sites against public court filings (LA Superior Court Receivership, Canadian Bankruptcy Trustee B. Riley Farber) and City of West Hollywood Business License Commission actions (Resolution BLC24-0004).

---

## 📐 Core Architecture & Schema

PTDAGY operates across a **Triphasic Engine**:
* **Solid State ($\text{Koppa } \mathbf{\text{Ϟ}}$):** Static boundaries, hard assets, physical moment frames, fixed IP tables, and court resolutions.
* **Liquid State ($\text{Digamma } \mathbf{\text{Ϝ}}$):** Hydraulic flow, standing wave resonance, subsurface runoff vectors, and dynamic data ingestion.
* **Gas State ($\text{Sampi } \mathbf{\text{Ϡ}}$):** Atmospheric pressure venting, RF carrier wave interference, and macro-systemic/legal overrides.

### Knowledge Graph Schema (`ptdagy_master_v2.5.json`)
The main repository payload includes structured JSON-LD objects defining:
* `tier_1_triphasic_engine`: Structural mechanisms and yield states.
* `tier_2_temporal_provenance_sequence`: Chronological event nodes from T-minus planning knowledge to T5 cascade.
* `tier_3_spatial_micro_nodes`: Geographic and physical site anchors (`N_origin`, `N_garage`, `N_smb_laurel_sink`).
* `tier_4_corroborating_evidence`: Verified news reports, municipal license proceedings, and court filings.
* `tier_5_triadic_wedge_analysis`: Acoustic WAV extraction findings (standing waves at 102–120 Hz, sub-bass 5–15 Hz).
* `causal_edges`: Directional relations connecting precursor events to physical manifestations and legal outcomes.

---

## 🤝 How You Can Help (Call for Contributors)

We are actively seeking contributions from researchers, open-source intelligence (OSINT) analysts, data engineers, paralegals, and local community members.

### Ways to Contribute:

1. **FOIA & California Public Records Act (PRA) Filings:**
   * Help file and log public records requests with the City of West Hollywood, LADWP, and DCC (see [`INVESTIGATIVE_ROADMAP.md`](./INVESTIGATIVE_ROADMAP.md)).
   * Submit received PDF disclosures or public meeting transcripts to the repository.

2. **Court Docket & Title Search:**
   * Pull active minute orders or receiver status reports from Los Angeles County Superior Court case files related to `MM CAN USA, Inc.` or commercial unlawful detainer actions on the 8200 block of Santa Monica Blvd.

3. **Data Verification & Graph Modeling:**
   * Review JSON-LD nodes for consistency and ensure all added data points adhere to strict public-record verification standards.
   * Help build visualization interfaces (D3.js, Cytoscape, or Graphviz) to render the DAG interactively.

4. **Acoustic & Signal Processing:**
   * Analyze raw audio or PoE security camera extractions for ambient spectrum analysis, low-frequency hums, or transient signatures.

---

## 📂 Repository Structure

```text
.
├── README.md                          # Repository overview and contribution guide
├── INVESTIGATIVE_ROADMAP.md           # Targets for FOIA, PRA, and court records
├── schema/
│   └── ptdagy_master_v2.5.json        # Primary Master Knowledge Graph Schema
├── docs/
│   ├── reports/                       # Deep research investigative summaries
│   └── public_records/                # Index of verified public municipal filings
└── scripts/
    └── ingest_env.py                  # Local environment harvester & secret redactor
