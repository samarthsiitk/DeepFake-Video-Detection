# DeepFake-Video-Detection
Course Project for EE655(Computer Vision and Deep Learning, under Prof. Koteswar Rao Jerripothula, IITK
 
 • Multi-Stream Fusion: Designed a leightweight efficient deepfake video detection model using
 a multi-stream CNN architecture that intelligently fuses RGB, Frequency (FFT), and Motion
 Residuals through Transformer-based attention mechanisms.
 • Transformer-Based Cross-Stream Attention: Used a cross-attention Transformer layer to
 fuse multi-stream features and model inter-modal relationships effectively.
 • Lightweight EfficientNet Backbones with CBAM: Each stream uses EfficientNet-B0 en
hanced by CBAM (Convolutional Block Attention Module) for per-stream spatial and channel
 attention.
 • Robust Performance: Achieved 96% accuracy on CelebDF and 91% on FaceForensics++ using
 the pipeline that is relatively more than the prior methods.
 • Deployment Ready: Preprocessed on large datasets like FceForencics++, CelebDF and DFD.
 The model is lightweight and suitable for real-time detection on resource-constrained devices.
