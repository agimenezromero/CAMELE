# CAMELE

Despite the mapping of several marine habitats has been successfully achieved through the use of side-scan sonar units, the cost and time-intensive nature of these methods present challenges in deploying continuous monitoring systems. We aim to address these challenges by combining the vast amount of remote sensing data available with recent advances in deep learning to develop a framework that can automatically map marine habitats from satellite imagery.  CAMELE (Consensus for Automatic Marine Ecosystem Labelling and Evaluation) is a deep learning-based system to automatically monitor marine ecosystems from satellite imagery.  This will enable the continuous monitoring of marine ecosystems at a fraction of the cost and time required by traditional methods and the opportunity to monitor larger areas. 

Here you can find an example code to use CAMELE model to predict the underlying habitat distribution of two satellite images from the coast of the Balearic Islands. The models and the data can be found at [zenodo](https://doi.org/10.5281/zenodo.10792281).

# Requirements

- Python 3.X

# Instructions (Linux)

- Download the models and the data from the Zenodo repository and place them in the corresponding folders.

- Create a suitable conda environment using the requirements.yml file

  ```bash
  conda env create -n requirements.yml
  ```

- Activate the environment

   ```bash
  conda activate camele
  ```

- Now you are ready tu run the *Example.ipynb* notebook. Have fun!
