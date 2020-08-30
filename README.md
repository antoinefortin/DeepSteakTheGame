# Deep Steak The Game - A place to chill it down
![Steak](https://i.imgur.com/WsWTleu.png)
Format: ![Alt Text](url)
# Hello 
This is  where we can prototype and explore new ideas, about how video games and data can talk together. It's not a game, it's an experience that drives the mindset of development. From GPU-CPU communications, to mesh encoding, to screen space shaders effects, I honestly do not give a -ick, it's all about crazy code and a place where I can go crazy on shaders!

# URP DX
Based on Unity URP, to inject passes, cut and paste pipelone source and inject command buffer in C#.

# Repo nomenclature 
| Ressource | Infos |
| ------ | ------ |
| /src | All the root code, place your hardware jam in here|
| /Steak | A sandbox, not tracked from local usage  |
| /UnitySolution | A drag and drop Unity Solution |
| /STeakers | A plug and play solution to test Steak driven shaders(DirectX and HLSL) |

# Usage
Drag and drop /UnitySolution to an existing URP project. Everything will should be ready to go...à=
if not !: 
Make sure to delete all CachedPackages and make the URP package in /UnitySolution/Packages (include ShaderGraph, it won't build if you leave if it CachedPackages 🤷)

If bug:
  - Delete .packagelock
  - Close Unity and delete CachedLibs and delete .packagelock in your local package
 
# For Xbox, PS and PC 
The code is not meant to be platform specific. Just fork it and have fun 😍
# Pipeline stuff
DX12 for RT stuff otherwise, fuck around the pipeline as you want.






