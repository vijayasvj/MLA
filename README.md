## Usage of Daisi

It is recommended to use this application on the daisi platform itself using the link https://app.daisi.io/daisies/vijay/ML_Assistant_for_CSV/app. However, you can still use your own editor using the below method:

### First, load the Packages:

```
import pydaisi as pyd
ml_assistant_for_csv = pyd.Daisi("vijay/ML_Assistant_for_CSV")
```

### Now, connect to Daisi and access the functions using the following functions:

Dataset Cleaning:

```
ml_assistant_for_csv.dataset_cleaner(df).value
```

Feature Extraction:

```
ml_assistant_for_csv.feature_extractor(dataframe).value
```

Dataset Augmentation:

```
ml_assistant_for_csv.augmentation(df, os_name, ch=None).value
```

Model Building:

```
ml_assistant_for_csv.model_training(df, os_name).value
```

## And done! We have the CSV Data Processed as per our needs!
