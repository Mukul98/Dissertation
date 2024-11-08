
# Iris Detection, Face Recognition and Final Fusion Jupyter Notebook

To run the Jupyter Notebooks titled "Iris_Detection.ipynb","Final_fusion_code.ipynb","Face_Recog.ipynb" ensure that the criterion below is met.

## Prerequisites

1. Python 3.x
2. Jupyter Notebook

## Installation
# Virtual environment setup for running the notebooks

## Prerequisites
* venv
* pip

# Setup

## Install all the required dependencies using requirements.txt 
```bash
pip install -r requirements.txt
```

### Installing Python:

If you don't have Python installed, download it from [python.org](https://www.python.org/downloads/).

### Installing Jupyter Notebook:

If you haven't installed Jupyter Notebook yet, you can do so using `pip`:

```
pip install jupyter
```

## Running the Notebook

1. **Download and Extract the Zip File**: 
   
   After downloading the zip file, extract its contents to a directory of your choice.

2. **Place the Dataset**:

   Keep the Folder name as Datasets which shall contain the face and iris datasets and provide the path of the Face Dataset and Iris Dataset into 'ROOT' variable of the jupyter notebooks "Iris_Detection.ipynb" and "Face_Recog.ipynb" respectively and provide paths for databases in the "Final_fusion_code.ipynb" in the variables "IRIS" and "FACE"respectively.


3. **Navigate to the Directory**:

   Open a terminal or command prompt and navigate to the directory where you've extracted the contents:

```
cd path/to/directory
```

Replace `path/to/directory` with the actual path where "Iris_Detection.ipynb","Final_fusion_code.ipynb","Face_Recog.ipynb" are located.

4. **Launch Jupyter Notebook**:

```
jupyter notebook
```

This will open a browser window/tab with the Jupyter dashboard. From there, click on "Iris_Detection.ipynb" to open and run the notebook.
Similarly run the "Face_Recog.ipynb" notebook after completion of the previous notebook. After both these notebooks are completed successfully the model weights for Face and Iris will be saved in the main directory in "face_siamese_model-final", "iris_siamese_model-final" folders respectively. While running the "Final_fusion_code.ipynb" notebook replace the path in variables "face_saved_model_path", "iris_saved_model_path" with the respective paths of the aforementioned folders.

 
 
