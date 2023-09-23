# unity-script-templates

このリポジトリはUnity向けのScriptテンプレートのコレクションです。Unityの機能に対応した多数のテンプレートを追加し、新しくScriptファイルを作成する際の手間を削減します。

[English README is here](README.md)

## セットアップ

独自のScriptテンプレートをエディタに追加するには2種類の方法があります。

### 1. プロジェクトにScriptTemplatesを追加する

各プロジェクトごとにScriptテンプレートを導入する際には、以下の手順に従って行います。

1. unitypackageファイルをダウンロードし、ダブルクリックしてインポートします。
2. エディタを再起動します。MenuItemにテンプレートを反映させるには再起動が必要です。
3. ProjectウィンドウのCreateメニューからテンプレートを利用できます。

`ScriptTemplates`フォルダはAssetsフォルダ直下に配置する必要があり、移動させることはできません。
   
### 2. UnityエディタにScriptTemplatesを追加する

Unityの実行ファイルに直接ScriptTemplatesを追加することも可能です。

1. エディタが起動していないことを確認します。
2. Unityのフォルダ内にある`ScriptTemplates`フォルダを開きます。
3. テンプレートのファイルをダウンロードし、Unityの`ScriptTemplates`フォルダ内に追加します。
4. エディタを開くと、ProjectウィンドウのCreateメニューからテンプレートを利用できます。

`ScriptTemplates`フォルダは以下の場所に置かれています。

Windows: `\Unity\Editor\Data\Resources\ScriptTemplates`
Mac: `/Unity.app/Contents/Resources/ScriptTemplates`

エディタのバージョンを変更した際には再度追加する必要があります。また、`Assets/ScriptTemplates`フォルダに同じ名前のテンプレートがある場合にはそちらが優先されます。

## 一覧

| テンプレート |
| - |
| <b>C#</b> |
| C# Class |
| C# Struct |
| C# Interface |
| - |
| <b>General</b> |
| MonoBehaviour |
| ScriptableObject |
| - |
| <b>Editor</b> |
| Editor |
| EditorWindow |
| PropertyDrawer |
| Editor (UIToolkit) |
| EditorWindow (UIToolkit) |
| PropertyDrawer (UIToolkit) |
| - |
| <b>ECS</b> |
| ComponentData |
| System (ISystem) |
| System (SystemBase) |
| Authoring |
| - |
| <b>Text Files</b> |
| Text |
| Json |
| Xml |
| Markdown |
| - |
| <b>その他</b> |
| Package Manifest |

## 貢献する

テンプレートの追加を提案したい場合には、このリポジトリをフォークしてプルリクエストを送信してください。

## ライセンス

[MIT License](LICENSE)