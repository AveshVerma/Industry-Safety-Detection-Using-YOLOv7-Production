# Industry-Safety-Detection-Using-YOLOv7-Production

## Workflows
- constants
- config_entity
- artifact_entity
- components
- pipeline
- app.py

## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```
## AWS Configurations

```bash
#https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
aws configure
#Now set the access key and secret access keys
git commit -m "Updated"

git push origin main

## How to run?

```bash
conda create -n safety python=3.8 -y
```

```bash
conda activate safety
```

```bash
pip install -r requirements.txt # Copied from YOLOv7 official documentation. -e . is used for setup.py installation
```

```bash
python app.py
```

I have renames best.pt to best.pt1 to push the model to Git, please rename the model as best.pt and copy it inside yolov7 folder to avoid training and use pretrained model.