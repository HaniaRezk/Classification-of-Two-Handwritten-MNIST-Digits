## **Project Overview**

The objective of this project is to create an inference pipeline capable of successfully classifying the result of the addition of combined images of two handwritten MNIST digits. 

---

## **Project Structure**

- `data.ipynb`                : Explores the MNIST dataset  
- `models.ipynb`              : Main notebook for implementing machine learning models  
- `requirements.txt`          : A list of all the required Python modules to ensure your environment is ready to run the notebook  
- `report/`                   : Folder containing the Coursework report  
- `trials/`                   
    - `NN_files/`                : Saved neural networks
      - `.h5` files               : Saved neural network models  
      - `weights.h5` files        : Weights of the saved neural network models   
      - `.json`files              : Training history of the saved neural network models    
      - `test_x_data.npy`         : Test image dataset file  
    - `test_y_data.npy`           : Test label dataset file  
    - `trials.ipynb`              : Notebook to load, visualize, and evaluate results of the optimization trials
    - `.db` files                 : Study files of the best neural network search

---

## **Setup and Requirements**

Make sure your environment is using Python 3.9 or higher.
You can check your current Python version by running:
```bash
python --version
```
If Python 3.9 or higher is not installed, you can download it from the official Python website.

Ensure you have the latest version of pip 24.3.1 installed in your environment.
You can upgrade pip by running the command:
```
pip install --upgrade pip

```

To set up the required Python environment for running the notebooks, run the following command in your environment terminal from the project folder (after having upgraded pip in your environment):

```bash
pip install -r requirements.txt
```

## Running

Run all the cells of the notebook sequentially to ensure the code executes correctly.

## Trials folder
Ensure that the neural networks files are available in a folder called `NN_trials` in the folder of the `trials.ipynb` notebook.
Ensure that the study and the data files are available in the same folder as `trials.ipynb`.

If you are working on google colab, import the `NN_trials` folder, the study and the data files in your colab environment.

## Virtual environments and kernels of the notebooks

If you are using a virtual environment to install the `requirements.txt` file, here's how you can configure a kernel to run the notebooks within this environment.

### Creating the Kernel

Use the following command to register your virtual environment as a kernel:

```bash
pip install ipykernel
python3.9 -m ipykernel install --user --name=name_of_your_env --display-name "Chosen Display Name"
```

### Selecting the kernel in your notebook

1. Open your notebook.  
2. Navigate to the **Kernel** menu and choose **Change kernel**.  
3. Select the kernel with your chosen display name.

# Declaration of use of AI tools

AI was used to display the results of hyperparameter tuning of logistic regression and SVM using the tabulate method in the `models.ipynb` notebook.
It was not used in any other parts of the notebooks
