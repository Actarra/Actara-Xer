# Actara-Xer

Free Excel add-in for reading Primavera P6 XER files, reviewing activity details, project statistics, schedule mechanics, and comparing updates.

## Download

Download **Actara-Xer.zip** from [Releases](https://github.com/Actarra/Actara-Xer/releases), under **Assets**. Use the release ZIP rather than GitHub's **Code > Download ZIP**, which contains this repository's documentation.

**The first release is being prepared. No add-in download is published yet.**

Like [Actara Planner](https://github.com/Actarra/Actara-Planner), the release package will contain the Excel add-in, a PDF installation and quick-use guide, and SHA-256 checksums. VBA source is not distributed in this repository.

## Installation

Platform: **Microsoft Excel Desktop for Windows**. VBA macros are required.

1. Close Excel.
2. Right-click the downloaded ZIP, choose **Properties**, and select **Unblock** if shown. Extract the ZIP.
3. Copy the `.xlam` file from the package to `%APPDATA%\Microsoft\AddIns`.
4. Open Excel and go to **File > Options > Add-ins**.
5. Beside **Manage: Excel Add-ins**, choose **Go**, then **Browse**.
6. Select the `.xlam` file, ensure it is checked, and choose **OK**.
7. Restart Excel and confirm the **Actara Xer** ribbon tab appears.

For the full installation and quick-use instructions, open the PDF guide included with the release package.

## Quick start

Open **XER Hub > Add XER...**, select an XER file, and load one project. The first project opens in **Activities**. When another project is already displayed, choose whether to replace the view or keep the new project loaded in the Hub.

The ribbon provides **Activity Detail**, **Project Overview**, **Schedule Mechanics**, **Compare XERs**, **Export for AI**, and **Create P6 PLF**. **Ctrl+Shift+X** opens the compact menu when the ribbon is unavailable.

## Updating or uninstalling

To update, close Excel and replace the installed add-in with the file from the new release. If its filename changes, use **Excel Add-ins > Browse** to select the new file.

To uninstall, clear the Actara Xer checkbox in **File > Options > Add-ins > Manage: Excel Add-ins > Go**, close Excel, and remove the installed `.xlam` file.
