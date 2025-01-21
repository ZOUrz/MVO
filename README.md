# MVO

```
conda create -n dpt-vo python=3.8
conda activate dpt-vo
```

```
conda install pytorch==1.8.1 torchvision==0.9.1 torchaudio==0.8.1 cudatoolkit=10.2
```

or

```
conda install pytorch==1.8.1 torchvision==0.9.1 torchaudio==0.8.1 cudatoolkit=11.3
```

```
python
```

```
import torch
print(torch.cuda.is_available())
print(torch.backends.cudnn.is_available())
print(torch.version.cuda)
print(torch.backends.cudnn.version())
```

```
pip install opencv-python==4.5.2.54
pip install timm==0.4.5
pip install tqdm==4.64.0
pip install matplotlib==3.5.2
pip install scikit-learn
```


