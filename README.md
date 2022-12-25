branch "model_params" and "bert-based-uncased" are two parts of model parameters.
Download them and put them into folders whose name is the same as the branch name. 
# ATTENTION: Please download the files "pytorch_model.bin" and "bert_classify.params" separately, not in bundles. 
that is, the file category should be the following:
-Bert_classify
  -_pycache_
  -bert-based-uncased
    -config.json
    -pytorch_model.bin
    -vocab.txt
  -model_params
    -bert_classify.params
  -BERT_classify.pyproj
  -BERT_classify_model.py
  -DataLoad.py
  -Predict.py
  -Test.py
  -Train.py
