This repository contains a notebook `ArizeDemo.ipynb`, which demonstrates one approach for integrating Arize with Algorithmia. The workflow contains the following steps:
* Train an `sklearn` model.
* Upload the model to Algorithmia.
* Call the model for inference by piping model input into the [sklearn_demo](https://algorithmia.com/algorithms/algorithmia_arize/sklearn_demo) algorithm hosted on Algorithmia's public cluster. The algorithm is set up to log inference metrics to Arize before returning a response.
