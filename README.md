# 🧠 Neural Network Architecture Visualizations

Interactive HTML visualizations for understanding classic deep learning architectures.

## 📁 Files

### LeNet-5 Architecture
**`lenet-architecture.html`**

The classic CNN for handwritten digit recognition (1998).

- **Input**: 32×32 grayscale images
- **Architecture**: 8 layers (Input → Conv1 → Pool1 → Conv2 → Pool2 → FC1 → FC2 → Output)
- **Parameters**: ~60K
- **Accuracy**: 99.2% on MNIST
- **Dataset**: MNIST handwritten digits (0-9)

### AlexNet Architecture  
**`alexnet-architecture.html`**

The breakthrough CNN that changed deep learning (2012).

- **Input**: 227×227 RGB images  
- **Architecture**: 11 layers with dual GPU streams
- **Parameters**: ~61M
- **Top-5 Error**: 15.3% on ImageNet (won the competition!)
- **Dataset**: ImageNet (1.2M images, 1000 classes)

## 🎯 Features

- 📊 **Interactive architecture diagrams** - Click any layer to see details
- 📐 **Layer dimensions** - Shows input/output shapes for each layer
- 🔢 **Parameter counts** - See how many weights each layer has
- ▶️ **Animate data flow** - Watch how data propagates through the network
- 🎨 **Color-coded layers** - Easy visual distinction between layer types:
  - 🔵 Cyan - Input
  - 🟣 Purple - Convolutional
  - 🟠 Orange - Pooling/Subsampling
  - 🟢 Green - Fully Connected
  - 🔴 Pink - Output

## 🚀 How to Use

1. Open either HTML file in any modern web browser
2. Click on any layer box to see detailed specifications
3. Use "Animate Data Flow" button to visualize data passing through
4. Click legend items to understand color coding

## ⌨️ Keyboard Shortcuts

- **Space** - Start animation
- **Escape** - Close modal

## 📖 Learning These Networks

### LeNet-5 (1998)
Yann LeCun's pioneering work that started it all. Used for bank check reading and digit recognition. Key innovations:
- Local receptive fields
- Shared weights
- Spatial subsampling

### AlexNet (2012)
The network that sparked the deep learning revolution. Key innovations:
- **ReLU activation** - 6x faster training than tanh
- **Dropout** - Prevents overfitting
- **GPU training** - First large-scale CNN on GPUs
- **Data augmentation** - Random crops and flipping
- **Overlapping pooling** - Better generalization

## 📊 Architecture Comparison

| Feature | LeNet-5 | AlexNet |
|---------|---------|---------|
| Year | 1998 | 2012 |
| Parameters | 60K | 61M |
| Conv Layers | 2 | 5 |
| FC Layers | 3 | 3 |
| Input Size | 32×32 | 227×227 |
| GPU Usage | No | 2 GPUs |
| Dataset | MNIST | ImageNet |

## 🔗 Links

- [LeNet Paper](http://yann.lecun.com/exdb/lenet/) - Original paper by LeCun
- [ImageNet](https://www.image-net.org/) - The dataset AlexNet was trained on

## 📝 License

See LICENSE file for details.