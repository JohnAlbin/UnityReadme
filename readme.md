# Unity Readme

Add a Readme / Tutorial to the inspector tab of your Unity project.

<img
  src="readme-screenshot.png?raw=true"
  alt="Screenshot of Unity 2018 showing the inspector with Readme content."
  width="439"
  height="336"
/>

## Usage

Download this [project’s Unity package](build/Readme.unitypackage?raw=true).

In your own Unity project, add the Readme by choosing “Assets” → “Import
Package” → “Custom Package” from the Unity editor’s menus.

<img
  src="readme-import-screenshot.png?raw=true"
  alt="Screenshot of Unity 2018 showing how to import a custom package."
  width="448"
  height="244"
/>

## How to edit the readme’s contents

First make sure the Readme is shown in the Unity editor “Inspector” tab. Then
the file can be edited by clicking on the drop-down menu to the right of the
“Inspector” tab and picking the “Debug” option.

The Readme contents are divided into “Sections”. Each section has a “Heading”
and a “Text” body.

Each section can have an optional “Link Text” and “Url” field. Adding both of
these fields will allow a user to open your link in their web browser.

To add more sections to the Readme, change the “Size” field at the top of
“Sections”.

The current icon used in this inspector is found at:
    »Readme / Icons / Readme_Builder.png

You can use any PNG file (and file name) for the icon.

1. Add the new icon to the project.
2. In the Unity inspector, change the icon’s “Texture Type” to “Editor GUI and
   Legacy GUI”.
3. Then open the “debug” version of the Readme inspector and drag the new icon
   into the “Icon” field.

## Advanced editing technique

Adding long text to the “text” field in Unity’s “debug” screen is cumbersome.

The Readme file can also be edited by opening this project’s “Readme.asset” file
in a text editor. The file is in Yaml syntax and can contain UTF-8 characters.

For example, this section was written using a text editor and uses the Yaml “|-”
(pipe and dash) characters to add multi-line text to a single yaml value.

[Learn about Yaml syntax](http://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html).

## License

Read the [license](LICENSE.md).
