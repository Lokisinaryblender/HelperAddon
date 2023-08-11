# Blender Helper Add-On

The Blender Helper Add-On is a custom extension for Blender that enhances your workflow by providing quick access to web search functionality based on recognized objects or entered text. It offers features to perform Google and YouTube searches related to the selected object or entered text.

## Installation

1. Download the entire repository as a ZIP file by clicking on the "Code" button and selecting "Download ZIP".
2. Open Blender.
3. Go to Edit > Preferences.
4. Click on the "Add-ons" tab.
5. Click on "Install..." and select the downloaded ZIP file.
6. Enable the "Blender Helper Add-On" by ticking the checkbox next to it.

Please note that the add-on requires an active internet connection to perform searches.

## Features

### Recognized Object Search

- Select an object in the 3D Viewport.
- In the "Helper" panel, click the "Google Search" or "YouTube Search" button to find tutorials related to the recognized object.
- You can also perform a web search using the "Search Web" button if no object is selected.

### Text Web Search

- Enter a search query in the "Custom Search Text" field.
- Choose between Google and YouTube search engines from the dropdown.
- Click the respective search buttons to perform a web search for the entered text using the selected search engine.

## Usage

1. Open Blender.
2. In the 3D Viewport, select an object (for Recognized Object Search) or enter text (for Text Web Search).
3. In the "Helper" panel located in the right-hand side N-panel, you'll find the available search buttons.
4. For Recognized Object Search:
   - If an object is recognized, the add-on will display its name along with Google and YouTube search buttons tailored for the object's name.
   - Click the appropriate search button to initiate the search based on the recognized object.
5. For Text Web Search:
   - Enter your desired search text in the "Custom Search Text" field.
   - Choose the desired search engine (Google or YouTube) from the dropdown.
   - Click the respective search button to initiate the web search for the entered text using the selected search engine.

Please note that the add-on includes safety checks to prevent sensitive or inappropriate keywords from being used in searches.

## Notes

- For Recognized Object Search, the add-on uses a recognition algorithm to identify objects based on their geometry and properties.
- The add-on's functionality is intended for quick access to search engines within Blender for relevant tutorials and information.
- Contributions are welcome! If you find any issues or have ideas to improve the add-on, feel free to create an issue or a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This add-on was developed by [lokisinary].
- Special thanks to the Blender community for their support and feedback.

## Support

For any questions, bug reports, or feature requests, please contact [lokisinary] at [lokisinaryblender@gmail.com].

## Version History

- Version 1.0:
  - Initial release of the Blender Helper Add-On.
  - Added Recognized Object Search and Text Web Search functionalities.
  - Supported Google and YouTube search engines.

