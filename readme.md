# awesome-go-cuda [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome go cuda projects and related material!


## Contents

- [idiomatic libraries](#idiomatic-libraries)
- [math/ml](#math-ml)
- [cgo](#cgo)
- [community](#community)
    - [early-parallization-ideas](#early-parallization-ideas)
- [alt](#alt)
    - [embedded-systems](#embedded-systems)
    - [fun](#fun)
- [cuda installation](#cuda-installation)
- [learn](#learn)
- [contribute](#Contribute)

## idiomatic-libraries

- [gorgonia-cu](https://github.com/gorgonia/cu/tree/master?tab=readme-ov-file) - error enhanced and revised to cuda-11 version of the `cu` library
- [cu](https://github.com/barnex/cuda5) - go bindings for cuda-5, inspiration `gorgonia-cu`.
- [cudagolabs](https://github.com/miguelzambrana/cudagolabs) - sample bindings to check `cu`

## math-ml

- [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#go) - in golang
- [gomlx](https://github.com/gomlx/gomlx) - an Accelerated ML and Math Framework (PyTorch/Jax/Tensorflow-like for Go)
- [go-featureprocessing](https://github.com/nikolaydubina/go-featureprocessing) no cgo, nor acceleration, but an example of go's strength in the ML arena

## cgo

About this section. Optional. Keep this short and focus on the list.

- [Standard Library](https://pkg.go.dev/cmd/cgo) - cgo as documented in the go standard library
- [The Go Blog](https://go.dev/blog/cgo) - cgo as originally introduced in the go blog
- [CGo Examples](https://github.com/andreiavrammsd/cgo-examples) - succinct examples of calling C routines from go, along with callbacks.
- [The CGO Call Boundary](https://github.com/graemenewlands/cgo-boundary) - an attempt at quantification of the cgo call boundary

## community

- [golang nuts](https://groups.google.com/g/golang-nuts/search?q=GPU) - the Google Group with associated GPU query
- [golang google*](https://www.google.com/search?q=site%3Agroups.google.com%2Fg%2Fgolang+gpu+cuda) - all the golang google groups
- [stackoverflow](https://stackoverflow.com/search?q=%5Bgolang%5D+gpu) - all stackoverflow GPU queries

### early-parallization-ideas 

- [vgo](https://github.com/remyoudompheng/go-vectops) - a compiler for vector operations
- [gopar](https://github.com/wetherbeei/gopar) - automatic loop parallization
- [gocublas](https://github.com/jbooth/gocublas/tree/master) - a simple early attempt at cublas support

## alt

- [go-opencl](https://pkg.go.dev/github.com/achilleasa/go-pathtrace/tracer/opencl) - opencl bindings for go, opencl offers acceleration on a broader set of hardware

### embedded-systems

- [periph](https://periph.io/) - embedded systems support for golang - does not use cgo

### fun

- [Game of Life](https://github.com/grahamjenson/cuda-gol/blob/main/main.cu) - the associated github repo of [Graham Jenson's](https://maori.geek.nz/game-of-life-cuda-vs-golang-5ca4ae6f1214) medium article.

## cuda-installation

- [CUDA Toolkit](https://developer.nvidia.com/cuda-downloads) - install the SDK
- [CUDA Samples](https://github.com/NVIDIA/cuda-samples/tree/master/Samples/1_Utilities) - bandwidthTest and deviceQuery not installed by default with the CUDA Toolkit
- [CUDA Library Samples](https://github.com/NVIDIA/CUDALibrarySamples) - detailed examples of every library type, cuTENSOR, cuSPARSE, etc..
- [Non Idiomatic Get Started](https://github.com/graemenewlands/go-cuda-helloworld) - this is an implementation of the GPU Hello World

## learn

- [Programming-Massively-Parallel-Processors](https://www.amazon.com/Programming-Massively-Parallel-Processors-Hands/dp/0323912311) - starts from first principles, designed for students with exercises
- [CUDA Handbook](https://www.amazon.com/CUDA-Handbook-Comprehensive-Guide-Programming/dp/0321809467) - relevent examples on memory management

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
