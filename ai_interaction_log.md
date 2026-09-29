# Homework #1: Generative AI Interaction & Human Judgment Log

**Student Name:** 湯惠剛 (Hui-Kang Tang / Tommy Tang)  
**Student ID:** D1500707  
**Course:** Generative AI (Homework #1)  
**Live Production URL:** https://d1500707-portfolio.netlify.app/  
**GitHub Repository:** https://github.com/tommyhktang-creator/portfolio  

---

## Overview & Methodology
This log documents the iterative engineering, prompt progression, and critical human oversight exercised while constructing a personal academic and executive portfolio website. In alignment with the course mandate, generative AI served as an accelerated drafting collaborator, while human domain judgment actively identified and rectified hallucinations, clinical safety discrepancies, and biographical inaccuracies.

---

### Round 1: Information Architecture & Semantic Scaffolding
- **Objective / Prompt:**  
  *"Act as an experienced front-end engineer. Scaffold a modern, single-page responsive portfolio website using pure semantic HTML and Tailwind CSS CDN. Structure it into four core sections: About, Education/Experience, Research/Projects, and Contact, supporting both desktop and mobile viewports."*
- **AI Output Highlights:**  
  The AI drafted a generic, clean single-page skeleton with placeholder content. However, the markup lacked required course identifiers, omitted Chinese/English dual names, and contained standard template filler text.
- **Human Critique & Intervention (Human Judgment):**  
  - Enforced exact grading requirements: embedded my student ID (`D1500707`), Chinese name (`湯惠剛`), and primary academic/industry identities (Doctoral Student in Clinical AI at Chang Gung University; Senior Vice President at LEO Systems).
  - Restructured the DOM into proper semantic sections (`<header>`, `<main>`, `<section>`, `<footer>`) to guarantee web accessibility and clear hierarchical readability.

---

### Round 2: Clinical Protocol Realism & Bioethical Safety Boundaries
- **Objective / Prompt:**  
  *"Incorporate my doctoral research into the Research section: 'Trustworthy AI for Personalized Digital Rehabilitation in Older Adults' (focusing on sarcopenia and closed-loop adaptive intervention). Deconstruct the research methodology into four sequential phases."*
- **AI Output Highlights:**  
  The AI produced a four-phase structure, but erroneously framed the machine learning algorithm as an *"autonomous diagnostic engine that directly prescribes corrective physical exercises without doctor intervention."*
- **Human Critique & Intervention (Human Judgment):**  
  - Intervened immediately to eliminate this dangerous clinical hallucination. In clinical healthcare, autonomous prescriptive AI poses grave liability and patient safety risks.
  - Re-anchored the technical narrative to my actual IRB research proposal: strictly defining AI as a *physician-supervised clinical decision support tool* with safety boundaries, uncertainty quantification, and Human-in-the-Loop clinician override.
  - Incorporated advanced methodological terms: Causal Forest for Heterogeneous Treatment Effects (HTE) and longitudinal digital phenotyping.

---

### Round 3: Biographical Fact-Checking (Excising Degree Hallucination)
- **Objective / Prompt:**  
  *"Audit and verify the Education and Experience section based on my authentic academic credentials."*
- **AI Output Highlights:**  
  The AI hallucinated a master's degree that I never attended: *"National Chengchi University (NCCU) Master's Program in Digital Content."*
- **Human Critique & Intervention (Human Judgment):**  
  - Caught and excised the hallucinated degree.
  - Restored my authentic academic lineage: Bachelor of Science (1987) and Master of Science (1992) in Materials Engineering from Tatung University, connecting my engineering foundation ("microstructure dictates bulk properties") to my ongoing Ph.D. studies in clinical AI at Chang Gung University.

---

### Round 4: Public Training Record Audit & Industry Association Correction
- **Objective / Prompt:**  
  *"Highlight my executive training and keynote lecturing track record for business enterprises and government trade bodies."*
- **AI Output Highlights:**  
  The AI generated fabricated training topics, including an invented workshop for a "Taipei Parking Association."
- **Human Critique & Intervention (Human Judgment):**  
  - Replaced the fabricated associations with my verified public speaking record:
    1. *Taipei Office Automation Equipment Association (台北市事務器械商業同業公會)*: Practical Agentic AI and enterprise knowledge bases.
    2. *Taiwan Food & Pharmaceutical Machinery Manufacturers' Association (台灣食品暨製藥機械同業公會)*: Smart manufacturing process automation.
    3. *Ministry of Economic Affairs & TAITRA (中華民國對外貿易發展協會)*: Global SEO/GEO algorithms and digital export tools.
    4. *University of Taipei Urban Research Institute*: Sustainable city AI governance.

---

### Round 5: Infusing Lived Experience & Empirical Health Transformation Data
- **Objective / Prompt:**  
  *"Integrate the deeply personal origin of my research: witnessing my mother and elderly relatives suffer catastrophic falls from sarcopenia, coupled with my self-administered N=1 AI-assisted body recomposition protocol (86.5 kg to 70.4 kg; blood pressure normalized from 145-152 to 116-122 mmHg)."*
- **AI Output Highlights:**  
  The AI initially placed this personal narrative as a brief, sterile sentence in the bio section, diluting its emotional and scientific impact.
- **Human Critique & Intervention (Human Judgment):**  
  - Created a dedicated visual highlight container: *"Research Origin & Lived Experience."*
  - Structured the quantitative physiological metrics into high-contrast metric cards (16.1 kg weight loss, blood pressure normalization), linking personal empathy directly to the motivation for clinical digital rehabilitation research.

---

### Round 6: Multi-Asset Alignment, File Extension Debugging & Deployment
- **Objective / Prompt:**  
  *"Integrate six high-impact photographic and diagrammatic assets into the site: keynote photos, fitness SOP diagram, resistance training guide, Smart Coordinator feature infographic, and the official 2026 Best AI Awards certificate."*
- **AI Output Highlights:**  
  The AI initially coded mismatched file extensions (`.jpg` instead of `.png` for `training_keynote_1`, `training_workshop_2`, and `smart_coordinator_feature`).
- **Human Critique & Intervention (Human Judgment):**  
  - Fixed file extension paths to ensure zero 404 broken images on case-sensitive Linux servers (Netlify).
  - Verified visual asset display across mobile and desktop viewports:
    - `assets/training_keynote_1.png`
    - `assets/training_workshop_2.png`
    - `assets/executive_fitness_sop.png`
    - `assets/home_resistance_exercises.jpg`
    - `assets/smart_coordinator_feature.png`
    - `assets/smart_coordinator_award.jpeg` (Official certificate signed by MOEA Minister Kung Ming-Hsin).
  - Configured custom Netlify routing: `https://d1500707-portfolio.netlify.app/`.