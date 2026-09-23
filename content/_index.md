---
title: ''
date: '2026-09-22'
type: landing
sections:
- block: about.biography
  id: about
  content:
    title: About Me
    username: admin
- block: experience
  id: research
  content:
    title: Research
    date_format: Jan 2006
    items:
    - title: Reinforcement Learning for Quantum Gate Control with Zero-Shot Generalization
      company: 'Stony Brook University · Advisors: Prof. Ji Liu & Prof. Hyeongrak Choi'
      company_url: ''
      location: Stony Brook, NY, USA
      date_start: '2026-04-01'
      date_end: ''
      description: '- Demonstrated zero-shot generalization across arbitrary two-qubit gates, with mean average gate fidelity
        above **0.98** and a **tenfold reduction in gate error** relative to an analytical baseline.

        - Built a pulse-level control workflow combining reinforcement learning, Walsh-function-based calibration, and projection-based
        observations; evaluated robustness under modeled non-Markovian detuning noise.

        - Ran parameter sweeps with Slurm and aggregated simulation results for analysis.'
    - title: Distributed Variational Quantum Linear Solver
      company: 'Stony Brook University · Advisor: Prof. Ji Liu'
      company_url: ''
      location: Stony Brook, NY, USA
      date_start: '2025-09-01'
      date_end: '2026-03-01'
      description: '- Designed a distributed solver for systems of dimension **2<sup>50</sup> × 2<sup>50</sup>**, using block
        matrix partitioning and local linear combination of unitaries (LCU) decompositions, coordinated through DIGing and
        collective Adam.

        - Derived a distributed least-squares formulation and local quantum cost functions, using Hadamard tests and parameter-shift
        gradients.

        - Demonstrated scaling with the number of agents in PennyLane simulations, including **51-qubit MPS simulation**,
        while tolerating sparse communication graphs.


        [Read the preprint →](https://arxiv.org/abs/2604.01426)'
    - title: Federated Variational Quantum Linear Solver
      company: 'Stony Brook University · Advisor: Prof. Ji Liu'
      company_url: ''
      location: Stony Brook, NY, USA
      date_start: '2025-09-01'
      date_end: '2026-04-01'
      description: '- Developed a federated VQLS protocol with LCU decomposition of private submatrices on local NISQ clients
        and a classical server coordinating parameter updates.

        - Showed in PennyLane simulations that increasing the client pool expands the solvable linear system dimension beyond
        a single NISQ processor.'
    - title: Machine-Learned Jet Time and Trackless Jet Vertexing
      company: 'University of Minnesota · Advisor: Prof. Zhen Liu'
      company_url: ''
      location: Minneapolis, MN, USA
      date_start: '2023-06-01'
      date_end: '2024-05-01'
      description: '- Combined collider timing data with deep learning to achieve jet-time precision **four times better**
        than prior work.

        - Built a time-based model for reconstructing displaced vertices and a data-generation, normalization, and parameter-scan
        workflow using TensorFlow and C++.'
    - title: Machine Learning for Top Quark Effective Theory
      company: 'Fudan University · Advisor: Prof. Jiayin Gu'
      company_url: ''
      location: Shanghai, China
      date_start: '2023-04-01'
      date_end: '2024-05-01'
      description: Integrated neural networks with the SMEFT framework to tighten constraints on new-physics couplings through
        learned likelihood scores and Fisher information.
  design:
    columns: '2'
- block: collection
  id: publications
  content:
    title: Publications & Preprints
    filters:
      folders:
      - publication
  design:
    columns: '2'
    view: citation
- block: experience
  id: experience
  content:
    title: Experience
    date_format: Jan 2006
    items:
    - title: Research Assistant
      company: Stony Brook University · Applied Mathematics & Statistics
      company_url: ''
      location: Stony Brook, NY, USA
      date_start: '2026-01-01'
      date_end: ''
      description: 'Advisor: [Prof. Ji Liu](https://sites.google.com/site/jiliucontrol). Research in distributed quantum computing,
        reinforcement learning, and quantum control.'
    - title: Teaching Assistant · Fundamentals of Computing
      company: 'Stony Brook University · Instructor: Prof. Chenyu You'
      company_url: ''
      location: Stony Brook, NY, USA
      date_start: '2025-08-01'
      date_end: '2026-01-01'
      description: Led office hours and live code walkthroughs for a **40-student** computing course, helping students diagnose
        programming errors and understand MATLAB, Python, and C++ implementations.
    - title: Visiting Scholar
      company: University of Minnesota · School of Physics and Astronomy
      company_url: ''
      location: Minneapolis, MN, USA
      date_start: '2023-06-01'
      date_end: '2023-08-01'
      description: 'Advisor: [Prof. Zhen Liu](https://zhenliu.net/). Worked with Energy Flow Networks, SHAP, deep learning,
        and particle physics tools.'
  design:
    columns: '2'
- block: markdown
  id: skills
  content:
    title: Skills & Coursework
    text: "**Quantum algorithms**  \nDistributed and variational algorithms, quantum linear solvers, LCU decomposition, circuit\
      \ simulation · Qiskit, PennyLane, QuTiP\n\n**Machine learning & optimization**  \nPyTorch, TensorFlow · Deep reinforcement\
      \ learning (DDPG / PPO / GRPO), distributed optimization, Monte Carlo methods, numerical methods for PDEs\n\n**Programming\
      \ & computing**  \nPython (NumPy, SciPy, Matplotlib), C/C++, MATLAB, Mathematica, Lean 4 · Linux, Git, Docker, Slurm\n\
      \n**AI research tools**  \nMCP server development, graph engineering, autonomous theorem proving\n\n### Selected coursework\n\
      Quantum Programming and Quantum Information Science with Prof. Tzu-Chieh Wei, including presentations on HHL, quantum\
      \ singular value transformation (QSVT), and the general parameter-shift rule.\n\nReinforcement Learning · Natural Language\
      \ Processing · Numerical Linear Algebra · Numerical Methods for PDEs · Foundations of Numerical Analysis"
  design:
    columns: '2'
- block: markdown
  id: community
  content:
    title: Academic Community
    text: "### Conferences\n- **IEEE Quantum Week (QCE 2026)** · Attendee  \n  Toronto, Canada · September 2026\n- **SIAM\
      \ New York–New Jersey–Pennsylvania Section Annual Conference** · Attendee  \n  State College, PA · November 2025\n\n\
      ### Awards & leadership\n- **Outstanding Graduates Scholarship, 3rd Prize** · Fudan University, 2024\n- **Physics Major\
      \ Scholarship** · Fudan University, 2023\n- **Youth Committee Member** · Fudan University New York Alumni Association,\
      \ 2024–present"
  design:
    columns: '2'
- block: contact
  id: contact
  content:
    title: Contact
    text: For research collaborations and quantum research or engineering internship opportunities, please get in touch.
    email: tong.shen.1@stonybrook.edu
    address:
      city: Stony Brook
      region: NY
      country: United States
      country_code: US
    contact_links:
    - icon: github
      icon_pack: fab
      name: GitHub
      link: https://github.com/VacuumFreezer
    - icon: linkedin
      icon_pack: fab
      name: LinkedIn
      link: https://www.linkedin.com/in/tong-shen-b14436306
    autolink: true
  design:
    columns: '2'
---

