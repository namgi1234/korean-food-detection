# korean-food-detection

## information

This project is our school's project to detect the Korean diet.
First, it recognize your diet. Next, your diet is scored and the information is emailed to you.

## befor start

This project is based on yolov5. Therefore, you must install yolov5 before starting.

```bash
git clone https://github.com/ultralytics/yolov5
cd yolov5
pip install -r requirements.txt
```

## running code

After running the above code, replace the detect.py file in the existing yolov5 folder and the detect.py file in this repository and save the best.pt file in the yolov5 folder.

Then, modify the detect.py code and run the command below.

```bash
python3 detect.py --weights best.pt --img 640 --conf 0.5 --source 0
```
