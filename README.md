# GPT-Histories
Final project for CS 182 of fall 2023, with David, Bridget, Alex, and Alp.

# Final Paper:
[finetuning_history_182_final_project.pdf](https://github.com/user-attachments/files/18615329/finetuning_history_182_final_project.pdf)

# Environment details
The notebooks were executed in Python 3.9.18. Cuda 11.8 was used with Torch 2.1.0 on a Nvidia RTX 3080. A Cuda-compatible Nvidia GPU is required to tractably compute this notebook.
- Install Cuda at https://developer.nvidia.com/cuda-11-8-0-download-archive.
- The default 2.1.0 installation of torch doesn't seem to innately support Cuda (its version reads `'2.1.0+cpu'`), so specifying the version as `2.1.0+cu118` from a PyTorch software repository installs a Cuda-compatible installation.
  ```
  pip install torch==2.1.0+cu118 -f https://download.pytorch.org/whl/torch_stable.html
  ```
