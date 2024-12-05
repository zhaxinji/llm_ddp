
```bash
# Anaconda3-2024.06-1
conda 24.1.2

conda create -n zhayongfu python=3.12

conda install pytorch torchvision torchaudio pytorch-cuda=12.4 -c pytorch -c nvidia

# 基础包
pip install scipy tqdm numpy pandas scikit-learn

# LLM相关包
pip install sentence_transformers setproctitle sentencepiece accelerate peft bitsandbytes transformers trl huggingface-hub 
```
