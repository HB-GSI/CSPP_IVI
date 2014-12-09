CSPP_IVI extends the CSPP_DeviceBase package of the CS++-Project. 

It contains derived classes of the CS++DeviceActor respectivly their device specific derived classes in CSPP_DeviceBase. 

Refer to https://github.com/HB-GSI/CSPP for CS++ project overview, details and documentation.

LabVIEW 2014 is the currently used development environment.

Related documents and information
=================================
- README.txt
- Release_Notes.txt
- EUPL v.1.1 - Lizenz.pdf
- Contact: H.Brand@gsi.de or D.Neidherr@gsi.de
- Download, bug reports... : http://github.com/HB-GSI/CSPP_IVI
- Documentation:
  - Refer to package folder
  - Project-Wiki: https://github.com/HB-GSI/CSPP/wiki
  - NI Actor Framework: https://decibel.ni.com/content/groups/actor-framework-2011?view=overview

GIT Submodules
==============
This package can be used as submodule
- Packages\CSPP_IVI: Implementations of derived CS++DeviceBase classes using IVI driver

External Dependencies
---------------------
- CSPP_Core: http://github.com/HB-GSI/CSPP_Core
- CSPP_DeviceBase: http://github.com/HB-GSI/CSPP_DeviceBase

Optional submodules
-------------------
- CSPP_Examples: http://github.com/HB-GSI/CSPP_Examples

Getting started:
=================================
- Add IVI-Content.vi into your own LabVIEW project. You can drag the desired libraries from the dependencies into your virtual project folder structure.
- Add IVI-Content.vi into your desired case of the CS++UserContents.vi
- You need to extend your project specific ini-file.
  - A sample ini-file should be available for all classes on disk in the corresponding package folder.
- You need to create and deploy your project specific shared variable libraries.
  - A sample shared variable library should be available on disk in the CSPP_DeviceBase package folder.


Author: H.Brand@gsi.de, D.Neidherr@gsi.de

Copyright 2013  GSI Helmholtzzentrum für Schwerionenforschung GmbH

Planckstr.1, 64291 Darmstadt, Germany

Lizenziert unter der EUPL, Version 1.1 oder - sobald diese von der Europäischen Kommission genehmigt wurden - Folgeversionen der EUPL ("Lizenz"); Sie dürfen dieses Werk ausschließlich gemäß dieser Lizenz nutzen.

Eine Kopie der Lizenz finden Sie hier: http://www.osor.eu/eupl

Sofern nicht durch anwendbare Rechtsvorschriften gefordert oder in schriftlicher Form vereinbart, wird die unter der Lizenz verbreitete Software "so wie sie ist", OHNE JEGLICHE GEWÄHRLEISTUNG ODER BEDINGUNGEN - ausdrücklich oder stillschweigend - verbreitet.

Die sprachspezifischen Genehmigungen und Beschränkungen unter der Lizenz sind dem Lizenztext zu entnehmen.