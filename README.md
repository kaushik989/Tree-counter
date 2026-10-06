# Hi, I'm Kousikarvind! 👋

## 🤖 My Tree-Counter Projects
I host my active models, datasets, and spaces on Hugging Face.
* 🔗 **[View My Hugging Face flora-tree-counter project](https://huggingface.co/spaces/kaushik137/flora-tree-counter)**

### 🚀 Featured Model:
The tool uses a pre-trained RetinaNet object detection model provided by the DeepForest library. This model was trained on millions of hand-annotated tree crowns from the National Ecological Observatory Network (NEON), which covers a diverse set of forest types across the United States.
When you upload an image (ideally high-resolution, e.g., 10cm-30cm per pixel), the image is processed and passed through the neural network. The network outputs bounding boxes representing the predicted locations and sizes of individual tree crowns, along with a confidence score for each detection.

### 💻 Technology Stack
Frontend/UI: Streamlit (Python-based framework for rapid web app development).
Computer Vision/ML: DeepForest (PyTorch, torchvision) for model inference.
Image Processing: OpenCV and Pillow for reading, manipulating, and drawing the detection results on the imagery.
Data Handling: Pandas and NumPy for managing detection coordinates and calculations.



