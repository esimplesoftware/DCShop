DCShop user manual

Draw the shop. Check whether the pipe can carry chips, and whether the collector can pull that air.

DCShop is a Windows desktop planner for a small woodshop dust-collection system. The drawing is the calculation. Measured length boxes are read-only because analysis uses the pipe on the floor.

Version 1.0.0. Paid license. Windows 10/11 64-bit.

Buy and install





Buy DCShop on Lemon Squeezy. They take payment and email the installer plus the license key.



Install the setup from that email (or from your Lemon Squeezy order page). Windows may show SmartScreen (“Windows protected your PC”). Choose More info → Run anyway. The build is not code-signed yet.



Accept the EULA. Open Help → License and paste the key from the receipt. DCShop checks the key online; this PC needs internet to activate and to validate.



Install is per-user (%LOCALAPPDATA%\DCShop). Optionally create a desktop shortcut.

To remove DCShop: Settings → Apps → DCShop → Uninstall.

First layout (the intended workflow)





Draw the room.



Place a collector.



Draw the main in 90° and 45° sticks.



Right-click the end of the main to cap it.



Place a machine from the catalog.



Connect a branch, blast gate, and flex to the selected machine.



Run analysis for that machine.



Read two answers:





Colors (green / yellow / red) — is air fast enough to carry chips?



The report — can this collector pull that air through this pipe?



Use recommended sizes if you want, apply them, and run again.



Save the shop. Export the printable page when you are ready to buy pipe.

A change that cannot be built is refused. The status line says why. Slide wyes and machine names rather than forcing an illegal stick.

What the colors are not

Green, yellow, and red answer only the transport-velocity question. A green run can still starve the machine if the collector cannot make that CFM at that static pressure. Read the report.

A derated planning curve is not the same thing as a manufacturer’s published fan curve. DCShop keeps those separate on purpose.

Analysis limits





One machine at a time (one blast gate open) is the supported case.



Lengths come from the drawing. Do not treat typed notes as the source of truth.



Flex, elbows, cyclone, and filter losses are included as the report lists them. Crushed flex, leaks, and undersized hoods in the real shop are on you.



This is not a stamped design and not an NFPA review. See the EULA.

Files







What



Typical location





Program



%LOCALAPPDATA%\DCShop\





Shop files



wherever you save them





Logs (if present)



%APPDATA%\DCShop\

If the installer name or install folder on your build is different, use that path instead.

Support

Email: esimplesoftware@gmail.com

Please include:





Windows version



DCShop version



A short description



The shop file if the question is about a layout

Known limits





SmartScreen warning until the installer is signed



One open machine per analysis



Results are planning estimates



Internet required to activate and validate the license

