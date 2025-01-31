.. meta::
  :description: ROCm installation for Linux
  :keywords: ROCm installation, AMD, ROCm, Package manager, AMDGPU

.. _rocm-install-home:

****************************************************************
ROCm installation for Linux
****************************************************************

This section describes the ROCm for Linux installation options.

.. note::

    Like AMD Instinct accelerators, AMD Radeon and Radeon Pro GPUs can be used in environments for compute purposes (no display information or graphics). If using AMD Radeon or Radeon Pro GPUs with ROCm for graphics-related purposes (for example, display connected), review the `Radeon installation instructions <https://rocm.docs.amd.com/projects/radeon/en/latest/index.html>`_ in the Use ROCm on Radeon GPU documentation to confirm system requirements.
    

.. grid:: 2
    :gutter: 3

    .. grid-item-card:: Install ROCm
      
       * :doc:`Quick start <install/quick-start>` - recommended for new users
       * :doc:`Detailed install <install/detailed-install>` - includes explanations

    .. grid-item-card:: Install deep learning frameworks

       * :doc:`PyTorch <install/3rd-party/pytorch-install>`
       * :doc:`TensorFlow <install/3rd-party/tensorflow-install>`
       * :doc:`JAX <install/3rd-party/jax-install>`


The documentation is structured as follows:

.. grid:: 2
    :gutter: 3

    .. grid-item-card:: How to

        * :doc:`Run Docker containers <how-to/docker>`
        * :doc:`Use Spack <how-to/spack>`

    .. grid-item-card:: Reference

        * :doc:`reference/docker-image-support-matrix`
        * :doc:`reference/package-manager-integration`
        * :doc:`reference/system-requirements`
        * :doc:`reference/3rd-party-support-matrix`
        * :doc:`Troubleshooting <reference/install-faq>`
        * :doc:`reference/user-kernel-space-compat-matrix`
        
