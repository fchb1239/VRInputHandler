# VRInputHandler
Makes VR Input easy

![Download](https://github.com/fchb1239/VRInputHandler/releases/download/1.0.0/VRInputHandler.cs)

Gets input
```cs
// Gets right hand
bool isLeftHand = false;
bool isPressing = InputHandler.GetInput(isLeftHand, InputType.Trigger);
```

Gets joystick direction
```cs
// Gets left hand
bool isLeftHand = true;
Vector2 direction = InputHandler.GetJoystick(isLeftHand);
```

Vibrates controllers
```cs
// Gets right hand
bool isLeftHand = false;
float strenght = 0.1f;
float duration = 0.1f;
Vector2 direction = InputHandler.VibrateController(isLeftHand, strength, duration);
```
