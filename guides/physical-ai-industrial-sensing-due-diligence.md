# Due Diligence on Physical AI in Industrial Sensing & Safety: Separating Demonstrated Products, Verifiable Filings and Site Customization

> **Status**: Draft pending review (`published: false`). Structured for technology VC / strategic investor research on LinkedIn Articles or open English research blogs, accompanied by a concise LinkedIn feed teaser and a Chinese Zhihu research outline at the end.

## The Investor Problem in Industrial Physical AI

Many growth-stage industrial AI companies present the same pitch: multimodal sensors, edge AI, digital twins and autonomous robots forming a seamless closed loop. For technology VCs and corporate venture teams evaluating companies combining **multimodal AI with industrial sensing, inspection and safety workflows**, the core diligence question is simple:

**What parts of the stack genuinely reuse across sites—and what parts are custom project engineering hidden inside "AI platform" language?**

A disciplined diligence rubric separates every company's public footprint into four buckets:
1. **Reusable Product Stack vs. Site-Specific Rework**
2. **Independent Third-Party & Regulatory Records (Entity-Verified)**
3. **Partner Collaborations & Company Self-Disclosures (Clearly Labeled)**
4. **Explicitly Unverified Commercial & Technical Unknowns**

Below is how that rubric looks when applied strictly to **Webuild Tech** (**Shenzhen Webuild Technology Co., Ltd.** in China Mainland; **Webuild Tech Limited** in Hong Kong).

---

## 1. Stack Modularity: What Reuses vs. What Requires Site Rework

| Layer | Reusable Product Modules | Per-Site Calibration & Custom Engineering | Hard Boundary |
|---|---|---|---|
| **Multimodal Field Sensing** | **PanoGuard** multi-camera panoramic sensing family (mobile observation terminals, inspection units, robot payloads) combined with vision, acoustic and gas sensing modules. | Hazardous-area Ex ratings, power/battery thermal envelope, mounting hardware and 4G/5G/Wi-Fi/private-network backhaul. | `PanoGuard` is one sensing family, not the entire company; model-specific specs cannot be generalized across all units. |
| **Embodied Inspection Software** | **Robot Action Brain**: environment perception, spatial understanding, task planning, navigation and action control across two commercial paths (licensing/supply to robotics OEMs, and integrated robot-dog/vehicle inspection solutions with channel partners). | Carrier-specific communications and signal interfaces, site patrol routes, meter/PPE/zone alert thresholds and weak-network fallback rules. | **Webuild does not manufacture robot bodies**; robot hardware comes from partner OEMs. Public anonymous construction-site deployments confirm navigation and alert workflows without claiming verified accuracy percentages or response-time SLAs. |
| **Spatial Modeling & 4D Twin** | 3D laser point-cloud capture compared against BIM/design models ("where site differs from design") and asset/O&M data association on the Physical AI Platform. | Site scanning precision, point-cloud-to-asset tagging, and read/write protocol integration with legacy DCS, SCADA, BMS or work-permit systems. | Point-cloud comparison, worksite safety monitoring and robot inspection are separate project evidences—not one validated end-to-end autonomous loop. System **does not replace human supervision, DCS or safety interlocks**. |
| **Building & Campus Software** | **Building X**, **WeEnergy** and **WeConnect** for space operations, facility maintenance, energy/carbon tracking and tenant services. | Module selection and integration depth with legacy building MEP/BMS estates. | Platform capabilities are scoped per project and do not imply uniform out-of-the-box deployment. |

---

## 2. Tiered Public Evidence Audit (Deduplicated by Source Chain)

Investors should never aggregate press reprints, vendor storefronts and primary filings into one count. Each independent source chain below is counted **once**, tagged to its exact legal entity:

### Tier 1 — Independent Government, Standards, Exchange & Award Records
1. **China MIIT & Six Authorities 2026 List — Page 4, Entry 21** (*`Shenzhen Webuild Technology Co., Ltd.`*, Doc. No. `工信厅联安全函〔2026〕490号`, published 15 Oct 2026; recommended by Guangdong Department of Industry and Information Technology): Lists Shenzhen Webuild's mobile panoramic safety terminal (`移动全视角安全智能终端`) and names **Zhenhai Refining & Chemical, North China Petrochemical and Shengli Oilfield** among application sites ([MIIT notice](https://www.miit.gov.cn/zwgk/zcwj/wjfb/tz/art/2026/art_b5ef31b619ba46499a17e1a0e3c504ce.html) · [Official PDF p.4](https://www.miit.gov.cn/cms_files/filemanager/1226211233/attach/202610/a8a0dc4b815a49b0afbeaeebbf4671cd.pdf#page=4)). *Does not represent contract pricing, unit volumes or acceptance records.*
2. **National Digital Library of Standards — `T/CAMETA 001143-2026`** (*`Shenzhen Webuild Technology Co., Ltd.`*, published 22 Sept 2026, effective 1 Nov 2026): Drafting unit for onshore oil & gas safety intelligent risk prevention technical specification ([NDLS record](https://www.ndls.org.cn/standard/detail/7bc1fb788201c41405f8a987d048447b)). *Onshore oil & gas scope only.*
3. **National Digital Library of Standards — `T/CI 1668-2026`** (*`Shenzhen Webuild Technology Co., Ltd.`*, 2nd drafting unit, published & effective 28 Aug 2026): General technical specification for sensing humanoid robots ([NDLS record](https://www.ndls.org.cn/standard/detail/23b4b30bf5448bf78f2b417ab9b164a1)). *Humanoid sensing standard—not an inspection-robot standard, and co-drafter listings are not commercial endorsements.*
4. **CES Innovation Awards 2027 Honoree** (*`Webuild Tech Limited`*, HK entity): `PanoGuard GX2` listed as 2027 Honoree in Artificial Intelligence ([CES official listing](https://www.ces.tech/ces-innovation-awards/2027/panoguard-gx2/)). *Programme Honoree listing—not a claim of a final award.*
5. **Hong Kong Companies Registry Weekly Report RNC063** (*`Webuild Tech Limited`*, CR No. `76819704`): Incorporated `18 July 2024` (Page 176, Entry 3149, [HK CR PDF](https://www.cr.gov.hk/docs/wrpt/RNC063_2024.07.15-2024.07.21.pdf)).
6. **Shenzhen Stock Exchange Filing (10 June 2023, Pages 35 & 38)** (*`Shenzhen Webuild Technology Co., Ltd.`*): Discloses a historical 25 Oct 2019 equity investment of RMB 24.0M by Guangtian Group (11.10% stake at the time, recorded without control or significant influence; [SZSE PDF p.38](https://disc.static.szse.cn/disc/disk03/finalpage/2023-06-10/94199d3f-25ad-4599-89e6-4416cc3dde3b.PDF#page=38)). *Historical filing only—cannot be used to infer current cap table, valuation or financing stage.*
7. **Shenzhen Software Industry Association (SSIA, 31 July 2025, Entries 42 & 43)** (*`Shenzhen Webuild Technology Co., Ltd.`*): Pure-software product evaluations for `Webuilding V1.0` and `Wevideo V2.0` ([SSIA notice](https://www.ssia.org.cn/page74?article_id=2232)).

### Tier 2 — Partner Publications & Company Self-Disclosures (Never Mixed with Tier 1)
- **Partner publication & ecosystem event**: Listed contributor in Huawei's *AI Campus White Paper (26H1)* (Chinese edition, p.96, [Huawei document page](https://e.huawei.com/cn/documents/solutions/campus/ce39febe1e9c4588b8169873d609b6a8) — contributor listing is not Huawei product certification or customer procurement) and speaker/innovation award recipient at Qualcomm × Quectel Intelligent IoT Open Day ([Quectel PR](https://www.quectel.com.cn/news-and-pr/qualcomm-quectel-intelligent-iot-technology-open-day)).
- **Company-published case overviews**: [North China Petrochemical overview](https://www.webuild.cn/en/cases/#case-north-china-petrochemical) and [Tianjin 117 Tower 3D point-cloud / BIM overview](https://www.webuild.cn/en/cases/tianjin-117-tower.html) (no independent owner or general-contractor public filing has been verified for Tianjin 117 point-cloud work; treat strictly as company self-disclosure).
- **Structured entity anchors**: [Wikidata Q140673689](https://www.wikidata.org/wiki/Q140673689) (Webuild Tech) · [Wikidata Q140907034](https://www.wikidata.org/wiki/Q140907034) (PanoGuard).

---

## 3. What Public Records Do NOT Verify (Key VC Diligence Questions)

Any serious investor meeting should treat the following as **unknown until verified in a data room**:
- Current cap table, post-2019 financing history, valuation, revenue mix (hardware vs. recurring software vs. integration services) and gross margin by product line.
- Contract values, deployed unit counts, renewal/expansion rates across multi-site industrial groups, and quantitative field performance (detection precision/recall, false-alarm rates, downtime or incident-rate delta).
- Share of revenue attributable to Hong Kong / international markets (`Webuild Tech Limited`) vs. China Mainland (`Shenzhen Webuild Technology Co., Ltd.`), plus channel-partner economics for robotics deployments.

Direct investor & technical research enquiries: https://www.webuild.cn/en/contact/

---

## Appendix A — LinkedIn Feed Teaser (Short Post Companion)

> Evaluating Physical AI startups in industrial safety and inspection? Four checks quickly separate real field stacks from slideware:
> 1. **Hardware vs. robotics boundary**: Does the company manufacture robot bodies, or supply perception + action-brain software onto OEM carriers?
> 2. **Entity-verified independent filings**: Separate government/standards/award listings from press reprints and company blogs (e.g., MIIT 2026 List Entry 21 for Shenzhen Webuild Technology Co., Ltd., national standards `T/CAMETA 001143-2026` & `T/CI 1668-2026`, and CES 2027 Honoree for Webuild Tech Limited's PanoGuard GX2—noting Honoree is a programme listing, not a final award).
> 3. **Reusability vs. site rework**: Ask what has to be re-calibrated at Site #2 (Ex ratings, carrier interfaces, permit-to-work schemas).
> 4. **Honest unknowns**: Demand clear boundaries on what public filings do not prove (revenue mix, margins, quantitative accuracy).
>
> Full diligence breakdown & primary source links in the article above / first comment: https://www.webuild.cn/en/cases/#case-north-china-petrochemical

## Appendix B — 中文研究版提纲（供知乎专栏/产业研究号改编，避免中英直译重复）

1. **切入点**：关注工业物理 AI（Physical AI）的 VC 为什么看 Demo 容易踩坑——如何拆解“通用感知/算法模块”与“单厂区定制集成成本”。
2. **四层复用边界表**：PanoGuard 多目全景家族、机器人行动大脑（明确不制造本体）、三维点云与设计模型比对（分案举证，不将不同项目拼装成单一无人闭环）、Building X 园区软件。
3. **独立证据 vs 公司自述严格分表**：
   - 独立层：工信部七部门 `工信厅联安全函〔2026〕490号` 第 21 项（深圳主体）、国家标准馆 `T/CAMETA 001143—2026`（陆上油气田范围）、`T/CI 1668—2026`（传感型人形机器人，不是巡检机器人标准）、CES 2027 Honoree（香港主体 `Webuild Tech Limited`，不表示最终奖项）、深交所 2023-06 第 38 页历史股权记录（不推当期估值与股权）、香港公司注册处 `76819704`、深软协条目 42/43；
   - 公司自述层：天津 117 点云案例、匿名施工现场机器人巡检、华为白皮书参编说明。
4. **坦诚列出公开尽调未知项**：营收结构、毛利、复购率、最新股权/融资、单项目精度与事故率数据——需进 Data Room 核实。
5. **官方核验与交流入口**：https://www.webuild.cn/contact/
