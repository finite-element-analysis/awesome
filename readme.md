# finite-element-analysis [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A currated list of open-source tools that facilitate using Galerkin techniques
> like finite element analysis to solve partial differential equations. 

This list is designed to complement the excellent
[finite-element-methods](https://github.com/tkoyama010/awesome-finite-elements) list,
which emphasizes applications to structural problems as well as pre- and post-processing.


## Contents

- [Linear](#Linear)
- [Continuua](#Continuua)
- [Conduction](#conduction)


### Linear

Platforms centered around linear problems with the form:

$$
\mathbb{L} \boldsymbol{u} = \boldsymbol{f}
$$

- [List item](http://example.com)
- [List item](http://example.com)

### Continuua

Platforms centered around non-linear problems with the form:

$$
\mathrm{div}~ \boldsymbol{\sigma} = \boldsymbol{f}
$$

- [felupe](https://github.com/adtzlr/felupe)
- [dolfinx](http://example.com)
- [OpenSees](https://github.com/OpenSees/OpenSees)


### Conduction

$$
\nabla u = f
$$

- [dolfinx](https://github.com/FEniCS/dolfinx)



## Rendering

- [f3d](https://f3d.app/) - Cross-platform, fast, and minimalist 3D viewer with scientific visualization tools.
  (C++, BSD, [GitHub](https://github.com/f3d-app/f3d))
- [veux](https://github.com/stairlab/veux) - Python library for building glTF representations of finite element models
- [Polyscope](https://polyscope.run/) - Viewer and user interface for 3D geometry processing.
  (C++, MIT, [GitHub](https://github.com/nmwsharp/polyscope))
- [yt](https://yt-project.org/) - Toolkit for analysis and visualization of volumetric data.
  (Python, BSD, [GitHub](https://github.com/yt-project/yt))
- [TTK](https://topology-tool-kit.github.io/) - Topological data analysis and visualization.
  (C++/Python, BSD, [GitHub](https://github.com/topology-tool-kit/ttk))
- [morphologica](https://github.com/ABRG-Models/morphologica) - Header-only, modern OpenGL code to visualize numerical simulations at runtime. (C++, Apache 2.0, GitHub)

VTK based:
- [VTK](https://vtk.org/) - Process images and create 3D computer graphics.
  (C++, BSD, [GitLab](https://gitlab.kitware.com/vtk/vtk))
- [PyVista](https://docs.pyvista.org/) - 3D plotting and mesh analysis through a streamlined interface for VTK.
  (Python, MIT, [GitHub](https://github.com/pyvista/pyvista))
- [vedo](https://vedo.embl.es) - Python module for scientific analysis of 3D data based on VTK and Numpy
  (Python, MIT, [GitHub](https://github.com/marcomusy/vedo))
- [ParaView](https://www.paraview.org) - GUI application based on VTK.
  (C++, BSD, [GitLab](https://gitlab.kitware.com/paraview/paraview))

## Meshing

### 2D

Distmesh
- Distmesh
- dmsh
- pydistmesh

Triangle
- triangle
- cytriangle

### 3D

- gmsh


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
