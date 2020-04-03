# EHANet: An effective hierarchical aggregation network for face parsing

## Performance Compare
| Category   | DFANet | UNet  | DANet     | DABNet    | CE2P      | EHANet-R34 |
| ---------- | ------ | ----- | --------- | --------- | --------- | ---------------- |
| Background | 88.12  | 89.36 | **93.04** | 90.36     | 92.78     | 92.98            |
| Skin       | 89.69  | 91.90 | 93.15     | 91.27     | 93.17     | **93.26**        |
| Nose       | 83.96  | 87.45 | 88.92     | 86.04     | 88.54     | **89.02**        |
| EyeGlass   | 69.29  | 75.27 | 84.04     | 72.62     | 84.44     | **84.91**        |
| LeftEye    | 69.19  | 77.62 | 80.65     | 73.69     | **81.95** | 81.85            |
| RightEye   | 69.12  | 78.05 | 80.84     | 74.38     | **82.03** | 82.02            |
| LeftBrow   | 66.04  | 72.53 | 75.63     | 69.78     | 75.55     | **75.66**        |
| RightBrow  | 66.05  | 71.96 | 75.37     | 69.25     | 75.51     | **75.52**        |
| LeftEar    | 66.52  | 75.08 | **78.93** | 72.28     | 78.35     | 78.76            |
| RightEar   | 65.85  | 74.20 | **78.29** | 70.83     | 77.82     | 78.00            |
| Mouth      | 70.23  | 81.98 | 85.45     | 78.41     | 85.65     | **85.69**        |
| UpperLip   | 66.17  | 78.00 | 80.41     | 73.91     | 80.89     | **81.04**        |
| LowerLip   | 70.26  | 80.97 | **83.52** | 78.37     | 83.57     | 83.47            |
| **Hair**   | 86.25  | 88.37 | **91.31** | 88.52     | 91.18     | 91.26            |
| Hat        | 61.02  | 56.07 | 75.87     | 63.56     | 76.13     | **77.05**        |
| Earring    | 25.68  | 39.61 | **52.78** | 36.23     | 52.47     | 51.84            |
| Necklace   | 0.00   | 0.00  | 9.46      | 0.01      | 19.73     | **20.19**        |
| Neck       | 76.38  | 79.39 | 83.55     | 78.74     | 83.53     | **84.15**        |
| Cloth      | 60.21  | 62.82 | **78.07** | 67.27     | 76.30     | 77.93            |
| **mIOU**   | 65.79  | 71.61 | 77.33     | 70.36     | 77.87     | **78.19**        |
| **Acc**    | 91.85  | 93.02 | **95.09** | 93.24     | 95.00     | 95.28            |
| **fps**    | 71.94  | 79.37 | 12.85     | **99.01** | 29.76     | > 70             |


## Visual Results
<div><div align=center>
  <img src="https://github.com/JACKYLUO1991/FaceParsing/blob/master/deployment/result/images/228.jpg" width="300" height="300" alt="raw"/>
<img src="https://github.com/JACKYLUO1991/FaceParsing/blob/master/deployment/result/renders/2.png" width="300" height="300" alt="pred"/></div>

## Highlight
1. Hierarchical Global Attention Mechanism
2. Semantic Gap Compensation Block
3. Boundary Branch 
4. Boundary Loss

## Thanks CelebAMask-HQ dataset
```
@article{CelebAMask-HQ,
  title={MaskGAN: Towards Diverse and Interactive Facial Image Manipulation},
  author={Lee, Cheng-Han and Liu, Ziwei and Wu, Lingyun and Luo, Ping},
  journal={arXiv preprint arXiv:1907.11922},
  year={2019}
}
```
