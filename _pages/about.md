---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .home-intro {
    padding: 1rem 1.1rem;
    margin-bottom: 1.35rem;
    border: 1px solid var(--global-border-color);
    border-left: 4px solid var(--global-link-color);
    border-radius: 10px;
    background: var(--global-bg-color);
  }

  .home-intro p {
    margin: 0.35rem 0;
  }

  .home-section {
    margin-top: 1.7rem;
  }

  .home-section-title {
    display: flex;
    align-items: center;
    gap: 0.55rem;
    margin-bottom: 0.8rem;
    font-size: 1.15rem;
    font-weight: 700;
  }

  .home-section-title i {
    width: 1.9rem;
    height: 1.9rem;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    border-radius: 999px;
    color: #fff;
    background: var(--global-link-color);
    font-size: 0.85rem;
  }

  .home-card {
    display: grid;
    grid-template-columns: 8.3rem 1fr;
    gap: 0.8rem;
    align-items: baseline;
    padding: 0.72rem 0;
    border-bottom: 1px solid var(--global-border-color);
  }

  .home-date {
    color: var(--global-link-color);
    font-weight: 700;
    white-space: nowrap;
    font-variant-numeric: tabular-nums;
  }

  .home-detail {
    line-height: 1.45;
  }

  .pub-list {
    display: grid;
    gap: 0.65rem;
  }

  .pub-group {
    margin-top: 0.85rem;
    border: 1px solid var(--global-border-color);
    border-radius: 10px;
    background: var(--global-bg-color);
    overflow: hidden;
  }

  .pub-group summary {
    cursor: pointer;
    padding: 0.75rem 0.9rem;
    color: var(--global-text-color);
    font-weight: 700;
    list-style-position: inside;
  }

  .pub-group[open] summary {
    border-bottom: 1px solid var(--global-border-color);
  }

  .pub-group .pub-list {
    padding: 0.75rem;
  }

  .pub-card {
    display: grid;
    grid-template-columns: auto 1fr;
    gap: 0.75rem;
    align-items: start;
    padding: 0.75rem 0.85rem;
    border: 1px solid var(--global-border-color);
    border-radius: 10px;
    background: var(--global-bg-color);
  }

  .pub-tag {
    display: inline-flex;
    align-items: center;
    padding: 0.2rem 0.55rem;
    border-radius: 999px;
    color: #fff;
    background: var(--global-link-color);
    font-size: 0.72rem;
    font-weight: 700;
    line-height: 1.25;
    white-space: nowrap;
  }

  .pub-title {
    font-weight: 650;
    line-height: 1.35;
  }

  .pub-authors {
    margin-top: 0.18rem;
    color: var(--global-text-color-light);
    font-size: 0.88rem;
    line-height: 1.35;
  }

  @media (max-width: 640px) {
    .home-card,
    .pub-card {
      grid-template-columns: 1fr;
      gap: 0.35rem;
    }

    .pub-tag {
      width: fit-content;
    }
  }
</style>

<div class="home-intro">
  <p>I am <strong>Wei Li</strong>, a Ph.D. student at the School of Computer Science, Peking University, expected to graduate in July 2027. I am a member of the Institute of Computational Linguistics, advised by Prof. Houfeng Wang. I am currently a research intern at ByteDance Seed.</p>
  <p>My research focuses on <strong>Coding Agents</strong>, especially learning to solve difficult problems and building Coding Agents for multimodal settings. More broadly, I am interested in extending the capabilities of Coding Agents, which I believe are one of the most promising near-term paths toward general-purpose AI systems.</p>
</div>

<section class="home-section">
  <div class="home-section-title"><i class="fas fa-graduation-cap" aria-hidden="true"></i><span>Education</span></div>
  <div class="home-card"><div class="home-date">2025.06 - 2027.07</div><div class="home-detail"><strong>Peking University</strong>, School of Computer Science, Ph.D. student in Computer Science</div></div>
  <div class="home-card"><div class="home-date">2022.07 - 2025.06</div><div class="home-detail"><strong>Peking University</strong>, School of Computer Science, Master's student in Computer Science</div></div>
  <div class="home-card"><div class="home-date">2019.09 - 2022.07</div><div class="home-detail"><strong>Tsinghua University</strong>, School of Economics and Management, B.A. in Economics, second bachelor's degree</div></div>
  <div class="home-card"><div class="home-date">2019.05 - 2022.07</div><div class="home-detail"><strong>Tsinghua University</strong>, Department of Automation, B.E. in Automation</div></div>
  <div class="home-card"><div class="home-date">2017.09 - 2019.05</div><div class="home-detail"><strong>Tsinghua University</strong>, Mechanical Engineering broad category</div></div>
</section>

<section class="home-section">
  <div class="home-section-title"><i class="fas fa-flask" aria-hidden="true"></i><span>Research Experience</span></div>
  <div class="home-card"><div class="home-date">2025.11 - Present</div><div class="home-detail"><strong>ByteDance Seed</strong>, Research Intern, Data for software engineering (SWE)</div></div>
  <div class="home-card"><div class="home-date">2024.09 - 2025.09</div><div class="home-detail"><strong>Microsoft Research Asia</strong>, Research Intern, Repository-level coding</div></div>
  <div class="home-card"><div class="home-date">2021.07 - 2021.09</div><div class="home-detail"><strong>MoonShot Team, Recurrent AI</strong>, Research Intern, zero-shot learning and prompt tuning</div></div>
</section>

<section class="home-section">
  <div class="home-section-title"><i class="fas fa-newspaper" aria-hidden="true"></i><span>Publications</span></div>
  <details class="pub-group" open>
    <summary>First-author Publications</summary>
    <div class="pub-list">
      <div class="pub-card"><span class="pub-tag">ICSME 2026, CCF-B</span><div><div class="pub-title">SWE-Ext: Scaling and Extending Augmented Data for Mid-Training of Repository-Level Coding Tasks</div><div class="pub-authors"><strong>Wei Li</strong>, X. Zhang, S. Wei, Y. Gao, Z. Guo, W. Luo, F. Song, Y. Huang, and H. Wang.</div></div></div>
      <div class="pub-card"><span class="pub-tag">ACL 2025, CCF-A</span><div><div class="pub-title">FEA-Bench: A Benchmark for Evaluating Repository-Level Code Generation for Feature Implementation</div><div class="pub-authors"><strong>Wei Li</strong>, X. Zhang, Z. Guo, S. Mao, W. Luo, G. Peng, Y. Huang, H. Wang, and S. Li.</div></div></div>
      <div class="pub-card"><span class="pub-tag">NAACL 2025, CCF-B</span><div><div class="pub-title">Explanation based In-Context Demonstrations Retrieval for Multilingual Grammatical Error Correction</div><div class="pub-authors"><strong>Wei Li</strong>, W. Luo, G. Peng, and H. Wang.</div></div></div>
      <div class="pub-card"><span class="pub-tag">ACL 2024, CCF-A</span><div><div class="pub-title">Detection-Correction Structure via General Language Model for Grammatical Error Correction</div><div class="pub-authors"><strong>Wei Li</strong> and H. Wang.</div></div></div>
      <div class="pub-card"><span class="pub-tag">ACM MM 2021, CCF-A</span><div><div class="pub-title">Transformer-based Feature Reconstruction Network for Robust Multimodal Sentiment Analysis</div><div class="pub-authors">Z. Yuan* and <strong>Wei Li</strong>*, H. Xu, and W. Yu.</div></div></div>
    </div>
  </details>

  <details class="pub-group">
    <summary>Co-author Publications</summary>
    <div class="pub-list">
      <div class="pub-card"><span class="pub-tag">ICML 2026, CCF-A</span><div><div class="pub-title">Measuring and Mitigating Post-hoc Rationalization in Reverse Chain-of-Thought Generation</div><div class="pub-authors">G. Peng, Z. Chen, W. Luo, Y. Wen, <strong>Wei Li</strong>, R. Feng, R. Le, C. Yang, Z. An, et al.</div></div></div>
      <div class="pub-card"><span class="pub-tag">ACL 2026, CCF-A</span><div><div class="pub-title">Two Pathways to Truthfulness: On the Intrinsic Encoding of LLM Hallucinations</div><div class="pub-authors">W. Luo, G. Peng, <strong>Wei Li</strong>, S. Wei, F. Song, L. Wang, N. Yang, X. Zhang, J. Jin, et al.</div></div></div>
      <div class="pub-card"><span class="pub-tag">NeurIPS 2025, CCF-A</span><div><div class="pub-title">Time: A Multi-level Benchmark for Temporal Reasoning of LLMs in Real-world Scenarios</div><div class="pub-authors">S. Wei, <strong>Wei Li</strong>, F. Song, W. Luo, T. Zhuang, H. Tan, Z. Guo, and H. Wang.</div></div></div>
      <div class="pub-card"><span class="pub-tag">arXiv:2510.09535</span><div><div class="pub-title">Mitigating Overthinking through Reasoning Shaping</div><div class="pub-authors">F. Song, S. Wei, B. Gao, Y. Wang, W. Luo, <strong>Wei Li</strong>, L. Yao, W. Xiong, L. Chen, et al.</div></div></div>
      <div class="pub-card"><span class="pub-tag">ACL 2025, CCF-A</span><div><div class="pub-title">Odysseus Navigates the Sirens' Song: Dynamic Focus Decoding for Factual and Diverse Open-ended Text Generation</div><div class="pub-authors">W. Luo, F. Song, <strong>Wei Li</strong>, G. Peng, S. Wei, and H. Wang.</div></div></div>
      <div class="pub-card"><span class="pub-tag">ACL 2025, CCF-A</span><div><div class="pub-title">Learn to Memorize: Scalable Continual Learning in Semiparametric Models with Mixture-of-Neighbors Induction Memory</div><div class="pub-authors">G. Peng, T. Ge, W. Luo, <strong>Wei Li</strong>, and H. Wang.</div></div></div>
      <div class="pub-card"><span class="pub-tag">ACL 2025 Findings</span><div><div class="pub-title">Encode Errors: Representational Retrieval of In-Context Demonstrations for Multilingual Grammatical Error Correction</div><div class="pub-authors">G. Peng, <strong>Wei Li</strong>, W. Luo, and H. Wang.</div></div></div>
      <div class="pub-card"><span class="pub-tag">arXiv:2406.07070</span><div><div class="pub-title">Halludial: A Large-scale Benchmark for Automatic Dialogue-level Hallucination Evaluation</div><div class="pub-authors">W. Luo, T. Shen, <strong>Wei Li</strong>, G. Peng, R. Xuan, H. Wang, and X. Yang.</div></div></div>
    </div>
  </details>
</section>

<section class="home-section">
  <div class="home-section-title"><i class="fas fa-heart" aria-hidden="true"></i><span>Interests</span></div>
  <p>Outside research, I enjoy languages, photography, and tennis. In addition to Chinese and English, I have intermediate-to-advanced proficiency in Japanese (JLPT N2) and Korean (TOPIK Level 5). I have also explored French, German, Portuguese, Italian, Arabic, and Russian.</p>
</section>
