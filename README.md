## :cyclone: _OPENVINO_
This is a project that utilizes the OpenVino Pre-trained models in running inference from a webapp. There three models available on the web app, they are Text Detection model, Human Pose Detection, Vehicle Attributes Detection model. These are pre-trained models from the openvino toolkit. There are plans to add more models to the webapp. Contributions are welcome.

## :page_with_curl:  _Instructions on testing the project locally_

**1)** Firstly download OpenVINO Toolkit in your local machine according to the instructions [here](https://software.intel.com/en-us/openvino-toolkit/choose-download)

**2)** Fire up your favourite console & clone this repo somewhere:

__`❍ git clone https://github.com/mohitpandeyji/askai.ga.git`__

**3)** Install [python](https://www.python.org/) if not already installed and run this command to create a virtual environment:

__`❍ conda create -n pyvenv `__

**4)** Activate the virtual environment:

__`❍ conda activate pyvenv `__

**5)** Run this command to install python packages/dependencies:

__`❍ pip install -r requirements.txt `__

**6)** Run to create migrations for changes:

__`❍ python manage.py makemigrations`__

**7)** Run to apply those changes to the database:

__`❍ python manage.py migrate`__

**8)** Start the server to view the webapp:

__`❍ python manage.py runserver `__

**9)** Open your browser and type in this URL to view the webapp:

__`❍ http://127.0.0.1:8000/`__

## :information_source: _Links:_
* [Here](https://www.askai.ga/) is the Live link to this project


## :m: _Model Documentation_

Once again, here are the links to the models, so you can use the **Output** section to help you get started (there are additional comments in the code to assist):

* Human Pose Estimation: [human-pose-estimation-0001](https://docs.openvinotoolkit.org/latest/_models_intel_human_pose_estimation_0001_description_human_pose_estimation_0001.html)
* Text Detection: [text-detection-0004](http://docs.openvinotoolkit.org/latest/_models_intel_text_detection_0004_description_text_detection_0004.html)
* Determining Car Type & Color: [vehicle-attributes-recognition-barrier-0039](https://docs.openvinotoolkit.org/latest/_models_intel_vehicle_attributes_recognition_barrier_0039_description_vehicle_attributes_recognition_barrier_0039.html)

__*Happy developing!*__
