---
title: ''
summary: 'Zhan Dai (戴栈), Fudan mathematics undergraduate and UCLA exchange student. Research in optimization, neural networks, quantitative modeling, and power systems.'
date: 2026-05-30
lastmod: 2026-09-29
type: landing

sections:
  # ==========================================
  # Block 1. 个人简介 (Hardcore Biography)
  # ==========================================
  - block: resume-biography-3
    content:
      username: me
      text: |
        As an undergraduate student at the School of Mathematical Sciences, Fudan University, my academic foundation is built upon rigorous mathematical training, including Ordinary Differential Equations, Point-Set Topology, and Real/Complex Analysis. 

        **Academic profile:** GPA **3.88/4.00**, **top 15%** at Fudan. Applied Mathematics exchange at **UCLA (Sep–Dec 2026)**, with coursework in graduate Probability Theory, graduate Equations of Mathematical Physics, and Optimization.

        My primary research ambition lies in **Neural Networks and Optimization Algorithms**, heavily grounded in Probability Theory. I am passionate about bridging theoretical mathematics with advanced computational models to solve critical bottlenecks in high-dimensional and complex systems. 

        **🔬 Research**
        *   **Urban Power Grid Hosting Capacity with Distributed Energy Resources (DER)** (Sep 2026–present): Researching power-flow algorithms using finite-element/Galerkin ideas, convergence analysis, and operator optimization. Preparing documentation for one planned invention patent.
        *   **Large-Scale Spatiotemporal Transcriptomic Dynamics Based on Graph-Regularized Unbalanced Flow Matching**: Research focus: algorithm optimization, mathematical derivation, and modeling continuous cellular dynamics.

        **💻 Technical Stack**
        *   Proficient in **Python** (Pandas, Matplotlib, Scikit-learn) for scientific computing, statistical analysis, and machine learning.
        *   Experienced in **LaTeX** for professional academic typesetting and algorithm documentation.
      button:
        text: Download latest CV (中文 PDF)
        url: /uploads/zhan-dai-cv.pdf
    design:
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  # ==========================================
  # Block 2. 实习经历 (带时间轴)
  # ==========================================
  - block: markdown
    id: internship
    content:
      title: '💼 Internship'
      text: |
        <div class="academic-timeline">
          <div class="timeline-item">
            <div class="timeline-date">Jul 2026<br>│<br>Sep 2026</div>
            <div class="timeline-content">
              <h3>ByteDance | ETF Mathematics Team Intern</h3>
              <ul>
                <li><strong>Mathematical Review:</strong> Reviewed Olympiad problems and model-generated solutions, checked proof completeness, and identified errors in critical derivation steps to improve training-data quality.</li>
                <li><strong>Data Annotation:</strong> Collaborated through Feishu, standardized mathematical notation and output formats, and applied multidimensional evaluation criteria to provide alignment feedback.</li>
              </ul>
            </div>
          </div>
          <div class="timeline-item">
            <div class="timeline-date">Apr 2026<br>│<br>Jul 2026</div>
            <div class="timeline-content">
              <h3>Soochow Securities | Quantitative Investment Intern</h3>
              <ul>
                <li><strong>Model Construction:</strong> Addressed the limitations of traditional multi-factor portfolios by introducing the maximum entropy principle, successfully constructing a multi-factor stock selection portfolio model with enhanced generalization capabilities.</li>
                <li><strong>Algorithm Derivation:</strong> Independently reviewed and optimized the original model framework, clarified the core logic, and drafted standardized algorithm analysis reports including mathematical derivations and flowcharts.</li>
                <li><strong>Work Results:</strong> Built a maximum entropy iterative portfolio architecture. The model's performance outperformed benchmark strategies (e.g., equal-weight addition). Produced underlying logic documentation and standard operating procedures.</li>
              </ul>
            </div>
          </div>
        </div>
    design:
      columns: '1'

  # ==========================================
  # Block 3. 项目经历 (带时间轴)
  # ==========================================
  - block: markdown
    id: projects
    content:
      title: '🔬 Projects'
      text: |
        <div class="academic-timeline">
          <div class="timeline-item">
            <div class="timeline-date">Sep 2026<br>│<br>Present</div>
            <div class="timeline-content">
              <h3>Urban Power Grid Hosting Capacity Assessment &amp; Optimization with DER</h3>
              <p class="project-role">Research Group Member · Ongoing research</p>
              <ul>
                <li><strong>Literature Review:</strong> Surveyed power-flow algorithms and the challenges of distributed energy resource integration, organized technical notes, and defined an algorithm research direction.</li>
                <li><strong>Algorithm Research:</strong> Investigating finite-element/Galerkin approaches to power-flow computation, convergence properties, and power-flow operator optimization to support dynamic hosting-capacity assessment.</li>
                <li><strong>Patent Preparation:</strong> Independently developing patent ideas and drafting documentation, with one invention patent planned. The algorithm design supports future prototype validation.</li>
              </ul>
            </div>
          </div>

          <div class="timeline-item">
            <div class="timeline-date">Mar 2026<br>│<br>May 2026</div>
            <div class="timeline-content">
              <!-- 🤖 这里去掉了 a 标签，恢复为纯文本标题 -->
              <h3>Research on the Employment Effects of Industrial Robots (Based on DTW-TWFE)</h3>
              <ul>
                <li><strong>Dynamic Heterogeneous Clustering:</strong> Introduced the Dynamic Time Warping (DTW) algorithm to measure the non-linear distance of industry automation penetration timelines. Combined with Ward hierarchical clustering and silhouette coefficients to study 12 manufacturing categories.</li>
                <li><strong>Non-linear Mechanism Estimation:</strong> Built a panel dataset using macro yearbooks and the IFR micro-database. Designed a Two-Way Fixed Effects (TWFE) variable-slope model with interaction terms, calculating the U-shaped theoretical inflection point.</li>
                <li><strong>Composite Time-Series Forecasting:</strong> Designed a composite forecasting architecture utilizing ARIMA for core robot density and Grey prediction models for small-sample capital intensity, evaluating predictions with MAE and MAPE.</li>
              </ul>
            </div>
          </div>

          <div class="timeline-item">
            <div class="timeline-date">Jan 2026<br>│<br>Feb 2026</div>
            <div class="timeline-content">
              <!-- 🔋 电池项目保留 PDF 跳转链接 -->
              <h3><a href="/uploads/battery.pdf" target="_blank" rel="noopener noreferrer" style="text-decoration: underline; color: inherit;">Smartphone Power Consumption Prediction Model (MCM)</a></h3>
              <ul>
                <li><strong>Mechanism Derivation & Modeling:</strong> Constructed an ECM-based continuous-time dynamic evolution framework. Established ODEs to quantify independent hardware power consumption and introduced an electro-thermal coupled feedback loop using the Arrhenius equation and Newton’s law of cooling.</li>
                <li><strong>Parameter Estimation & Simulation:</strong> Applied OLS for processor power features, the L-M algorithm for screen brightness non-linear power-law parameters, used trust-region reflective optimization, and built a discrete-time iteration framework in Python for coupled numerical integration.</li>
                <li><strong>Uncertainty Quantification:</strong> Used Monte Carlo simulation and global sensitivity analysis to assess hardware parameter tolerances and ambient temperature effects. Evaluated transient tracking under highly variable loads through residual analysis and statistical metrics.</li>
              </ul>
            </div>
          </div>

          <div class="timeline-item">
            <div class="timeline-date">Jan 2025<br>│<br>Feb 2025</div>
            <div class="timeline-content">
              <!-- 🏅 奥运项目保留 PDF 跳转链接 -->
              <h3><a href="/uploads/olympic.pdf" target="_blank" rel="noopener noreferrer" style="text-decoration: underline; color: inherit;">2028 Olympic Medal Prediction Model (MCM)</a></h3>
              <ul>
                <li><strong>High-Dimensional Feature Extraction:</strong> Designed a dual-algorithm pipeline: utilized linear regression to predict future participation scales, Random Forests to capture non-linear relationships, and built a Deep Neural Network in PyTorch.</li>
              </ul>
            </div>
          </div>
        </div>
    design:
      columns: '1'

# ==========================================
  # Block 4. 校园经历 (带时间轴)
  # ==========================================
  - block: markdown
    id: campus
    content:
      title: '🏫 Leadership'
      text: |
        <div class="leadership-card">
          <div class="leadership-backdrop" aria-hidden="true">
            <img src="/img/leader.jpg" alt="" loading="lazy" style="width: 100%; height: 100%; object-fit: cover; opacity: 0.4; filter: grayscale(80%); display: block; margin: 0;">
            <div class="leadership-shade"></div>
          </div>
          <div style="position: relative; z-index: 1;">
            <div class="academic-timeline">
              <div class="timeline-item">
                <div class="timeline-date">May 2026<br>│<br>Present</div>
                <div class="timeline-content">
                  <h3>Student Union, School of Mathematical Sciences | Presidium Member</h3>
                  <p>Serving on the Student Union presidium at Fudan University.</p>
                </div>
              </div>
              <div class="timeline-item">
                <div class="timeline-date">Sep 2025<br>│<br>Present</div>
                <div class="timeline-content">
                  <h3 style="margin-top: 0;">The 13th Siyuan Project, Fudan University | Core Member</h3>
                  <ul>
                    <li><strong>Custom Cultivation:</strong> Selected into this highly competitive 30-student university-level initiative; participated in tailored training to enhance management and strategic thinking.</li>
                    <li><strong>Social Horizon:</strong> Engaged in social practices, conducting collaborative field research with Siyuan members from peer universities.</li>
                  </ul>
                </div>
              </div>
              <div class="timeline-item">
                <div class="timeline-date">May 2025<br>│<br>May 2026</div>
                <div class="timeline-content">
                  <h3>Student Union, School of Mathematical Sciences | Head of Liaison Dept.</h3>
                  <ul>
                    <li><strong>External Outreach:</strong> Connected with off-campus enterprises, leading negotiations to secure sponsorships that supported over 10 department-level events.</li>
                    <li><strong>Cross-Department Collaboration:</strong> Spearheaded inter-departmental collaborations, expanding event reach.</li>
                  </ul>
                </div>
              </div>
              <div class="timeline-item">
                <div class="timeline-date">Sep 2024<br>│<br>Present</div>
                <div class="timeline-content">
                  <h3>Class Monitor | Class 2, Grade 2024, SMS</h3>
                  <ul>
                    <li>Managed academic notices and closely coordinated core administrative processes including merit scholarships.</li>
                  </ul>
                </div>
              </div>
              <div class="timeline-item">
                <div class="timeline-date">Sep 2024<br>│<br>Jun 2025</div>
                <div class="timeline-content">
                  <h3>Student Union, School of Mathematical Sciences | Art Dept. Member</h3>
                  <ul>
                    <li>Co-organized large-scale school cultural events, overseeing early-stage program recruitment and on-site logistics.</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
    design:
      columns: '1'

  # ==========================================
  # Block 5. 技能与荣誉
  # ==========================================
  - block: skills
    id: skills
    content:
      username: me
      title: Skills & Languages
    design:
      columns: '1'

  - block: markdown
    id: awards
    content:
      title: 'Honors & Awards'
      text: |
        - **Honorable Mention**, Mathematical Contest in Modeling (MCM).
        - **Second Prize, Shanghai**, Statistical Modeling Competition.
        - **Second Prize, Zhejiang Province**, National High School Mathematics League; **First Prize in the preliminary round**.
        - **First-class Named Scholarship**, School of Mathematical Sciences, Fudan University.
        - **Outstanding Communist Youth League Member** and **Outstanding Student Cadre**, Fudan University.
    design:
      columns: '1'
---
