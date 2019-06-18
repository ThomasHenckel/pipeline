Thanks Chris for a great workshop

[Hands-on Learning with KubeFlow + Keras/TensorFlow 2.0 + TF Extended (TFX) + Kubernetes + PyTorch + XGBoost + Airflow + MLflow + Spark + Jupyter + TPU](https://www.eventbrite.com/e/full-day-workshop-kubeflow-kerastensorflow-20-tf-extended-tfx-kubernetes-pytorch-xgboost-airflow-tickets-63363033539)

**To watch the recording go here:** [KubeFlow +Keras/TensorFlow2 +TF Extended (TFX) +Kubernetes +PyTorch +XGBoost +Airflow +MLflow +Spark](https://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](https://www.youtube.com/watch?v=OhIa2cnGD8Y)

**Install**

run: 
```curl https://raw.githubusercontent.com/ThomasHenckel/pipeline/master/kubeflow/infrastructure/user-data-cpu.sh | bash```

This will install with some minor modifications i neded to get it to run


**Setup VM**

If you dont have a system, you can create on in google cloud, see: [Quickstart Using a Linux VM](https://cloud.google.com/compute/docs/quickstart-linux)
The system needs quit a bit of hd, and CPU, i used 16 cpu's 200 gb hdd, and a ubuntu 18.04 LTS image

when the system is up login from the terminal, there is a SSH -> "Open in browser" option. and run the install command

When done installing click on the external ip link, for me i had to use http instead of https

**Run an example**

To run the taxi example you have to clone https://github.com/kubeflow/pipelines and compile the sample, using the sample instructions.
