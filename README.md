# Ventilator-Pressure-Prediction

- **Problem :**
Current simulators are trained as an ensemble, where each model simulates a single lung setting. However, lungs and their attributes form a continuous space, so a parametric approach must be explored that would consider the differences in patient lungs

- **Solution:**
Generalize the simulation rather than to confine a simulator to a single lung type.

- **Approach**
Usage of LSTM driven models which predict the correct pressure depending upon the type of lung, provided the lung attributes; Hence providing a better system to work with.
___
| **[Code](https://github.com/Bot-7037/Ventilator-Pressure-Prediction/blob/main/Notebook.ipynb)** |
**[Playground](https://bot-7037.github.io/Ventilator-Pressure-Prediction/Presentation/RevealJsMaterial/index.html)** |
