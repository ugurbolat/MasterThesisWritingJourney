Thesis Feebacks from Sven

# General
* Include reference to the equation and algorithms as much as possible.
* Find formal synonyms for in doing so, for doing so, etc.
* State your motivation clearly why you did what you did.
* Link chapter&section with couple of sentences.
+ Reference style - Biblatex
* Improve notation for transformation and pose.
  * It is too much effort change all notation according to Robotic Vision and 
    Control book so just make it more consistent over all thesis.
* Brackets for equation references
- VO problem -> Point set registration problem: CANCELLED.
  * In point set registration problem, feature matches might be unknown.
      Regardless of it, the main goal is to align point sets. In VO, we are not
      aligning, we know that they are matched and only minimize the errors.
  * So, I will keep it as it is.

# C1 - Intro
* After first paragraph, describe sensor fusion and other sensors to get
    ego-motion. Discuss the advantages of using VO and RGB-D.
* Integrate the content with motivation.

# C2 - Cam 
* Fix transformation notation.
+ Triangulation Model section - fix first sentences about losing angle.

# C3 - VO
* Remove the ORB part

# C4 - Motiv
* Move motivation part to the intro

# C5 - Error-aware VO
+ Give an intro paragraph about what is error-aware vo means
+ Modify Algorithm Description section so that it looks like you're describing
    the implementation of COVO
+ Explain why you modify the traditional residuals function in VO 
+ Move the LSQ on manifold to the Appendices

# C6 - Evaluation
* Improve the content

# C7 - Conc
* Future work and open questions

# C8 - App
* Remove Newton's method in the appendices. Leave LM related part briefly.


