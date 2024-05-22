# VMLU submission

This repository was forked from https://github.com/ZaloAI-Jaist/VMLU. Please follow the below instructions to generate the submission file:

```
$ pip install -r requirements.txt
$ python test_prompt.py \
    --llm vtrungnhan9/vmlu-llm \
    --device cuda
```

After running these commands, the submission file: **vtrungnhan9-vmlu-llm.csv** is generated in **./logs** folder. Please note that our model was publicly pushed to [HuggingFace](https://huggingface.co/) and it is automatically downloaded when you run **test_prompt.py** script.
