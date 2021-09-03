# Automate Windows Setup
*You can prevent some or all of the user interface (UI) pages from Windows Setup from being displayed during installation. The default behavior of Windows Setup is to display the Setup UI if any of the required settings are incorrect or empty.*

## Use an answer file while installing Windows
You can automate Windows installation by using an answer file:

**Use a USB flash drive**
1. Use this existing answer files or create your own with Windows System Image Manager (Windows SIM).
2. Save the file as autounattend.xml on the root of a USB flash drive.
3. On a new PC, insert a Windows installation USB flash drive, as well as the flash drive that contains Autounattend.xml and then boot the PC. When no other answer file is selected, Windows Setup searches for this file.
