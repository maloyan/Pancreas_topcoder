# [Pancreatic Cancer Detection Challenge](https://www.topcoder.com/challenges/a96a2d2e-2b0c-4864-872b-3086242ee0ef)

To accomplish this goal, proposed algorithms would have to initially be able to accurately auto-segment the boundaries of pancreatic tumors and 3 major peripancreatic blood vessels [superior mesenteric artery (SMA), celiac axis/common hepatic artery continuum (CA/CHA), and superior mesenteric vein/portal vein continuum (SMV/PV)]

![Image](https://lh3.googleusercontent.com/8Xp5DVSu1T6tVWgkLQhMFbWUQ--FNQ6hD2TnMEwoDRL95MSPV7Bsv2Drlq8boFuFZjxdR6BP4BqI2dygUPQD0FnGLVmA9oQS0BHBpkFV9m0R3W2ZilSEscL5_DNUvPHO3I4QoqFO)

# My result
##### 55.47595 on public leaderboard - 14 place
Tumor segmentation example

![Tumor segmentation](https://github.com/maloyan/mri_topcoder/blob/master/segmentation_example.png)

# Files to download 
###### Project structure
├── [unetplusplus-resnet34\_best\_model.pth](https://drive.google.com/file/d/1rEsGESUilxBN8GgJVWouG0zfSXb3Efd8/view?usp=sharing)

├── experiments.ipynb

├── [train](https://drive.google.com/file/d/1VATCc18rOy8s5bD_ELxHCC4EbO0l91zU/view)

└── [test](https://drive.google.com/file/d/1ovHmEUFUXgXM7XLWR9PcnbYaepb_migT/view)

# How to improve:
- Blend with EfficientNetB2 Unet/Unet++
- Sampling 0.7 with tumor, 0.3 without tumor
- Random sized crop around tumor
