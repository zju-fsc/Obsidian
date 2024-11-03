# FLOP
**GFLOPS** 就是 _Giga Floating-point Operations Per Second_,即每秒10亿次的浮点运算数,常作为GPU性能参数但不一定代表GPU的实际表现，因为还要考虑具体如何拆分多边形和像素、以及纹理填充，理论上该数值越高越好。1GFLOPs = 10^9 FLOPs。

**FLOPs** 是_floating point of operations_的缩写，是浮点运算次数，可以用来衡量算法/模型复杂度。常用当然还有GFLOPs和TFLOPs

**FLOPS** （全部大写）是_floating-point operations per second_的缩写，意指每秒浮点运算次数。用来衡量硬件的性能。

# RAM&Memory

| **RAM**                                                      | **Memory**                                                                                   |
| ------------------------------------------------------------ | -------------------------------------------------------------------------------------------- |
| Short for Random Access Memory.                              | Refers to the device’s storage capacity.                                                     |
| Temporary storage.                                           | Permanent storage.                                                                           |
| Affects device performance.                                  | Affects device’s storage capacity.                                                           |
| Usually has lower capacity than storage memory, up to 32 GB. | Has bigger capacity compared to RAM, can reach more than 200 exabyte (around 200 billion GB) |
|                                                              |                                                                                              |

# Roofline
 The roofline model is an intuitive visual performance model used to provide performance estimates of a given compute kernel or application running on multi-core, many-core, or accelerator processor architectures, by showing inherent hardware limitations, and potential benefit and priority of optimizations. By combining locality, bandwidth, and different parallelization paradigms into a single performance figure, the model can be an effective alternative to assess the quality of attained performance instead of using simple percent-of-peak estimates, as it provides insights on both the implementation and inherent performance limitations.
