# Shap_Text_Explainability_Turkish

We evaluate three multilingual transformer models' (Bert-multilingual-base, XLM-Roberta-base and dbmdz-Turkish-BERT-model) performance on the irony detection task. We used the IronyTR Dataset which was published at: https://github.com/teghub/IronyTR

After that, using Shap text plots, we try to explain predictions of irony detection models. Shap text plots provides both single instance and global explanations. Moreover, the reddish tokens push the model for positive prediction (ironic) while blue tokens push the model for negative prediction (non-ironic). 
