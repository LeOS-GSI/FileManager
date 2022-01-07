# LeOS FileManager
An open source Material Design file manager, for LeOS-GSI

## Features

- Open source: Lightweight, clean and secure.
- Material Design: Follows Material Design guidelines, with attention into details.
- Breadcrumbs: Navigate in the filesystem with ease.
- Root support: View and manage files with root access.
- Archive support: View, extract and create common compressed files.
- NAS support: View and manage files on SFTP and SMB servers.
- Themes: Customizable UI colors, plus night mode with optional true black.

## Inclusion in custom ROMs

Thank you if you choose to include FileManager in your custom ROM! However since I've received several user complaints due to improper inclusion, I'd like to offer some suggestions on including this app properly for the good of end users:

- Please don't replace the AOSP [DocumentsUI](https://android.googlesource.com/platform/packages/apps/DocumentsUI/) app with this app. This app is not designed to replace DocumentsUI and can't handle a number of functionalities in DocumentsUI - in fact, it relies on DocumentsUI to do things like granting external SD card access.

- Please make sure this app can be uninstalled or at least disabled. Some users may not want this app for a variety of reasons, and get very upset when they can't remove it.

- Please avoid conflict with the Play/F-Droid version of this app. App stores cannot update apps signed with a different signature, so you can either ship an APK that's signed by me (or F-Droid) so that users will be able to update it on Play/F-Droid, or fork this project and rename the package name when you need to sign the APK with a different certificate and potentially making other changes.

## License

    Copyright (C) 2018 Hai Zhang

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
