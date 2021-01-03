# Advances in network visualisation with an application to serious games

This thesis concerns the visualisation of networks, through an in-depth study into the node-link diagram representation.
Three subtopics are explored within this space. The first is the problem of node layout, where the optimisation of a popular energy function, known as stress, is improved through an algorithm known as stochastic gradient descent.
The second is the method of edge bundling, where the idea of hierarchical edge bundling is explored in the absence of a known ground truth hierarchy. Its similarity to a topologically lossless bundling method known as power-confluent drawing is then leveraged, in order to improve technical problems with the underlying algorithms.
The final topic is an engineering application in the form of a serious game called EcoBuilder, which utilises the node-link diagram to visualise the dynamical behaviour of food webs. Its purpose is to crowdsource research through a citizen science approach, with outcomes in both visualisation and mathematical ecology.

TODOS:
- Add Daniel and James to acknowledgements

## Post-viva revisions:
requested:
1. Chapter numbers now start from 1. (and will be referred to with their new numberings here)
2. A fair amount of restructuring was done to enforce the separation of background and contribution, as this was the largest concern from the viva:
  - For Chapter 2, this was caused by not placing the 'constraint relaxation' and 'large graphs' literature in the Background section. This has now been refactored and reworded so that the Background section now contains both.
  - For Chapter 3, the same problem was caused by not placing the description of dissimilarity measures in the Background, and this has been similarly refactored.
  - Chapter 4 has now moved the definitions of confluent drawing and the description of greedy agglomeration into its new Background section, which was not previously separate at all.
  - Background on dynamic graph layout has been refactored out into a new Section 2.1.4. The 'User interface' section of Chapter 5 has also been moved to the end of the chapter as an appendix, following the comment that it reads a little like a user manual.
3. These new references have all been added as follows:
  a) These have been added, along with the suggested survey papers in the pre-viva report.
  b) Extra paragraphs and a new section have been added to include the Brandes paper. The 'drawing via gradient descent' paper has been included at the end of the discussion in Section 2.5, just before the conclusions.
  c&d) These papers have been added to the new Background Section 2.1.4, along with moving the previous content on dynamic layout there as well. 
4. An extra paragraph has been added to Section 2.2 (penultimate paragraph before 2.2.1) to give early emphasis on the possibility of smart initialisation. This then references a new subsection 2.2.4, which discusses the Brandes paper in detail, within the context of discussing the results.  
5. An extra paragraph has been added to the start of Section 2.2, and the extra references have been added to Section 2.1. Comparing the method to different (non-hierarchical) methods has also been added to the discussion in Section 2.3.
6. An extra paragraph has been added to the start of Section 3.2, and the potential future work of analysing how often the pathological case occurs has been added to the discussion in Section 3.3 (third paragraph).
7. This acknowledgement has been added to the new Section 2.1.4, with potential improvements also noted in the discussion in Section 2.3.3.
8. Two extra paragraphs have been added to the Introduction, just before Section 1.1, in order to tie together the narrative of the thesis under the motivation of EcoBuilder.
9. Citations have been changed to the authoryear style.
10. These errors have all been fixed.

recommended:
1. The potential future work of finding such a real example has been added to the discussion in Chapter 4
2. This could be achieved with a different type of spline, but quadratic B-splines require two overlapping routing nodes, and so a path of three nodes (and therefore three nested groups) is required to reproduce the error.
3. An extra paragraph has been added to Section 2.3.1 to elaborate the choice of pivot selection strategy. (paragraph 3)
4.
5. The following changes not already covered in the requested points above are as follows:
Chapter 2:
  a) The section title has been changed to be more specific to the problem at hand.
  b) Citations regarding what humans do when asked to draw a network have been added to the introductory section.
  c) An extra paragraph has been added to the start of Section 2.1.1 to make clear that the optimisation interpretation is not novel. Simulated annealing was also mentioned again when discussing the exponential schedule at the end of "fixed number of iterations", Section 2.2.1
  d) The suggested multilevel coarsening comparison paper was included in the (now Background) review for large graphs.
  e) the extra reference to emphasise the danger of using the rainbow colourmap was included in Section 2.4.2, paragraph 3.
Chapter 3:
  a) "thus far" has been changed to "thus far in this thesis"
Chapter 4:
  a) "Greedy agglomeration, again" has been changed to simply "Greedy agglomeration"
Chapter 5:
  a) The one-tailed test was elaborated as a permutation test, and a reference added.