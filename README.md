# Robot Arm Rigging

Rigging the robot arm from CS6983 Coding Assignment 2 in Blender.

## Files

| File | Description |
|---|---|
| `robot_arm.blend` | Rigged robot arm (armature with bones, each part attached to its bone) |
| `robot_arm.fbx` | FBX export of the rigged arm (+Z forward, Y up) |

## Rigging process

Here's what I did step by step:
I selected a part which was the base in the first step. I clicked shift +s -> Cursor to Selected then added an armature from the add menu. I aligned the tip of that bone with the next shape and extruded from there. I repeated everything then one by one attached each part to its bone.

The difficult part was understanding which part to attach to the bone. I often did that wrong and got weird interactions when I tried rotating that bone.

The rest of the task was pretty easy and straightforward

## AI Usage

I used Claude (Anthropic) for step-by-step Blender rigging instructions. The rigging in Blender was done by me.
