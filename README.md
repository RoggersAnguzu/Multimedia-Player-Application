# RanguzuMultimedia
Multimedia Player is a simple Windows Forms application that allows users to play audio files using the Windows Media Player component. This project demonstrates how to create a basic multimedia player with play, pause, stop, and resume functionality.

# Features
Play audio files.
Pause and resume playback.
Stop playback.
Getting Started
Prerequisites
Windows operating system
.NET Framework
Installation
Clone or download the repository.

bash
Copy code
git clone https://github.com/RoggersAnguzu/multimedia-player.git
Open the solution in Visual Studio.

Build the solution to restore any missing packages.

# ScreenShots
![Screenshot 2023-08-24 104430](https://github.com/RoggersAnguzu/RanguzuMultimedia/assets/141458053/826dfd84-f525-405d-ae0e-ffc378ea3832)

# Usage
Launch the application.

Click the Open button to select an audio file from your local system.

Use the Play, Pause, and Stop buttons to control audio playback.

# How It Works
The application is built using Windows Forms, a graphical user interface framework provided by .NET. The main components and their functionalities are as follows:

axWindowsMediaPlayer1: This is an instance of the Windows Media Player ActiveX control, which is used to play multimedia content.

Open Button: Clicking this button opens a file dialog to select an audio file to play.

Play Button: Initiates audio playback using the URL of the selected audio file.

Pause Button: Pauses the currently playing audio.

Stop Button: Stops the audio playback and resets the player to the beginning of the track.

# Contributions
Contributions are welcome! If you find any issues or want to add new features, feel free to open a pull request.
