# Optic Disc and Cup Segmentation

This repository contains a Jupyter Notebook for segmenting the optic disc and cup in fundus images. The segmentation helps in diagnosing and analyzing glaucoma and other retinal diseases.

## Features
- Uses deep learning techniques for segmentation.
- Implements a web interface using Streamlit.
- Downloads and processes fundus images.
- Provides visualization of segmentation results.

## Installation

Before running the notebook, install the required dependencies:

```sh
pip install -r requirements.txt
```

Alternatively, install key dependencies manually:

```sh
pip install streamlit
```

## Usage

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/optic-disc-segmentation.git
   cd optic-disc-segmentation
   ```

2. Run the Jupyter Notebook:
   ```sh
   jupyter notebook "Optic Disc and Cup Segmentation.ipynb"
   ```

3. If using Streamlit for visualization, run:
   ```sh
   streamlit run app.py
   ```

## Data
The model requires fundus images for training and inference. Ensure your dataset is available in the appropriate format.

## Contributing
Feel free to fork this repository and submit pull requests with improvements or bug fixes.

## License
This project is licensed under the MIT License.
