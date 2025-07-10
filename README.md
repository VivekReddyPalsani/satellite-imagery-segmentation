# Remote Sensing Data Insights with Deep Learning

This project delivers a full-stack workflow for extracting actionable insights from high-resolution satellite imagery using deep learning models. From preprocessing raw geospatial data to generating human-readable summaries, the pipeline bridges the gap between pixel-level segmentation and narrative interpretations — empowering stakeholders to visualize and understand land-cover changes over time.

## Project Highlights

- **Preprocessed and tiled imagery**  
  Used Python scripts and NumPy operations to read, normalize, and tile large satellite scenes into manageable patches, ensuring consistency in resolution and dynamic range.

- **Developed segmentation workflows**  
  Built and tested both **Siamese Network** and **U‑Net** architectures in PyTorch. We compared **Intersection-over-Union (IoU)** and **pixel accuracy** to select the best-performing model for change detection.

- **Integrated a vision-language model**  
  Extended the pipeline with a **PeliGamma LLM** to automatically generate concise, human-readable summaries of detected changes — transforming raw change maps into actionable spatial narratives.

- **Ensured reproducibility**  
  Managed code versioning with Git and organized modules into clear notebooks (`siamese.ipynb`, `U-Net.ipynb`, `llmintegration.ipynb`) and helper scripts under the `/src` directory to support easy collaboration and reproducibility.

## 📂 Dataset

The code assumes access to a satellite imagery dataset. Please provide the dataset link below:

- **Dataset link:** *[Insert dataset URL here]*

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. **Run the notebooks**

   Open and follow the Jupyter notebooks in this order:
- siamese.ipynb – Siamese model for change detection
- U-Net.ipynb – U-Net segmentation baseline
- llmintegration.ipynb – Vision-language summary generation
