# Deploy Age and Gender Recognition Model to the Edge App

This project uses Intel Openvino to build an age and gender recognition app, which can be deployed as an edge application.

The app takes in an image and performs inference on it to predict the gender of the person in the image


```
python app.py -i "images/sitting-on-car.jpg" -t "DETECTION" -m "/home/workspace/models/age-gender-recognition-retail-0013.xml" -c "/opt/intel/openvino/deployment_tools/inference_engine/lib/intel64/libcpu_extension_sse4.so"
```

