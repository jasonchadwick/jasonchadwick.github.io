Figure 1. Viewing a hybrid-erasure architecture as a game of Minesweeper.
*Top:* In a standard surface code, we receive syndrome bits (red and blue
1s) indicating that an error string terminates nearby. The decoder must find
a valid explanation (red and blue flags) based only on this information. If
the decoder guesses wrong, a logical error can occur. *Bottom:* When data
qubits are *erasure qubits*, we gain extra information before decoding (black
bombs and green checks on left) that help us decide which error string to
predict, avoiding logical errors and achieving better error suppression. *Middle:*
Partial improvements over error suppression persists when a carefully selected
a subset of qubits are erasure qubits.