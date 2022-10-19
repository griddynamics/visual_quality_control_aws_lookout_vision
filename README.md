# Visual Quality Control with AWS Lookout for Vision

## Project description

Amazon Web Services (AWS) provides a Lookout for Vision service for detecting anomalies in images. This is a convenient AutoML service, but is often requires the development of custom video stream preprocessors to integrate the service for use in real-world scenarios, as well as the preparation of labeled datasets to train the anomaly detection model. In this starting kit, we demonstrate how to build an advanced video preprocessor and integrate it with AWS Lookout for Vision using for industry that are using conveyor belts during the manufacturing process.

## How to Use the starting kit

- Upload notebook to `AWS SageMaker`
- Under `Create and train an AWS Lookout for Vision model` provide details of `dataset_folder` with training images for `Lookout For Vision` and `bucket` where folder is stored
- Under `Define I/O locations` in notebook `aws_video_quality_control_starting_kit`, define full s3 location of input video file
- (Optional) Adjust hyperparameters in notebook `aws_video_quality_control_starting_kit` under `Object detection functions`, `Lookout for vision related functions` and `Multi-object tracking` sections
- Run notebook

## License

```
Copyright 2022 Grid Dynamics International, Inc. All Rights Reserved

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```