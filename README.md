README.md
# Yolo v5n human detection

The model recognises humans from far (4feet) with accuracy 
## training

using yolo v5n trained on custom dataset via 

{universe.roboflow.com, and custom dataset(self labeled) 

## format
The following model is provided in ".pt" format for yolo and also in ".tflite" format for better integration on less compute devices
## Deployment

To deploy this project run

```bash
  conda env create -f environment.yml
  conda activate y5train310
```



## Running Model

To run the model using yolo
```bash
  python main.py
```
And to run via tensorflow lite
```bash
  python tflite.py
```


## Authors

- [@Gandhaar Joshi](gandhaarjoshi@outlook.com)
