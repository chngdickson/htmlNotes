## Column 1

```
torch.Size([1, 3, 448, 640])
[0] models.common.Conv 
Before
-1 : torch.Size([1, 3, 448, 640])
After
 torch.Size([1, 32, 448, 640]) 

[1] models.common.Conv 
Before
0 : torch.Size([1, 32, 448, 640])
After
 torch.Size([1, 64, 224, 320]) 

[2] models.common.Conv 
Before
1 : torch.Size([1, 64, 224, 320])
After
 torch.Size([1, 64, 224, 320]) 

[3] models.common.Conv 
Before
2 : torch.Size([1, 64, 224, 320])
After
 torch.Size([1, 128, 112, 160]) 

[4] models.common.Conv 
Before
3 : torch.Size([1, 128, 112, 160])
After
 torch.Size([1, 64, 112, 160]) 

[5] models.common.Conv 
Before
3 : torch.Size([1, 128, 112, 160])
After
 torch.Size([1, 64, 112, 160]) 

[6] models.common.Conv 
Before
5 : torch.Size([1, 64, 112, 160])
After
 torch.Size([1, 64, 112, 160]) 

[7] models.common.Conv 
Before
6 : torch.Size([1, 64, 112, 160])
After
 torch.Size([1, 64, 112, 160]) 

[8] models.common.Conv 
Before
7 : torch.Size([1, 64, 112, 160])
After
 torch.Size([1, 64, 112, 160]) 

[9] models.common.Conv 
Before
8 : torch.Size([1, 64, 112, 160])
After
 torch.Size([1, 64, 112, 160]) 

[10] models.common.Concat 
Before
9 : torch.Size([1, 64, 112, 160])
7 : torch.Size([1, 64, 112, 160])
5 : torch.Size([1, 64, 112, 160])
4 : torch.Size([1, 64, 112, 160])
After
 torch.Size([1, 256, 112, 160]) 

[11] models.common.Conv 
Before
10 : torch.Size([1, 256, 112, 160])
After
 torch.Size([1, 256, 112, 160]) 

[12] models.common.MP 
Before
11 : torch.Size([1, 256, 112, 160])
After
 torch.Size([1, 256, 56, 80]) 

[13] models.common.Conv 
Before
12 : torch.Size([1, 256, 56, 80])
After
 torch.Size([1, 128, 56, 80]) 

[14] models.common.Conv 
Before
11 : torch.Size([1, 256, 112, 160])
After
 torch.Size([1, 128, 112, 160]) 

[15] models.common.Conv 
Before
14 : torch.Size([1, 128, 112, 160])
After
 torch.Size([1, 128, 56, 80]) 

[16] models.common.Concat 
Before
15 : torch.Size([1, 128, 56, 80])
13 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 256, 56, 80]) 

[17] models.common.Conv 
Before
16 : torch.Size([1, 256, 56, 80])
After
 torch.Size([1, 128, 56, 80]) 

[18] models.common.Conv 
Before
16 : torch.Size([1, 256, 56, 80])
After
 torch.Size([1, 128, 56, 80]) 

[19] models.common.Conv 
Before
18 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 128, 56, 80]) 

[20] models.common.Conv 
Before
19 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 128, 56, 80]) 

[21] models.common.Conv 
Before
20 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 128, 56, 80]) 

[22] models.common.Conv 
Before
21 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 128, 56, 80]) 

[23] models.common.Concat 
Before
22 : torch.Size([1, 128, 56, 80])
20 : torch.Size([1, 128, 56, 80])
18 : torch.Size([1, 128, 56, 80])
17 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 512, 56, 80]) 

[24] models.common.Conv 
Before
23 : torch.Size([1, 512, 56, 80])
After
 torch.Size([1, 512, 56, 80]) 

[25] models.common.MP 
Before
24 : torch.Size([1, 512, 56, 80])
After
 torch.Size([1, 512, 28, 40]) 

[26] models.common.Conv 
Before
25 : torch.Size([1, 512, 28, 40])
After
 torch.Size([1, 256, 28, 40]) 

[27] models.common.Conv 
Before
24 : torch.Size([1, 512, 56, 80])
After
 torch.Size([1, 256, 56, 80]) 

[28] models.common.Conv 
Before
27 : torch.Size([1, 256, 56, 80])
After
 torch.Size([1, 256, 28, 40]) 

[29] models.common.Concat 
Before
28 : torch.Size([1, 256, 28, 40])
26 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 512, 28, 40]) 

[30] models.common.Conv 
Before
29 : torch.Size([1, 512, 28, 40])
After
 torch.Size([1, 256, 28, 40]) 

[31] models.common.Conv 
Before
29 : torch.Size([1, 512, 28, 40])
After
 torch.Size([1, 256, 28, 40]) 

[32] models.common.Conv 
Before
31 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 256, 28, 40]) 

[33] models.common.Conv 
Before
32 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 256, 28, 40]) 

[34] models.common.Conv 
Before
33 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 256, 28, 40]) 

[35] models.common.Conv 
Before
34 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 256, 28, 40]) 

[36] models.common.Concat 
Before
35 : torch.Size([1, 256, 28, 40])
33 : torch.Size([1, 256, 28, 40])
31 : torch.Size([1, 256, 28, 40])
30 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 1024, 28, 40]) 

[37] models.common.Conv 
Before
36 : torch.Size([1, 1024, 28, 40])
After
 torch.Size([1, 1024, 28, 40]) 

[38] models.common.MP 
Before
37 : torch.Size([1, 1024, 28, 40])
After
 torch.Size([1, 1024, 14, 20]) 

[39] models.common.Conv 
Before
38 : torch.Size([1, 1024, 14, 20])
After
 torch.Size([1, 512, 14, 20]) 

[40] models.common.Conv 
Before
37 : torch.Size([1, 1024, 28, 40])
After
 torch.Size([1, 512, 28, 40]) 

[41] models.common.Conv 
Before
40 : torch.Size([1, 512, 28, 40])
After
 torch.Size([1, 512, 14, 20]) 

[42] models.common.Concat 
Before
41 : torch.Size([1, 512, 14, 20])
39 : torch.Size([1, 512, 14, 20])
After
 torch.Size([1, 1024, 14, 20]) 

[43] models.common.Conv 
Before
42 : torch.Size([1, 1024, 14, 20])
After
 torch.Size([1, 256, 14, 20]) 

[44] models.common.Conv 
Before
42 : torch.Size([1, 1024, 14, 20])
After
 torch.Size([1, 256, 14, 20]) 

[45] models.common.Conv 
Before
44 : torch.Size([1, 256, 14, 20])
After
 torch.Size([1, 256, 14, 20]) 

[46] models.common.Conv 
Before
45 : torch.Size([1, 256, 14, 20])
After
 torch.Size([1, 256, 14, 20]) 

[47] models.common.Conv 
Before
46 : torch.Size([1, 256, 14, 20])
After
 torch.Size([1, 256, 14, 20]) 

[48] models.common.Conv 
Before
47 : torch.Size([1, 256, 14, 20])
After
 torch.Size([1, 256, 14, 20]) 

[49] models.common.Concat 
Before
48 : torch.Size([1, 256, 14, 20])
46 : torch.Size([1, 256, 14, 20])
44 : torch.Size([1, 256, 14, 20])
43 : torch.Size([1, 256, 14, 20])
After
 torch.Size([1, 1024, 14, 20]) 

[50] models.common.Conv 
Before
49 : torch.Size([1, 1024, 14, 20])
After
 torch.Size([1, 1024, 14, 20]) 

[51] models.common.SPPCSPC 
Before
50 : torch.Size([1, 1024, 14, 20])
After
 torch.Size([1, 512, 14, 20]) 

[52] models.common.Conv 
Before
51 : torch.Size([1, 512, 14, 20])
After
 torch.Size([1, 256, 14, 20]) 

[53] torch.nn.modules.upsampling.Upsample 
Before
52 : torch.Size([1, 256, 14, 20])
After
 torch.Size([1, 256, 28, 40]) 

[54] models.common.Conv 
Before
37 : torch.Size([1, 1024, 28, 40])
After
 torch.Size([1, 256, 28, 40]) 

[55] models.common.Concat 
Before
54 : torch.Size([1, 256, 28, 40])
53 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 512, 28, 40]) 

[56] models.common.Conv 
Before
55 : torch.Size([1, 512, 28, 40])
After
 torch.Size([1, 256, 28, 40]) 

[57] models.common.Conv 
Before
55 : torch.Size([1, 512, 28, 40])
After
 torch.Size([1, 256, 28, 40]) 

[58] models.common.Conv 
Before
57 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 128, 28, 40]) 

[59] models.common.Conv 
Before
58 : torch.Size([1, 128, 28, 40])
After
 torch.Size([1, 128, 28, 40]) 

[60] models.common.Conv 
Before
59 : torch.Size([1, 128, 28, 40])
After
 torch.Size([1, 128, 28, 40]) 

[61] models.common.Conv 
Before
60 : torch.Size([1, 128, 28, 40])
After
 torch.Size([1, 128, 28, 40]) 

[62] models.common.Concat 
Before
61 : torch.Size([1, 128, 28, 40])
60 : torch.Size([1, 128, 28, 40])
59 : torch.Size([1, 128, 28, 40])
58 : torch.Size([1, 128, 28, 40])
57 : torch.Size([1, 256, 28, 40])
56 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 1024, 28, 40]) 

[63] models.common.Conv 
Before
62 : torch.Size([1, 1024, 28, 40])
After
 torch.Size([1, 256, 28, 40]) 

[64] models.common.Conv 
Before
63 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 128, 28, 40]) 

[65] torch.nn.modules.upsampling.Upsample 
Before
64 : torch.Size([1, 128, 28, 40])
After
 torch.Size([1, 128, 56, 80]) 

[66] models.common.Conv 
Before
24 : torch.Size([1, 512, 56, 80])
After
 torch.Size([1, 128, 56, 80]) 

[67] models.common.Concat 
Before
66 : torch.Size([1, 128, 56, 80])
65 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 256, 56, 80]) 

[68] models.common.Conv 
Before
67 : torch.Size([1, 256, 56, 80])
After
 torch.Size([1, 128, 56, 80]) 

[69] models.common.Conv 
Before
67 : torch.Size([1, 256, 56, 80])
After
 torch.Size([1, 128, 56, 80]) 

[70] models.common.Conv 
Before
69 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 64, 56, 80]) 

[71] models.common.Conv 
Before
70 : torch.Size([1, 64, 56, 80])
After
 torch.Size([1, 64, 56, 80]) 

[72] models.common.Conv 
Before
71 : torch.Size([1, 64, 56, 80])
After
 torch.Size([1, 64, 56, 80]) 

[73] models.common.Conv 
Before
72 : torch.Size([1, 64, 56, 80])
After
 torch.Size([1, 64, 56, 80]) 

[74] models.common.Concat 
Before
73 : torch.Size([1, 64, 56, 80])
72 : torch.Size([1, 64, 56, 80])
71 : torch.Size([1, 64, 56, 80])
70 : torch.Size([1, 64, 56, 80])
69 : torch.Size([1, 128, 56, 80])
68 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 512, 56, 80]) 

[75] models.common.Conv 
Before
74 : torch.Size([1, 512, 56, 80])
After
 torch.Size([1, 128, 56, 80]) 

[76] models.common.MP 
Before
75 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 128, 28, 40]) 

[77] models.common.Conv 
Before
76 : torch.Size([1, 128, 28, 40])
After
 torch.Size([1, 128, 28, 40]) 

[78] models.common.Conv 
Before
75 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 128, 56, 80]) 

[79] models.common.Conv 
Before
78 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 128, 28, 40]) 

[80] models.common.Concat 
Before
79 : torch.Size([1, 128, 28, 40])
77 : torch.Size([1, 128, 28, 40])
63 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 512, 28, 40]) 

[81] models.common.Conv 
Before
80 : torch.Size([1, 512, 28, 40])
After
 torch.Size([1, 256, 28, 40]) 

[82] models.common.Conv 
Before
80 : torch.Size([1, 512, 28, 40])
After
 torch.Size([1, 256, 28, 40]) 

[83] models.common.Conv 
Before
82 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 128, 28, 40]) 

[84] models.common.Conv 
Before
83 : torch.Size([1, 128, 28, 40])
After
 torch.Size([1, 128, 28, 40]) 

[85] models.common.Conv 
Before
84 : torch.Size([1, 128, 28, 40])
After
 torch.Size([1, 128, 28, 40]) 

[86] models.common.Conv 
Before
85 : torch.Size([1, 128, 28, 40])
After
 torch.Size([1, 128, 28, 40]) 

[87] models.common.Concat 
Before
86 : torch.Size([1, 128, 28, 40])
85 : torch.Size([1, 128, 28, 40])
84 : torch.Size([1, 128, 28, 40])
83 : torch.Size([1, 128, 28, 40])
82 : torch.Size([1, 256, 28, 40])
81 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 1024, 28, 40]) 

[88] models.common.Conv 
Before
87 : torch.Size([1, 1024, 28, 40])
After
 torch.Size([1, 256, 28, 40]) 

[89] models.common.MP 
Before
88 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 256, 14, 20]) 

[90] models.common.Conv 
Before
89 : torch.Size([1, 256, 14, 20])
After
 torch.Size([1, 256, 14, 20]) 

[91] models.common.Conv 
Before
88 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 256, 28, 40]) 

[92] models.common.Conv 
Before
91 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 256, 14, 20]) 

[93] models.common.Concat 
Before
92 : torch.Size([1, 256, 14, 20])
90 : torch.Size([1, 256, 14, 20])
51 : torch.Size([1, 512, 14, 20])
After
 torch.Size([1, 1024, 14, 20]) 

[94] models.common.Conv 
Before
93 : torch.Size([1, 1024, 14, 20])
After
 torch.Size([1, 512, 14, 20]) 

[95] models.common.Conv 
Before
93 : torch.Size([1, 1024, 14, 20])
After
 torch.Size([1, 512, 14, 20]) 

[96] models.common.Conv 
Before
95 : torch.Size([1, 512, 14, 20])
After
 torch.Size([1, 256, 14, 20]) 

[97] models.common.Conv 
Before
96 : torch.Size([1, 256, 14, 20])
After
 torch.Size([1, 256, 14, 20]) 

[98] models.common.Conv 
Before
97 : torch.Size([1, 256, 14, 20])
After
 torch.Size([1, 256, 14, 20]) 

[99] models.common.Conv 
Before
98 : torch.Size([1, 256, 14, 20])
After
 torch.Size([1, 256, 14, 20]) 

[100] models.common.Concat 
Before
99 : torch.Size([1, 256, 14, 20])
98 : torch.Size([1, 256, 14, 20])
97 : torch.Size([1, 256, 14, 20])
96 : torch.Size([1, 256, 14, 20])
95 : torch.Size([1, 512, 14, 20])
94 : torch.Size([1, 512, 14, 20])
After
 torch.Size([1, 2048, 14, 20]) 

[101] models.common.Conv 
Before
100 : torch.Size([1, 2048, 14, 20])
After
 torch.Size([1, 512, 14, 20]) 

[102] models.common.Conv 
Before
75 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 256, 56, 80]) 

[103] models.common.Conv 
Before
88 : torch.Size([1, 256, 28, 40])
After
 torch.Size([1, 512, 28, 40]) 

[104] models.common.Conv 
Before
101 : torch.Size([1, 512, 14, 20])
After
 torch.Size([1, 1024, 14, 20]) 

[105] models.common.Merge 
Before
102 : torch.Size([1, 256, 56, 80])
103 : torch.Size([1, 512, 28, 40])
104 : torch.Size([1, 1024, 14, 20])
After
torch.Size([1, 256, 56, 80])
torch.Size([1, 512, 28, 40])
torch.Size([1, 1024, 14, 20])
[106] models.common.Conv 
Before
75 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 64, 56, 80]) 

[107] torch.nn.modules.upsampling.Upsample 
Before
106 : torch.Size([1, 64, 56, 80])
After
 torch.Size([1, 64, 112, 160]) 

[108] models.common.Conv 
Before
11 : torch.Size([1, 256, 112, 160])
After
 torch.Size([1, 64, 112, 160]) 

[109] models.common.Concat 
Before
108 : torch.Size([1, 64, 112, 160])
107 : torch.Size([1, 64, 112, 160])
After
 torch.Size([1, 128, 112, 160]) 

[110] models.common.BottleneckCSPB 
Before
109 : torch.Size([1, 128, 112, 160])
After
 torch.Size([1, 64, 112, 160]) 

[111] models.common.Conv 
Before
110 : torch.Size([1, 64, 112, 160])
After
 torch.Size([1, 64, 112, 160]) 

[112] models.common.Refine 
Before
75 : torch.Size([1, 128, 56, 80])
88 : torch.Size([1, 256, 28, 40])
101 : torch.Size([1, 512, 14, 20])
After
 torch.Size([1, 128, 56, 80]) 

[113] models.common.Conv 
Before
112 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 128, 56, 80]) 

[114] torch.nn.modules.upsampling.Upsample 
Before
113 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 128, 112, 160]) 

[115] models.common.Conv 
Before
114 : torch.Size([1, 128, 112, 160])
After
 torch.Size([1, 128, 112, 160]) 

[116] models.common.Conv 
Before
111 : torch.Size([1, 64, 112, 160])
After
 torch.Size([1, 128, 112, 160]) 

[117] models.common.Shortcut 
Before
116 : torch.Size([1, 128, 112, 160])
115 : torch.Size([1, 128, 112, 160])
After
 torch.Size([1, 128, 112, 160]) 

[118] models.common.Conv 
Before
117 : torch.Size([1, 128, 112, 160])
After
 torch.Size([1, 128, 112, 160]) 

[119] torch.nn.modules.conv.Conv2d 
Before
118 : torch.Size([1, 128, 112, 160])
After
 torch.Size([1, 4, 112, 160]) 

[120] models.common.Refine 
Before
75 : torch.Size([1, 128, 56, 80])
63 : torch.Size([1, 256, 28, 40])
51 : torch.Size([1, 512, 14, 20])
After
 torch.Size([1, 128, 56, 80]) 

[121] models.common.Conv 
Before
120 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 128, 56, 80]) 

[122] torch.nn.modules.upsampling.Upsample 
Before
121 : torch.Size([1, 128, 56, 80])
After
 torch.Size([1, 128, 112, 160]) 

[123] models.common.Conv 
Before
122 : torch.Size([1, 128, 112, 160])
After
 torch.Size([1, 128, 112, 160]) 

[124] models.common.Conv 
Before
111 : torch.Size([1, 64, 112, 160])
After
 torch.Size([1, 128, 112, 160]) 

[125] models.common.Shortcut 
Before
124 : torch.Size([1, 128, 112, 160])
123 : torch.Size([1, 128, 112, 160])
After
 torch.Size([1, 128, 112, 160]) 

[126] models.common.Conv 
Before
125 : torch.Size([1, 128, 112, 160])
After
 torch.Size([1, 128, 112, 160]) 

[127] torch.nn.modules.conv.Conv2d 
Before
126 : torch.Size([1, 128, 112, 160])
After
 torch.Size([1, 1, 112, 160]) 

[128] models.yolo.MT 
Before
torch.Size([1, 256, 56, 80])
torch.Size([1, 512, 28, 40])
torch.Size([1, 1024, 14, 20])
119 : torch.Size([1, 4, 112, 160])
127 : torch.Size([1, 1, 112, 160])
After
mask_iou : None
test : torch.Size([17640, 85])
attn : torch.Size([17640, 980])
bbox_and_cls : torch.Size([1, 3, 56, 80, 85])
bases : torch.Size([4, 112, 160])
sem : torch.Size([1, 112, 160])
```

## Column 2

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
   
   [75, 1, Conv, [256, 3, 1] ],
   [88, 1, Conv, [512, 3, 1] ],
   [101, 1, Conv, [1024, 3, 1]],
   
   [[102, 103, 104], 1, Merge, [[256, 512, 1024]]],  # 105
   
   [75, 1, Conv, [64, 1, 1] ],
   [-1, 1, nn.Upsample, [None, 2, 'nearest'] ],
   [11, 1, Conv, [64, 1, 1] ], # route backbone P2
   [[-1, -2], 1, Concat, [1] ],
   [-1, 2, BottleneckCSPB, [64] ], 
   [-1, 1, Conv, [64, 1, 1] ], # 111

   [[75, 88, 101], 1, Refine, [128, 3, 1]],
   [-1, 1, Conv, [128, 3, 1]],
   [-1, 1, nn.Upsample, [None, 2, 'bilinear']],
   [-1, 1, Conv, [128, 3, 1]],
   [111, 1, Conv, [128, 3, 1]],
   [[-1, -2], 1, Shortcut, [1]],
   [-1, 1, Conv, [128, 3, 1]],
   [-1, 1, nn.Conv2d, [4, 1]],  # 119
  
   [[75, 63, 51], 1, Refine, [128, 3, 1]],
   [-1, 1, Conv, [128, 3, 1]],
   [-1, 1, nn.Upsample, [None, 2, 'bilinear']],
   [-1, 1, Conv, [128, 3, 1]],
   [111, 1, Conv, [128, 3, 1]],
   [[-1, -2], 1, Shortcut, [1]],
   [-1, 1, Conv, [128, 3, 1]],
   [-1, 1, nn.Conv2d, [1, 1]],  # 127
   
   [[105, 119, 127], 1, MT, [nc, anchors, 980]],   # Detect(P3, P4, P5)
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