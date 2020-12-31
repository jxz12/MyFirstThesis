# Advances in network visualisation with an application to serious games

This thesis concerns the visualisation of networks, through an in-depth study into the node-link diagram representation.
Three subtopics are explored within this space. The first is the problem of node layout, where the optimisation of a popular energy function, known as stress, is improved through an algorithm known as stochastic gradient descent.
The second is the method of edge bundling, where the idea of hierarchical edge bundling is explored in the absence of a known ground truth hierarchy. Its similarity to a topologically lossless bundling method known as power-confluent drawing is then leveraged, in order to improve technical problems with the underlying algorithms.
The final topic is an engineering application in the form of a serious game called EcoBuilder, which utilises the node-link diagram to visualise the dynamical behaviour of food webs. Its purpose is to crowdsource research through a citizen science approach, with outcomes in both visualisation and mathematical ecology.

TODOS:
- note somewhere that one of the ecobuilder sections will read like a user guide
- include Brandes and Kobourov papers to show impact of SGD (add an extra section?) (point 4)
- pages 35 and 39, pivotMDS is mentioned. this is a good point to first bring up initialisation (and point towards a new section, possibly in the Discussion)
- mention multilevel algorithms and why connected components are separated (no shortest path between them)
- Section 1.4.2, emphasise the badness of uniform colourmap more
- Add Daniel and James to acknowledgements
- make it clear that Bach et al. may never result in the problems presented
- conclusion should probably also emphasise ecobuilder as the main narrative driver

## Post-viva revisions:
requested:
1. Chapter numbers now start from 1.
2. For Chapter 2, the lack of a clear separation was caused by not placing the constraint relaxation literature in the Background section. This has now been refactored and reworded so that the Background section contains it. For Chapter 3, the same problem was caused by not placing the description of dissimilarity measures in the Background, and this has been similarly refactored. Chapter 4 has now moved the definitions of confluent drawing and the description of greedy agglomeration into its new Background section. Extra sentences and page breaks have further been added to emphasise the demarcation between background and new contributions.
3.
4.
5. An extra paragraph has been added to the start of Section 2.2, and the extra references have been added to Section 2.1. Comparing the method to different (non-hierarchical) methods has also been added to the discussion in 2.3.
6. An extra paragraph has been added to the start of Section 3.2, and the potential future work of analysing how often the pathological case occurs has been added to the discussion in Section 3.3 (third paragraph).
7.
8. Two extra paragraphs have been added to the Introduction, just before Section 1.1, in order to tie together the narrative of the thesis under the motivation of EcoBuilder.
9. Citations have been changed to the authoryear style.
10. These errors have all been fixed.

recommended:
1. TODO: mention that the bit where this can happen is not within scope for Bach et al.
2.
3. An extra paragraph has been added to Section 2.3.1 to elaborate the choice of pivot selection strategy.
4.
5.
 Chapter 2:
  a) The section title has been changed to be more specific to the problem at hand.
  b) Citations regarding what humans do when asked to draw a network have been added to the introductory section.
  c) A footnote has been added to the start of Section 2.1.1 to make clear that the optimisation interpretation is not novel.
 Chapter 3:
  a) "thus far" has been changed to "thus far in this thesis"
 Chapter 4:
  a) "Greedy agglomeration, again" has been changed to simply "Greedy agglomeration"