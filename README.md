# Virtual Satellite 4 - FreeCAD Module

Virtual Satellite 4 - FreeCAD Module is an extension for FreeCAD that allows to create a round-trip engineering workflow with Virtual Satellite.

## Project Status

Status [![Build Status](https://travis-ci.com/virtualsatellite/VirtualSatellite4-FreeCAD-mod.svg?branch=development)](https://travis-ci.com/virtualsatellite/VirtualSatellite4-FreeCAD-mod) for *Development* build.

Status [![Build Status](https://travis-ci.com/virtualsatellite/VirtualSatellite4-FreeCAD-mod.svg?branch=master)](https://travis-ci.com/virtualsatellite/VirtualSatellite4-FreeCAD-mod) for *Master* build.

## Purpose

Virtual Satellite 4 FreeCAD Module is an extension to FreeCAD. FreeCAD is an open source mechanical engineering CAD tool. The extension can be easily installed to FreeCAD. It allows to import structural configuration information into FreeCAD and keep it consistently synchronized with Virtual Satellite 

## Requirements 

This program is based on FreeCAD and Python. The following infrastructure is required:
 - FreeCAD 0.18 64bit
 
## Quickstart for users

If you just want to use Virtual Satellite feel free to download it from the [Releases](https://github.com/virtualsatellite/VirtualSatellite4-FreeCAD-mod/releases) section here on GitHub.

## Quickstart for developers

1. Create a new folder in the _mod_ subdirectory of FreeCAD.
2. Copy the zip file from the releases into this directory.
3. Unzip the file.
4. Start FreeCAD.

The Virtual Satellite Workbench is now available in FreeCAD

## Travis CI and Releases

Tarvis CI is set-up to start a build job for every branch and every new commit to the repository. It executes all relevant tests. Making a successful pull-request into development requires all tests to pass.

Starting a Travis CI job on development deploys all relevant artifacts.

For creating a new release, create a tag starting with *Release_* on the *master* branch. All artifacts are automatically deployed.

## Provided Features

- A new Virtual Satellite Workbench
- Functionality to uplaod a design to Virtual Satellite.
- Functionality to download a design from Virtual Satellite.

## Contribution

We are happy to receive your contributions. Nevertheless in such a big project there is a lot to respect and to obey. 
One thing to respect are legal requirements such as authorship rights and privacy protection. 
Therefore, before we can accept your contributions we need you to sign our *Contributor License Agreement (CLA)*.
The CLA is provided in *English* language only:

[Contributor License Agreement CLA](cla/20190724_DLR_Individual_Contributor_License_Agreement_Virtual_Satellite_en_v1.2.pdf)

Before you sign it and send it to us, you have to read the privacy policy as well.
The privacy policy is available in *English* and *German (Deutsch)* language: 

To contribute to this project follow the given steps:

[Declaration of consent data processing and privacy policy](cla/20190724_Declaration_of_consent_data_processing_and_privacy_policy_Virtual_Satellite_en_v1.2.pdf)

[Einverständniserklärung Datenverarbeitung und Datenschutz](cla/20190724_Einverständniserklärung_Datenverabreitung_und_Datenschutz_VirtualSatellite_de_v1.2.pdf)

If you agree to the CLA and privacy policy, please fill out the CLA and send it back to us. The detailed process of how to submit the documents is described in the documents themself.

Once you are an authorized committer feel free to contribute. We will not activate your account within our organization. Therefore use Pull-Requests to contribute:

1. Create your own fork of the project.
2. Apply your changes.
3. Make sure you own all relevant rights to make this contribution.
4. Make sure you are obeying legal requirements.
5. Create a pull-request of your change to our development branch.

To increase chance that we accept your pull-request, make sure all tests are working. The best indicator is the Travis CI job. Next we will review your pull-request, give comments and maybe accept it.

## License

Copyright (C) 2019 by

   DLR (German Aerospace Center),
   Software for Space Systems and interactive Visualization
   Braunschweig, Germany

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Lesser General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU Lesser General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.