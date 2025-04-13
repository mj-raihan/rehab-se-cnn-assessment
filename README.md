This repository contains the code and data used in the paper:

> **"A Deep Learning Model with Interpretable Squeeze-and-Excitation for Automated Rehabilitation Exercise Assessment"**  
> Md. Johir Raihan · Md Atiqur Rahman Ahad · Abdullah-Al Nahid 
<!-- > [Conference/Journal Name], [Year] -->

## 📁 Repository Structure

- `rehab_kfold_viewer.ipynb`: A reproducible Jupyter Notebook that loads and displays K-fold split metadata used in training and evaluation.
- `./k fold release kimore/`: Directory containing the preprocessed `.pkl` files for various rehabilitation exercise subsets (Joint Position (JP), Joint Orientation (JO), Joint Angle (JA)) across all, healthy, and disabled groups.

## 📦 Requirements

This notebook was developed and tested using:

- Python 3.8+
- Jupyter Notebook
- `pickle`
- (Optional) `numpy` for additional array manipulations

To run the notebook, make sure the required `.pkl` files are present in the `k fold release kimore` folder.

## 🧪 Contents of the `.pkl` Files

Each file in the `k fold release kimore` folder contains a dictionary with keys such as:

- `'Kfold 1'`, `'Kfold 2'`, ..., `'Kfold N'`: Each representing a fold of the K-fold split
- Inside each fold:
  - `'train index'`: Indices used for training
  - `'test index'`: Indices used for testing

Example inspection output from the notebook includes:
- Available keys in the loaded pickle file
- Shapes of training and testing splits for Fold 2
- A preview of the first few indices for both train and test splits

## 📜 Usage

1. Clone the repository:

```bash
git clone https://github.com/mj-raihan/rehab-se-cnn-assessment.git
cd rehab-se-cnn-assessment
```
2. Open the notebook in Jupyter and run it:
```bash
jupyter notebook rehab_kfold_viewer.ipynb
```
3. Modify paths inside the notebook if necessary to match your local folder structure.
## 📂 Data Notes
The .pkl files are shared solely for reproducibility purposes.
They do not contain any raw personal health information.

<!-- ## 📃 License
This project is licensed under the MIT License.
See the LICENSE file for details. -->

## 📧 Contact
For questions or feedback, feel free to reach out:
- Md. Johir Raihan
- Email: mj.raihan2@gmail.com
