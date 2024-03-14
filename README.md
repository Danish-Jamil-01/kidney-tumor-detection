# Kidney Disease Detection with CT Scan Images

<br>
This repository contains code for detecting kidney diseases using CT scan images. The project explores how changes in input image resolution affect the algorithm's output. Various resolutions, ranging from 2x2 to 256x256 pixels, are considered.

<br>

## File Structure
The repository has the following structure:
<br>
- <code>dataset/</code><br>
- <code>resized dataset/</code><br>
- <code>.DS_Store/</code><br>
- <code>128x128.ipynb</code><br>
- <code>16x16.ipynb</code><br>
- <code>256x256.ipynb</code><br>
- <code>2x2.ipynb</code><br>
- <code>32x32.ipynb</code><br>
- <code>4x4.ipynb</code><br>
- <code>64x64.ipynb</code><br>
- <code>8x8.ipynb</code><br>
- <code>LICENSE</code><br>
- <code>README.md</code><br>
- <code>requirements.txt</code><br>

<br>

## Usage

To use this code, follow these steps:

<ol>

<li><b>Clone the repository to your local machine:</b>
 <br>

 ```bash
git clone https://github.com/Danish-Jamil-01/kidney-tumor-detection.git
```
</li>
<br>


<li><b>Setup:</b>

- Ensure you have Python 3.x installed.
- Install the required libraries using <b>'pip install -r requirements.txt'</b>.
</li>
<br>


<li><b>Data Preprocessing:</b>

- The <b>'dataset'</b> folder contains the original CT scan images.
- Run the notebook corresponding to the desired input resolution (e.g., <b>'2x2.ipynb'</b>) to preprocess the images.
- The <b>'resized dataset'</b> folder will contain the resized images.
</li>

<br>

<li><b>Model Training:</b>
<br>

- Execute the notebook related to the desired input resolution (e.g., <b>'2x2.ipynb'</b>) to train the deep learning model.
- Experiment with different resolutions to observe their impact on model performance. 
</li>

<br>

<li><b>Evaluation:</b>
<br>

- Run the notebook related to the desired input resolution (e.g., <b>'2x2.ipynb'</b>) to evaluate the trained model using test data.
- Compare the evaluation metrics across different input resolutions.
</li>

<br>

<li><b>Sample Prediction:</b>
<br>

- Use the trained model from the corresponding notebook to make predictions on new CT scan images of the same resolution.
</li>

</ol>

<br>



## Results

The project demonstrates how changes in input image resolution affect the algorithm's output. By comparing the performance metrics (e.g., accuracy, F1 score) across different resolutions, insights can be gained into the optimal resolution for kidney disease detection.

The F1 Score across different input resolutions is as follows:
- 2x2 --> 0.445
- 4x4 --> 0.62
- 8x8 --> 0.68
- 16x16 --> 0.76
- 32x32 --> 0.865
- 64x64 --> 0.92
- 128x128 --> 0.93
- 256x256 --> 0.945
<br>

## Future Improvements

Potential improvements to enhance the project:

- Explore additional image preprocessing techniques.
- Incorporate advanced deep learning algorithms for improved performance.
- Conduct further analysis on the impact of input resolution on model interpretability.


<br>

## Contributing
Contributions to this project are welcome. Feel free to open an issue or submit a pull request.

<br>

## License
This project is licensed under the [MIT License](LICENSE).

<br>

## Acknowledgments
- <b>Dataset:</b> [CT-KIDNEY-DATASET-Normal-Cyst-Tumor-Stone](https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone)
