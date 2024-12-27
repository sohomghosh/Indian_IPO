# Indian_IPO

Datasets: The datasets can be btained from https://huggingface.co/datasets/sohomghosh/Indian_IPO_datasets/

Note: The code structure for Opening, High, Closing prices remaings the same. Only the name of dependant (Y) variable changes. We are presneting codes for Opening prices. You can use it for High and Closing prices too.

For Training models with numeric & categorical features only
-
Refer to the folder: https://github.com/sohomghosh/Indian_IPO/tree/main/numeric_categorical_only_models
File names having _Underpricing in their names are used for training underpricing predicting models. Other files are used for predicting direction of prices.

For Training models with probabilities from Machine Learning models trained using Nomic Embeddings
-
Refer to the folder: https://github.com/sohomghosh/Indian_IPO/tree/main/nomic_based_models
For extracting nomic embeddings: https://github.com/sohomghosh/Indian_IPO/blob/main/nomic_based_models/Nomic_embeddings.ipynb
For training Machine Learning models with Nomic Embeddings: https://github.com/sohomghosh/Indian_IPO/blob/main/nomic_based_models/model_make_text_features_nomic_embeddings.ipynb
Out of the remaining files, the ones having _Underpricing in their names are used for training underpricing predicting models. Other files are used for predicting direction of prices.

For Training DeBERTa models
-
Refer to the folder: https://github.com/sohomghosh/Indian_IPO/tree/main/DeBERTa_based_models
For extracting deberta based probabilities: https://github.com/sohomghosh/Indian_IPO/blob/main/DeBERTa_based_models/success-high-deberta-sme.ipynb
Out of the remaining files, the ones with names ending with _underpricing are used for training underpricing predicting models. Other files are used for predicting direction of prices.




```bibtex
@misc{ghosh2024experimentingmultimodalinformationpredict,
      title={Experimenting with Multi-modal Information to Predict Success of Indian IPOs}, 
      author={Sohom Ghosh and Arnab Maji and N Harsha Vardhan and Sudip Kumar Naskar},
      year={2024},
      eprint={2412.16174},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2412.16174}, 
}
```
