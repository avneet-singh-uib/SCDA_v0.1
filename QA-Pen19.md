Thoughts on the paper:

After going through the paper in entirety, I didn't find anything particularly relevant in it to our goal, either in methodology or the conclusions. The SCDA discussion in the paper is limited from a fundamental point of view, however, there is lots of information and lots of conclusions that are relevant to the MAOOAM model. In particular, there is nothing new in it for us when you look at it from the special perspective of maximising cross-covariance influence in SCDA methods e.g. LACC (since it is the most recent method [?]). They have compared a number of uncoupled (forced), coupled, CDA, WCDA, SCDA methods with respect to the MAOOAM model which might prove helpful later as a benchmark for testing new methods on a realistic model. 

Personal perspective: 

In course of understanding this paper, I had to dig into topology, chaos/ergodic theories etc which was really exciting and new for me, from a mathematical point of view. The practical aspect was also rewarding since I now have a good grasp of the MAOOAM model and the general dynamics of the Ocean-Atmosphere interactions and how they affect different Analysis-Forecast methods. The use of Lyapunov exponents/vectors and their spectrum is my key takeaway from this paper (rather the references therein).

Important sidenote:

When making the LACC method infographic, I had noted that 'selective mode filtering' could be useful when assimilating leading averaged observations over some leading time T (ref: Liu15.png). After becoming aware of the Lyapunov formulation, I wondered whether one could use their spectrum to filter stable and unstable modes from a set of leading observations spanning time T and formulate an approach that will assimilate only the useful information and discard 'trash'. Thus, what follows below is a first pseudo-description of it.

01
