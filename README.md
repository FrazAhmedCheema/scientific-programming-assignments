Scientific Programming Assignments

Debugging exercises for admission to NHL Stenden's Master Computer Vision & Data Science.

The notebook covers four exercises:

1. Looking up fruits by index using an ordered list.

2. Swapping bounding-box coordinates without changing the class IDs or input array.

3. Reading numeric CSV data and plotting precision against recall.

4. Fixing batch handling and progress reporting in a GAN trained on MNIST.

Running the notebook

Use Python 3.12 and install the dependencies:

python -m pip install -r requirements.txt
python -m pip install jupyterlab
python -m jupyterlab scientific_programming_assignments.ipynb

Open the notebook and run the cells in order. The first run needs internet access to download MNIST.

The notebook includes saved plots. Exercise 4 runs for one full epoch to check that the corrected training loop works; the generated images are not intended to show a fully trained model.