# unrealScriptEditor-plugin
A plugin wrapper for Lei Xingyu's [unrealScriptEditor](https://github.com/leixingyu/unrealScriptEditor).

![](https://camo.githubusercontent.com/043f1b6edea7f5e80a6f55f139d623047ed75c12765e25c891a9d387570933f8/68747470733a2f2f692e696d6775722e636f6d2f4b736369786c552e706e67)

See original [docs](PythonScriptEditor/Content/Python/unrealScriptEditor/README.md)

## Installation
### Plugget install (recommended)
Installation with plugget automatically installs all dependencies.
1. Install the [plugget Unreal plugin](https://github.com/hannesdelbeke/plugget-unreal)
2. Run these 2 Python commands: (in the bottom left of the Unreal editor) 
```python
import plugget
plugget.install("unreal-script-editor")
```

### Manual install

#### plugin install
- Copy the unrealScriptEditor folder to your unreal plugin folder. either in your project, or in `C:\Program Files\Epic Games\UE_5.0\Engine\Plugins`, or see [UE plugin docs](https://docs.unrealengine.com/5.0/en-US/plugins-in-unreal-engine/)
- Manually install the dependencies with pip from the `requirements.txt` file
- Start Unreal, and go to the menu `Edit/Plugins`
- Search for `python script editor` and enable the plugin named `python script editor`, do not this confuse with `python editor script plugin`

### Finish Install
- Restart Unreal, if all went well a button should now appear the tool bar
<img width="590" alt="image" src="https://user-images.githubusercontent.com/3758308/232469631-7b457d0c-3f18-409c-b725-8f8d1cb0de01.png">

## Community
- unreal forum [thread](https://forums.unrealengine.com/t/free-plugin-python-script-editor/1192090)
- tech-artists.org [thread](https://discourse.techart.online/t/free-plugin-python-script-editor/15918)
