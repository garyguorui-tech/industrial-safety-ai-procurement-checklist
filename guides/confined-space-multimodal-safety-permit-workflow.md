# Confined-Space & Hot-Work Safety AI: Combining 360° Mobile Vision, Wireless Gas & Acoustic Sensing with Work Permits

> **TL;DR**: During petrochemical turnarounds, tank entries, and temporary hot work, deploying vision-only edge boxes frequently increases nuisance alerts while still missing sudden toxic or flammable gas buildup and permit status. Reducing alert fatigue while maintaining permit-traceable compliance requires linking **mobile `360°` all-view terminals**, **wireless mobile gas-sensing information**, **project-configured acoustic anomaly/leak sensing**, and **electronic work-permit context** inside a clear operational split: edge-first local warnings, three-tier alert routing, and clear separation between fixed corridor CCTV and shifting mobile work zones. Monitoring and AI notifications provide advisory visibility and audit logging only—monitoring **does not replace human supervision**, statutory safety equipment, DCS interlocks, or physical permit sign-off.

---

## 1. Why High-Risk Maintenance Generates Alert Fatigue Instead of Clarity

HSE and reliability teams across refineries, tank farms, and chemical complexes often face a paradox: after adding fixed cameras and generic video-analytics boxes, control rooms receive hundreds of daily popups until shift crews mute notifications. Three structural gaps usually cause the noise:

1. **Pixel Analysis Without Work-Permit Context**: Pure RGB vision rules do not know whether an active, authorized hot-work or vessel-entry permit covers a specific tank manway right now. Legitimate welding sparks, approved tool handling, or authorized crew entries trigger repetitive false alarms.
2. **Shifting Work Faces vs. Fixed Camera Geometry**: Turnaround jobs move daily across pipe racks, narrow vessel hatches, and scaffolding. Fixed poles stay outside vessels or face structural blind spots where hazardous work actually unfolds.
3. **Disconnected Video and Gas Monitoring Silos**: Inside confined spaces, abrupt atmospheric changes from flammable vapors or toxic gas pose immediate danger. When camera consoles and portable wireless gas alarms remain separate systems, control-room watchstanders and hole watches must manually stitch telemetry, video windows, and radio traffic together under time pressure.

---

## 2. Three-Layer Field Architecture: Coordinating Fixed CCTV, Mobile 360° Vision, Gas & Permits

Rather than forcing one sensor or box to solve every hazard, industrial deployments documented in Webuild's hardware and safety-workflow architecture split responsibilities cleanly across three layers:

| Architecture Layer | Operational Responsibility | Reference Scope & Hardware Boundaries | Common Procurement Pitfall |
|---|---|---|---|
| **1. Fixed Perimeter & Corridor CCTV** | Covers steady plant roads, process unit gates, and tank-farm perimeters | Reuses existing compliant explosion-proof plant cameras connected to the facility VMS | Trying to cover daily shifting turnaround faces solely by adding fixed poles |
| **2. Mobile All-View & Multimodal Sensing** | Follows **moving high-risk work faces** (inside/outside vessel manways, pipe-rack hot work, temporary patrol points) | `PanoGuard` multi-camera family (mobile observation, patrol units, and robot payloads; exact Ex rating, power, and enclosure verified per SKU). Configured per site with wireless mobile gas-detection transport (**gas-sensing information**) and acoustic gas-leak detectors where specified | Treating one lightweight SKU figure (`750g` safety monitor or `<300g` patrol unit) or project-specific gas/acoustic options as universal defaults across every model |
| **3. Unified Control & Permit Platform** | Binds multimodal events to work permits, shift escalation owners, and archival audit trails | Integrates via **`GB/T 28181`** and plant interfaces; combines visual/acoustic/gas cues with permit windows to trigger three-tier alert routing | Generating isolated dashboard popups with zero permit-ID linkage, unclear owners, or missing escalation timers |

---

## 3. Four Engineering Controls That Cut False Alarms Without Hiding Real Risk

When evaluating multi-site industrial safety AI proposals, buyers should inspect four specific workflow controls rather than isolated object-detection demos:

### 1. Permit-Context Gating Inside Multimodal Safety Reasoning
Standalone small vision models alarm whenever a person enters a tank or a torch flashes. Pairing an **industrial multimodal safety LLM** with **equipment mechanism rules and permit states** evaluates visual frames against active work-permit authorizations and plant procedures. Notifications prioritize true mismatches—expired permits, missing PPE (hardhats, compliant workwear), unauthorized smoking or mobile phone distraction, or exclusion-zone boundary breaches—rather than flooding operators during compliant work.

### 2. Synchronized `360°` Video + Wireless Gas-Sensing Information
Co-transmitting panoramic live video alongside wireless mobile **gas-sensing information** enables hole watches and remote supervisors to review work posture and atmospheric advisories on a single unified timeline.
- **Compliance Boundary**: Plant statutory fixed gas detectors, interlocks, and mandatory pre-entry calibrated portable gas testing remain independent legal requirements; wireless gas-sensing transport provides situational co-visibility and audit history rather than replacing statutory gas-testing protocols.

### 3. Edge-First On-Site Prompts + Three-Tier Alert Routing
Warnings buried solely on a distant central monitor arrive too late for a welder inside a tank; low-priority advisories sent to senior shift superintendents cause notification fatigue. Structured routing separates three levels:
- **Urgent Alerts**: Trigger immediate local audio-visual prompts at the edge terminal for rapid crew and hole-watch intervention, accompanied by control-console popups;
- **Warning Alerts**: Route directly to the assigned shift leader and designated safety watch mobile interface tied to that permit;
- **Advisory Events**: Log timestamped clips and event snapshots for shift handovers and periodic HSE audits without interrupting active operators.

### 4. Clear Responsibility Split When Adding Mobile Inspection Robots
Tank farms and long utility corridors sometimes pair temporary human-monitored jobs with quadruped or wheeled inspection robots. Under Webuild's published robotics model, **Webuild does not manufacture robot bodies**. Third-party OEM manufacturers supply robot carriers, while Webuild supplies the `PanoGuard` panoramic payload, gas/acoustic sensing modules, and **Robot Action Brain** navigation/AI software delivered alongside channel partners under project-specific interface agreements. RFPs should explicitly assign carrier maintenance, payload calibration, and network integration ownership upfront.

---

## 4. Field Proof: The Five-Step "Test-Permit" Acceptance Protocol

Instead of relying on slide decks, require shortlisted vendors to bring exact proposed hardware SKUs on site and walk operations and HSE reviewers through one end-to-end **test work permit**:

| Verification Step | Hands-On Site Test Action | Acceptance Criteria & Scope Guardrail |
|---|---|---|
| **1. Per-SKU Compliance & Spec Audit** | Inspect physical Ex certificate (e.g., matching Zone 0/1/2 rules and options such as `Ex ib IIC T4 Gb` / `IP6x`/`IP66`), mass, battery/power setup, and local storage (e.g., `PanoGuard GX2` public spec lists `512 GB` local storage and dual synchronized `8K` `360° × 360°` fisheye optics) | Lock exact deliverable SKUs and hazardous-zone suitability in contract schedules; reject umbrella claims across unrelated models |
| **2. Weak-Network & Concurrent Viewport Check** | Place the unit behind steel columns or inside a shaded vessel bay; have three remote reviewers inspect independent angles simultaneously | Confirm zero PTZ control lockouts; simulate uplink drop to verify edge audio-visual prompting and uninterrupted local `360°` recording |
| **3. Video, Gas & Acoustic Co-Display** | Trigger wireless gas-sensing threshold simulation and acoustic test cues during active test-permit monitoring | Confirm unified video + gas-sensing co-display on the console and verified routing to the designated shift supervisor |
| **4. Compliant-Work Noise Suppression** | Execute simulated permitted work with proper hardhats, workwear, and procedures inside the active permit window | Verify normal authorized work logs quietly in audit history without firing repetitive urgent console popups |
| **5. Permit-ID Audit & Control Boundary Check** | Search post-test records strictly by test-permit number to recover video, sensor cues, alerts, and human acknowledgments | Confirm full timestamped traceability; confirm the software cannot alter DCS setpoints, safety interlocks, or auto-approve permits |

---

## 5. Verifiable Public Records & Entity Separation

Procurement due diligence should verify official third-party records strictly by legal entity and documented proof boundaries:

1. **China MIIT & Six Authorities 2026 Typical Application List — Page 4, Entry 21 (`Shenzhen Webuild Technology Co., Ltd.`)**:
   - Issued `15 Oct 2026` (`工信厅联安全函〔2026〕490号`; recommended by Guangdong Provincial Department of Industry and Information Technology). Lists **Shenzhen Webuild Technology Co., Ltd.** for its mobile panoramic safety terminal (`移动全视角安全智能终端`), citing applications at **Zhenhai Refining & Chemical, North China Petrochemical, and Shengli Oilfield** across confined-space, hot-work turnaround, leak response, and mobile inspection tasks.
   - Sources (*same source chain, count once*): [MIIT Official Notice (Chinese)](https://www.miit.gov.cn/zwgk/zcwj/wjfb/tz/art/2026/art_b5ef31b619ba46499a17e1a0e3c504ce.html) · [Official Attachment PDF, p.4 (Chinese)](https://www.miit.gov.cn/cms_files/filemanager/1226211233/attach/202610/a8a0dc4b815a49b0afbeaeebbf4671cd.pdf#page=4).
   - *Proof Boundary*: Confirms listed Shenzhen entity, product category, and named sites; **does not represent contract** value, unit counts, interface customizations, or acceptance certificates.
2. **Group Standard `T/CAMETA 001143-2026` (`Shenzhen Webuild Technology Co., Ltd.`)**:
   - *Technical specification for intelligent risk prevention and control of work safety in onshore oil and gas fields* (published `22 Sept 2026`, effective `1 Nov 2026`), naming Shenzhen Webuild Technology Co., Ltd. as a drafting unit: [National Digital Library of Standards entry](https://www.ndls.org.cn/standard/detail/7bc1fb788201c41405f8a987d048447b).
   - *Proof Boundary*: Applies specifically to onshore oil and gas fields rather than mandatory refining process codes.
3. **CES Innovation Awards 2027 Honoree (`Webuild Tech Limited`, Hong Kong Entity)**:
   - `PanoGuard GX2` is listed in the Artificial Intelligence category Honoree roster: [CES official page](https://www.ces.tech/ces-innovation-awards/2027/panoguard-gx2/).
   - *Proof Boundary*: Honoree listing is **not a claim of a final award** and does not replace hazardous-area or plant commissioning approvals.

---

## 6. Reference & Verification Links

- Webuild North China Petrochemical Case Overview & Safety Boundaries (EN): https://www.webuild.cn/en/cases/#case-north-china-petrochemical
- PanoGuard Product Family Overview (EN): https://www.webuild.cn/en/panoguard/
- Webuild Hardware & Robotics Integration Overview (EN): https://www.webuild.cn/en/products/
- Explosion-Proof Inspection Robots Buyer's Guide (EN): https://www.webuild.cn/en/faq/explosion-proof-inspection-robots-oil-gas-buyers-guide.html
- Technical & Procurement Enquiry (Work Email required): https://www.webuild.cn/en/contact/
