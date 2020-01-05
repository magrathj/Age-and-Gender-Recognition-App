# Deploy Age and Gender Recognition Model to the Edge App

This project uses Intel Openvino to build an age and gender recognition app, which can be deployed as an edge application.

The app takes in an image and performs inference on it to predict the gender of the person in the image. Using the [age-gender-recognition-retail-0013](https://docs.openvinotoolkit.org/latest/_models_intel_age_gender_recognition_retail_0013_description_age_gender_recognition_retail_0013.html)


```
python app.py -i "images/download (1).jpg" -t "DETECTION" -m "/home/workspace/models/age-gender-recognition-retail-0013.xml" -c "/opt/intel/openvino/deployment_tools/inference_engine/lib/intel64/libcpu_extension_sse4.so"

```


![input](https://github.com/magrathj/Age-and-Gender-Recognition-App/blob/master/images/download%20(1).jpg)




![output](https://github.com/magrathj/Age-and-Gender-Recognition-App/blob/master/outputs/DETECTION-output.png)
