## RTX4090

```plaintext
<------ TESTING AES-128 CTR Mode ------>
Use Default Key:

GPU Compute Capability = [8.9], clock: 2565000 asynCopy: 2 MapHost: 1 SM: 128
msgSize: 1024 MB         counter blocks: 256 M Block
65536 blocks and 1024 threads

|       Encryption in CPU: Started      |

Output data (First 32 Bytes):   
c6a13b377346139449d68751b9ad2b2d
3063b6db9b82998cd45efc54b9322f1e

|       Encryption in GPU: Started      |

AES GPU (one-T): 1024 MB of data. Kernel: 3057.4178 [Gbps]
GPU (one-T) Output data (First 32 Bytes):   
c6a13b377346139449d68751b9ad2b2d
3063b6db9b82998cd45efc54b9322f1e
The results in CPU and GPU match!
```
