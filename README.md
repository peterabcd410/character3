# 概述

本章的代码基于opencood，基准模型为F-copper。

参考链接：https://opencood.readthedocs.io/en/latest/md_files/data_intro.html


# 训练
```python
python tools/train.py --hypes_yaml ${CONFIG_FILE} [--model_dir  ${CHECKPOINT_FOLDER} --half]
```

# 测试
```python
python tools/inference.py --model_dir ${CHECKPOINT_FOLDER} --fusion_method ${FUSION_STRATEGY} [--show_vis] [--show_sequence]
```
