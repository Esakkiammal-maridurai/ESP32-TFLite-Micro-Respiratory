# First TFLite Micro Inference on ESP32

## Project Description

This project demonstrates how to deploy a small pre-trained TensorFlow Lite (`.tflite`) model on an ESP32 using **TensorFlow Lite for Microcontrollers (TFLite Micro)**.

The ESP32 loads the TensorFlow Lite model, provides a hardcoded sample input, performs inference, and prints the predicted class through the Serial Monitor.

## Objective

- Deploy a small `.tflite` model on ESP32.
- Use TensorFlow Lite for Microcontrollers.
- Run inference using a hardcoded sample value.
- Display the predicted class in the Serial Monitor.

## Components Required

- ESP32 Development Board
- USB Cable
- Arduino IDE
- TensorFlow Lite for Microcontrollers library
- Trained `.tflite` model

## Working

```text
TFLite Model
     ↓
ESP32
     ↓
Load Model
     ↓
Provide Hardcoded Input
     ↓
Run Inference
     ↓
Get Prediction
     ↓
Print Predicted Class
```

## Example

A sample input value is given to the ESP32.

```text
Input: 28
```

The TensorFlow Lite model processes the input and predicts a class.

```text
Predicted Class: Normal
```

## Technologies Used

- ESP32
- Arduino IDE
- C/C++
- TensorFlow Lite
- TensorFlow Lite for Microcontrollers

## Expected Output

The Serial Monitor displays the input value and the predicted class.

```text
TFLite Micro Inference
Input: 28
Predicted Class: Normal
```

## Result

The TensorFlow Lite model was successfully deployed on the ESP32 using TensorFlow Lite for Microcontrollers, and inference was performed on a hardcoded sample value to obtain the predicted class.
