Spin qubits in quantum dots offer an expansive design landscape for architecting scalable device layouts. Two exchange-only (EO) qubits can be connected in many ways, but the study of two-EO-qubit operations has so far been limited to a small number of the possible configurations, and previous works lack analyses of design considerations and implications for quantum error correction. We develop a simple method to efficiently find the optimal mapping of a fixed all-to-all pulse sequence to any restricted dot connectivity. We provide complete pulse sequences for CX, CZ, iSWAP, leakage-controlled CX, and leakage-controlled CZ two-qubit gates on 450 unique planar six-dot topologies and analyze differences in sequence length (up to 43\% reduction) across topology classes. In addition, we show that relaxing constraints on post-operation spin locations can yield further reductions in sequence length; conversely, constraining these locations in a particular way generates a CXSWAP operation with almost no additional cost over a standard CX. We experimentally verify pulses sequences for different operations in a linear-connectivity device and confirm that they work as expected. Finally, we explore architectural implications of these results for quantum error correction. Our work guides hardware and software design choices for future implementations of scalable quantum dot architectures.