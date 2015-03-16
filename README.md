# android-string-localization-tool
As the name says, it's an eclipse plugin for "Android Development Tools (ADT)" to support the localization for string resources in android. This can be plugged/installed on existing ADT. This plugin supports the translation the elements of strings.xml to more than 60 languages.

How it works:
This plugin reads the "strings.xml" from "res/values" folder and parses each element in the XML file. Each element is then converted to the languages selected by user using Google Translate. The translated files are kept under respective folders for ex. For "FRENCH" languages, the file is kept under "res/values-fr" folder.

For suggestions/comments, please email to "santoshbmath@gmail.com". For issues, raise an issue in issues tab.

Features:
1. Very light weight (less than 50KB).
2. Supports more than 60 languages.
3. Support of using proxy settings.
4. Can be integrated with existing eclipse instead of using separate tool.

Installation:
1. Download the plugin from "com.ud.stringlocalization_1.0.0.jar" or from "Links" section (on right side of this page).
2. Copy the jar file into your ADT_INSTALL_LOCATION/plugins/ or ECLIPSE_INSTALL_LOCATION/plugins/ folder.
3. Restart the eclipse or ADT.

Usage:
1. Right click on any android project and select "Android Tools > Create Localization Resources".
2. Select the languages you want to translate and click "Translate".
3. Optionally, if you are behind proxy server, enable and set the proxy details.

Note:
1. It requires internet connection to translate.
2. It will overwrite the existing file(if any).
3. It will translate all the variables of strings.xml.

Future Enhancements:
1. Support for translating multiple lines.
2. Provide option to user to enable/disable overwriting of existing file.
3. An option to de-slect translating certain variables in strings.xml.
