# Capy releases

Public Windows downloads and update metadata for Capy, a native software and developer tools launcher. This repository is for release distribution.

## Download

Get the Windows x64 portable ZIP from [Releases](https://github.com/anonmms/capyapp-launcher/releases/latest). Each release includes latest.json and SHA256SUMS.txt.

## Install or update

1. Let active installations finish, then close Capy.
2. Extract the ZIP to your application folder. Keep capy.exe, capy-cli.exe and myapp-command.exe together.
3. Run capy.exe. For an update, replace all three executables together.

Your library is stored separately in %LOCALAPPDATA%\CapyAppLauncher. Do not delete or overwrite it when updating the application.

## Update checker

Capy 0.1.1 adds a Capy updates button and optional daily checks. It reads latest.json from the latest stable GitHub Release and opens the release page when a newer version is available. Updates are installed manually in this first version.

## Verification and status

Compare the downloaded ZIP with SHA256SUMS.txt. Checksums detect corruption; they are not publisher signatures. Current builds are development previews and are not Windows publisher-signed.

## Source and licenses

Development source and issue tracking: [olatte2023/myapp-launcher](https://github.com/olatte2023/myapp-launcher). Capy is MIT-licensed. Bundled artwork notices are included in the archive. Third-party app names and logos identify their respective projects; no endorsement is implied.
