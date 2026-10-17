# google-hashcode-literature
A curated list of academic literature on Google Hash Code problems: theses, research papers, conference presentations, and more, organized by problem. Unofficial and community-maintained.

## 2017 Practice Round Pizza

- **[Proceedings of the XCSP3 Competition 2023](https://arxiv.org/pdf/2312.05877)**, G. Audemard, C. Lecoutre, E. Lonca (2023).
  Proceedings of the XCSP3 constraint-solving competition, where Pizza was one of the optimization benchmarks used to evaluate solvers. Section 2.2.7 (pp. 40–41) gives a PyCSP3 constraint model of the problem and a random instance generator.

## 2020 Practice Round More Pizza

No published academic literature yet. Know of one? [Open an issue or pull request](../../issues).

## 2021 Practice Round Even More Pizza

No published academic literature yet. Know of one? [Open an issue or pull request](../../issues).

## 2022 Practice Round One Pizza

No published academic literature yet. Know of one? [Open an issue or pull request](../../issues).

## 2015 Qualification Round Optimize a Data Center

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics and proposes a general modeling framework in Python. Chapter 5 models Optimize a Data Center in detail and solves it with heuristic construction, beam search, and iterated local search.

- **[Amplifying Human Performance in Combinatorial Competitive Programming](https://arxiv.org/pdf/2411.19744)**, P. Veličković, A. Vitvitskyi, L. Markeeva, B. Ibarz, L. Buesing, M. Balog, A. Novikov, Google DeepMind (2024).
  Uses FunSearch to evolve the scoring functions inside human-written greedy solutions for every Hash Code qualification round from 2015 to 2022. On Optimize a Data Center, the evolved solution beats the top human team's score.

- **[Algorithm Discovery With LLMs: Evolutionary Search Meets Reinforcement Learning](https://arxiv.org/pdf/2504.05108)**, A. Surina, A. Mansouri, L. Quaedvlieg, A. Seddas, M. Viazovska, E. Abbe, C. Gulcehre, EPFL (2025).
  Introduces EvoTune, which combines LLM-based evolutionary search with reinforcement-learning fine-tuning of the LLM. The Data Center problem is one of its benchmarks, where EvoTune scores 418, above FunSearch's 414 and the top human score of 407.

## 2016 Qualification Round Drone Delivery

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics, including a description of Drone Delivery (Section 3.2.3). The detailed modeling in the thesis covers other problems.

- **[Applied Routing Problem for a Fleet of Delivery Drones Using a Modified Parallel Genetic Algorithm](https://applmathjournal.spbu.ru/article/view/18072/11577)**, A. Markelova, A. Allahverdyan, A. Martemyanov, I. Sokolova, O. Petrosian, M. Svirkin, *Vestnik of Saint Petersburg University. Applied Mathematics. Computer Science. Control Processes*, 18(1), 135–148 (2022).
  Formulates the problem as a split-delivery, multi-depot, multi-trip, multi-product vehicle routing problem. It solves the problem with a mixed-dimensional parallel genetic algorithm (MDPGA), which shortens drone travel distance by 10–30% compared with a greedy solution.

- **[A Heuristics Based Approach for Optimizing Delivery Schedule of an Unmanned Aerial Vehicle (Drone) Based Delivery System](https://ieeexplore.ieee.org/abstract/document/8593145)**, V. Yadav, A. Narasimhamurthy, BITS Pilani Hyderabad, IEEE ICAPR (2017).
  Proposes and compares several greedy scheduling heuristics for minimizing the total delivery time. It evaluates them on simulated instances and on the Hash Code 2016 qualification dataset.

- **[Amplifying Human Performance in Combinatorial Competitive Programming](https://arxiv.org/pdf/2411.19744)**, P. Veličković, A. Vitvitskyi, L. Markeeva, B. Ibarz, L. Buesing, M. Balog, A. Novikov, Google DeepMind (2024).
  Uses FunSearch to evolve the scoring functions inside human-written greedy solutions for every Hash Code qualification round from 2015 to 2022. On Drone Delivery, the evolved solution reaches the top percentile of competing teams.

## 2017 Qualification Round Streaming Videos

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics, including a description of Streaming Videos (Section 3.2.4). The detailed modeling in the thesis covers other problems.

- **[Amplifying Human Performance in Combinatorial Competitive Programming](https://arxiv.org/pdf/2411.19744)**, P. Veličković, A. Vitvitskyi, L. Markeeva, B. Ibarz, L. Buesing, M. Balog, A. Novikov, Google DeepMind (2024).
  Uses FunSearch to evolve the scoring functions inside human-written greedy solutions for every Hash Code qualification round from 2015 to 2022. On Streaming Videos, the evolved solution reaches the top percentile of competing teams.

- **[Towards Efficient Solvers for Optimisation Problems](https://ieeexplore.ieee.org/abstract/document/8752700)**, H.-P. Vo, Uppsala University, IEEE/ACM CCGRID (2019).
  Models Streaming Videos as a bin-packing problem in MiniZinc in two ways: one built on heuristics and one built on global constraints. It benchmarks both models on five constraint-programming and MIP solvers, comparing running time and final score on the Hash Code instances.

- **[Towards Efficient Algorithms for Constraint Satisfaction Problems](https://easychair.org/publications/preprint/Vk7H)**, H.-P. Vo, EasyChair Preprint no. 1732 (2019).
  A preprint by the same author that applies the same MiniZinc modeling and solver benchmarking to Streaming Videos.
  
## 2018 Qualification Round Self-Driving Rides

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics, including a description of Self-Driving Rides (Section 3.2.5). The detailed modeling in the thesis covers other problems.

- **[Amplifying Human Performance in Combinatorial Competitive Programming](https://arxiv.org/pdf/2411.19744)**, P. Veličković, A. Vitvitskyi, L. Markeeva, B. Ibarz, L. Buesing, M. Balog, A. Novikov, Google DeepMind (2024).
  Uses FunSearch to evolve the scoring functions inside human-written greedy solutions for every Hash Code qualification round from 2015 to 2022. On Self-Driving Rides, the evolved solution beats the top human team's score.

- **[Algorithm Discovery With LLMs: Evolutionary Search Meets Reinforcement Learning](https://arxiv.org/abs/2504.05108)**, A. Surina, A. Mansouri, L. Quaedvlieg, A. Seddas, M. Viazovska, E. Abbe, C. Gulcehre, EPFL (2025).
  Introduces EvoTune, which combines LLM-based evolutionary search with reinforcement-learning fine-tuning of the LLM. On Self-Driving Rides it evolves the function that picks each car's next ride and reaches the 87.6th percentile of human teams, slightly ahead of FunSearch's 87.1th, though neither beats the top team.







  
