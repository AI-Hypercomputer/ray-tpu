# Ray TPU

This is a repository containing utilities for running [Ray](https://www.ray.io/)
on Cloud TPUs. For more information about TPUs, please check out the official
Google Cloud documentation [here](https://cloud.google.com/tpu).

## Why this package?

TPUs are different from other accelerators like GPUs because they are
"pod-centric". Scheduling jobs and workloads on TPUs require awareness of slice
topologies and other factors. This package introduces higher level utilities
that simplify running Ray workloads on TPU pod slices as if they were single
nodes.

## Installation

Run the following command to install the package:
```
pip install ray-tpu
```

Check out the [tutorials section](https://github.com/AI-Hypercomputer/ray-tpu/tree/main/tutorials/0-basic%20tutorial) for more details.
