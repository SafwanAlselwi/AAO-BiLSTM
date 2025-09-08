<h2> <a href="https://doi.org/10.1016/j.rineng.2024.103261" target="_blank">Smart Grid Stability Prediction Using Adaptive Aquila Optimizer and Ensemble Stacked BiLSTM</h2>

---

<a href="https://doi.org/10.1016/j.rineng.2024.103261" target="_blank">
    <img src="https://img.shields.io/badge/DOI-10.1016/j.rineng.2024.103261-blue" alt="DOI">
</a>

<br>

<p style="text-align: justify;">
<b>Background</b>:<br>
Smart grids, characterized by their ability to integrate renewable energy sources and manage the dynamic balance between supply and demand, require sophisticated prediction models to maintain stability. Traditional machine learning (ML) models often fall short in predicting the highly variable nature of smart grid operations.

<b>Methods</b>:<br>
This study introduces an ensemble stacked bidirectional Long Short-Term Memory model enhanced by a proposed Adaptive Aquila Optimizer (AAO). The AAO uses a Sigmoid Factor to balance exploration and exploitation, adapting the transition from broad searches to focused ones based on iteration progress. It is utilized for feature selection by identifying and excluding irrelevant and redundant features and methodically evaluates seven key hyperparameters to fine-tune the model's performance. Additionally, a weighted voting mechanism is employed to aggregate predictions in the ensemble model.

<b>Results</b>:<br>
Multiple rounds of empirical experiments using different sets of optimizers and configurations, supported by the visualization capabilities of TensorBoard, demonstrate significant improvements in the performance of the proposed AAO-BiLSTM model. The results show profound potential with accuracy, precision, recall, and F1-score rates of 99.55%, surpassing both traditional ML algorithms and state-of-the-art approaches.
</p>

## Research Highlights
* An Adaptive Aquila Optimizer (AAO) uses an adaptive Sigmoid Factor for effective hyperparameter tuning and feature selection.
* An ensemble stacked BiLSTM enhanced by the proposed AAO, utilizing a weighted voting mechanism to aggregate predictions.
* Multiple rounds of experiments visualized using TensorBoard provide interpretable insights into the model's effectiveness.
* The AAO-BiLSTM outperforms state-of-the-art models, achieving accuracy, precision, recall, and F1-score of up to 99.55%.


## Files

<ol>
  <li><b>AO.py</b>: Contains the implementation of the Aquila Optimizer (AO) and the Adaptive Aquila Optimizer (AAO) algorithms using the MEALPY Python library.</li>
  <li><b>code_01_data_preprocessing.ipynb</b>: Code for preprocessing the dataset used in smart grid stability prediction. Includes cleaning, normalization, and splitting the data into training and testing sets.</li>
  <li><b>code_02_hyperparameters_tuning.ipynb</b>: Code for hyperparameter tuning using AAO or any other optimizer from MEALPY.</li>
  <li><b>code_03_feature_selection.ipynb</b>: Code for feature selection using AAO or any other optimizer from MEALPY.</li>
  <li><b>code_04_ml_comparison.ipynb</b>: Code for comparing the performance of the proposed model with various machine learning models.</li>
  <li><b>data_org.csv</b>: The original dataset used for smart grid stability prediction before preprocessing.</li>
  <li><b>data_a.csv</b>: The augmented version of the dataset before preprocessing</li>
</ol>


## AAO in MEALPY
The proposed AAO has been integrated into the MEALPY Python library and can be used directly from this <a href="https://github.com/thieu1995/mealpy/blob/master/mealpy/swarm_based/AO.py">link</a>.


## Please consider citing our work:
Al-Selwi, S. M., Hassan, M. F., Abdulkadir, S. J., Ragab, M. G., Alqushaibi, A., & Sumiea, E. H. (2024). Smart Grid Stability Prediction Using Adaptive Aquila Optimizer and Ensemble Stacked BiLSTM. Results in Engineering, 24, 103261. doi: https://doi.org/10.1016/j.rineng.2024.103261.
<br>

## BibTeX
```
@article{alselwi2024smart,
  title={Smart Grid Stability Prediction Using Adaptive Aquila Optimizer and Ensemble Stacked BiLSTM},
  author={Al-Selwi, Safwan Mahmood and Hassan, Mohd Fadzil and Abdulkadir, Said Jadid and Ragab, Mohammed Gamal and Alqushaibi, Alawi and Sumiea, Ebrahim Hamid},
  journal={Results in Engineering},
  pages={103261},
  year={2024},
  publisher={Elsevier},
  doi = {https://doi.org/10.1016/j.rineng.2024.103261},
  url = {https://www.sciencedirect.com/science/article/pii/S2590123024015159}
}
```


Corresponding author [Safwan Mahmood Al-Selwi](mailto:saf1.alselwi@gmail.com?Subject=RNN_LSTM_SLR) @ 2024

Thank you
