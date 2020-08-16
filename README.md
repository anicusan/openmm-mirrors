# openmm-mirrors
The official [OpenMM repository](https://github.com/openmm/openmm) acts as the development version of the code, while the stable versions are only provided as [zip files](https://github.com/openmm/openmm/releases) ([source](http://docs.openmm.org/latest/userguide/library.html#get-the-openmm-source-code)).

This repository hosts those stable versions independently - check its branches. This is helpful for using the OpenMM source code as a [git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules).

## OpenMM
[OpenMM](http://openmm.org) is a toolkit for molecular simulation. It can be used either as a stand-alone application for running simulations, or as a library you call from your own code. It provides a combination of extreme flexibility (through custom forces and integrators), openness, and high performance (especially on recent GPUs) that make it truly unique among simulation codes.

## Disclaimer
All rights go to Stanford University and the OpenMM Authors. The license section given in the [OpenMM documentation](http://docs.openmm.org/latest/userguide/library.html#license) is reproduced below.

## License
Two different licenses are used for different parts of OpenMM. The public API, the low level API, the reference platform, the CPU platform, and the application layer are all distributed under the MIT license. This is a very permissive license which allows them to be used in almost any way, requiring only that you retain the copyright notice and disclaimer when distributing them.

The CUDA and OpenCL platforms are distributed under the GNU Lesser General Public License (LGPL). This also allows you to use, modify, and distribute them in any way you want, but it requires you to also distribute the source code for your modifications. This restriction applies only to modifications to OpenMM itself; you need not distribute the source code to applications that use it.

OpenMM also uses several pieces of code that were written by other people and are covered by other licenses. All of these licenses are similar in their terms to the MIT license, and do not significantly restrict how OpenMM can be used.

All of these licenses may be found in the “licenses” directory included with OpenMM.

## Referencing OpenMM
Any work that uses OpenMM should cite the following publication:

> P. Eastman, J. Swails, J. D. Chodera, R. T. McGibbon, Y. Zhao, K. A. Beauchamp, L.-P. Wang, A. C. Simmonett, M. P. Harrigan, C. D. Stern, R. P. Wiewiora, B. R. Brooks, and V. S. Pande. “OpenMM 7: Rapid development of high performance algorithms for molecular dynamics.” PLOS Comp. Biol. 13(7): e1005659. (2017)