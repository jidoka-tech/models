

### Version 1 

- Forked tensorflow/models repo on Oct 28,2018
- Bug fixes
  - Added the following line of code at line #25 of object_detection/model_lib.py
    - ```import matplotlib; matplotlib.use('Agg')```
  - For using Python3, add list() to category_index.values() in model_lib.py about line 414 as this list(category_index.values()).
    - Refer: https://github.com/tensorflow/models/issues/4780#issuecomment-405441448
