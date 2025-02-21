# Research Values Codebook

This codebook provides a framework for analyzing values expressed in computer science research papers, developed through iterative qualitative coding to identify commonly occurring research values. While not exhaustive of all possible values in computer science research, it captures 10 key recurring values: Performance, Novelty, Efficiency, Generalizability, Understanding, Simplicity, Fairness, Society, Openness, and Usability. For each value, we provide a clear definition and illustrative excerpts from papers that exemplify how these values are expressed in research writing. This resource is designed to help researchers better understand and identify the underlying values that shape computer science research contributions.

## Value Definitions and Examples

1. **Performance** refers to the effectiveness (success rate) of a method or model, often (but not always) in comparison to existing approaches with quantitative measures such as accuracy, loss, and error rate. Here are some example excerpts:
   - boost the accuracy
   - achieves results beyond the current state of the art results in F1
   - precision score inferior to the existing approach
   - decrease root mean squared error
   - reduce errors

2. **Novelty** refers to the pursuit of introducing new things to a field, often by resolving existing gaps in research, extending the boundaries, or opening up new possibilities. Here are some example excerpts:
    - propose / create / introduce / construct / develop / design / curate something
    - use a new / novel / innovative method
    - is the first attempt / work
    - enables new applications
    - resolves an open gap
    - open or constrain technological possibilities
    - very little attention has been paid to
    - there is a missed/unique opportunity
    - limitations of prior work
    - yields surprisingly interesting results
    - feasibility / previous methods are not feasible in doing something
    - demonstrate the superiority/advantages of our method (compared to existing methods)
    - compared to previous/existing/prior/SoTA work
    - achieves improvement on the previous work
    - on the contrary to existing methods
    - building on recent work

3. **Efficiency** refers to the ability to achieve desired outcomes with minimal resource expenditure, such as time, money, data, memory, storage, and computational power. Scalability is also part of efficiency, because it often seeks to handle large amounts of users, data, and traffic efficiently. Here are some example excerpts:
    - introduce an efficient / efficacious method
    - make the the inference speed faster / quicker
    - reduce the training / test time
    - using as few samples as possible
    - does not increase the number of parameters
    - solely by initializing a small fraction of layers locally
    - has lower costs compared to previous methods
    - reduces per-task storage and memory usage
    - prior work has higher time / space complexity
    - have parallelizable computation and light-weight structure
    - treats multiple pairs in a sentence simultaneously
    - propose distributed, “mini-batch”learners
    - scale up to millions of users
    - propose a power model
    - with a small runtime
    - reduce workloads of the server
    - costly / expensive to collect data

4. **Generalizability** refers to the ability to adapt and perform well across a wide range of tasks, conditions, and scenarios. Also known as generalization, universality, adaptability, robustness, flexibility, extensibility. Here are some example excerpts:
    - this algorithm has been successfully applied to a variety of tasks
    - generalize well to out-of-distribution (OOD) domains
    - use regularization to prevent overfitting to this dataset
    - representations are universally applicable across a wide array of tasks
    - can only deal with specific languages
    - adapt poorly to unseen tasks / situations
    - dynamically adapt
    - require very strong assumptions
    - shows a lack of flexibility
    - we test on two different datasets
    - our guidelines are widely applicable (labeled as generalizability because “widely”, but also label as usability for “applicable”)
    - extensive experiments and evaluations
    - unified / unifying 
    - across languages / cultures / populations
    - in/support both [scenario A] and [scenario B]
    - 2x better for small sets and 20% better for large sets
    - jointly solves

5. **Understanding** (Phenomenon Understanding & Theoretical Grounding) refers to understanding phenomena by (1) by providing empirical evidence and insights, (2) by citing, developing, and applying theories, proofs, and theoretical frameworks. Here are some example excerpts:
    - provide empirical evidence to Zipf's law
    - show extensive / systematic evidence to understand this phenomenon 
    - provide a proof of convergence
    - provide formal guarantees
    - build on the Complexity Theory in our work
    - propose a game theoretic framework
    - further our understanding of theory of mind by extending a theory of mind model
    - lack a theoretical basis
    - A first observation in the multi-body setting is that when treated naively, ghosting artifacts will emerge
    - We observe empirically that using the heuristic weight hyperparameter is not necessary with our method.
    - we adopt relational aesthetics as a lens for our study
    - we rely on four concepts (waiting, dependency, anxiety, and absence) introduced by Barthes
    - any discussion of time and space complexity such as using big O
    - proved correct
    - derive tight bounds
    - can be solved / solvable
    - expressions like “show”, “reveal”, “illustrate”, “observe”, “find”, “investigate” are very likely to be phenomenon findings. Ensure to check their contexts too.
    - mathematically
    - assurance of the correctness
    - accuracy guarantee
    - deep understanding
    - propose a concept
    - causal effects and correlation analysis
        - X be responsible for Y (causal analysis to understand mechanisms)
        - whether X plays a role in Y
        - study the relationship between A and B
        - measure the influence of A in B
        - highlight/show that X is important to Y
    - definition and characterization such as “we propose that the observed morpheme deletion is morphological, and that vowel elision is phonological”

6. **Simplicity** refers to the pursuit of creating simple and elegant methods, models, and theories that minimize complexity. Please do NOT include usefulness and easiness-to-use. Here are some example excerpts:
    - propose a simple method
    - simplifies the model architecture
    - existing methods are complex / complicated
    - assumptions, such as “the underlying model assumptions are justified”
    - using the heuristic weight hyperparameter is not necessary
    - BERT requires two pretraining tasks but we find that next sentence prediction is unnecessary
    - Convert a new task to an existing problem
    - the first work to provide an approximate aggregate result with an effective accuracy guarantee, and without relying on factoid queries
    - there exists an elegant and uniform solution

7. **Fairness** (Fairness, Bias, Privacy & Ethics) refers to the commitment to promote equity and social justice, avoid social bias, ensure privacy and security, and address ethical issues in the use of computer technologies. Here are some example excerpts:
    - propose a procedural justice framework
    - reduce algorithmic accountability
    - mitigate the problem of bias in algorithms
    - reduce both gender and racial prejudice
    - preserve user privacy
    - improve cyber security
    - introduces ever-increasing security and privacy risks
    - discuss the ethical implications
    - they fail to detect attacks using different protocols
    - equal opportunity
    - risk assessment practices
    - leak of 600GB worth of logs
    - anti-malware

8. **Society** (Societal Implications) refer to the potential of research to impact social change, promote well-being, and address challenges faced by societies and communities. We focus on societal level impacts, instead of individual-level usability. Please do NOT include user experience. Here are some example excerpts:
    - promoting their socio-emotional wellbeing
    - implications for technology development
    - revolutionary changes in the workplace
    - improve and broaden undergraduate STEM education
    - empower youth to participate in civic engagement
    - recommend the following policy to combat misinformation
    - pose an important challenge for social correction approaches
    - present potential downstream consequences
    - We contribute a way of looking at activism online
    - Discussion about well-being and healthcare such as “immune systems”, “disease”, “symptoms”, etc
        - improve these symptoms
    - a group (stakeholders) is involved, e.g., “educators”, “students”, “playtesters”, “residents”, “researchers”
    - discussions on governance and policies
    - a real-world censorship ecosystem
    - improve rigor and reproducibility of experimental games research within the CHI PLAY community
    - We also learned the most appropriate functions for robots in nursing homes were helping with minor tasks and encouraging social interaction among residents.

9. **Openness** (Openness, Reproducibility, Collaboration, & Future Work) refers to promoting open science (keeping transparent and sharing information about research procedures, data, methods, and results), reproducibility (ensuring others can repeat the process to obtain the same results), collaboration across different fields, and discussions of future work. Here are some example excerpts:
    - promote the practice of open science
    - increase transparency about data use
    - increasing transparency of product
    - data and code are open sourced / shared
    - code is available for future reproducibility
    - reproduce classic results in modern settings
    - could not replicate the results of prior work
    - we propose a research agenda for future work
    - Interdisciplinary collaboration
    - expose the problems for the research community
    - MOOC

10. **Usability** refers to the commitment to improve user experience and real-world applications by making systems more user-friendly, easy-to-use, interpretable, engaging, popular, inclusive, and accessible. Here are some example excerpts:
    - increase the usability
    - easy to use / implement / work with
    - make the model more explicable / interpretable / explainable
    - lower accessibility barriers
    - model requires no human-crafted features
    - promoting multi-party interactions
    - making user interaction socially engaging
    - make our toolkit more inclusive / popular
    - making them nearly inaccessible
    - with a high degree of automation
    - automatic
    - our guidelines are widely applicable (labeled as generalizability because “widely”, but also label as usability for “applicable”)
    - ALL user studies
        - “we test these environments with students in an online graduate program through surveys and a controlled experiment”
        - “relied on human intervention”
        - “validate the use cases via a pilot study”
    - the system is widely used / widely accepted
    - personalization / recommendation system / user preference
    - reliability
    - reusability
    - end to end
    - the increasing computational demands of the applications
    - understanding and alleviating application performance issues
    - can be used / applied to
    - production experience
    - enable [social group] to do good things
        - NOT: “enable miscreants to do business with each other and utilize others' resources.”
    - allow/making it easier someone to do something
        - “allowing researchers to redefine dynamically the granularity of their “web entities”
