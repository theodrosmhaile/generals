
# Proposal ideas

## Part 1: Introduction

### Definition of strategies and what their possible hallmarks are.
Different strategies can be used to learn a skill. This is largely due to the assumption that multiple learning mechanisms could be used to for learning and there is often a degree of choice. But some strategies are more efficient than others and depending on the skill, might help achieve higher levels of skill faster.

 Some of these strategies heavily depend on **declarative memory**, and some others depend on **procedural memory**. But, according to some theories of skill learning (Anderson, 1987), there is a specific trajectory of learning. They posit that as more learning trials are encountered, active retrieval of required skill information and  maintenance in working memory for performance is deemphasized. If a learner starts to rely less on instruction or retrieved declarative memory, they will experience a speed-up in performance as they will have more streamlined procedures to meet learning goals. Examples of strategies are below. Note that in all likelihood, especially in the case of complex skills, multiple strategies may be used at the same time.

#### declarative strategies:
- application of algorithm by recalling or reading instruction.
-  hypothesis testing by trial and error, while maintaining the goal and outcomes in working memory.
- recall an example and perform an analogical extrapolation to the current problem.
- with practice, a learner might produce a declarative rule that simplifies the initial, more complex algorithm.   

#### procedural strategies:
- streamlined procedural rules that are instinctive replace declarative strategies.
- trial and error exploration that has memory of only the most immediate outcomes but otherwise shapes learning incrementally and slowly.

#### meta-learning strategy:
Quite simply, a learner might choose any combination of the available strategies. For instance, a learner with learned proceduralized responses might choose to interrupt those procedures and recall the algorithm and apply it laboriously. It is not clear why one would do that, but:  

#### *How does this choice affect measured learning outcomes? What are maladaptive choices in a specific context? How can we detect poor choices and change instruction to improve learning outcomes?*

## Part 2: Proposed experiments
### proposal 1: Quantification of strategy use through on-task EEG.

Some strategies as described above require extensive deployment of attentional and working memory systems and so maybe traceable through specific EEG band oscillations. We may also be able to quantify how resource use changes through the course of learning. If we trace transition of EEG markers from effortful attention intensive processes to effortless, proceduralized performance, could we see if and when poor performers fall into strategies that are not helpful? To that end, *how do we capture strategies using EEG?*

 If it is possible to mark, encoding and retrieval of declarative memory, active maintenance in working memory etc., using EEG, we may perhaps compare how patterns of activity early in learning differ from patterns of activity later in learning. These changes might signify changes in strategy induced by experience. For instance, would we see fewer markers of encoding of new declarative information and working memory deployment later in learning? This would suggest a learning trajectory similar to Anderson's Declarative to procedural move. There are many papers that describe such markers using EEG with human subjects.

> E.g. " there was a significant decrease of power in low beta, high beta bands over fronto-central area and a decrease in low beta, high beta and gamma bands over left temporal area related to successful subsequent memory effect" during encoding. "...Significant decreases in alpha power were observed over fronto-central area during decoding". *Kalafatovich and Lee, 2020,Neural Oscillations for Encoding and Decoding Declarative Memory using EEG Signals IEEE*

To identify strategies we would need to know and measure the following to construct a 'strategy profile':
  -  sustained attention.
  -  active maintenance in wm.
  - declararive memory retrieval.
  - declarative memory encoding.
  -  procedural memory?
  - Is there drop off in these markers that are associated with efficiency?

  Lastly, we could conduct a second experiment where learners could be alerted of poor strategy choices if their previous sessions indicate it. Will this change their learning outcomes?

### Proposal 2: Quantification of strategy use through tracked behavior and computational models.
While measures of brain activity could reveal cognitive function use, patterns of tracked behavior maybe similarly telling. A few studies have looked at such metrics as time spent analyzing a problem, formulating a solution, and responding, that hinted at which cognitive mechanisms were being utilized to tackle the problem (Tenison, Fincham and Anderson, 2016). These experiments were in much simpler environments, compared to programming learning environments, where only a handful of predictable strategies were possible. Therefore, for more complex learning tasks, a constellation of behavioral measures maybe necessary. For instance, frequent use of maintenance in working memory to solve a problem may be revealed by tracking how often a learner refers back to instructions on the screen, how often they test solutions to problems etc. A highly formalized pattern of behaviors would need to be constructed which might require tracking and time-stamping typing behavior and eye-tracking.

To infer strategy use, the outcomes from these behavioral measures would then need to be compared to clearly defined multiple computational models as in Haile et al. 2020. Then, as in above, if tracking strategies across the learning arc is possible, we could identify how strategy choices change and which ones lead to better learning out comes. We might also follow up with a second experiment where we could attempt to change how learners engage with the task if we can predict that they will attempt to use poor strategies.

### Proposal 3: Limitations imposed by learning environment could necessitate specific strategies. Given that, who thrives and who suffers? Why?

Do all strategies start out as declarative? In what situations would a majority of learners attempt to utilize a strategy that does not have declarative access? It is clear that task environments impose or require specific strategies for successful completion. Therefore, the more restrictive the environment the more constrained the available set of strategies are. Two examples can demonstrate this point. 
Firstly, a learning environment that does not have instructions and works only through reinforcement of incidental discoveries by the learner will not have much learned information that could be represented declaratively. This may be especially true in the later stages of learning after the learner has associated a large number of motor movements to task outcomes. 
Alternatively, an environment that gives adequate instruction and even prompts the learner to repeatedly rehearse concepts until they can be easily recalled before application, forces a declarative strategy. Now, the important question is, who learns better in one of these situations? Further, how adaptable are learners to different environments? And lastly, would a high level of adaptability to changing environments suggest a meta-learning strategy that, to my knowledge, has not been explored but could be a critical component in learning?


