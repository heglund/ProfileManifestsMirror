# Mirror of ProfileManifests in JSON Format for Jamf

[![Build Status Badge](https://github.com/Jamf-Custom-Profile-Schemas/ProfileManifestsMirror/actions/workflows/build.yml/badge.svg)](https://github.com/Jamf-Custom-Profile-Schemas/ProfileManifestsMirror/actions/workflows/build.yml)
![Manifest Count](https://img.shields.io/badge/manifests-223-blue)

This repository contains Jamf JSON schema manifests automatically generated from the repository of [ProfileCreator manifests](https://github.com/ProfileCreator/ProfileManifests).

To find a manifest on this repo's GitHub page, type `T` and then type part of the preference domain for the app you wish to manage.

## Use at your own risk

Because these manifests have been automatically generated by a relatively new build script, they should be used with caution. The manifest files come with no warranty as to their accuracy or functionality, and are meant to serve as a convenient reference repository for Jamf administrators. Check the raw plist prior to deploying any profile to ensure the contents are as you expect.

## Submit _manifest_ changes upstream

Any corrections, additions, or modifications to the manifests in this repository should be submitted upstream to the [ProfileManifests](https://github.com/ProfileCreator/ProfileManifests) repository. Once pull requests are merged there, subsequent builds of this repository will include the changes.

## Submit _build script_ changes here

On the other hand, pull requests are welcome here if you have contributions to the [`build.py`](https://github.com/Jamf-Custom-Profile-Schemas/ProfileManifestsMirror/blob/main/build.py) script that produces the manifests or the [`build.yml`](https://github.com/Jamf-Custom-Profile-Schemas/ProfileManifestsMirror/blob/main/.github/workflows/build.yml) GitHub workflow that triggers the script. There are a few items marked TODO if you'd like some puzzles to solve.

## Further reading

- [Elliot Jordan: ProfileCreator Manifests Now Available for Jamf](https://www.elliotjordan.com/posts/profilemanifestsmirror/)
- [Jamf: Application & Custom Settings](https://developer.jamf.com/developer-guide/docs/application-and-custom-settings)
- [ProfileCreator](https://github.com/ProfileCreator/ProfileCreator)
- [iMazing Profile Editor](https://imazing.com/profile-editor)
