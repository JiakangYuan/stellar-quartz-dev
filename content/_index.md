---
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: 'About Me'
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    id: news
    content:
      title: 'News'
      subtitle: ''
      text: |-
        - *2026.4*: Three papers (MME-Reasoning, VisualScore, and, SAPO) are accepted by <span style="color: var(--color-primary-600); font-weight: 600;">ICML 2026</span>. Two of them are about multimodal reasoning, another is about visual quality assessment.
        - *2026.4*: Bi3D++ is accepted by <span style="color: var(--color-primary-600); font-weight: 600;">IEEE T-PAMI 2026</span>.
        - *2026.4*: Our survey about reward hacking is out on arxiv and github. Feel free to check it.
        - *2026.4*: Two papers (FlowSearch and Controllable Memory Usage) are accepted by <span style="color: var(--color-primary-600); font-weight: 600;">ACL 2026</span>. One is about DeepResearch, the other is about agent memory.
        - *2026.3*: Intern-S1-Pro technical report is released.
        - *2026.2*: InternAgent-1.5 technical report is released.
        - *2025.12*: SciEvalKit (An Open-source Evaluation Toolkit for Scientific General Intelligence) is released.
        - *2025.10*: Codes of InternAgent 1.0 is released on github.

        <details>
        <summary style="cursor: pointer; color: var(--color-primary-600); font-weight: 500; margin-top: 8px;">Show more ↓</summary>


        - *2025.7*: SPOT is accepted by <span style="color: var(--color-primary-600); font-weight: 600;">IEEE T-PAMI 2025</span>.
        - *2025.6*: Two papers (Lumina Image 2.0 and Chimera) are accepted by <span style="color: var(--color-primary-600); font-weight: 600;">ICCV 2025</span>.
        - *2025.5*: Two papers (SurveyForge and Dolphin) are accepted by <span style="color: var(--color-primary-600); font-weight: 600;">ACL 2025</span>.
        - *2025.5*: We release InternAgent (NovelSeek), a unified closed-loop multi-agent framework for Automatic Scientific Research.
        - *2025.2*: One paper (CST-Stereo) is accepted by <span style="color: var(--color-primary-600); font-weight: 600;">CVPR 2025</span>.
        - *2024.12*: One paper (GeoX) is accepted by <span style="color: var(--color-primary-600); font-weight: 600;">ICLR 2025</span>      
        - *2024.12*: One paper (AIOStereo) is accepted by <span style="color: var(--color-primary-600); font-weight: 600;">AAAI 2025</span>.
        - *2024.10*: I receive the <span style="color: var(--color-primary-600); font-weight: 600;">National Scholarship</span>.
        - *2024.09*: Two papers (AdaptiveDiffusion and 3DET-Mamba) are accepted by <span style="color: var(--color-primary-600); font-weight: 600;">NeurIPS 2024</span>.
        - *2024.07*: One paper (Reg-TTA3D) is accepted by <span style="color: var(--color-primary-600); font-weight: 600;">ECCV 2024</span>.
        - *2024.01*: One paper (ReSimAD) is accepted by <span style="color: var(--color-primary-600); font-weight: 600;">ICLR 2024</span>.
        - *2023.09*: One paper (AD-PT) is accepted by <span style="color: var(--color-primary-600); font-weight: 600;">NeurIPS 2023</span>.
        - *2023.02*: Two papers (Bi3D and Uni3D) are accepted by <span style="color: var(--color-primary-600); font-weight: 600;">CVPR 2023</span>.
        - *2022.07*: One paper (HelixFormer) is accepted by <span style="color: var(--color-primary-600); font-weight: 600;">ACM'MM 2022</span>.

        </details>
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: 'max-w-none'
  - block: collection
    id: publications
    content:
      title: Selective Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: paper-box
      columns: 1
  - block: markdown
    content:
      title: ''
      text: |-
        <div style="text-align: center; margin-top: -10px;">
          <a href="/publications/" class="see-all-btn" style="display: inline-flex; align-items: center; gap: 8px; padding: 10px 24px; border-radius: 8px; border: 1px solid var(--color-primary-200); color: var(--color-primary-600); font-weight: 500; text-decoration: none; transition: all 0.3s;">See All Publications →</a>
        </div>
    design:
      columns: '1'
      spacing:
        padding: ['0', '0', '20px', '0']
  - block: resume-experience
    id: educations
    content:
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: true
  - block: markdown
    id: talks
    content:
      title: 'Invited Talks'
      subtitle: ''
      text: |-
        - **Efficient Pre-training of Autonomous Driving**, 2023.09 — [Watch Video](https://www.bilibili.com/video/BV1e8411C7ZK/?spm_id_from=333.337.search-card.all.click&vd_source=478510f65af6875433547b21fe148987)
        - **Towards 3D General Representation**, Techbeat, 2023.07 — [Watch Video](https://www.techbeat.net/talk-info?id=795)
        - **Transferability of Autonomous Driving**, 2023.03 — [Watch Video](https://www.bilibili.com/video/BV1Vo4y1b7pS/?spm_id_from=333.337.search-card.all.click)
    design:
      columns: '1'
  - block: markdown
    id: services
    content:
      title: 'Academic Services'
      subtitle: 'Reviewer'
      text: |-
        <div style="display: flex; flex-wrap: wrap; gap: 10px; justify-content: center;">
        <span style="display: inline-block; padding: 6px 16px; border-radius: 20px; background: var(--color-primary-50); color: var(--color-primary-700); font-weight: 700; border: 1px solid var(--color-primary-200); font-size: 14px;">CVPR</span>
        <span style="display: inline-block; padding: 6px 16px; border-radius: 20px; background: var(--color-primary-50); color: var(--color-primary-700); font-weight: 700; border: 1px solid var(--color-primary-200); font-size: 14px;">ICCV</span>
        <span style="display: inline-block; padding: 6px 16px; border-radius: 20px; background: var(--color-primary-50); color: var(--color-primary-700); font-weight: 700; border: 1px solid var(--color-primary-200); font-size: 14px;">ECCV</span>
        <span style="display: inline-block; padding: 6px 16px; border-radius: 20px; background: var(--color-primary-50); color: var(--color-primary-700); font-weight: 700; border: 1px solid var(--color-primary-200); font-size: 14px;">NeurIPS</span>
        <span style="display: inline-block; padding: 6px 16px; border-radius: 20px; background: var(--color-primary-50); color: var(--color-primary-700); font-weight: 700; border: 1px solid var(--color-primary-200); font-size: 14px;">ICML</span>
        <span style="display: inline-block; padding: 6px 16px; border-radius: 20px; background: var(--color-primary-50); color: var(--color-primary-700); font-weight: 700; border: 1px solid var(--color-primary-200); font-size: 14px;">ICLR</span>
        <span style="display: inline-block; padding: 6px 16px; border-radius: 20px; background: var(--color-primary-50); color: var(--color-primary-700); font-weight: 700; border: 1px solid var(--color-primary-200); font-size: 14px;">ACM'MM</span>
        <span style="display: inline-block; padding: 6px 16px; border-radius: 20px; background: var(--color-primary-50); color: var(--color-primary-700); font-weight: 700; border: 1px solid var(--color-primary-200); font-size: 14px;">T-PAMI</span>
        <span style="display: inline-block; padding: 6px 16px; border-radius: 20px; background: var(--color-primary-50); color: var(--color-primary-700); font-weight: 700; border: 1px solid var(--color-primary-200); font-size: 14px;">T-IP</span>
        <span style="display: inline-block; padding: 6px 16px; border-radius: 20px; background: var(--color-primary-50); color: var(--color-primary-700); font-weight: 700; border: 1px solid var(--color-primary-200); font-size: 14px;">T-CSVT</span>
        <span style="display: inline-block; padding: 6px 16px; border-radius: 20px; background: var(--color-primary-50); color: var(--color-primary-700); font-weight: 700; border: 1px solid var(--color-primary-200); font-size: 14px;">T-MM</span>
        </div>
    design:
      columns: '1'
---
