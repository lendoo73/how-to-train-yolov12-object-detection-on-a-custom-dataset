# Train YOLOv12 on a Custom Dataset

This project follows Roboflow's tutorial, [How to Train a YOLOv12 Object Detection Model on a Custom Dataset](https://roboflow.com/blog/train-yolov12-model). The matching [Roboflow notebook](https://github.com/roboflow-ai/notebooks/blob/main/notebooks/train-yolov12-object-detection-model.ipynb) is the source for the training workflow.

## Dataset

The project uses the [Circuit Voltages dataset, version 2](https://universe.roboflow.com/roboflow-100/circuit-voltages/dataset/2). Its included dataset metadata states that it is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) and attributes the original dataset to Vanitchaporn. Preserve that attribution and license when redistributing the dataset.

## Environment

Install the packages listed in `requirements.txt` in a Python environment:

```shell
pip install -r requirements.txt
```

Then open `train_yolov12_object_detection_model.ipynb` with Jupyter. The environment file is a snapshot of the project's local pinned dependencies; some packages are transitive dependencies rather than imports used directly by the notebook.

Set `ROBOFLOW_API_KEY` in a local `.env` file when downloading a dataset from Roboflow. Never commit `.env` or publish API keys.

## Publication notes

The notebook is based on Roboflow's notebook linked above. Verify its redistribution terms before publishing a copy. Model checkpoints and training outputs are local artifacts; verify their redistribution terms before sharing them.
