[1] Setting up virtual env

    pip install virtualenv 
    python -m venv myenv
    pip install -r requirements.txt
    pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118


    for windows use pip,
        linux use pip3
[2] EDA_and_classifier ipynb file contains EDA, PCA, t-SNE results and classifier model  using RandomForest and XGBoost 

[3] customer_offer inpynb file does some preprocessing and export a train dataset file

[4] autoencoder ipynb file contains the multi-label classification model

For more details read the final report