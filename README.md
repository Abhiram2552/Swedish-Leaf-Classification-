
# Swedish Leaf Classification – ANN, SOM, and VGG16 Models

This project presents a comparative study of multiple machine learning models for **leaf classification** using the **Swedish Leaf dataset**. The models implemented include:

-  Artificial Neural Network (ANN)
-  Self-Organizing Map (SOM)
-  VGG16-based Deep Convolutional Neural Network

## Files

| File Name                 | Description                                      |
|--------------------------|--------------------------------------------------|
| `SwedishLeaf_ANN.ipynb`  | Implements a basic ANN model                     |
| `swedish-leaf-som.ipynb` | Uses SOM for unsupervised feature mapping        |
| `swedishleaf-vgg16.ipynb`| Uses transfer learning with pre-trained VGG16    |

## Dataset

The [Swedish Leaf dataset](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/) contains images of 15 species of Swedish tree leaves with variations in shape and texture.

##  Models Used

- **ANN:** Simple fully-connected neural network
- **SOM:** Unsupervised clustering based on feature similarity
- **VGG16:** Pre-trained deep CNN model fine-tuned for leaf classification

##Evaluation Metrics

- Accuracy
- Loss Curves
- Confusion Matrix
- Visualizations for SOM neurons

## How to Run

1. Clone the repository
2. Open any `.ipynb` file in Jupyter Notebook or Google Colab
3. Ensure you have required libraries installed (TensorFlow, Keras, matplotlib, numpy)

```bash
pip install tensorflow keras matplotlib numpy
```

##Objective

To evaluate and compare performance of different ML approaches in leaf classification, specifically:
- Supervised (ANN, VGG16)
- Unsupervised (SOM)

## License

This project is for academic and research purposes.

---

 Developed as part of a machine learning project on shape-based classification.
