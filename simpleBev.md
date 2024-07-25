### 1. Extrinsics
---
```
Before models.common.Conv
torch.Size([1, 3, 640, 640])
After torch.Size([1, 32, 640, 640]) 

Before models.common.Conv
torch.Size([1, 32, 640, 640])
After torch.Size([1, 64, 320, 320]) 

Before models.common.Conv
torch.Size([1, 64, 320, 320])
After torch.Size([1, 64, 320, 320]) 

Before models.common.Conv
torch.Size([1, 64, 320, 320])
After torch.Size([1, 128, 160, 160]) 

Before models.common.Conv
torch.Size([1, 128, 160, 160])
After torch.Size([1, 64, 160, 160]) 

Before models.common.Conv
torch.Size([1, 128, 160, 160])
After torch.Size([1, 64, 160, 160]) 

Before models.common.Conv
torch.Size([1, 64, 160, 160])
After torch.Size([1, 64, 160, 160]) 

Before models.common.Conv
torch.Size([1, 64, 160, 160])
After torch.Size([1, 64, 160, 160]) 

Before models.common.Conv
torch.Size([1, 64, 160, 160])
After torch.Size([1, 64, 160, 160]) 

Before models.common.Conv
torch.Size([1, 64, 160, 160])
After torch.Size([1, 64, 160, 160]) 

Before List models.common.Concat
torch.Size([1, 64, 160, 160])
torch.Size([1, 64, 160, 160])
torch.Size([1, 64, 160, 160])
torch.Size([1, 64, 160, 160])
After torch.Size([1, 256, 160, 160]) 

Before models.common.Conv
torch.Size([1, 256, 160, 160])
After torch.Size([1, 256, 160, 160]) 

Before models.common.MP
torch.Size([1, 256, 160, 160])
After torch.Size([1, 256, 80, 80]) 

Before models.common.Conv
torch.Size([1, 256, 80, 80])
After torch.Size([1, 128, 80, 80]) 

Before models.common.Conv
torch.Size([1, 256, 160, 160])
After torch.Size([1, 128, 160, 160]) 

Before models.common.Conv
torch.Size([1, 128, 160, 160])
After torch.Size([1, 128, 80, 80]) 

Before List models.common.Concat
torch.Size([1, 128, 80, 80])
torch.Size([1, 128, 80, 80])
After torch.Size([1, 256, 80, 80]) 

Before models.common.Conv
torch.Size([1, 256, 80, 80])
After torch.Size([1, 128, 80, 80]) 

Before models.common.Conv
torch.Size([1, 256, 80, 80])
After torch.Size([1, 128, 80, 80]) 

Before models.common.Conv
torch.Size([1, 128, 80, 80])
After torch.Size([1, 128, 80, 80]) 

Before models.common.Conv
torch.Size([1, 128, 80, 80])
After torch.Size([1, 128, 80, 80]) 

Before models.common.Conv
torch.Size([1, 128, 80, 80])
After torch.Size([1, 128, 80, 80]) 

Before models.common.Conv
torch.Size([1, 128, 80, 80])
After torch.Size([1, 128, 80, 80]) 

Before List models.common.Concat
torch.Size([1, 128, 80, 80])
torch.Size([1, 128, 80, 80])
torch.Size([1, 128, 80, 80])
torch.Size([1, 128, 80, 80])
After torch.Size([1, 512, 80, 80]) 

Before models.common.Conv
torch.Size([1, 512, 80, 80])
After torch.Size([1, 512, 80, 80]) 

Before models.common.MP
torch.Size([1, 512, 80, 80])
After torch.Size([1, 512, 40, 40]) 

Before models.common.Conv
torch.Size([1, 512, 40, 40])
After torch.Size([1, 256, 40, 40]) 

Before models.common.Conv
torch.Size([1, 512, 80, 80])
After torch.Size([1, 256, 80, 80]) 

Before models.common.Conv
torch.Size([1, 256, 80, 80])
After torch.Size([1, 256, 40, 40]) 

Before List models.common.Concat
torch.Size([1, 256, 40, 40])
torch.Size([1, 256, 40, 40])
After torch.Size([1, 512, 40, 40]) 

Before models.common.Conv
torch.Size([1, 512, 40, 40])
After torch.Size([1, 256, 40, 40]) 

Before models.common.Conv
torch.Size([1, 512, 40, 40])
After torch.Size([1, 256, 40, 40]) 

Before models.common.Conv
torch.Size([1, 256, 40, 40])
After torch.Size([1, 256, 40, 40]) 

Before models.common.Conv
torch.Size([1, 256, 40, 40])
After torch.Size([1, 256, 40, 40]) 

Before models.common.Conv
torch.Size([1, 256, 40, 40])
After torch.Size([1, 256, 40, 40]) 

Before models.common.Conv
torch.Size([1, 256, 40, 40])
After torch.Size([1, 256, 40, 40]) 

Before List models.common.Concat
torch.Size([1, 256, 40, 40])
torch.Size([1, 256, 40, 40])
torch.Size([1, 256, 40, 40])
torch.Size([1, 256, 40, 40])
After torch.Size([1, 1024, 40, 40]) 

Before models.common.Conv
torch.Size([1, 1024, 40, 40])
After torch.Size([1, 1024, 40, 40]) 

Before models.common.MP
torch.Size([1, 1024, 40, 40])
After torch.Size([1, 1024, 20, 20]) 

Before models.common.Conv
torch.Size([1, 1024, 20, 20])
After torch.Size([1, 512, 20, 20]) 

Before models.common.Conv
torch.Size([1, 1024, 40, 40])
After torch.Size([1, 512, 40, 40]) 

Before models.common.Conv
torch.Size([1, 512, 40, 40])
After torch.Size([1, 512, 20, 20]) 

Before List models.common.Concat
torch.Size([1, 512, 20, 20])
torch.Size([1, 512, 20, 20])
After torch.Size([1, 1024, 20, 20]) 

Before models.common.Conv
torch.Size([1, 1024, 20, 20])
After torch.Size([1, 256, 20, 20]) 

Before models.common.Conv
torch.Size([1, 1024, 20, 20])
After torch.Size([1, 256, 20, 20]) 

Before models.common.Conv
torch.Size([1, 256, 20, 20])
After torch.Size([1, 256, 20, 20]) 

Before models.common.Conv
torch.Size([1, 256, 20, 20])
After torch.Size([1, 256, 20, 20]) 

Before models.common.Conv
torch.Size([1, 256, 20, 20])
After torch.Size([1, 256, 20, 20]) 

Before models.common.Conv
torch.Size([1, 256, 20, 20])
After torch.Size([1, 256, 20, 20]) 

Before List models.common.Concat
torch.Size([1, 256, 20, 20])
torch.Size([1, 256, 20, 20])
torch.Size([1, 256, 20, 20])
torch.Size([1, 256, 20, 20])
After torch.Size([1, 1024, 20, 20]) 

Before models.common.Conv
torch.Size([1, 1024, 20, 20])
After torch.Size([1, 1024, 20, 20]) 

Before models.common.SPPCSPC
torch.Size([1, 1024, 20, 20])
After torch.Size([1, 512, 20, 20]) 

Before models.common.Conv
torch.Size([1, 512, 20, 20])
After torch.Size([1, 256, 20, 20]) 

Before torch.nn.modules.upsampling.Upsample
torch.Size([1, 256, 20, 20])
After torch.Size([1, 256, 40, 40]) 

Before models.common.Conv
torch.Size([1, 1024, 40, 40])
After torch.Size([1, 256, 40, 40]) 

Before List models.common.Concat
torch.Size([1, 256, 40, 40])
torch.Size([1, 256, 40, 40])
After torch.Size([1, 512, 40, 40]) 

Before models.common.Conv
torch.Size([1, 512, 40, 40])
After torch.Size([1, 256, 40, 40]) 

Before models.common.Conv
torch.Size([1, 512, 40, 40])
After torch.Size([1, 256, 40, 40]) 

Before models.common.Conv
torch.Size([1, 256, 40, 40])
After torch.Size([1, 128, 40, 40]) 

Before models.common.Conv
torch.Size([1, 128, 40, 40])
After torch.Size([1, 128, 40, 40]) 

Before models.common.Conv
torch.Size([1, 128, 40, 40])
After torch.Size([1, 128, 40, 40]) 

Before models.common.Conv
torch.Size([1, 128, 40, 40])
After torch.Size([1, 128, 40, 40]) 

Before List models.common.Concat
torch.Size([1, 128, 40, 40])
torch.Size([1, 128, 40, 40])
torch.Size([1, 128, 40, 40])
torch.Size([1, 128, 40, 40])
torch.Size([1, 256, 40, 40])
torch.Size([1, 256, 40, 40])
After torch.Size([1, 1024, 40, 40]) 

Before models.common.Conv
torch.Size([1, 1024, 40, 40])
After torch.Size([1, 256, 40, 40]) 

Before models.common.Conv
torch.Size([1, 256, 40, 40])
After torch.Size([1, 128, 40, 40]) 

Before torch.nn.modules.upsampling.Upsample
torch.Size([1, 128, 40, 40])
After torch.Size([1, 128, 80, 80]) 

Before models.common.Conv
torch.Size([1, 512, 80, 80])
After torch.Size([1, 128, 80, 80]) 

Before List models.common.Concat
torch.Size([1, 128, 80, 80])
torch.Size([1, 128, 80, 80])
After torch.Size([1, 256, 80, 80]) 

Before models.common.Conv
torch.Size([1, 256, 80, 80])
After torch.Size([1, 128, 80, 80]) 

Before models.common.Conv
torch.Size([1, 256, 80, 80])
After torch.Size([1, 128, 80, 80]) 

Before models.common.Conv
torch.Size([1, 128, 80, 80])
After torch.Size([1, 64, 80, 80]) 

Before models.common.Conv
torch.Size([1, 64, 80, 80])
After torch.Size([1, 64, 80, 80]) 

Before models.common.Conv
torch.Size([1, 64, 80, 80])
After torch.Size([1, 64, 80, 80]) 

Before models.common.Conv
torch.Size([1, 64, 80, 80])
After torch.Size([1, 64, 80, 80]) 

Before List models.common.Concat
torch.Size([1, 64, 80, 80])
torch.Size([1, 64, 80, 80])
torch.Size([1, 64, 80, 80])
torch.Size([1, 64, 80, 80])
torch.Size([1, 128, 80, 80])
torch.Size([1, 128, 80, 80])
After torch.Size([1, 512, 80, 80]) 

Before models.common.Conv
torch.Size([1, 512, 80, 80])
After torch.Size([1, 128, 80, 80]) 

Before models.common.MP
torch.Size([1, 128, 80, 80])
After torch.Size([1, 128, 40, 40]) 

Before models.common.Conv
torch.Size([1, 128, 40, 40])
After torch.Size([1, 128, 40, 40]) 

Before models.common.Conv
torch.Size([1, 128, 80, 80])
After torch.Size([1, 128, 80, 80]) 

Before models.common.Conv
torch.Size([1, 128, 80, 80])
After torch.Size([1, 128, 40, 40]) 

Before List models.common.Concat
torch.Size([1, 128, 40, 40])
torch.Size([1, 128, 40, 40])
torch.Size([1, 256, 40, 40])
After torch.Size([1, 512, 40, 40]) 

Before models.common.Conv
torch.Size([1, 512, 40, 40])
After torch.Size([1, 256, 40, 40]) 

Before models.common.Conv
torch.Size([1, 512, 40, 40])
After torch.Size([1, 256, 40, 40]) 

Before models.common.Conv
torch.Size([1, 256, 40, 40])
After torch.Size([1, 128, 40, 40]) 

Before models.common.Conv
torch.Size([1, 128, 40, 40])
After torch.Size([1, 128, 40, 40]) 

Before models.common.Conv
torch.Size([1, 128, 40, 40])
After torch.Size([1, 128, 40, 40]) 

Before models.common.Conv
torch.Size([1, 128, 40, 40])
After torch.Size([1, 128, 40, 40]) 

Before List models.common.Concat
torch.Size([1, 128, 40, 40])
torch.Size([1, 128, 40, 40])
torch.Size([1, 128, 40, 40])
torch.Size([1, 128, 40, 40])
torch.Size([1, 256, 40, 40])
torch.Size([1, 256, 40, 40])
After torch.Size([1, 1024, 40, 40]) 

Before models.common.Conv
torch.Size([1, 1024, 40, 40])
After torch.Size([1, 256, 40, 40]) 

Before models.common.MP
torch.Size([1, 256, 40, 40])
After torch.Size([1, 256, 20, 20]) 

Before models.common.Conv
torch.Size([1, 256, 20, 20])
After torch.Size([1, 256, 20, 20]) 

Before models.common.Conv
torch.Size([1, 256, 40, 40])
After torch.Size([1, 256, 40, 40]) 

Before models.common.Conv
torch.Size([1, 256, 40, 40])
After torch.Size([1, 256, 20, 20]) 

Before List models.common.Concat
torch.Size([1, 256, 20, 20])
torch.Size([1, 256, 20, 20])
torch.Size([1, 512, 20, 20])
After torch.Size([1, 1024, 20, 20]) 

Before models.common.Conv
torch.Size([1, 1024, 20, 20])
After torch.Size([1, 512, 20, 20]) 

Before models.common.Conv
torch.Size([1, 1024, 20, 20])
After torch.Size([1, 512, 20, 20]) 

Before models.common.Conv
torch.Size([1, 512, 20, 20])
After torch.Size([1, 256, 20, 20]) 

Before models.common.Conv
torch.Size([1, 256, 20, 20])
After torch.Size([1, 256, 20, 20]) 

Before models.common.Conv
torch.Size([1, 256, 20, 20])
After torch.Size([1, 256, 20, 20]) 

Before models.common.Conv
torch.Size([1, 256, 20, 20])
After torch.Size([1, 256, 20, 20]) 

Before List models.common.Concat
torch.Size([1, 256, 20, 20])
torch.Size([1, 256, 20, 20])
torch.Size([1, 256, 20, 20])
torch.Size([1, 256, 20, 20])
torch.Size([1, 512, 20, 20])
torch.Size([1, 512, 20, 20])
After torch.Size([1, 2048, 20, 20]) 

Before models.common.Conv
torch.Size([1, 2048, 20, 20])
After torch.Size([1, 512, 20, 20]) 

Before models.common.RepConv
torch.Size([1, 128, 80, 80])
After torch.Size([1, 256, 80, 80]) 

Before models.common.RepConv
torch.Size([1, 256, 40, 40])
After torch.Size([1, 512, 40, 40]) 

Before models.common.RepConv
torch.Size([1, 512, 20, 20])
After torch.Size([1, 1024, 20, 20]) 

torch.Size([1, 1024, 20, 20])
```

```
backbone:
  # [from, number, module, args]
  [[-1, 1, Conv, [32, 3, 1]],  # 0
  
   [-1, 1, Conv, [64, 3, 2]],  # 1-P1/2      
   [-1, 1, Conv, [64, 3, 1]],
   
   [-1, 1, Conv, [128, 3, 2]],  # 3-P2/4  
   [-1, 1, Conv, [64, 1, 1]],
   [-2, 1, Conv, [64, 1, 1]],
   [-1, 1, Conv, [64, 3, 1]],
   [-1, 1, Conv, [64, 3, 1]],
   [-1, 1, Conv, [64, 3, 1]],
   [-1, 1, Conv, [64, 3, 1]],
   [[-1, -3, -5, -6], 1, Concat, [1]],
   [-1, 1, Conv, [256, 1, 1]],  # 11
         
   [-1, 1, MP, []],
   [-1, 1, Conv, [128, 1, 1]],
   [-3, 1, Conv, [128, 1, 1]],
   [-1, 1, Conv, [128, 3, 2]],
   [[-1, -3], 1, Concat, [1]],  # 16-P3/8  
   [-1, 1, Conv, [128, 1, 1]],
   [-2, 1, Conv, [128, 1, 1]],
   [-1, 1, Conv, [128, 3, 1]],
   [-1, 1, Conv, [128, 3, 1]],
   [-1, 1, Conv, [128, 3, 1]],
   [-1, 1, Conv, [128, 3, 1]],
   [[-1, -3, -5, -6], 1, Concat, [1]],
   [-1, 1, Conv, [512, 1, 1]],  # 24
         
   [-1, 1, MP, []],
   [-1, 1, Conv, [256, 1, 1]],
   [-3, 1, Conv, [256, 1, 1]],
   [-1, 1, Conv, [256, 3, 2]],
   [[-1, -3], 1, Concat, [1]],  # 29-P4/16  
   [-1, 1, Conv, [256, 1, 1]],
   [-2, 1, Conv, [256, 1, 1]],
   [-1, 1, Conv, [256, 3, 1]],
   [-1, 1, Conv, [256, 3, 1]],
   [-1, 1, Conv, [256, 3, 1]],
   [-1, 1, Conv, [256, 3, 1]],
   [[-1, -3, -5, -6], 1, Concat, [1]],
   [-1, 1, Conv, [1024, 1, 1]],  # 37
         
   [-1, 1, MP, []],
   [-1, 1, Conv, [512, 1, 1]],
   [-3, 1, Conv, [512, 1, 1]],
   [-1, 1, Conv, [512, 3, 2]],
   [[-1, -3], 1, Concat, [1]],  # 42-P5/32  
   [-1, 1, Conv, [256, 1, 1]],
   [-2, 1, Conv, [256, 1, 1]],
   [-1, 1, Conv, [256, 3, 1]],
   [-1, 1, Conv, [256, 3, 1]],
   [-1, 1, Conv, [256, 3, 1]],
   [-1, 1, Conv, [256, 3, 1]],
   [[-1, -3, -5, -6], 1, Concat, [1]],
   [-1, 1, Conv, [1024, 1, 1]],  # 50
  ]

# yolov7 head
head:
  [[-1, 1, SPPCSPC, [512]], # 51
  
   [-1, 1, Conv, [256, 1, 1]],
   [-1, 1, nn.Upsample, [None, 2, 'nearest']],
   [37, 1, Conv, [256, 1, 1]], # route backbone P4
   [[-1, -2], 1, Concat, [1]],
   
   [-1, 1, Conv, [256, 1, 1]],
   [-2, 1, Conv, [256, 1, 1]],
   [-1, 1, Conv, [128, 3, 1]],
   [-1, 1, Conv, [128, 3, 1]],
   [-1, 1, Conv, [128, 3, 1]],
   [-1, 1, Conv, [128, 3, 1]],
   [[-1, -2, -3, -4, -5, -6], 1, Concat, [1]],
   [-1, 1, Conv, [256, 1, 1]], # 63
   
   [-1, 1, Conv, [128, 1, 1]],
   [-1, 1, nn.Upsample, [None, 2, 'nearest']],
   [24, 1, Conv, [128, 1, 1]], # route backbone P3
   [[-1, -2], 1, Concat, [1]],
   
   [-1, 1, Conv, [128, 1, 1]],
   [-2, 1, Conv, [128, 1, 1]],
   [-1, 1, Conv, [64, 3, 1]],
   [-1, 1, Conv, [64, 3, 1]],
   [-1, 1, Conv, [64, 3, 1]],
   [-1, 1, Conv, [64, 3, 1]],
   [[-1, -2, -3, -4, -5, -6], 1, Concat, [1]],
   [-1, 1, Conv, [128, 1, 1]], # 75
      
   [-1, 1, MP, []],
   [-1, 1, Conv, [128, 1, 1]],
   [-3, 1, Conv, [128, 1, 1]],
   [-1, 1, Conv, [128, 3, 2]],
   [[-1, -3, 63], 1, Concat, [1]],
   
   [-1, 1, Conv, [256, 1, 1]],
   [-2, 1, Conv, [256, 1, 1]],
   [-1, 1, Conv, [128, 3, 1]],
   [-1, 1, Conv, [128, 3, 1]],
   [-1, 1, Conv, [128, 3, 1]],
   [-1, 1, Conv, [128, 3, 1]],
   [[-1, -2, -3, -4, -5, -6], 1, Concat, [1]],
   [-1, 1, Conv, [256, 1, 1]], # 88
      
   [-1, 1, MP, []],
   [-1, 1, Conv, [256, 1, 1]],
   [-3, 1, Conv, [256, 1, 1]],
   [-1, 1, Conv, [256, 3, 2]],
   [[-1, -3, 51], 1, Concat, [1]],
   
   [-1, 1, Conv, [512, 1, 1]],
   [-2, 1, Conv, [512, 1, 1]],
   [-1, 1, Conv, [256, 3, 1]],
   [-1, 1, Conv, [256, 3, 1]],
   [-1, 1, Conv, [256, 3, 1]],
   [-1, 1, Conv, [256, 3, 1]],
   [[-1, -2, -3, -4, -5, -6], 1, Concat, [1]],
   [-1, 1, Conv, [512, 1, 1]], # 101
   
   [75, 1, RepConv, [256, 3, 1]],
   [88, 1, RepConv, [512, 3, 1]],
   [101, 1, RepConv, [1024, 3, 1]],

   [[102,103,104], 1, IDetect, [nc, anchors]],   # Detect(P3, P4, P5)
  ]
# parameters
nc: 80  # number of classes
depth_multiple: 1.0  # model depth multiple
width_multiple: 1.0  # layer channel multiple

# anchors
anchors:
  - [12,16, 19,36, 40,28]  # P3/8
  - [36,75, 76,55, 72,146]  # P4/16
  - [142,110, 192,243, 459,401]  # P5/32
```

