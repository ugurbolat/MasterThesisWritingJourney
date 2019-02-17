Thesis Feebacks from Sven

# General
* [x] Include reference to the equation and algorithms as much as possible.
* [x] Find formal synonyms for in doing so, for doing so, etc.
* [x] State your motivation clearly why you did what you did.
* [x] Link chapter&section with couple of sentences.
+ [x] Reference style - Biblatex
* [x] Improve notation for transformation and pose.
  * It is too much effort change all notation according to Robotic Vision and 
    Control book so just make it more consistent over all thesis.
* [x] Brackets for equation references
- [x] VO problem -> Point set registration problem: CANCELLED.
  * In point set registration problem, feature matches might be unknown.
      Regardless of it, the main goal is to align point sets. In VO, we are not
      aligning, we know that they are matched and only minimize the errors.
  * So, I will keep it as it is.

# C1 - Intro
* [x] After first paragraph, describe sensor fusion and other sensors to get
    ego-motion. Discuss the advantages of using VO and RGB-D.
* [x] Integrate the content with motivation.

# C2 - Cam 
* [x] Fix transformation notation.
+ [x] Triangulation Model section - fix first sentences about losing angle.

# C3 - VO
* [x] Move the ORB part to appendices
* [x] Explain why you choose ORB and refer to appendices

# C4 - Motiv
* [x] Move motivation part to the intro

# C5 - Error-aware VO
+ [x] Give an intro paragraph about what is error-aware vo means
+ [x] Modify Algorithm Description section so that it looks like you're describing
    the implementation of COVO
+ [x] Explain why you modify the traditional residuals function in VO 
+ [x] Move the LSQ on manifold to the Appendices

# C6 - Evaluation
* [x] Editting
* [x] Improve your arguments

# C7 - Conc
* [x] Editting
* [x] Future work and open questions

# C8 - App
* [x] Editting
* [x] Remove Newton's method in the appendices. Leave LM related part briefly.
* [x] Prettify the parameters tables

# Format Checklist 

* [x] Grammar
* [x] Clarity of your arguments
* [x] TOC
* [ ] LOF - Left Margin Issue
* [x] LOA
* [ ] Acknowledgement
* [ ] Declaration 
* [ ] Figures and Tables
* [x] Bibliography
* [x] Fix transposes: \top
* [x] Change J' to J_tq

