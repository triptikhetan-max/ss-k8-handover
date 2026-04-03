**Subject:** Social Studies K-8 Project Handover — Research, Decisions, and Dashboard

---

Hi,

I'm handing over the Social Studies K-8 curriculum research project. Everything is in one interactive dashboard — start there.

**Dashboard (start here):**
https://triptikhetan-max.github.io/ss-k8-handover/

7 tabs: Overview, Key Decisions, Standards Analysis, Curriculum Stack, App Evaluations, Assessment Framework, and What's Not Done.

**WorkFlowy (full research + thought process):**
https://workflowy.com/#/3a3ee65e7a25
All the research, all the details, all the relevant document links, and the entire thought process.

---

## What This Project Is

A research foundation for building Alpha's K-8 Social Studies curriculum across multiple states. This is NOT the curriculum — it's the research, decisions, and architecture that should inform whoever builds it.

**What was researched:**
- What content to teach, in what sequence, using which organizational model
- How to handle 50 different state standards with one coherent curriculum
- How to adapt teacher-led curricula for self-paced autonomous learning
- Which published curricula to license vs. build from scratch
- The full K-8 social studies landscape (experts, frameworks, standards, debates)

**Out of scope:** High school, lesson-by-lesson implementation, LMS/tech, deep pedagogy, international frameworks.

---

## The Problem

Three structural problems that don't exist in math or ELA:

1. **No national standards.** 50 different state frameworks. No Common Core equivalent for social studies.
2. **Teacher-dependent curricula.** Every published SS curriculum assumes a teacher present. None are built for autonomous learning.
3. **Marginalized subject.** 62% of elementary students get <60 min/week of SS. 16% get zero. Collapsed since NCLB.

---

## Key Decisions

### Standards: TEKS as Baseline
- Only state requiring all 4 domains (history, geography, civics, economics) every year K-8
- Tied to state accountability (STAAR Grade 8)
- Alpha has 11 Texas campuses
- 92.5% of TEKS standards overlap with at least one other state — only 34 of 564 are unique to Texas
- Compared against Massachusetts, New York, Tennessee, Florida, California

### Curriculum Foundation: Core Knowledge (CKHG)
- Content-rich, sequential K-8, cumulative spiraling design
- Best alignment with TEKS when state-specific content removed
- Key challenge: deeply teacher-dependent — requires extensive adaptation for autonomous delivery
- Supplement civics with Bill of Rights Institute (BRI)
- Add state-specific modules for compliance

### Short-Term Instruction Stack (G3-G5)
- **Instruction:** BrainPOP lesson videos (IXL has no SS instruction)
- **Practice:** IXL-style questions (high volume, focused repetition, progressive difficulty)
- **Assessment:** State-independent tests from overlapping content
- BrainPOP = concept clarity; IXL-style = mastery and accountability

### Long-Term Architecture
CKHG base content -> BRI civics supplement -> State-specific modules -> "Universal-Plus" curriculum integrating universal content from all states. One curriculum with configuration logic for 50 states, not 50 separate curricula. Modular: common core (~70%) + state supplements (~30%).

---

## Design Principles (SPOVs — Non-Negotiable)

1. **Skills-based architecture breaks social studies.** Unlike math, SS depends on narrative relationships. Decomposing into isolated skills (IXL-style) breaks meaning.
2. **Standards are NOT a curriculum.** Standards list what to cover, not how understanding builds. Design curriculum first, map standards back for compliance.
3. **Domains are lenses, not sequences.** History, geography, civics, economics are analytical lenses on human experience, not separate silos.
4. **Coherence scales better than customization.** One strong curriculum with standards mapping beats 50 fragmented versions.
5. **If inquiry requires a teacher to animate it, it's not scalable.** Core at Alpha = students practice independently with objective feedback.

---

## What Was Researched

- **65 experts** catalogued across 8 domains (civics, history, geography, economics, standards, inquiry, knowledge-based advocates, organizations)
- **6-state standards overlap analysis** — quantitative comparison of TX, MA, NY, TN, FL, CA standards with Python scripts and CSV data
- **50-state assessment landscape** — which states test SS, at what grades, what question types, what frameworks
- **7 apps evaluated** against 6 criteria (iCivics, BrainPOP, Core Knowledge, inquirED, TCI, Studies Weekly, BRI)
- **Grade 3-5 assessment blueprints** — test blueprints with vertical alignment from STAAR Grade 8
- **Multi-campus assessment options** — Iowa Assessments, Stanford-10, TerraNova compared (NWEA MAP has no SS component)
- **Current assessment system diagnosis** — manual Edulastic creation is broken, automated solution designed
- **Curriculum adaptation research** — competency-based learning, TTS, vocabulary scaffolding, automated feedback, gamification

---

## App Evaluations Summary

| Resource | Classification | Why |
|----------|---------------|-----|
| iCivics | **CORE** (civics only) | Decision engine for civic systems. Passes all criteria. |
| BrainPOP | Supplement | Good for exposure, fails narrative coherence. Not mastery. |
| Core Knowledge (CKHG) | **Best content*** | Sequential, cumulative, content-rich. But deeply teacher-dependent. |
| inquirED | Misaligned | Digital but teacher-dependent. Pedagogy requires complete redesign. |
| TCI | Misaligned | Collaborative/experiential. Hardest to adapt for solo learning. |
| Studies Weekly | Misaligned | Accessible but too shallow. No cumulative knowledge building. |
| BRI | Supplement (civics) | Strong free civics content. Not comprehensive K-8. |

*License content, rebuild delivery system for autonomous learning.

---

## Assessment Framework

**Grade 3-5 test blueprints designed** with vertical alignment from STAAR Grade 8:
- Grade 3: 20-25 items, 35-40 min (DOK: 40/40/20)
- Grade 4: 25-30 items, 45-50 min (DOK: 35/45/20)
- Grade 5: 30-35 items, 50-60 min (DOK: 30/45/25) — includes DBQ-lite, cause-effect diagrams

**Current system is broken:** Tests built manually in Edulastic with no framework enforcement. Students tested on untaught content. Each new test introduces different standards. Automated solution designed but not built.

---

## What's Done vs. Not Done

**Done:**
- 65 experts catalogued, 6-state analysis, TEKS selected, CKHG selected, short-term stack, long-term architecture, 7 apps evaluated, Grade 3-5 blueprints, 50-state landscape, multi-campus options, assessment diagnosis, Grade 3 Unit 1 Lesson 1 mapped, SPOVs established

**On Hold:**
- Grade 3 course v0.1 (Unit 1 partial)
- Automated assessment system (designed, not built)
- Multi-campus assessment decision (Iowa vs Stanford-10 vs TerraNova)

**Not Started:**
- Pedagogy research (placeholder)
- Grade 4-8 course design
- State-specific content modules
- Standards auto-mapping system
- Building anything in an LMS

---

## For Whoever Picks This Up

1. Don't start from scratch — 237K+ words of research exist. Read the SPOVs first.
2. TEKS-as-backbone is validated by data (92.5% overlap) and examples (IDEA, BASIS networks).
3. Core Knowledge is the best content IF you invest in adaptation (TTS, chunking, vocab scaffolds).
4. Assessment system is the most urgent gap.
5. Grade 3 Unit 1 Lesson 1 is the most advanced prototype — use as template.
6. "Digital" does not mean "autonomous." Most tools assume teacher-present.
7. Position SS as "integrated content-literacy solution" to protect instructional time.

The dashboard has all the details visually. Start there.

Tripti
