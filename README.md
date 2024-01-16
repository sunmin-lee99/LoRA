# LoRA

### 1. Install
```
pip install accelerate torchvision transformers datasets ftfy tensorboard
```

```
pip install diffusers
```

```
git clone https://github.com/huggingface/diffusers.git
```

### 2. Accelerate
```
accelerate config
```

### 3. Datasets
[Dataset](https://huggingface.co/datasets/lambdalabs/pokemon-blip-captions)

### 4. Download file
```
download train_lora.bash & inference.py
```

|- diffusers
|  |- examples
|  |  |- text_to_image
|  |  |  |- train_lora.bash
|  |  |  |- inference.py

### 5. Train
```
train_lora.sh
```

```
python inference.py
```

