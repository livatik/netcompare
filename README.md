# NETCOMPARE

Netcompare is an experimental viewer for neural network, deep learning, and machine learning models, built to compare two models side by side.
It highlights structural differences using intuitive, human‑readable color categories:
- Matched nodes: Light Gray 
- Modified nodes: Light Yellow
- Added nodes: Light Green
- Removed nodes: Light Red

<img width="1707" height="1380" alt="image" src="https://github.com/user-attachments/assets/5dec41e6-f2ec-4531-a0d5-e67639a504b8" />

Netcompare is experimental and inspired by the excellent work behind netron.app. 

Netcompare requires that both models use the same framework (e.g., ONNX vs ONNX, Keras vs Keras) and that one model is a modification or evolution of the other.
Comparing unrelated architectures is not supported.
