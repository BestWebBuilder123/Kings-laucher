# Download, install, and verify

The current GitHub release provides a Windows executable named **KingsLaucher-1.0.0.exe**.

[Open the v1.0.0 release](https://github.com/BestWebBuilder123/Kings-laucher/releases/tag/v1.0.0)

## 1. Download from the official release page

Open the release page above and download KingsLaucher-1.0.0.exe. Avoid third-party download mirrors or files shared through unrelated links.

The release asset is approximately 74.8 MB. The repository does not currently publish detailed minimum system requirements.

## 2. Verify the SHA-256 digest

On Windows, open PowerShell and run the following command:

    Get-FileHash "$env:USERPROFILE\Downloads\KingsLaucher-1.0.0.exe" -Algorithm SHA256

The expected SHA-256 value for the published file is:

    53058ed2c3acadedf9bfb3eea6a7a79ec28b68a5c1ad30ce74e5eba7c18b3c22

The value printed by PowerShell should match exactly. If it does not match, do not run the file; delete it and download a fresh copy from the release page.

A matching hash confirms that the downloaded bytes match the digest published for this release. It does not establish that the program is safe, signed, or independently audited.

## 3. Review Windows security prompts

Only proceed if you trust the source and understand the permissions the program requests. Do not disable Microsoft Defender, SmartScreen, or other security tools to get the application running. If Windows blocks the file or reports a concern, stop and investigate rather than bypassing the warning.

## 4. Installation details

The release provides an EXE asset. The repository does not yet document the installer's exact screens, startup behavior, or system requirements. Follow only the prompts presented by the application, and do not grant permissions that you do not understand.

## Having trouble?

Open a [bug report](https://github.com/BestWebBuilder123/Kings-laucher/issues/new?template=bug_report.yml) with the release version, Windows version, steps to reproduce, and the exact error text. Remove personal information from screenshots and logs.
