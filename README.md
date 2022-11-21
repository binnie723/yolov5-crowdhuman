##  참고한 Head & Person Detection Model 

원래 model LinkL https://github.com/deepakcrk/yolov5-crowdhuman
Download Link:  [YOLOv5m-crowd-human](https://drive.google.com/file/d/1gglIwqxaH2iTvy6lZlXuAcMpd_U0GCUb/view?usp=sharing) 


<br/>

**Output **

![image](https://user-images.githubusercontent.com/86834982/203069703-8484a7e4-3fe5-4a90-b9af-4a56007b871b.png){: width="70%" height="70%"}

<br/>



## Test

```bash
$ python detect.py --weights crowdhuman_yolov5m.pt --source _test/ --view-img

```
  
  
## Test (Only Person Class)

```bash
python3 detect.py --weights crowdhuman_yolov5m.pt --source _test/ --view-img  --person
```

  
## Test (Only Heads)

```bash
python3 detect.py --weights crowdhuman_yolov5m.pt --source _test/ --view-img  --heads
```
