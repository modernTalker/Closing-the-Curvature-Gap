# Closing the Curvature Gap: Full Transformer Hessians and Their Implications for Scaling Laws

<!-- Change `modernTalker/2025-Project-182` to `intsystems/your-repository`-->
[![License](https://badgen.net/github/license/modernTalker/2025-Project-182?color=green)](https://github.com/modernTalker/2025-Project-182/blob/main/LICENSE)
[![GitHub Contributors](https://img.shields.io/github/contributors/modernTalker/2025-Project-182)](https://github.com/modernTalker/2025-Project-182/graphs/contributors)
[![GitHub Issues](https://img.shields.io/github/issues-closed/modernTalker/2025-Project-182.svg?color=0088ff)](https://github.com/modernTalker/2025-Project-182/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr-closed/modernTalker/2025-Project-182.svg?color=7f29d6)](https://github.com/modernTalker/2025-Project-182/pulls)

<table>
    <tr>
        <td align="left"> <b> Author </b> </td>
        <td> Egor Petrov </td>
    </tr>
    <tr>
        <td align="left"> <b> Consultant </b> </td>
        <td> Nikita Kiselev </td>
    </tr>
    <tr>
        <td align="left"> <b> Advisor </b> </td>
        <td> Andrey Grabovoy, PhD </td>
    </tr>
</table>

## Assets

- [LinkReview](LINKREVIEW.md)
- [Code](code)
- [Paper](paper)
- [Slides](slides)

## Abstract

The lack of theoretical results for Layer Normalization and feedforward Hessians
has left a gap in the study of Transformer optimization landscapes. We address
this by deriving explicit second-order expressions for these components, thereby
completing the Hessian characterization of full Transformer blocks. Our results
generalize prior self-attention analyses and yield estimations for the role of each
sublayer in curvature propagation. We demonstrate how these Hessian structures
inform both convergence dynamics and the empirical scaling laws governing largemodel performance. 
Further, we propose a Taylor-expansion–based framework 
for analyzing loss differences to quantify convergence trajectories. By extending
Hessian theory to the full Transformer architecture, this work establishes a new
foundation for theoretical and empirical investigations of optimization in large-scale
deep learning.

## Citation

If you find our work helpful, please cite us.
```BibTeX
@misc{petrov2025closingcurvaturegaptransformer,
      title={Closing the Curvature Gap: Full Transformer Hessians and Their Implications for Scaling Laws}, 
      author={Egor Petrov and Nikita Kiselev and Vladislav Meshkov and Andrey Grabovoy},
      year={2025},
      eprint={2510.16927},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2510.16927}, 
}
```

## Licence

Our project is MIT licensed. See [LICENSE](LICENSE) for details.
