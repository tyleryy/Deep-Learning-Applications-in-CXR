Do not run the first cell unless using Google Colab.

Import necessary modules from next cell.

At this point, you may either train a new model, or load pretrained weights and evaluate.
  
  For option 1:
  
  Run all cells in order from top to bottom until reaching the header titled "Train".
  So far, the data will have been downloaded, cleaned, and placed into dataloaders. The models will also have been initialized.

  Run the first two cells, stopping at the one with the comment "clear GPU cache (RUN THIS BEFORE EVERY TRAINING RUN)".
  This cell will delete the models and weights, so do not run this for now.

  Run the next cell to train the model. After this finishes, the next two cells display the learning curves and some example images.
  If the training fails, run the previously mentioned cell with the comment "clear GPU cache (RUN THIS BEFORE EVERY TRAINING RUN)",
  then go up to the label "GANs model". After so, run the cells below it in the previously detailed manner to train a new model.

  For option 2:

  Go to the bottom of the notebook to the label titled "Load pretrained GANs model".
  Run the cells sequentially to load in pretrained weights and generate pictures. Make sure to edit the file path to be the path of the weights file you intend to load.

  
