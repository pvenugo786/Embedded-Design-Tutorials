.. 
   

.. meta::
   :keywords: Vitis, tutorials, core, development
   :description: Learn how to develop accelerated applications using the Vitis core development kit.
   :xlnxdocumentclass: Document
   :xlnxdocumenttype: Tutorials
   

   

Overview
###########


.. _Getting Started:


Getting Started Pathway
========================

Learn how to `develop accelerated applications using the Vitis core development kit <./vitis-getting-started/README.html>`__.

.. toctree::
   :maxdepth: 5
   :caption: Getting Started Pathway
   :hidden:

   1-introduction
   2-system-performance-modeling-project
   3-monitor-framework
   4-getting-started-with-SPM
   5-evaluating-software-performance
   6-evaluating-high-performance-ports
   7-evaluating-DDR-controller-settings
   8-evaluating-memory-hierarchy-ACP
   9-working-with-custom-target
   10-end-to-end-performance-analysis
   A-performance-checklist
   
      
   
.. _Intermediate:

Intermediate
=============

.. list-table:: 
   :widths: 30 20 50
   :header-rows: 1

   * - Tutorial
     - Kernel
     - Description

   * - `Getting Started with RTL Kernels <./getting-started-rtl-kernels/README.html>`__
     - RTL
     - This tutorial demonstrates how to use the Vitis core development kit to program an RTL kernel into an FPGA and build a Hardware Emulation using a common development flow.

   * - `Vitis HLS Analysis and Optimization <./vitis_hls_analysis/README.html>`__
     - C
     - This tutorial demonstrates how you can use the Vitis HLS tool GUI to build, analyze, and optimize a hardware kernel.

   * - `Mixing C and RTL <./mixing-c-rtl-kernels/README.html>`__
     - C and RTL
     - This tutorial demonstrates working with an application containing RTL and OpenCL kernels to familiarize yourself with the Vitis core development kit flow, along with various design analysis features.

   * - `Using Multiple Compute Units <using-multiple-cu/README.html>`__
     - C and RTL
     - This tutorial demonstrates the flexible kernel linking process to increase the number of kernel instances on an FPGA, which improves the parallelism in a combined host-kernel system.  

   * - `Host Code Optimization <host-code-opt/README.html>`__
     - C and RTL
     - This tutorial demonstrates applying host code optimization techniques to your design.

   * - `Using Multiple DDR Banks <mult-ddr-banks/README.html>`__
     - C and RTL
     - This tutorial demonstrates how using multiple DDRs can improve data transfer between kernels and global memory.  

.. toctree::
   :maxdepth: 5
   :caption: Intermediate
   :hidden:

   getting-started-rtl-kernels/README
   vitis_hls_analysis/README
   mixing-c-rtl-kernels/README
   using-multiple-cu/README
   host-code-opt/README
   mult-ddr-banks/README


.. _Advanced:

Advanced
=========


.. list-table:: 
   :widths: 30 20 50
   :header-rows: 1

   * - Tutorial
     - Kernel
     - Description

   * - `Controlling Vivado Implementation <./controlling-vivado-impl/README.html>`__
     - RTL
     - This tutorial demonstrates how you can control the Vivado® tools flow when implementing your project.

.. toctree::
   :maxdepth: 2
   :caption: Advanced
   :hidden:

   controlling-vivado-impl/README

.. _Versions:

.. toctree::
   :maxdepth: 2
   :caption: Versions
   :hidden:


   Master <https://xilinx.github.io/Vitis-Tutorials/2020-1/docs/README.html>
   
   2019.2 <https://github.com/Xilinx/Vitis-Tutorials/blob/Vitis-Tutorials-2019.2-Hotfix1/README.md>

      
	 


   