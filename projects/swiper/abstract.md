Real-time decoding is a key ingredient in future fault-tolerant quantum systems, yet many decoders are too slow to run in real time.
Prior work has shown that parallel window decoding schemes can
scalably meet throughput requirements in the presence of increasing decoding times, given enough classical resources. However,
windowed decoding schemes require that some decoding tasks be
delayed until others have completed, which can be problematic during time-sensitive operations such as T gate teleportation, leading
to suboptimal program runtimes. To alleviate this, we introduce
SWIPER, a *speculative* window decoding scheme. Taking inspiration from branch prediction in classical computer architecture,
SWIPER utilizes a light-weight speculation step to predict data dependencies between adjacent decoding windows, allowing multiple
layers of decoding tasks to be resolved simultaneously. Through
a state-of-the-art compilation pipeline and a detailed open-source
simulator, we find that SWIPER reduces application runtimes by
40% on average compared to prior parallel window decoders.

\* indicates equal contribution