# unity-script-templates
 A collection of script templates for Unity

[![license](https://img.shields.io/badge/LICENSE-MIT-green.svg)](LICENSE)

[日本語版READMEはこちら](README_JP.md)

This repository is a collection of script templates for Unity. It includes numerous templates that are tailored to Unity features, reducing the effort required when creating new script files.

## Setup

There are two methods to add custom script templates to your editor.

### 1. Add ScriptTemplates to your project

To introduce script templates into each project, follow these steps:

1. Download the unitypackage file and double click to import it.
2. Restart the editor. A restart is necessary to reflect the templates in the MenuItem.
3. You can access the templates from the Create menu in the Project window.

The `ScriptTemplates` folder must be placed directly under the Assets folder and should not be moved.

### 2. Add ScriptTemplates to Unity Editor

You can also add ScriptTemplates directly to the Unity Editor executable.

1. Ensure that the editor is not running.
2. Open the `ScriptTemplates` folder within Unity's folder.
3. Download the template files and add them to Unity's `ScriptTemplates` folder.
4. When you open the editor, you can access the templates from the Create menu in the Project window.

The `ScriptTemplates` folder is located in the following locations:

Windows: `\Unity\Editor\Data\Resources\ScriptTemplates`
Mac: `/Unity.app/Contents/Resources/ScriptTemplates`

You will need to add them again if you change the editor version. Templates with the same name in the `Assets/ScriptTemplates` folder take priority.

## Templates

| C# |
| - |
| C# Class |
| C# Struct |
| C# Interface |

| General |
| - |
| MonoBehaviour |
| ScriptableObject |

| Editor |
| - |
| Editor |
| EditorWindow |
| PropertyDrawer |
| Editor (UIToolkit) |
| EditorWindow (UIToolkit) |
| PropertyDrawer (UIToolkit) |

| ECS |
| - |
| ComponentData |
| System (ISystem) |
| System (SystemBase) |
| Authoring |

| Text Files |
| - |
| Text |
| Json |
| Xml |
| Markdown |

| Others |
| - |
| Package Manifest |

## Contribute

If you'd like to propose the addition of templates, fork this repository and submit a pull request.

## License

[MIT License](LICENSE)
