# Command Mapper
A small python3 programm to map shell commands and python3 code to your controller through the inputs library

# Usage

Install python 3 and execute **pip install** -r **requirements**.**txt**.
After that simply run the programm with **python** **main.py**

# Bindings
You can edit your bindings in the **inputs.json** file.
You can use following buttons: 

| Button Name | XBox                      |
|-------------|---------------------------|
| BTN_SOUTH   | A                         |
| BTN_NORTH   | Y                         |
| BTN_WEST    | X                         |
| BTN_EAST    | B                         |
| BTN_SELECT  | Bottom right of XBox Logo |
| BTN_START   | Bottom left of XBox Logo  |
| BTN_THUMBR  | Right thumbstick click    |
| BTN_THUMBL  | Left thumbstick click     |
| BTN_TR      | RB                        |
| BTN_TL      | LB                        |
| ABS_HAT0Y   | DPad up and down          |
| ABS_HAT0X   | DPad left and right       |

When you starts your command with **(@PY)** it will be executed as python 3 code else it will be executed as a shell command.
## Example
```json
{
  "BTN_SOUTH": [
    "git init",
    "(@PY)print(\"South\")"
  ],
  "BTN_WEST": [
    "(@PY)print(\"West\")"
  ]
}
```
# Credits
**Inputs** by **zeth** used to acces the controller inputs: https://github.com/zeth/inputs
