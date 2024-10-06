# QLSTM_SystemCalls
System Call Analysis using QLSTM

## References

This code is based on the work by DiSipio, Huang, Chen described in the paper in reference 1 below.

1. Di Sipio R, Huang J-H, Chen SY-C, et al (2022) The Dawn of Quantum Natural Language Processing. In: ICASSP 2022 - 2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, Singapore, Singapore, pp 8612–8616
2. Chen SY-C, Yoo S, Fang Y-LL (2022) Quantum Long Short-Term Memory. In: ICASSP 2022 - 2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP). IEEE, Singapore, Singapore, pp 8622–8626

### Prints circuit by calling QLSTM.draw_mpl method

```lua
QModel.draw_mpl('default', input, weights)
```
<img width="570" alt="image" src="https://github.com/user-attachments/assets/4f57be9e-fcdb-4520-8954-44bb05c31db9">

### Another print method 

```lua
QModel.print(input, weights)
```
<img width="624" alt="image" src="https://github.com/user-attachments/assets/fdb3de4e-1bb9-4321-9920-843e65db321d">

