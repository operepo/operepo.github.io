# Classroom Deployment – Sync Online to Offline
Deployment is hard. The first goal is to build a system that allows you to easily choose from a list of prison ready apps, and deploy them in an offline environment.

Deployment into an offline classroom enables students to interact with these websites in a normal manner while still being located in a secured network.
The “SyncApp” is the tool used by staff to select what “apps” you want to deploy. The app allows you to pull updates and Docker apps to the USB drive, and push those updates to an offline server at the facility.  This gives staff a point and click tool to do complex deployment tasks and keep systems up to date when internet access is limited or nonexistent.
When it comes to apps, the OPE project builds and maintains prison ready options including:
-	Canvas LMS Server – The Open Source version of Canvas which has been secured and configured for prison use. This is a central part of curriculum delivery and gives an incarcerated student access to similar tools to what they would use in the real world.
-	SMC (Student Management Console) – Has import tools to help easily manage student and faculty accounts. Also integrates with Active Directory and Canvas to manage enrollment, keep passwords synced, and setup initial desktop environments.  It also has media tools like an offline youtube like video and document tool that lets you replace online linked materials with a local link that will work offline.
-	FOG – Deployment server to help push out computer images across the network. Used to image laptops and also available for use in classroom computer labs.
-	KALite – Offline version of Khan Academy.
-	CodeCombat – Offline version of codecombat.com
-	GCFLearnFree – Offline version of gcflearnfree.org
-	WA State Library Reentry Wiki – A wiki full of reentry resources collected by the WA State Library and converted for use offline.
-	*** Future Apps ***
-	WAMAP –
-	RACHEL – 
-	JSBin
-	More in the works…
# Prison Ready Curriculum Repository
As curriculum is converted for prison use, open source materials can be gathered in a central location where the whole state can benefit. Curriculum like IDEA and HS21 can be posted for others to download and use, saving themselves a tremendous amount of work.
# Laptops and Last Mile Deployment – Access in the cell
Prison spec laptops are designed to sync on the education floor and go back to the unit with the inmate to continue their studies. As such, much of this section is about using Sync Boxes or Docking Stations and the security features in place.
## Sync Boxes
Due to limited connectivity options (see Laptop Hardware below), it is intentionally difficult to plug the laptops into normal network environments.  Depending on the model, you will either need a secured Sync Box which includes USB adaptors to plug into, or you will need a secure docking station. Without the appropriate option, you will NOT be able to gain access to resources on that network.
Regardless of the model in use, the Sync Box or Docking Station will be deployed only in supervised areas where students can come and plug in to turn in homework and gather new materials.
## LMS App/Credentialing
The primary interface for students to work in their cell is to use the LMS app to sync the laptop with the Canvas LMS server. Once done, they should be able to view most of the canvas materials offline and turn in assignments.  This creates an opportunity for students to complete course work when their education class time is limited.
## Laptop Hardware
Prison spec laptops are custom built to include the following hardware features:
-	Clear components – Parts of the case are clear so that security staff can easily check and monitor for tampering.
-	Non USB Power Plugs – Power adaptors use barrel connectors and do not separate or have USB plugs in them to prevent use in tattoo guns.
-	No WIFI/Bluetooth – The adaptor isn’t physically present.
-	No Camera – No built in web cam.
-	Limited Ports – Depending on the model, the USB Ports can be locked with USB locks and other ports are not physically present (e.g. no firewire, no network port, etc…).
-	Hardened BIOS – Ability to disable extra features and alternate boot devices is present in the BIOS.
-	Security Screws are used to keep the case secure.
-	No BIOS reset – Common tricks like jumpers or removing the CMOS battery don’t work.
## Laptop Software
The laptops are designed to run with Windows 10 Pro/Enterprise. To credential and use them to sync student work with Canvas, you are required to use the full credential process. When this process runs, it ads several security layers including strict firewall rules, tightened security settings, disabling removable devices, device monitoring which disables any unwanted devices in the system and extra monitoring features such as random interval screenshots.
Beyond security settings and the LMS app – the laptops are designed to be able to run appropriate approved apps. For example, an accounting class that uses QuickBooks could have that software on the laptop which would require much less lab time on the education floor to complete assignments.
