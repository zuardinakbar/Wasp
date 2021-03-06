# Wasp - Discrete Design for Grasshopper

![wasp logo](https://github.com/ar0551/Wasp/blob/master/Graphics/Logo_01_hexaBkg.png?raw=true)

Discrete Design with Grasshopper plug-in (GPL) initiated by Andrea Rossi

[![Stable](https://img.shields.io/github/v/release/ar0551/Wasp?label=stable&style=flat-square)]()
[![Wip](https://img.shields.io/github/v/release/ar0551/Wasp?include_prereleases&label=wip&style=flat-square)]()
[![Last Commit](https://img.shields.io/github/last-commit/ar0551/Wasp?style=flat-square)]()
[![Downloads](https://img.shields.io/github/downloads/ar0551/Wasp/total?style=flat-square)]()
[![License](https://img.shields.io/github/license/ar0551/Wasp?style=flat-square)]()

Wasp is a set of Grasshopper components, developed in Python, directed at representing and designing with discrete elements (Rossi and Tessmann 2017). This is achieved by combining geometric representation and abstract graph information (Klavins et al. 2004) of individual modules, as well as providing different procedures for modular aggregation.
The description of each individual part includes basic information necessary for the aggregation process (part geometry, connections location and orientation). The set of connections define the topological graph of the part, which is then used to define the possibilities of aggregation with other parts.

The core of the framework relies on a set of aggregation procedures, allowing generation of specific structures from the combination of different modules. Each of these procedures is composed of strategies for the selection of basic aggregation rules, described as an instruction to orient one module over a selected connection of another module. Currently available procedures include stochastic aggregation and field-driven aggregation.

# License
Wasp: Discrete Design with Grasshopper plug-in (GPL) initiated by Andrea Rossi

Copyright (c) 2017, Andrea Rossi

Wasp is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License version 3.0 as published by the Free Software Foundation. 

Wasp is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with Wasp; If not, see <http://www.gnu.org/licenses/>.

@license GPL-3.0 <https://www.gnu.org/licenses/gpl.html>

# Credits
![ddu logo](http://www.dg.architektur.tu-darmstadt.de/media/architektur/fachgruppe_b/ika/flash/DDU_Logo_Website_182x0.jpg)
Significant parts of Wasp have been developed by Andrea Rossi as part of research on digital materials and discrete design at DDU Digital Design Unit - Prof. Oliver Tessmann - Technische Universität Darmstadt (http://www.dg.architektur.tu-darmstadt.de/dg/startseite_3/index.de.jsp)

Wasp is heavily influenced by Ladybug (https://github.com/mostaphaRoudsari/ladybug), a free and open source environmental plugin for Grasshopper. It is using its code template, and follows the Labybug code organization. Some methods from Ladybug may have also been copied.

# References
Klavins, E, Ghrist, R and Lipsky, D. 2004. Graph grammars for self-assembling robotic systems. In Robotics and Automation, 2004. Proceedings. ICRA

Rossi, A and Tessmann, O. 2017. Designing with DigitalMaterials. In Proceedings of CAADRIA 2017, Suzhou.

Rossi A., Tessmann O. 2019. From Voxels to Parts: Hierarchical Discrete Modeling for Design and Assembly. In: Cocchiarella L. (eds) ICGG 2018 - Proceedings of the 18th International Conference on Geometry and Graphics. ICGG 2018. Advances in Intelligent Systems and Computing, vol 809. Springer, Cham

