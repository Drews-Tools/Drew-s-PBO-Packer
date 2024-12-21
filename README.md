# Drew-s-PBO-Packer

# Overview

Drews PBO Packer is a standalone utility designed to streamline the process of packing and managing PBO files for DayZ mods. This program offers an intuitive GUI interface, ensuring that mod creators can efficiently package their mods without diving into complex command-line instructions. It is distributed as a ready-to-use executable, requiring no prior setup or installation of Python.

# Features

DayZ Tools Integration: Automatically detects the installation directory for DayZ Tools.

Mod Source and Destination Management: Allows users to specify the mod source folder and destination for the packed files.

Key Management: Supports creating new keys or using existing private keys for signing mods.

Theme Customization: Choose from multiple themes to personalize the application's appearance.

Progress Feedback: Real-time progress updates and status messages to guide the user through the packing process.

Icon and Resource Inclusion: Ensures all necessary resources, such as icons and images, are included in the final packed output.

# How It Works

DayZ Tools Path:

Upon launching, the program attempts to automatically detect the DayZ Tools installation directory.

If multiple potential paths are found, the user is prompted to select the correct one.

# Mod Packing:

Specify the source folder containing the mod files.

Define the destination folder where the packed PBO files will be stored.

Enter a name for the mod, which will be used to create the final @ModName folder.

# Key Options:

Create New Key: Generates a new private-public key pair for signing the mod.

Use Existing Key: Use an already generated private key for signing the mod files.

# PBO Packing Process:

The program validates the DayZ Tools path and necessary executables.

It packages the mod into a .pbo file using the AddonBuilder tool from DayZ Tools.

The .pbo file is signed with the specified key to ensure compatibility with DayZ servers.

# Output:

The packed .pbo file is placed in the Addons folder of the final @ModName directory.

The .bikey file (if a new key is created) is moved to the Keys folder.

The program provides a success message and the location of the packed mod.

# Requirements

A valid installation of DayZ Tools.

The program is distributed as a standalone .exe file and does not require Python or additional installations.

# User Interface

The GUI is designed to be user-friendly:

Path Selection: Intuitive file and directory selectors for DayZ Tools, mod source, and destination folders.

Status Updates: Clearly visible status labels and a progress bar to track the process.

Key Options: Easy-to-configure key management settings.

# Support and Contributions

# For support, feature requests, or to report issues, please contact the developer through the provided communication channels in the program.

# Enjoy seamless mod packing with Drews PBO Packer!

