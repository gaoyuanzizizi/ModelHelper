

```python
from ModelHelper.Recognition.RecognitionModels.Template import SarRecognitionTemplate

if __name__ == '__main__':
    word_index_path = '/recognition/alphabeta.txt'
    template = SarRecognitionTemplate(word_index_path)
    train_folder = '/recognition/train'
    test_folder = '/recognition/test'
    output_folder = '/recognition/output'
    model_name = 'Resnet50SarRecognitionModel'
    template.run(train_folder=train_folder, test_folder=test_folder, output_folder=output_folder, model_name=model_name)

```
