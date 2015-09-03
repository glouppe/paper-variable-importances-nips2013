Understanding variable importances in forests of randomized trees
=================================================================

* Gilles Louppe <g.louppe@gmail.com>
* Louis Wehenkel <l.wehenkel@ulg.ac.be>
* Antonio Sutera <a.sutera@ulg.ac.be>
* Pierre Geurts <p.geurts@ulg.ac.be>

Despite growing interest and practical use in various scientific areas, variable
importances derived from tree-based ensemble methods are not well understood
from a theoretical point of view. In this work we characterize the Mean Decrease
Impurity (MDI) variable importances as measured by an ensemble of totally
randomized trees in asymptotic sample and ensemble size conditions. We derive a
three-level decomposition of the  information jointly provided by all input
variables about the output in terms of i) the MDI importance of each input
variable, ii) the degree of interaction of a given input variable with the other
input variables, iii) the different interaction terms of a given degree. We then
show that this MDI importance of a variable is equal to zero if and only if the
variable is irrelevant and that the MDI importance of a relevant variable is
invariant with respect to the removal or the addition of irrelevant variables.
We illustrate these properties on a simple example and discuss how they may
change in the case of  non-totally randomized trees such as Random Forests and
Extra-Trees.

Paper available at http://orbi.ulg.ac.be/handle/2268/155642

Please cite using the following BibTex entry:

```
@inproceedings{louppe2013understanding,
  title={Understanding variable importances in forests of randomized trees},
  author={Louppe, Gilles and Wehenkel, Louis and Sutera, Antonio and Geurts, Pierre},
  booktitle={Advances in Neural Information Processing Systems},
  pages={431--439},
  year={2013}
}
```

---

_Structure of the repository:_
- `code/`: Demo and source code.
- `paper/`: Latex files of the paper and supplementary materials.
- `poster/`: Latex files of the poster.

_License:_ BSD 3 clause

_Contact:_ Gilles Louppe (@glouppe, <g.louppe@gmail.com>)




