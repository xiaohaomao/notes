  A computer program is said to learn from experience E with respect to some task T and some performance measure P, if its performance on T, as measured by P, improves with experience E.


  * [**overview**](#overview)
  * [**theory**](#theory)
  * [**methods**](#methods)
  * [**representation learning**](#representation-learning)
  * [**program synthesis**](#program-synthesis)
  * [**meta-learning**](#meta-learning)
  * [**automated machine learning**](#automated-machine-learning)
  * [**interesting papers**](#interesting-papers)
    - [**theory**](#interesting-papers---theory)
    - [**automated machine learning**](#interesting-papers---automated-machine-learning)
    - [**systems**](#interesting-papers---systems)

----

  [**deep learning**](https://github.com/brylevkirill/notes/blob/master/Deep%20Learning.md)  
  [**reinforcement learning**](https://github.com/brylevkirill/notes/blob/master/Reinforcement%20Learning.md)  
  [**bayesian inference and learning**](https://github.com/brylevkirill/notes/blob/master/Bayesian%20Inference%20and%20Learning.md)  
  [**probabilistic programming**](https://github.com/brylevkirill/notes/blob/master/Probabilistic%20Programming.md)  
  [**causal inference**](https://github.com/brylevkirill/notes/blob/master/Causal%20Inference.md)  



---
### overview

  ["The Talking Machines"](http://thetalkingmachines.com/blog/) podcast `audio`

  overview by Igor Kuralenok ([first](https://youtu.be/ynS7XvkAdLU?t=12m5s), [second](https://youtu.be/jiyD0r2SC-g?t=12m55s)) `video` `in russian`


#### applications

  [**artificial intelligence**](https://github.com/brylevkirill/notes/blob/master/Artificial%20Intelligence.md)  
  [**knowledge representation and reasoning**](https://github.com/brylevkirill/notes/blob/master/Knowledge%20Representation%20and%20Reasoning.md)  
  [**natural language processing**](https://github.com/brylevkirill/notes/blob/master/Natural%20Language%20Processing.md)  
  [**recommender systems**](https://github.com/brylevkirill/notes/blob/master/Recommender%20Systems.md)  
  [**information retrieval**](https://github.com/brylevkirill/notes/blob/master/Information%20Retrieval.md)  

  ["Machine Learning is The New Algorithms"](http://nlpers.blogspot.ru/2014/10/machine-learning-is-new-algorithms.html) by Hal Daume  
  ["When is Machine Learning Worth It?"](http://inference.vc/when-is-machine-learning-worth-it/) by Ferenc Huszar  

  Any source code for expression y = f(x), where f(x) has some parameters and is used to make decision, prediction or estimate, has potential to be replaced by machine learning algorithm.


#### knowledge bases

  <http://metacademy.org>  
  <http://en.wikipedia.org/wiki/Machine_learning> ([*guide*](https://github.com/Nixonite/open-source-machine-learning-degree/blob/master/Introduction%20to%20Machine%20Learning%20-%20Wikipedia.pdf))  
  <http://machinelearning.ru> `in russian`  


#### guides

  ["Machine Learning Basics"](http://www.deeplearningbook.org/contents/ml.html) by Ian Goodfellow, Yoshua Bengio, Aaron Courville  
  ["A Few Useful Things to Know about Machine Learning"](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) by Pedro Domingos  
  ["Expressivity, Trainability, and Generalization in Machine Learning"](http://blog.evjang.com/2017/11/exp-train-gen.html) by Eric Jang  
  ["Classification vs. Prediction"](http://fharrell.com/2017/01/classification-vs-prediction.html) by Frank Harrell  
  ["Causality in Machine Learning"](http://unofficialgoogledatascience.com/2017/01/causality-in-machine-learning.html) by Muralidharan et al.  
  ["Are ML and Statistics Complementary?"](https://www.ics.uci.edu/~welling/publications/papers/WhyMLneedsStatistics.pdf) by Max Welling  
  ["Introduction to Information Theory and Why You Should Care"](https://blog.recast.ai/introduction-information-theory-care/) by Gil Katz  
  ["Ideas on Interpreting Machine Learning"](https://oreilly.com/ideas/ideas-on-interpreting-machine-learning) by Hall et al.  
  ["Clever Methods of Overfitting"](http://hunch.net/?p=22) by John Langford  
  ["Common Pitfalls in Machine Learning"](http://danielnee.com/?p=155) by Daniel Nee  
  ["Software Engineering vs Machine Learning Concepts"](http://machinedlearnings.com/2017_02_01_archive.html) by Paul Mineiro  
  ["Rules of Machine Learning: Best Practices for ML Engineering"](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf) by Martin Zinkevich  


#### courses

  [course](https://youtube.com/playlist?list=PLLssT5z_DsK-h9vYZkQkYNWcItqhlRJLN) by Andrew Ng `video`  
  [course](http://youtube.com/playlist?list=PLE6Wd9FR--Ecf_5nCbnSQMHqORpiChfJf) by Nando de Freitas `video`  
  [course](http://youtube.com/playlist?list=PLE6Wd9FR--EdyJ5lbFl8UuGjecvVw66F6) by Nando de Freitas `video`  
  [course](http://youtube.com/playlist?list=PLTPQEx-31JXgtDaC6-3HxWcp7fq4N8YGr) by Pedro Domingos `video`  
  [course](http://youtube.com/playlist?list=PLZSO_6-bSqHTTV7w9u7grTXBHMH-mw3qn) by Alex Smola `video`  
  [course](http://dataschool.io/15-hours-of-expert-machine-learning-videos/) by Trevor Hastie and Rob Tibshirani `video`  
  [course](https://youtube.com/playlist?list=PLD0F06AA0D2E8FFBA) by Jeff Miller `video`  

  [course](http://ciml.info) by Hal Daume

  [course](http://coursera.org/specializations/machine-learning-data-analysis) by Yandex `video` `in russian`  
  [course](https://github.com/Yorko/mlcourse_open) by OpenDataScience `video` `in russian`  
  [course](http://youtube.com/playlist?list=PLJOzdkh8T5kp99tGTEFjH_b9zqEQiiBtC) by Konstantin Vorontsov `video` `in russian`  
  [course](http://youtube.com/playlist?list=PLlb7e2G7aSpTd91sd82VxWNdtTZ8QnFne) by Igor Kuralenok `video` `in russian`  
  [course](http://youtube.com/playlist?list=PLlb7e2G7aSpSWVExpq74FnwFnWgLby56L) by Igor Kuralenok `video` `in russian`  
  [course](http://youtube.com/playlist?list=PLlb7e2G7aSpSSsCeUMLN-RxYOLAI9l2ld) by Igor Kuralenok `video` `in russian`  
  [course](http://lektorium.tv/course/22975) by Igor Kuralenok `video` `in russian`  


#### books

  ["The Master Algorithm"](http://basicbooks.com/full-details?isbn=9780465065707) by Pedro Domingos  
  ["A First Encounter with Machine Learning"](https://www.ics.uci.edu/~welling/teaching/ICS273Afall11/IntroMLBook.pdf) by Max Welling  
  ["Deep Learning"](http://www.deeplearningbook.org) by Ian Goodfellow, Yoshua Bengio, Aaron Courville  
  ["Reinforcement Learning: An Introduction"](http://incompleteideas.net/book/ebook/the-book.html)
	([second edition](http://incompleteideas.net/book/the-book-2nd.html)) by Richard Sutton and Andrew Barto  
  ["Machine Learning"](https://goo.gl/tyNHMH) by Tom Mitchell  
  ["Understanding Machine Learning: From Theory to Algorithms"](http://cs.huji.ac.il/~shais/UnderstandingMachineLearning/) by Shai Shalev-Shwartz and Shai Ben-David  
  ["Pattern Recognition and Machine Learning"](https://goo.gl/58Yvvp) by Chris Bishop  
  ["Computer Age Statistical Inference"](https://web.stanford.edu/~hastie/CASI_files/PDF/casi.pdf) by Bradley Efron and Trevor Hastie  
  ["The Elements of Statistical Learning"](http://statweb.stanford.edu/~tibs/ElemStatLearn/printings/ESLII_print10.pdf) by Trevor Hastie, Robert Tibshirani, Jerome Friedman  
  ["Machine Learning - A Probabilistic Perspective"](https://goo.gl/Vh7Jje) by Kevin Murphy  
  ["Information Theory, Inference, and Learning Algorithms"](http://users.aims.ac.za/~mackay/itila/book.html) by David MacKay  
  ["Bayesian Reasoning and Machine Learning"](http://web4.cs.ucl.ac.uk/staff/D.Barber/pmwiki/pmwiki.php?n=Brml.Online) by David Barber  
  ["Foundations of Machine Learning"](http://www.cs.nyu.edu/~mohri/mlbook/) by Mehryar Mohri  
  ["Scaling Up Machine Learning: Parallel and Distributed Approaches"](https://goo.gl/dE7jPb) by Ron Bekkerman, Mikhail Bilenko, John Langford  


#### blogs

  <http://inference.vc>  
  <http://offconvex.org>  
  <http://argmin.net>  
  <http://blog.shakirm.com>  
  <http://hunch.net>  
  <http://machinedlearnings.com>  
  <http://nlpers.blogspot.com>  
  <http://ruder.io>  
  <http://fastml.com>  
  <http://wildml.com>  
  <http://blogs.princeton.edu/imabandit>  
  <http://timvieira.github.io/blog>  
  <http://r2rt.com>  
  <http://danieltakeshi.github.io>  
  <http://theneuralperspective.com>  


#### news and discussions

  <https://jack-clark.net/import-ai>  
  <https://newsletter.ruder.io>  
  <https://www.getrevue.co/profile/wildml>  

  <https://reddit.com/r/MachineLearning>


#### conferences

  - ICML 2018  
	<https://facebook.com/icml.imls/videos> `video`

	<https://david-abel.github.io/blog/posts/misc/icml_2018.pdf> `notes`

  - ICLR 2018  
	<https://facebook.com/iclr.cc/videos> `video`

	<http://search.iclr2018.smerity.com>  
	<http://iclr2018.mmanukyan.io>  
	<http://chillee.github.io/OpenReviewExplorer>  

  - NIPS 2017  
	<https://nips.cc/Conferences/2017/Videos> `video`  
	<https://facebook.com/pg/nipsfoundation/videos/> `video`  

	<https://nips17.ml>

	<https://github.com/hindupuravinash/nips2017>  
	<https://github.com/kihosuh/nips_2017>  
	<https://github.com/sbarratt/nips2017>  

	<https://cs.brown.edu/~dabel/blog/posts/misc/nips_2017.pdf> `notes`

  - ICML 2017  
	<https://icml.cc/Conferences/2017/Videos> `video`

	<http://artem.sobolev.name/posts/2017-08-14-icml-2017.html>  
	<https://olgalitech.wordpress.com/tag/icml2017/>  

  - ICLR 2017  
	<https://facebook.com/iclr.cc/videos> `video`

	<https://medium.com/@karpathy/iclr-2017-vs-arxiv-sanity-d1488ac5c131>

  - NIPS 2016  
	<https://channel9.msdn.com/Events/Neural-Information-Processing-Systems-Conference/Neural-Information-Processing-Systems-Conference-NIPS-2016> `video`  
	<https://nips.cc/Conferences/2016/SpotlightVideos> `video`  

	<https://youtube.com/playlist?list=PLPwzH56Rdmq4hcuEMtvBGxUrcQ4cAkoSc> `video`  
	<https://youtube.com/playlist?list=PLJscN9YDD1buxCitmej1pjJkR5PMhenTF> `video`  
	<https://youtube.com/channel/UC_LBLWLfKk5rMKDOHoO7vPQ> `video`  
	<https://youtube.com/playlist?list=PLzTDea_cM27LVPSTdK9RypSyqBHZWPywt> `video`  

	<https://github.com/hindupuravinash/nips2016>  
	<http://artem.sobolev.name/posts/2016-12-31-nips-2016-summaries.html>  

  - ICML 2016  
	<http://techtalks.tv/icml/2016/> `video`

  - ICLR 2016  
	<http://videolectures.net/iclr2016_san_juan/> `video`

	<http://www.computervisionblog.com/2016/06/deep-learning-trends-iclr-2016.html>  

  - NIPS 2015  
	<https://youtube.com/playlist?list=PLD7HFcN7LXRdvgfR6qNbuvzxIwG0ecE9Q> `video`  
	<https://youtube.com/user/NeuralInformationPro/search?query=NIPS+2015> `video`  
 
	<http://reddit.com/r/MachineLearning/comments/3x2ueg/nips_2015_overviews_collection/>  
	<http://cinrizasti.blogspot.ru/2015/12/a-blog-post-about-blog-posts-about-nips.html>  

  - ICML 2015  
	<https://youtube.com/playlist?list=PLdH9u0f1XKW8cUM3vIVjnpBfk_FKzviCu> `video`  
	<http://dpkingma.com/?page_id=483> `video`  

  - ICLR 2015  
	<http://youtube.com/channel/UCqxFGrNL5nX10lS62bswp9w> `video`

  - NIPS 2014  
	<https://youtube.com/user/NeuralInformationPro/search?query=NIPS+2014> `video`



---
### theory

  [machine learning has become alchemy](https://youtube.com/watch?v=Qi1Yry33TQE&t=11m2s) by Ali Rahimi `video` ([post](http://argmin.net/2017/12/05/kitchen-sinks/))  
  [statistics in machine learning](https://youtube.com/watch?v=uyZOcUDhIbY&t=17m27s) by Michael I. Jordan `video`  
  [theory in machine learning](https://youtube.com/watch?v=uyZOcUDhIbY&t=23m1s) by Michael I. Jordan `video`  

  ["Learning Theory: Purely Theoretical?"](https://hips.seas.harvard.edu/blog/2013/02/15/learning-theory-purely-theoretical/) by Jonathan Huggins

----

  problems:  
  - What does it mean to learn?  
  - When is a concept/function learnable?  
  - How much data do we need to learn something?  
  - How can we make sure what we learn will generalize to future data?  

  theory helps to:  
  - design algorithms  
  - understand behaviour of algorithms  
  - quantify knowledge/uncertainty  
  - identify new and refine old challenges  

  frameworks:  
  - [**statistical learning theory**](#theory---statistical-learning-theory)  
  - [**computational learning theory**](#theory---computational-learning-theory) (PAC learning or PAC-Bayes)  


----
#### theory - statistical learning theory

  ingredients:
  - distributions
  - i.i.d. samples
  - learning algorithms
  - predictors
  - loss functions

  *A priori analysis*: How well a learning algorithm will perform on new data?  
  - (Vapnik's learning theory) Can we compete with best hypothesis from a given set of hypotheses?  
  - (statistics) Can we match the best possible loss assuming data generating distribution belongs to known family?  

  *A posteriori analysis*: How well is a learning algorithm doing on some data? Quantify uncertainty left

  *Fundamental theorem of statistical learning theory*:  
  In binary classification, to match the loss of hypothesis in class H up to accuracy ε, one needs O(VC(H)/ε^2) observations.

  *Theorem (computational complexity of learning linear classifiers)*:  
  Unless NP=RP, linear classifiers (hyperplanes) cannot be learned in polynomial time.

----

  ["Machine Learning Theory"](https://mostafa-samir.github.io/ml-theory-pt1/) by Mostafa Samir  
  ["Crash Course on Learning Theory"](https://blogs.princeton.edu/imabandit/2015/10/13/crash-course-on-learning-theory-part-1/) by Sebastien Bubeck  
  ["Statistical Learning Theory"](https://web.stanford.edu/class/cs229t/Lectures/percy-notes.pdf) by Percy Liang  

  [course](http://www.mit.edu/~9.520/fall17/) by Tomaso Poggio, Lorenzo Rosasco, Georgios Evangelopoulos `video`  
  [course](http://work.caltech.edu/telecourse.html) by Yaser Abu-Mostafa `video`  
  [course](http://youtube.com/watch?v=jX7Ky76eI7E) by Sebastien Bubeck `video`  


----
#### theory - computational learning theory

  ["Computational Learning Theory, AI and Beyond"](https://www.math.ias.edu/files/mathandcomp.pdf) chapter of "Mathematics and Computation" book by Avi Wigderson

  ["Probably Approximately Correct - A Formal Theory of Learning"](http://jeremykun.com/2014/01/02/probably-approximately-correct-a-formal-theory-of-learning/) by Jeremy Kun  
  ["A Problem That is Not (Properly) PAC-learnable"](http://jeremykun.com/2014/04/21/an-un-pac-learnable-problem/) by Jeremy Kun  
  ["Occam’s Razor and PAC-learning"](http://jeremykun.com/2014/09/19/occams-razor-and-pac-learning/) by Jeremy Kun  


----
#### theory - applications

  [**bayesian inference and learning**](https://github.com/brylevkirill/notes/blob/master/Bayesian%20Inference%20and%20Learning.md#theory)

  [**deep learning**](https://github.com/brylevkirill/notes/blob/master/Deep%20Learning.md#theory)

  [**reinforcement learning**](https://github.com/brylevkirill/notes/blob/master/Reinforcement%20Learning.md#problems)  
  ["Theory of Reinforcement Learning"](http://videolectures.net/deeplearning2017_szepesvari_theory_of_rl/) by Csaba Szepesvari `video`  



---
### methods

  **challenges**  
  - How to decide which representation is best for target knowledge?  
  - How to tell genuine regularities from chance occurrences?  
  - How to exploit pre-existing domain knowledge?  
  - How to learn with limited computational resources?  
  - How to learn with limited data?  
  - How to make learned results understandable?  
  - How to quantify uncertainty?  
  - How to take into account the costs of decisions?  
  - How to handle non-indepedent and non-stationary data?  

----

  ["The Three Cultures of Machine Learning"](https://www.cs.jhu.edu/~jason/tutorials/ml-simplex.html) by Jason Eisner  
  ["Algorithmic Dimensions"](https://justindomke.wordpress.com/2015/09/14/algorithmic-dimensions/) by Justin Domke  
  ["All Models of Learning Have Flaws"](http://hunch.net/?p=224) by John Langford  

----

  <http://en.wikipedia.org/wiki/List_of_machine_learning_algorithms>

  <http://eferm.com/wp-content/uploads/2011/05/cheat3.pdf>  
  <http://github.com/soulmachine/machine-learning-cheat-sheet/blob/master/machine-learning-cheat-sheet.pdf>  

  <http://scikit-learn.org/stable/tutorial/machine_learning_map/index.html>  



---
### representation learning

  "Representation is a formal system which makes explicit certain entities and types of information, and which can be operated on by an algorithm in order to achieve some information processing goal. Representations differ in terms of what information they make explicit and in terms of what algorithms they support. As example, Arabic and Roman numerals - the fact that operations can be applied to particular columns of Arabic numerals in meaningful ways allows for simple and efficient algorithms for addition and multiplication."

  "In representation learning, our goal isn’t to predict observables, but to learn something about the underlying structure. In cognitive science and AI, a representation is a formal system which maps to some domain of interest in systematic ways. A good representation allows us to answer queries about the domain by manipulating that system. In machine learning, representations often take the form of vectors, either real- or binary-valued, and we can manipulate these representations with operations like Euclidean distance and matrix multiplication."

  "In representation learning, the goal isn’t to make predictions about observables, but to learn a representation which would later help us to answer various queries. Sometimes the representations are meant for people, such as when we visualize data as a two-dimensional embedding. Sometimes they’re meant for machines, such as when the binary vector representations learned by deep Boltzmann machines are fed into a supervised classifier. In either case, what’s important is that mathematical operations map to the underlying relationships in the data in systematic ways."

----

  ["What is representation learning?"](https://hips.seas.harvard.edu/blog/2013/02/25/what-is-representation-learning/) by Roger Grosse  
  ["Predictive learning vs. representation learning"](https://hips.seas.harvard.edu/blog/2013/02/04/predictive-learning-vs-representation-learning/) by Roger Grosse  

----

  [**deep learning**](https://github.com/brylevkirill/notes/blob/master/Deep%20Learning.md)  
  [**probabilistic programming**](https://github.com/brylevkirill/notes/blob/master/Probabilistic%20Programming.md)  
  [**knowledge representation**](https://github.com/brylevkirill/notes/blob/master/Knowledge%20Representation%20and%20Reasoning.md#knowledge-representation)  



---
### program synthesis

  programmatic representations:  
  - *well-specified*  
	Unlike sentences in natural language, programs are unambiguous, although two distinct programs can be precisely equivalent.  
  - *compact*  
	Programs allow us to compress data on the basis of their regularities.  
  - *combinatorial*  
	Programs can access the results of running other programs, as well as delete, duplicate, and rearrange these results.  
  - *hierarchical*  
	Programs have an intrinsic hierarchical organization and may be decomposed into subprograms.  

  challenges:  
  - *open-endedness*  
	In contrast to other knowledge representations in machine learning, programs may vary in size and shape, and there is no obvious problem-independent upper bound on program size. This makes it difficult to represent programs as points in a fixed-dimensional space, or learn programs with algorithms that assume such a space.  
  - *over-representation*  
	Often syntactically distinct programs will be semantically identical (i.e. represent the same underlying behavior or functional mapping). Lacking prior knowledge, many algorithms will inefficiently sample semantically identical programs repeatedly.  
  - *chaotic execution*  
	Programs that are very similar, syntactically, may be very different, semantically. This presents difficulty for many heuristic search algorithms, which require syntactic and semantic distance to be correlated.  
  - *high resource-variance*  
	Programs in the same space may vary greatly in the space and time they require to execute.  

----

  "For me there are two types of generalisation, which I will refer to as Symbolic and Connectionist generalisation. If we teach a machine to sort sequences of numbers of up to length 10 or 100, we should expect them to sort sequences of length 1000 say. Obviously symbolic approaches have no problem with this form of generalisation, but neural nets do poorly. On the other hand, neural nets are very good at generalising from data (such as images), but symbolic approaches do poorly here. One of the holy grails is to build machines that are capable of both symbolic and connectionist generalisation."

  *(Nando de Freitas)*

----

  [inductive programming](https://en.wikipedia.org/wiki/Inductive_programming)

  ["Program Synthesis Explained"](http://homes.cs.washington.edu/~bornholt/post/synthesis-for-architects.html) by James Bornholt

  ["Inductive Programming Meets the Real World"](https://microsoft.com/en-us/research/publication/inductive-programming-meets-real-world/) by Gulwani et al. `paper`  
  ["Program Synthesis"](https://microsoft.com/en-us/research/wp-content/uploads/2017/10/program_synthesis_now.pdf) by Gulwani, Polozov, Singh `paper`  
  ["Approaches and Applications of Inductive Programming"](http://drops.dagstuhl.de/opus/volltexte/2018/8590/pdf/dagrep_v007_i009_p086_17382.pdf) by Schmid, Muggleton, Singh `paper`  

  ["Program Synthesis in 2017-18"](https://alexpolozov.com/blog/program-synthesis-2018) by Oleksandr Polozov  
  ["Recent Advances in Neural Program Synthesis"](https://arxiv.org/abs/1802.02353) by Neel Kant `paper`  

  [**interesting recent papers**](https://github.com/brylevkirill/notes/blob/master/interesting%20recent%20papers.md#program-induction)  
  [**selected papers**](https://yadi.sk/d/LZYQN7Lu3WxVVb)  

----

  ["Deep Learning Trends: Program Induction"](https://facebook.com/nipsfoundation/videos/1552060484885185?t=5412) by Scott Reed `video`  
  ["Learning to Code: Machine Learning for Program Induction"](https://youtu.be/vzDuVhFMB9Q?t=2m40s) by Alex Gaunt `video`  

  ["Neural Abstract Machines & Program Induction"](https://uclmr.github.io/nampi) workshop at NIPS 2016
	([videos](https://youtube.com/playlist?list=PLzTDea_cM27LVPSTdK9RypSyqBHZWPywt))  
  [panel](https://youtu.be/nqiUFc52g78?t=1h29m3s) at NAMPI 2016
	with Percy Liang, Juergen Schmidhuber, Joshua Tenenbaum, Martin Vechev, Daniel Tarlow, Dawn Song `video`  

----

  ["The Future of Deep Learning"](https://blog.keras.io/the-future-of-deep-learning.html) by Francois Chollet ([talk](https://youtu.be/MUF32XHqM34) `video`)



---
### meta-learning

  [overview](https://facebook.com/nipsfoundation/videos/1554594181298482?t=277) by Pieter Abbeel `video`  
  [overview](https://vimeo.com/250423463) by Oriol Vinyals `video`  
  [overview](http://videolectures.net/deeplearning2017_de_freitas_learning_to_learn/#t=631) by Nando de Freitas `video`  

  [Metalearning symposium](http://metalearning-symposium.ml) `video`

  [Metalearning symposium](https://vimeo.com/250399623) panel `video`  
  [RNN symposium](https://youtube.com/watch?v=zSNkbhgMkzQ) panel `video`  

  [**interesting recent papers**](https://github.com/brylevkirill/notes/blob/master/interesting%20recent%20papers.md#meta-learning)

----

  [overview](http://scholarpedia.org/article/Metalearning) by Tom Schaul and Juergen Schmidhuber

  ["On Learning How to Learn Learning Strategies"](https://vimeo.com/250399374) by Juergen Schmidhuber `video`  
  ["Learning how to Learn Learning Algorithms: Recursive Self-Improvement"](https://youtube.com/watch?v=nqiUFc52g78) by Juergen Schmidhuber `video`  

  [**Goedel Machine**](https://github.com/brylevkirill/notes/blob/master/Artificial%20Intelligence.md#meta-learning---goedel-machine)

----

  ["The Future of Deep Learning"](https://blog.keras.io/the-future-of-deep-learning.html) by Francois Chollet ([talk](https://youtu.be/MUF32XHqM34?t=16m55s) `video`)

----

  "Current commercial AI algorithms are still missing something fundamental. They are no self-referential general purpose learning algorithms. They improve some system’s performance in a given limited domain, but they are unable to inspect and improve their own learning algorithm. They do not learn the way they learn, and the way they learn the way they learn, and so on (limited only by the fundamental limits of computability)."

  *(Juergen Schmidhuber)*



---
### automated machine learning

  AutoML aims to automate many different stages of the machine learning process:  
  - model selection, hyper-parameter optimization, and model search  
  - meta learning and transfer learning  
  - representation learning and automatic feature extraction / construction  
  - automatic generation of workflows / workflow reuse  
  - automatic problem "ingestion" (from raw data and miscellaneous formats)  
  - automatic feature transformation to match algorithm requirements  
  - automatic detection and handling of skewed data and/or missing values  
  - automatic acquisition of new data (active learning, experimental design)  
  - automatic report writing (providing insight on automatic data analysis)  
  - automatic selection of evaluation metrics / validation procedures  
  - automatic selection of algorithms under time/space/power constraints  
  - automatic prediction post-processing and calibration  
  - automatic leakage detection  
  - automatic inference and differentiation  
  - user interfaces for AutoML  

  problems:  
  - different data distributions: the intrinsic/geometrical complexity of the dataset  
  - different tasks: regression, binary classification, multi-class classification, multi-label classification  
  - different scoring metrics: AUC, BAC, MSE, F1, etc  
  - class balance: Balanced or unbalanced class proportions  
  - sparsity: Full matrices or sparse matrices  
  - missing values: Presence or absence of missing values  
  - categorical variables: Presence or absence of categorical variables  
  - irrelevant variables: Presence or absence of additional irrelevant variables (distractors)  
  - number Ptr of training examples: Small or large number of training examples  
  - number N of variables/features: Small or large number of variables  
  - aspect ratio Ptr/N of the training data matrix: Ptr >> N, Ptr = N or Ptr << N  

----

  ["Automated Machine Learning: A Short History"](https://datarobot.com/blog/automated-machine-learning-short-history/) by Thomas Dinsmore

  ["Automated Machine Learning"](https://youtube.com/watch?v=AFeozhAD9xE) by Andreas Mueller `video`  
  ["AutoML and How To Speed It Up"](https://vimeo.com/250399200) by Frank Hutter `video`  
  ["Neural Architecture Search"](https://vimeo.com/250399509) by Quoc Le `video`
	([post](https://research.googleblog.com/2017/11/automl-for-large-scale-image.html))  

  [**interesting papers**](#interesting-papers---automated-machine-learning)

----

  [auto-sklearn](https://github.com/automl/auto-sklearn) project  

  [TPOT](https://github.com/EpistasisLab/tpot) project  

  [auto_ml](http://auto-ml.readthedocs.io) project  

  [The Automatic Statistician](https://automaticstatistician.com) project  
  - [overview](https://youtube.com/watch?v=aPDOZfu_Fyk) by Zoubin Ghahramani `video`  
  - [overview](https://youtu.be/H7AMB0oo__4?t=53m20s) by Zoubin Ghahramani `video`  
  - [overview](https://youtube.com/watch?v=WW2eunuApAU) by Zoubin Ghahramani `video`  
  - [overview](https://www.snn.ru.nl/v2/img/ml2015/slides/Ghahramani_nijmegen15part2.pdf) by Zoubin Ghahramani `slides`  

----

  [AutoML](http://automl.chalearn.org) challenge  
>	"Design the perfect machine learning “black box” capable of performing all model selection and hyper-parameter tuning without any human intervention"  

----

  ["The Future of Deep Learning"](https://blog.keras.io/the-future-of-deep-learning.html) by Francois Chollet ([talk](https://youtu.be/MUF32XHqM34?t=11m43s) `video`)

----

  ["Why Tool AIs Want to Be Agent AIs"](http://www.gwern.net/Tool%20AI) by Gwern Branwen:  

  "Roughly, we can try to categorize the different kinds of agentiness by level of neural network they work on. There are:  

  - actions internal to a computation
    * inputs
    * intermediate states
    * accessing the external environment
    * amount of computation
    * enforcing constraints/finetuning quality of output
    * changing the loss function applied to output
  - actions internal to training the neural network
    * the gradient itself
    * size & direction of gradient descent steps on each parameter
    * overall gradient descent learning rate and learning rate schedule
    * choice of data samples to train on
  - internal to the neural network design step
    * hyperparameter optimization
    * neural network architecture
  - internal to the dataset
    * active learning
    * optimal experiment design
  - internal to interaction with environment
    * adaptive experiment
    * multi-armed bandit
    * exploration for reinforcement learning"

  "The logical extension of these neural networks all the way down papers is that an actor like Google / Baidu / Facebook / MS could effectively turn neural networks into a black box: a user/developer uploads through an API a dataset of input/output pairs of a specified type and a monetary loss function, and a top-level neural network running on a large GPU cluster starts autonomously optimizing over architectures & hyperparameters for the neural network design which balances GPU cost and the monetary loss, interleaved with further optimization over the thousands of previous submitted tasks, sharing its learning across all of the datasets / loss functions / architectures / hyperparameters, and the original user simply submits future data through the API for processing by the best neural network so far."

  *(Gwern Branwen)*



---
### interesting papers

  - [**theory**](#interesting-papers---theory)
  - [**automated machine learning**](#interesting-papers---automated-machine-learning)
  - [**systems**](#interesting-papers---systems)


[**interesting papers - deep learning**](https://github.com/brylevkirill/notes/blob/master/Deep%20Learning.md#interesting-papers)  
[**interesting papers - reinforcement learning**](https://github.com/brylevkirill/notes/blob/master/Reinforcement%20Learning.md#interesting-papers)  
[**interesting papers - bayesian inference and learning**](https://github.com/brylevkirill/notes/blob/master/Bayesian%20Inference%20and%20Learning.md#interesting-papers)  
[**interesting papers - probabilistic programming**](https://github.com/brylevkirill/notes/blob/master/Probabilistic%20Programming.md#interesting-papers)  


[**interesting recent papers**](https://github.com/brylevkirill/notes/blob/master/interesting%20recent%20papers.md)



---
### interesting papers - theory


#### ["A Theory of the Learnable"](https://people.mpi-inf.mpg.de/~mehlhorn/SeminarEvolvability/ValiantLearnable.pdf) Valiant
>	"Humans appear to be able to learn new concepts without needing to be programmed explicitly in any conventional sense. In this paper we regard learning as the phenomenon of knowledge acquisition in the absence of explicit programming. We give a precise methodology for studying this phenomenon from a computational viewpoint. It consists of choosing an appropriate information gathering mechanism, the learning protocol, and exploring the class of concepts that can be learned using it in a reasonable (polynomial) number of steps. Although inherent algorithmic complexity appears to set serious limits to the range of concepts that can be learned, we show that there are some important nontrivial classes of propositional concepts that can be learned in a realistic sense."

>	"Proof that if you have a finite number of functions, say N, then every training error will be close to every test error once you have more than log N training cases by a small constant factor. Clearly, if every training error is close to its test error, then overfitting is basically impossible (overfitting occurs when the gap between the training and the test error is large)."


#### ["Statistical Modeling: The Two Cultures"](http://projecteuclid.org/euclid.ss/1009213726) Breiman
>	"There are two cultures in the use of statistical modeling to reach conclusions from data. One assumes that the data are generated by a given stochastic data model. The other uses algorithmic models and treats the data mechanism as unknown. The statistical community has been committed to the almost exclusive use of data models. This commitment has led to irrelevant theory, questionable conclusions, and has kept statisticians from working on a large range of interesting current problems. Algorithmic modeling, both in theory and practice, has developed rapidly in fields outside statistics. It can be used both on large complex data sets and as a more accurate and informative alternative to data modeling on smaller data sets. If our goal as a field is to use data to solve problems, then we need to move away from exclusive dependence on data models and adopt a more diverse set of tools."


#### ["A Few Useful Things to Know about Machine Learning"](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf) Domingos
>	"Machine learning algorithms can figure out how to perform important tasks by generalizing from examples. This is often feasible and cost-effective where manual programming is not. As more data becomes available, more ambitious problems can be tackled. As a result, machine learning is widely used in computer science and other fields. However, developing successful machine learning applications requires a substantial amount of “black art” that is hard to find in textbooks. This article summarizes twelve key lessons that machine learning researchers and practitioners have learned. These include pitfalls to avoid, important issues to focus on, and answers to common questions."


#### ["Learning with Intelligent Teacher: Similarity Control and Knowledge Transfer"](http://link.springer.com/chapter/10.1007/978-3-319-17091-6_1) Vapnik, Izmailov
>	"This paper introduces an advanced setting of machine learning problem in which an Intelligent Teacher is involved. During training stage, Intelligent Teacher provides Student with information that contains, along with classification of each example, additional privileged information (explanation) of this example. The paper describes two mechanisms that can be used for significantly accelerating the speed of Student’s training: (1) correction of Student’s concepts of similarity between examples, and (2) direct Teacher-Student knowledge transfer."

>	"During last fifty years a strong machine learning theory has been developed. This theory includes: 1. The necessary and sufficient conditions for consistency of learning processes. 2. The bounds on the rate of convergence which in general cannot be improved. 3. The new inductive principle (SRM) which always achieves the smallest risk. 4. The effective algorithms, (such as SVM), that realize consistency property of SRM principle. It looked like general learning theory has been complied: it answered almost all standard questions that is asked in the statistical theory of inference. Meantime, the common observation was that human students require much less examples for training than learning machine. Why? The talk is an attempt to answer this question. The answer is that it is because the human students have an Intelligent Teacher and that Teacher-Student interactions are based not only on the brute force methods of function estimation from observations. Speed of learning also based on Teacher-Student interactions which have additional mechanisms that boost learning process. To learn from smaller number of observations learning machine has to use these mechanisms. In the talk I will introduce a model of learning that includes the so called Intelligent Teacher who during a training session supplies a Student with intelligent (privileged) information in contrast to the classical model where a student is given only outcomes y for events x. Based on additional privileged information x* for event x two mechanisms of Teacher-Student interactions (special and general) are introduced: 1. The Special Mechanism: To control Student's concept of similarity between training examples. and 2. The General Mechanism: To transfer knowledge that can be obtained in space of privileged information to the desired space of decision rules. Both mechanisms can be considered as special forms of capacity control in the universally consistent SRM inductive principle. Privileged information exists for almost any inference problem and can make a big difference in speed of learning processes."

  - `video` <https://video.ias.edu/csdm/2015/0330-VladimirVapnik> (Vapnik)
  - `press` <http://learningtheory.org/learning-has-just-started-an-interview-with-prof-vladimir-vapnik/>


#### ["Compression and Machine Learning: A New Perspective on Feature Space Vectors"](http://www.eecs.tufts.edu/~dsculley/papers/compressionAndVectors.pdf) Sculley, Brodley
>	"The use of compression algorithms in machine learning tasks such as clustering and classification has appeared in a variety of fields, sometimes with the promise of reducing problems of explicit feature selection. The theoretical justification for such methods has been founded on an upper bound on Kolmogorov complexity and an idealized information space. An alternate view shows compression algorithms implicitly map strings into implicit feature space vectors, and compression-based similarity measures compute similarity within these feature spaces. Thus, compression-based methods are not a “parameter free” magic bullet for feature selection and data representation, but are instead concrete similarity measures within defined feature spaces, and are therefore akin to explicit feature vector models used in standard machine learning algorithms. To underscore this point, we find theoretical and empirical connections between traditional machine learning vector models and compression, encouraging cross-fertilization in future work."



---
### interesting papers - automated machine learning


#### ["Design of the 2015 ChaLearn AutoML Challenge"](http://www.causality.inf.ethz.ch/AutoML/automl_ijcnn15.pdf) Guyon et al.
>	"ChaLearn is organizing for IJCNN 2015 an Automatic Machine Learning challenge (AutoML) to solve classification and regression problems from given feature representations, without any human intervention. This is a challenge with code submission: the code submitted can be executed automatically on the challenge servers to train and test learning machines on new datasets. However, there is no obligation to submit code. Half of the prizes can be won by just submitting prediction results. There are six rounds (Prep, Novice, Intermediate, Advanced, Expert, and Master) in which datasets of progressive difficulty are introduced (5 per round). There is no requirement to participate in previous rounds to enter a new round. The rounds alternate AutoML phases in which submitted code is “blind tested” on datasets the participants have never seen before, and Tweakathon phases giving time (~1 month) to the participants to improve their methods by tweaking their code on those datasets. This challenge will push the state-of-the-art in fully automatic machine learning on a wide range of problems taken from real world applications."


#### ["Population Based Training of Neural Networks"](https://arxiv.org/abs/1711.09846) Jaderberg et al.
>	"Neural networks dominate the modern machine learning landscape, but their training and success still suffer from sensitivity to empirical choices of hyperparameters such as model architecture, loss function, and optimisation algorithm. In this work we present Population Based Training, a simple asynchronous optimisation algorithm which effectively utilises a fixed computational budget to jointly optimise a population of models and their hyperparameters to maximise performance. Importantly, PBT discovers a schedule of hyperparameter settings rather than following the generally sub-optimal strategy of trying to find a single fixed set to use for the whole course of training. With just a small modification to a typical distributed hyperparameter training framework, our method allows robust and reliable training of models. We demonstrate the effectiveness of PBT on deep reinforcement learning problems, showing faster wall-clock convergence and higher final performance of agents by optimising over a suite of hyperparameters. In addition, we show the same method can be applied to supervised learning for machine translation, where PBT is used to maximise the BLEU score directly, and also to training of Generative Adversarial Networks to maximise the Inception score of generated images. In all cases PBT results in the automatic discovery of hyperparameter schedules and model selection which results in stable training and better final performance."

>	"Two common tracks for the tuning of hyperparameters exist: parallel search and sequential optimisation, which trade-off concurrently used computational resources with the time required to achieve optimal results. Parallel search performs many parallel optimisation processes (by optimisation process we refer to neural network training runs), each with different hyperparameters, with a view to finding a single best output from one of the optimisation processes – examples of this are grid search and random search. Sequential optimisation performs few optimisation processes in parallel, but does so many times sequentially, to gradually perform hyperparameter optimisation using information obtained from earlier training runs to inform later ones – examples of this are hand tuning and Bayesian optimisation. Sequential optimisation will in general provide the best solutions, but requires multiple sequential training runs, which is often unfeasible for lengthy optimisation processes."

>	"In this work, we present a simple method, Population Based Training which bridges and extends parallel search methods and sequential optimisation methods. Advantageously, our proposal has a wallclock run time that is no greater than that of a single optimisation process, does not require sequential runs, and is also able to use fewer computational resources than naive search methods such as random or grid search. Our approach leverages information sharing across a population of concurrently running optimisation processes, and allows for online propagation/transfer of parameters and hyperparameters between members of the population based on their performance."

>	"Furthermore, unlike most other adaptation schemes, our method is capable of performing online adaptation of hyperparameters – which can be particularly important in problems with highly non-stationary learning dynamics, such as reinforcement learning settings, where the learning problem itself can be highly non-stationary (e.g. dependent on which parts of an environment an agent is currently able to explore). As a consequence, it might be the case that the ideal hyperparameters for such learning problems are themselves highly non-stationary, and should vary in a way that precludes setting their schedule in advance."

  - `post` <https://deepmind.com/blog/population-based-training-neural-networks/>
  - `video` <https://vimeo.com/250399261> (Jaderberg)


#### ["Data Programming: Creating Large Training Sets, Quickly"](https://arxiv.org/abs/1605.07723) Ratner, Sa, Wu, Selsam, Re
>	"Large labeled training sets are the critical building blocks of supervised learning methods and are key enablers of deep learning techniques. For some applications, creating labeled training sets is the most time-consuming and expensive part of applying machine learning. We therefore propose a paradigm for the programmatic creation of training sets called data programming in which users provide a set of labeling functions, which are programs that heuristically label large subsets of data points, albeit noisily. By viewing these labeling functions as implicitly describing a generative model for this noise, we show that we can recover the parameters of this model to “denoise” the training set. Then, we show how to modify a discriminative loss function to make it noise-aware. We demonstrate our method over a range of discriminative models including logistic regression and LSTMs. We establish theoretically that we can recover the parameters of these generative models in a handful of settings. Experimentally, on the 2014 TAC-KBP relation extraction challenge, we show that data programming would have obtained a winning score, and also show that applying data programming to an LSTM model leads to a TAC-KBP score almost 6 F1 points over a supervised LSTM baseline (and into second place in the competition). Additionally, in initial user studies we observed that data programming may be an easier way to create machine learning models for non-experts."

>	"In the data programming approach to developing a machine learning system, the developer focuses on writing a set of labeling functions, which create a large but noisy training set. Snorkel then learns a generative model of this noise - learning, essentially, which labeling functions are more accurate than others - and uses this to train a discriminative classifier. At a high level, the idea is that developers can focus on writing labeling functions - which are just (Python) functions that provide a label for some subset of data points - and not think about algorithms or features!"

  - `video` <https://youtube.com/watch?v=iSQHelJ1xxU>
  - `video` <https://youtube.com/watch?v=HmocI2b5YfA> (Re)
  - `post` <http://hazyresearch.github.io/snorkel/blog/weak_supervision.html>
  - `post` <http://hazyresearch.github.io/snorkel/blog/dp_with_tf_blog_post.html>
  - `audio` <https://soundcloud.com/nlp-highlights/28-data-programming-creating-large-training-sets-quickly> (Ratner)
  - `notes` <https://github.com/b12io/reading-group/blob/master/data-programming-snorkel.md>
  - `code` <https://github.com/HazyResearch/snorkel>
  - [Snorkel](https://github.com/brylevkirill/notes/blob/master/Knowledge%20Representation%20and%20Reasoning.md#machine-reading-projects---snorkel) project `summary`


#### ["Socratic Learning: Empowering the Generative Model"](http://arxiv.org/abs/1610.08123) Varma et al.
>	"A challenge in training discriminative models like neural networks is obtaining enough labeled training data. Recent approaches have leveraged generative models to denoise weak supervision sources that a discriminative model can learn from. These generative models directly encode the users' background knowledge. Therefore, these models may be incompletely specified and fail to model latent classes in the data. We present Socratic learning to systematically correct such generative model misspecification by utilizing feedback from the discriminative model. We prove that under mild conditions, Socratic learning can recover features from the discriminator that informs the generative model about these latent classes. Experimentally, we show that without any hand-labeled data, the corrected generative model improves discriminative performance by up to 4.47 points and reduces error for an image classification task by 80% compared to a state-of-the-art weak supervision modeling technique."

  - `video` <https://youtube.com/watch?v=0gRNochbK9c>
  - `post` <http://hazyresearch.github.io/snorkel/blog/socratic_learning.html>
  - `code` <https://github.com/HazyResearch/snorkel>
  - [Snorkel](https://github.com/brylevkirill/notes/blob/master/Knowledge%20Representation%20and%20Reasoning.md#machine-reading-projects---snorkel) project `summary`


#### ["Snorkel: Rapid Training Data Creation with Weak Supervision"](https://arxiv.org/abs/1711.10160) Ratner, Bach, Ehrenberg, Fries, Wu, Re
>	"Labeling training data is increasingly the largest bottleneck in deploying machine learning systems. We present Snorkel, a first-of-its-kind system that enables users to train stateof-the-art models without hand labeling any training data. Instead, users write labeling functions that express arbitrary heuristics, which can have unknown accuracies and correlations. Snorkel denoises their outputs without access to ground truth by incorporating the first end-to-end implementation of our recently proposed machine learning paradigm, data programming. We present a flexible interface layer for writing labeling functions based on our experience over the past year collaborating with companies, agencies, and research labs. In a user study, subject matter experts build models 2.8× faster and increase predictive performance an average 45.5% versus seven hours of hand labeling. We study the modeling tradeoffs in this new setting and propose an optimizer for automating tradeoff decisions that gives up to 1.8× speedup per pipeline execution. In two collaborations, with the U.S. Department of Veterans Affairs and the U.S. Food and Drug Administration, and on four open-source text and image data sets representative of other deployments, Snorkel provides 132% average improvements to predictive performance over prior heuristic approaches and comes within an average 3.60% of the predictive performance of large hand-curated training sets."

  - `video` <https://youtube.com/watch?v=HmocI2b5YfA> (Re)
  - [Snorkel](https://github.com/brylevkirill/notes/blob/master/Knowledge%20Representation%20and%20Reasoning.md#machine-reading-projects---snorkel) project `summary`



---
### interesting papers - systems


#### ["Machine Learning: The High-Interest Credit Card of Technical Debt"](http://research.google.com/pubs/pub43146.html) Sculley et al.
>	"Machine learning offers a fantastically powerful toolkit for building complex systems quickly. This paper argues that it is dangerous to think of these quick wins as coming for free. Using the framework of technical debt, we note that it is remarkably easy to incur massive ongoing maintenance costs at the system level when applying machine learning. The goal of this paper is highlight several machine learning specific risk factors and design patterns to be avoided or refactored where possible. These include boundary erosion, entanglement, hidden feedback loops, undeclared consumers, data dependencies, changes in the external world, and a variety of system-level anti-patterns."

  - `post` <http://john-foreman.com/blog/the-perilous-world-of-machine-learning-for-fun-and-profit-pipeline-jungles-and-hidden-feedback-loops>


#### ["TensorFlow: A system for large-scale machine learning"](https://arxiv.org/abs/1605.08695) Abadi et al.
>	"TensorFlow is a machine learning system that operates at large scale and in heterogeneous environments. TensorFlow uses dataflow graphs to represent computation, shared state, and the operations that mutate that state. It maps the nodes of a dataflow graph across many machines in a cluster, and within a machine across multiple computational devices, including multicore CPUs, general-purpose GPUs, and custom designed ASICs known as Tensor Processing Units (TPUs). This architecture gives flexibility to the application developer: whereas in previous “parameter server” designs the management of shared state is built into the system, TensorFlow enables developers to experiment with novel optimizations and training algorithms. TensorFlow supports a variety of applications, with particularly strong support for training and inference on deep neural networks. Several Google services use TensorFlow in production, we have released it as an open-source project, and it has become widely used for machine learning research. In this paper, we describe the TensorFlow dataflow model in contrast to existing systems, and demonstrate the compelling performance that TensorFlow achieves for several real-world applications."


#### ["A Reliable Effective Terascale Linear Learning System"](http://arxiv.org/abs/1110.4198) Agarwal, Chapelle, Dudik, Langford
  `Vowpal Wabbit`
>	"We present a system and a set of techniques for learning linear predictors with convex losses on terascale data sets, with trillions of features, 1 billions of training examples and millions of parameters in an hour using a cluster of 1000 machines. Individually none of the component techniques are new, but the careful synthesis required to obtain an efficient implementation is. The result is, up to our knowledge, the most scalable and efficient linear learning system reported in the literature. We describe and thoroughly evaluate the components of the system, showing the importance of the various design choices."

>	"
>	 - Online by default  
>	 - Hashing, raw text is fine  
>	 - Most scalable public algorithm  
>	 - Reduction to simple problems  
>	 - Causation instead of correlation  
>	 - Learn to control based on feedback"  

  - <https://github.com/JohnLangford/vowpal_wabbit/wiki>
  - `video` <http://youtube.com/watch?v=wwlKkFhEhxE> (Langford)
  - `paper` ["Bring The Noise: Embracing Randomness Is the Key to Scaling Up Machine Learning Algorithms"](http://online.liebertpub.com/doi/pdf/10.1089/big.2013.0010) by Brian Dalessandro


#### ["Making Contextual Decisions with Low Technical Debt"](http://arxiv.org/abs/1606.03966) Agarwal et al.
  - <https://github.com/brylevkirill/notes/blob/master/Reinforcement%20Learning.md#making-contextual-decisions-with-low-technical-debt-agarwal-et-al>


#### ["CatBoost: Gradient Boosting with Categorical Features Support"](http://learningsys.org/nips17/assets/papers/paper_11.pdf) Dorogush, Ershov, Gulin
>	"In this paper we present CatBoost, a new open-sourced gradient boosting library that successfully handles categorical features and outperforms existing publicly available implementations of gradient boosting in terms of quality on a set of popular publicly available datasets. The library has a GPU implementation of learning algorithm and a CPU implementation of scoring algorithm, which are significantly faster than other gradient boosting libraries on ensembles of similar sizes."

>	"Two critical algorithmic advances introduced in CatBoost are the implementation of ordered boosting, a permutation-driven alternative to the classic algorithm, and an innovative algorithm for processing categorical features. Both techniques were created to fight a prediction shift caused by a special kind of target leakage present in all currently existing implementations of gradient boosting algorithms."

  - <https://catboost.yandex>
  - `video` <https://youtube.com/watch?v=8o0e-r0B5xQ> (Dorogush)
  - `video` <https://youtube.com/watch?v=db-iLhQvcH8> (Prokhorenkova)
  - `video` <https://youtube.com/watch?v=UYDwhuyWYSo> (Dorogush) `in russian`
  - `video` <https://youtube.com/watch?v=9ZrfErvm97M> (Dorogush) `in russian`
  - `video` <https://youtube.com/watch?v=Q_xa4RvnDcY> (Dorogush) `in russian`
  - `code` <https://github.com/catboost/catboost>
  - `paper` ["CatBoost: Unbiased Boosting with Categorical Features"](https://arxiv.org/abs/1706.09516) by Prokhorenkova, Gusev, Vorobev, Dorogush, Gulin


#### ["Consistent Individualized Feature Attribution for Tree Ensembles"](https://arxiv.org/abs/1802.03888) Lundberg, Erion, Lee
>	"Interpreting predictions from tree ensemble methods such as gradient boosting machines and random forests is important, yet feature attribution for trees is often heuristic and not individualized for each prediction. Here we show that popular feature attribution methods are inconsistent, meaning they can lower a feature's assigned importance when the true impact of that feature actually increases. This is a fundamental problem that casts doubt on any comparison between features. To address it we turn to recent applications of game theory and develop fast exact tree solutions for SHAP (SHapley Additive exPlanation) values, which are the unique consistent and locally accurate attribution values. We then extend SHAP values to interaction effects and define SHAP interaction values. We propose a rich visualization of individualized feature attributions that improves over classic attribution summaries and partial dependence plots, and a unique "supervised" clustering (clustering based on feature attributions). We demonstrate better agreement with human intuition through a user study, exponential improvements in run time, improved clustering performance, and better identification of influential features. An implementation of our algorithm has also been merged into XGBoost and LightGBM."
