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

## 2019 Qualification Round Photo Slideshow

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics, including a description of Photo Slideshow (Section 3.2.6). The detailed modeling in the thesis covers other problems.

- **[Amplifying Human Performance in Combinatorial Competitive Programming](https://arxiv.org/pdf/2411.19744)**, P. Veličković, A. Vitvitskyi, L. Markeeva, B. Ibarz, L. Buesing, M. Balog, A. Novikov, Google DeepMind (2024).
  Uses FunSearch to evolve the scoring functions inside human-written greedy solutions for every Hash Code qualification round from 2015 to 2022. On Photo Slideshow, the evolved solution reaches the top percentile of competing teams.

- **[Побудова математичної моделі подачі контекстної інформації](https://essuir.sumdu.edu.ua/server/api/core/bitstreams/de37a40f-d035-48aa-a57b-36f98d38de5a/content)** (*Building a Mathematical Model for Presenting Contextual Information*), V. V. Shuryha, MSc thesis, Sumy State University (2019). In Ukrainian.
  Develops a fast, user-independent recommendation algorithm that orders items described by tags into a coherent sequence. It uses tag matrices, set intersections, and a directed tree, and is evaluated on the 80,000 tagged photos from the Hash Code 2019 dataset.

- **[Iterated Local Search with Genetic Algorithms for the Photo Slideshow Problem](https://link.springer.com/chapter/10.1007/978-3-031-26504-4_45)**, L. Arbneshi, K. Sylejmani, *Metaheuristics: 14th International Conference, MIC 2022*, Springer LNCS, pp. 537–543 (2023).
  A short conference paper that introduces the two-stage approach: a genetic algorithm builds an initial slideshow, and iterated local search then improves it.

- **[Automated Slideshow Design from a Set of Photos Based on a Hybrid Metaheuristic Approach](https://link.springer.com/article/10.1007/s43069-023-00261-0)**, L. Arbneshi, K. Sylejmani, N. Halili, E. Krasniqi, *Operations Research Forum*, 4, 75 (2023).
  The extended journal version of the MIC 2022 paper. It combines a genetic algorithm with iterated local search and compares the results against ILP and CP-SAT models. It matches the top competition results and sets new best scores on two of the four official instances. It also introduces 55 new instances and an instance generator. Code: [GA-ILS](https://github.com/labeatarbneshi/photo-slideshow), [ILP](https://github.com/ksylejmani/Photo-Slideshow-ILP), [CP-SAT](https://github.com/Ndriqim-H/Photo-SlideShow-CP-Sat-Solver).

## 2020 Qualification Round Book Scanning

- **[Amplifying Human Performance in Combinatorial Competitive Programming](https://arxiv.org/pdf/2411.19744)**, P. Veličković, A. Vitvitskyi, L. Markeeva, B. Ibarz, L. Buesing, M. Balog, A. Novikov, Google DeepMind (2024).
  Uses FunSearch to evolve the scoring functions inside human-written greedy solutions for every Hash Code qualification round from 2015 to 2022. On Book Scanning, the evolved solution beats the top human team's score.

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics and proposes a general modeling framework in Python. Chapter 6 models Book Scanning in detail with a two-phase approach and evaluates it on the competition instances.

- **[Optimization of the Book Scanning Problem via Iterated Local Search and Genetic Algorithms](https://ceur-ws.org/Vol-4044/paper14.pdf)**, D. Alija, M. Kryeziu, E. Hoda, L. Islami, L. Mustafa, Y. Berisha, K. Sylejmani, A. Ahmeti, L. Arbneshi, *RTA-CSIT 2025*, CEUR Workshop Proceedings, Vol. 4044 (2025).
  A short paper that formulates Book Scanning as a set-packing problem with time and capacity constraints and gives a MILP model. It builds initial solutions with GRASP and improves them with either iterated local search or a genetic algorithm. Both are evaluated on the competition and synthetic instances; the GA matches or beats the best-known results on most instances, with less variation between runs.

## 2021 Qualification Round Traffic Signaling

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics, including a description of Traffic Signaling (Section 3.2.8). The detailed modeling in the thesis covers other problems.

- **[Amplifying Human Performance in Combinatorial Competitive Programming](https://arxiv.org/pdf/2411.19744)**, P. Veličković, A. Vitvitskyi, L. Markeeva, B. Ibarz, L. Buesing, M. Balog, A. Novikov, Google DeepMind (2024).
  Uses FunSearch to evolve the scoring functions inside human-written greedy solutions for every Hash Code qualification round from 2015 to 2022. On Traffic Signaling, the evolved solution beats the top human team's score.

- **[Solving the Traffic Signaling Problem Using the Iterated Local Search Metaheuristic](https://link.springer.com/article/10.1007/s42452-025-07054-6)**, E. Misini, U. Lajçi, K. Sylejmani, A. Limani, F. Gashi, L. Kurtaj, A. Ahmeti, E. Krasniqi, *Discover Applied Sciences*, 7, 792 (2025).
  Solves the problem with iterated local search, using a neighborhood of two basic moves and their guided and greedy variants, hill climbing within each iteration, and a perturbation operator. It is evaluated on 48 instances (5 from the competition and 43 new ones) and ranks first on 8 of them within 30 minutes.

- **[Metaheuristic Techniques for Automated Traffic Light Scheduling to Minimize Commute Time](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5470833)**, U. Lajçi, A. Limani, E. Misini, F. Gashi, K. Sylejmani, A. Ahmeti, *Proceedings of PATAT 2024* (14th International Conference on the Practice and Theory of Automated Timetabling), extended abstract (2024).
  Compares iterated local search with an evolutionary algorithm on the same 48 instances. Both are competitive with Shporer's greedy solver and together set new best results on 12 instances.

- **[Smart Traffic Signal Optimization with an Artificial Bee Colony Algorithm](https://www.researchgate.net/profile/Uran-Lajci/publication/413738394_Smart_Traffic_Signal_Optimization_with_an_Artificial_Bee_Colony_Algorithm/links/6a929c3a7e8edd1da26fb446/Smart-Traffic-Signal-Optimization-with-an-Artificial-Bee-Colony-Algorithm.pdf)**, A. Limani, K. Sylejmani, U. Lajçi, E. Misini, E. Krasniqi, B. Krasniqi, University of Prishtina, poster.
  Applies an Artificial Bee Colony algorithm in seven variants. The strongest variant starts from Shporer's greedy solution and sets 23 new best results on the 48-instance benchmark.

- **[Traffic Signal Optimization](https://dspace.cuni.cz/handle/20.500.11956/206702)** ([PDF](https://davidruda.github.io/bachelor-thesis/thesis.pdf)), D. Ruda, BSc thesis, Charles University, Prague (2025).
  Builds a fast simulator for evaluating solutions and uses it to compare a genetic algorithm, hill climbing, and simulated annealing on the competition datasets. It reaches new best scores on two datasets.

- **[Building a Simulator and Emulator for Traffic Signaling](https://victorzxy.github.io/project/traffic-sim/TrafficSim-Report.pdf)**, W. Li, Y. Sun, X. Zhao, University of Cambridge, project report.
  Builds a microscopic traffic simulator that accepts the Hash Code 2021 input format, then uses Bayesian optimization to search for signal schedules. It compares four scheduling schemes.

## 2022 Qualification Round Mentorship and Teamwork

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics, including a description of Mentorship and Teamwork (Section 3.2.9). The detailed modeling in the thesis covers other problems.

- **[Amplifying Human Performance in Combinatorial Competitive Programming](https://arxiv.org/pdf/2411.19744)**, P. Veličković, A. Vitvitskyi, L. Markeeva, B. Ibarz, L. Buesing, M. Balog, A. Novikov, Google DeepMind (2024).
  Uses FunSearch to evolve the scoring functions inside human-written greedy solutions for every Hash Code qualification round from 2015 to 2022. On Mentorship and Teamwork, the evolved solution beats the top human team's score; the paper also uses this problem's scoring function as its worked example (Figure 2).

- **[Iterated Local Search with Random Restarts for the Mentorship and Teamwork Problem](https://doi.org/10.5281/zenodo.23440031)**, U. Lajçi, E. Misini, K. Sylejmani, L. Arbneshi, University of Prishtina, conference presentation, AlbShkenca, Kosovo (2023). In Albanian.
  Builds an initial assignment of engineers to projects with a greedy method, then improves it with iterated local search using engineer-swap, project-removal, and project-insertion moves, plus random restarts. Results are compared against publicly available competition solutions.

## 2014 Final Round Street View Routing

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics, including a description of Street View Routing (Section 3.2.1).

## 2015 Final Round Project Loon

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics, including a description of Project Loon (Section 3.2.2).

## 2016 Final Round Satellites

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics, including a description of Satellites (Section 3.2.3).

## 2017 Final Round Router Placement

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics, including a description of Router Placement (Section 3.2.4).

- **[Genetic Algorithms and Greedy-Randomized Adaptive Search Procedure for Router Placement Problem in Wireless Networks](https://journals.sagepub.com/doi/abs/10.3233/JHS-190616)**, K. Sylejmani, A. Kadriu, E. Ilazi, B. Krasniqi, *Journal of High Speed Networks*, 25(3), 273–300 (2019).
  Gives an ILP formulation of the problem and solves it with a genetic algorithm and with GRASP. Both use moves that add, remove, jump, and shift routers, plus an operator that shifts routers intelligently within a neighborhood. On the four competition instances, both approaches are competitive with the best published results.

## 2018 Final Round City Plan

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics, including a description of City Plan (Section 3.2.5).

## 2019 Final Round Compiling Google

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics, including a description of Compiling Google (Section 3.2.6).

## 2020 Final Round Assembling Smartphones

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics, including a description of Assembling Smartphones (Section 3.2.7).

## 2021 Final Round Software Engineering at Scale

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics, including a description of Software Engineering at Scale (Section 3.2.8).

## 2022 Final Round Santa Tracker

- **[Principled Modeling of the Google Hash Code Problems for Meta-Heuristics](https://estudogeral.uc.pt/retrieve/265403/tese_final_pedro_rodrigues.pdf)**, P. M. D. Rodrigues, MSc thesis, University of Coimbra (2023).
  Analyzes all Hash Code problems from 2014 to 2022 as benchmarks for metaheuristics, including a description of Santa Tracker (Section 3.2.9).  
