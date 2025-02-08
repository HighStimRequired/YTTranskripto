# YTTranskripto

YTTranskripto is a desktop application that allows users to retrieve and export YouTube video transcripts effortlessly. Built with Python and PyQt5, the app leverages the [youtube-transcript-api](https://github.com/jdepoix/youtube-transcript-api) and [pytube](https://github.com/pytube/pytube) libraries to fetch transcripts and provides flexible export options in multiple formats (TXT, CSV, JSON, DOCX, SRT). The application also offers options to toggle the inclusion of timestamps and select the preferred timestamp format, all within a sleek dark-themed interface.

## Features

* **Transcript Retrieval:** Automatically fetch transcripts for YouTube videos using the English transcript if available, with a fallback to the first available language.

* **Timestamp Options:** Enable or disable timestamps and choose between "HH:MM:SS" and "mm:ss" formats.

* **Export Options:** Save transcripts in various formats:

  * **TXT**: Plain text with optional timestamps.
  * **CSV**: Comma-separated values including transcript text and duration.
  * **JSON**: Raw transcript data in JSON format.
  * **DOCX**: Formatted transcript in a Word document.
  * **SRT**: SubRip subtitle file for use in video players.

* **Dark-Themed UI:** Enjoy a visually pleasing interface with YouTube-red accents and a user-friendly layout.

* **User Preferences:** Settings such as export format, timestamp inclusion, and timestamp format are preserved between sessions using QSettings.

## Requirements

* Python 3.6 or later
* [PyQt5](https://pypi.org/project/PyQt5/)
* [youtube-transcript-api](https://pypi.org/project/youtube-transcript-api/)
* [pytube](https://pypi.org/project/pytube/)
* [python-docx](https://pypi.org/project/python-docx/)

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/YTTranskripto.git
   cd YTTranskripto
   ```

2. **Install Dependencies:**

   Use pip to install the required packages:

   ```bash
   pip install PyQt5 youtube-transcript-api pytube python-docx
   ```

3. **Run the Application:**

   ```bash
   python yttranskripto.py
   ```

## Usage

1. **Enter a YouTube URL:**\
   Launch the application and enter the URL of the YouTube video you wish to transcribe.

2. **Fetch the Transcript:**\
   Click the "Get Transcript" button to retrieve the transcript.

3. **Toggle Timestamp Settings:**\
   Use the checkbox to include or exclude timestamps and select your preferred format from the dropdown. The transcript display updates immediately based on your selection.

4. **Export the Transcript:**\
   Choose an export format from the "Export as:" dropdown and click "Export Transcript" to save your transcript to the desired file format.

## Contributing

Contributions are welcome! If you have suggestions, bug fixes, or new features, please feel free to fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](https://chatgpt.com/c/LICENSE) file for details.

***
