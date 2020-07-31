# Simulator

The JavaScript simulator allows you to test and execute most BBC micro:bit programs in the browser.
It allows you to emulate sensor data or user interactions.

```sim
input.onButtonPressed(Button.A, function () {
    devices.tellCameraTo(MesCameraEvent.LaunchPhotoMode)
    basic.pause(1000)
    devices.tellCameraTo(MesCameraEvent.TakePhoto)
})
input.onButtonPressed(Button.AB, function () {
    devices.tellCameraTo(MesCameraEvent.StopVideoCapture)
})
input.onButtonPressed(Button.B, function () {
    devices.tellCameraTo(MesCameraEvent.LaunchVideoMode)
    basic.pause(1000)
    devices.tellCameraTo(MesCameraEvent.StartVideoCapture)
})
```
