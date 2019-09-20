
=======
Program
=======


June 20, 2019, Thursday

* 14:00 -- 14:05 Introduction (Hartwig Anzt): [ `PDF <../presentations/SDASC19.pdf>`_ ]

* 14:05 -- 14:55 Keynote: Dhabaleswar K. (DK) Panda (The Ohio State University)

  **Title:** Scalable and Distributed DNN Training on Modern HPC Systems: Challenges and Solutions
  [ `PDF <../presentations/sdas19_distributed_training_dk.pdf>`_ ]

  **Abstract:** This talk will start with an overview of challenges being faced by
  the AI community to achieve scalable and distributed DNN training on Modern
  HPC systems. Next, an overview of the emerging HPC technologies will be
  provided. Next, we will focus on a range of solutions to bring together HPC
  and Deep Learning together to address the challenges in scalable and
  distributed DNN training. Solutions along the following directions will be
  presented: 1) MPI-driven Deep Learning for CPU- based and GPU-based clusters,
  2) Co-designing Deep Learning Stacks with High-Performance MPI, 3)
  Out-of-core DNN training, 4) Accelerating TensorFlow over gRPC on HPC
  Systems, and 5) Efficient Deep Learning over Big Data Stacks like Spark and
  Hadoop.

  **Speaker short Bio:** DK Panda is a Professor and University Distinguished
  Scholar of Computer Science and Engineering at the Ohio State University. He
  has published over 450 papers in the area of high-end computing and
  networking.  The MVAPICH2 (High Performance MPI and PGAS over InfiniBand,
  Omni-Path, iWARP and RoCE) libraries, designed and developed by his research
  group (http://mvapich.cse.ohio-state.edu), are currently being used by more
  than 3,000 organizations worldwide (in 88 countries). More than 540,000
  downloads of this software have taken place from the project's site. This
  software is empowering several InfiniBand clusters (including the 3rd, 14th,
  17th, and 27th ranked ones) in the TOP500 list. The RDMA packages for Apache
  Spark, Apache Hadoop and Memcached together with OSU HiBD benchmarks from his
  group (http://hibd.cse.ohio-state.edu) are also publicly available. These
  libraries are currently being used by more than 310 organizations in 35
  countries. More than 30,000 downloads of these libraries have taken place.
  High-performance and scalable versions of the Caffe and TensorFlow framework
  are available from https://hidl.cse.ohio-state.edu. Prof. Panda is an IEEE
  Fellow. More details about Prof. Panda are available at
  http://www.cse.ohio-state.edu/~panda.


* 14:55 -- 15:00 *Question/Answers session*

* 15:00 -- 15:30 Paper 1: Kushal Datta, **Training Multiscale-CNN for Large Microscopy Image Classification in One Hour**
  [ `PDF <../presentations/SDASC2019_v1_0.pdf>`_ ]

* 15:30 -- 16:00 Paper 2: Valentin Kozlov, **Benchmarking Deep Learning Infrastructures by the Means of Tensorflow and Containers**
  [ `PDF <../presentations/BenchmarkingDLinfrastructures.pdf>`_ ]

* 16:00 -- 16:30 *Coffee break*

* 16:30 -- 17:20 Invited Talk: Kai Krajsek (Juelich Supercomputing Centre, Forschungszentrum Jülich GmbH)

  **Title:** The Helmholtz Analytics Toolkit (HeAT) - A HPC Library for Scientific Big Data Analytics

  **Abstract:** This talk presents the Helmholtz Analytics Toolkit (HeAT), a
  HPC data analytics library for scientific applications. HeAT builds on top of
  PyTorch which provides many required features such as automatic
  differentiation, CPU and GPU support, linear algebra operations and basic MPI
  functionalities. However, distributed computations must be designed by hand
  for each basic communication and furthermore PyTorch implements only a subset
  of MPI functionalities. HeAT starts at this point providing a distributed
  tensor data object on which operations can be performed. The tensor data
  objects reside either on the CPU or on the GPU and, if desired, are
  distributed over various nodes. Operations on tensor objects are transparent
  to the user, i.e.  they remain the same irrespective of whether the HeAT data
  object resides on a single node or if it is distributed over several nodes.
  On the basis of this core structure, HeAT implements typical data analytics
  methods motivated from various scientific use cases.

  After motivating the framework and specifying its scope, the talk describes
  its concept and its realization in detail. The presentation demonstrates the
  usage of HeAT by means of several typical examples from data analytics. The
  presentation closes with a discussion on the downsides, further developments
  and future challenges of HeAT.

* 17:20 -- 17:50 Paper 3: Stanimire Tomov, **MagmaDNN: Towards High-Performance Data Analytics and Machine Learning for Data-Driven Scientific Computing**
  [ `PDF <../presentations/ISC19-ScaleML-Tomov.pdf>`_ ]

* 17:50 -- 18:00 Closing remarks (Hartwig Anzt)

*SDASC 2019 Workshop concludes*
