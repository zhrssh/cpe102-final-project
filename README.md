# CPE102 Final Project
This a final requirement for our elective course, Intelligent Systems. This project uses yolov5 model to detect people with or without face masks. It labels people who are currently wearing masks and who are not. The model was trained in Google Colab.

## Members:
1. Jayme, Karla Danielle
2. Mayordo, Zherish Galvin
3. Natividad, Marc Alvin

**Note:** This project was executed using Google Colab.

## How to run:
1. Clone yolov5 using: `git clone https://github.com/ultralytics/yolov5.git`
2. Install yolov5 requirements: `pip install -r yolov5/requirements.txt`
3. Run **best.pt**: `python yolov5/detect.py --weights path/to/best.pt --source 0`
