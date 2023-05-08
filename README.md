# Learning to connect JavaScript with hardware

Just one of the things I'm learning. https://github.com/hchiam/learning

https://web.dev/devices-introduction

- hardware inputs: `KeyboardEvent`, `onpointerover`/`onpointerdown`/etc., `navigator.getGamepads`/`gamepadconnected`/etc. (details: https://web.dev/devices-introduction)
- hardware audio/video: `navigator.mediaDevices` (details: https://web.dev/devices-introduction)
- print to device: `window.print()` (details: https://web.dev/devices-introduction)
- authenticate with device: WebAuthn (details: https://web.dev/devices-introduction)
- files on device: `await (await [await window.showOpenFilePicker()].getFile()).text();` or `document.getElementById('input[type="file"]').files[0];` (details: https://web.dev/devices-introduction)
- hardware sensors: (`in window`) `Accelerometer`, `Gyroscope`, `LinearAccelerationSensor`, `AbsoluteOrientationSensor`, `RelativeOrientationSensor`, `GravitySensor`, `AmbientLightSensor`, `Magnetometer`; or `DeviceOrientationEvent`, `DeviceMotionEvent` (details: https://web.dev/devices-introduction)
- device GPS: `Geolocation` (details: https://web.dev/devices-introduction)
- device battery: `BatteryManager`, `navigator.getBattery()`, `onchargingchange`/`onlevelchange`/`chargingtimechange`/`dischargingtimechange` (details: https://web.dev/devices-introduction)
- communicate with device over network: `PresentationRequest`, `fetch()`, `WebSocket`, `WebTransport`, `RTCPeerConnection()` (details: https://web.dev/devices-introduction)
