🔤 Fonts

Custom fonts used in my Omarchy setup.

All font files are stored in this directory and can be installed locally on Linux.

📁 Installation

Copy the font files to the user's local font directory:

mkdir -p ~/.local/share/fonts
cp fonts/files/\* ~/.local/share/fonts/

Then rebuild the font cache:

fc-cache -fv
🔍 Verify Installation

List installed fonts:

fc-list

Search for a specific font:

fc-list | grep -i "Ravi"

You can also list the available font families:

fc-list : family | sort -u
📍 Font Location

User-installed fonts are stored in:

~/.local/share/fonts/

System-wide fonts can be installed in:

/usr/share/fonts/

This setup uses the user-level directory, so sudo is not required.

🔄 Updating Fonts

After adding or replacing font files:

fc-cache -fv
