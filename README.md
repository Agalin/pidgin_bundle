# Pidgin Bundle

Simple bundle (MacOS application) structure for Pidgin.  
Displays correct icons (including x2 resolution) in Dock and notifications.  
High resolution icons generated from official svg file.  
Without bundle, application cannot send MacOS notifications!

## Usage
* Download and unpack bundle.
* Create symbolic link named `Pidgin` in `Pidgin.app/Contents/MacOS` linking to your Pidgin binary.
  If installed using Homebrew, then path will be similar to: `/usr/local/Cellar/pidgin/2.13.0_2/bin/pidgin`.
* Copy Pidgin.app to Applications directory.
