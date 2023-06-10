# music-making
How to set up this environment to run the notebook
1. Download the Anaconda Distribution
2. Create a new environment, and conda install all the imports. Here is a more informative tutorial: https://www.codecademy.com/article/setup-deep-learning-environment
3. Download JupyterLab as well in this environment. I decided to use JupyterLab instead of JupyterNotebook because it's much easier to set up a GPU to run with the code in JupyterLab instead of JupyterNotebook
4. (If you want to regenerate new music) Click Restart Kernal and Run all Cells (It's the double forward arrow symbol)
5. Output the data through graphs and piano rolls

A few things to keep in mind about this repo
1. LSTMmusicmodel.ipynb is the primary notebook with all the code used
2. "Model.pt" is the smallest built model, with only 5 musical files and 10 epochs
3. "Midmodel.pt" is the second largest built model, with 50 musical files and 20 epochs
4. "Newmodel.pt" is the largest built model, with 50 musical files and 120 epochs
5. Plots of the piano roll of generated music as well as distributions of the generated music's pitch, step, and duration can be seen at the bottom