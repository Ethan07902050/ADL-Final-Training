# ADL-Final-Training

### Execution
```
python sgd_qa.py \
    do_training=true \
    pretrained_model=sgdqa_bertbasecased \
    model.dataset.data_dir=/content/gdrive/MyDrive/ADL21-Final/data-0625 \
    model.dataset.dialogues_example_dir=examples \
    model.dataset.task_name=sgd_all \
    model.dataset.use_fuzzy_match=false \
    model.dataset.joint_acc_across_turn=true \
    model.nemo_path=sgdqa_bertbasecased.nemo \
    trainer.max_epochs=1 \
    trainer.gpus=1
```
