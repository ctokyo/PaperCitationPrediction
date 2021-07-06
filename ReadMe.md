## Dataset

- The dataset contains 384 ICLR papers' review texts and related  citing texts.

- The dataset consists of  ```citing_text.xlsx``` and ```ICLR_reviews.csv```

----

### ICLR_reviews.csv

The ICLR review texts come from the following paper:

*Li S, Zhao W X, Yin E J, et al. A neural citation count prediction model based on peer review text[C]//Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP). 2019: 4914-4924.*

<table>
  <tr>
    <th>sentence</th>
    <th>label</th>
    <th>id</th>
  </tr>
  <tr>
    <td>This paper introduces...</td>
    <td>1</td>
    <td>304</td>
  </tr>
  <tr>
    <td>Matrix Approximation...</td>
    <td>0</td>
    <td>305</td>
  </tr>
  <tr>
    <td>This paper focuses...</td>
    <td>1</td>
    <td>306</td>
 </table>
**sentence**: the ICLR paper's  review text

**label**: the review text's sentiment label

**id**: ICLR paper id

----

### citing_text.xlsx

The corresponding citing texts are collected by us.

<table>
  <tr>
    <th>id</th>
    <th>citing paper</th>
    <th>citing text</th>
  </tr>
  <tr>
    <td>304</td>
    <td>Inferring and Executing Programs for Visual Reasoning</td>
    <td>This paper fits...</td>
  </tr>
  <tr>
    <td>304</td>
    <td>Communication Algorithms via Deep Learning</td>
    <td>In this paper...</td>
  </tr>
  <tr>
    <td>304</td>
    <td>Programmable Agents</td>
    <td>The majority...</td>
 </table>

**id**: ICLR paper id

**citing paper**: ICLR paper's relevant citing paper

**citing text**: the citing text in the citing paper

