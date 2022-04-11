# KerasOpenCL
An implementation of Keras using OpenCL. You must have PlaidML installed (instructions here: https://github.com/plaidml/plaidml). The code was tested on an AMD Radeon Pro 5300 M GPU on MacBook Pro 16-inch running MacOS Monterey. In the code, make sure to replace the pathname with your own.

TensorFlow was essentially built to be used with NVIDIA drivers and NVIDIA-proprietary GPUs, however, using the technology of OpenCL we can change Keras with a backend of TensorFlow with OpenCL. PlaidML makes OpenCL extremely accessible with a simplified UX to setup on your own machine.
