# VR Input Handler
Makes VR input easy

[Download](https://github.com/fchb1239/VRInputHandler/releases/download/1.0.0/VRInputHandler.cs)

Gets input
```cs
// Gets right hand
bool isLeftHand = false;
bool isPressing = VRInputHandler.GetInput(isLeftHand, InputType.Trigger);
```

Gets joystick direction
```cs
// Gets left hand
bool isLeftHand = true;
Vector2 direction = VRInputHandler.GetJoystick(isLeftHand);
```

Vibrates controllers
```cs
// Gets right hand
bool isLeftHand = false;
float strenght = 0.1f;
float duration = 0.1f;
Vector2 direction = VRInputHandler.VibrateController(isLeftHand, strength, duration);
```
