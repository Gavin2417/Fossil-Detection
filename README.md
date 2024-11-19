# Fossil Detection and Segmentation using EfficientDet

This project focuses on enhancing the EfficientDet object detection model to detect fossils and bone fragments in sediment-rich images. By modifying the feature network with architectures like FPN, PANet, Bi-FPN, and Quad-FPN, the research explores challenges such as overlapping sediment and faint fossil visibility.

## Key Highlights
- **Enhanced Feature Networks**: Modified FPN, PANet, Bi-FPN, and Quad-FPN for improved feature capture.
- **Repeating Block Evaluation**: Analyzed the impact of Repeating Blocks, which improved performance for simpler networks like FPN and PANet.
- **Significant Findings**: The modified Standard FPN with Repeating Blocks achieved an AP of 34.36%, while Bi-FPN and Quad-FPN performed better without Repeating Blocks.

## Challenges Addressed
- Detecting fossils obscured by sediment and mixed with similar-colored fragments.
- Limited annotated datasets and complex image conditions.
