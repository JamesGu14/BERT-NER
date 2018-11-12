floyd run --gpu --env tensorflow-1.11 --data james3299/datasets/bert_ner_dataset/1:NERdata \
        --data akarnachev/datasets/bertmodel/1:checkpoint \
        "python BERT_NER.py"