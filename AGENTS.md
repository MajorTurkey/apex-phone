# Jacks

You are the bot for Jack's Desk and the field phone. That product is Apex. It is free. Nicholas Trautman (also known as MajorTurkey) owns the copyright. Jack uses it. Do not work on the suite.

The suite is a different product. Its repo is MajorTurkey/desk-phone-suite. Its name on screen is Suite. Do not edit it. Do not email Jack about it. Do not put Apex pricing, lease keys, or Suite copy into Jack's Desk.

SkipTrek (MajorTurkey/skip-desk) is also different. The purple and green screen is SkipTrek, not Jack's desk.

## Who

- Jack's desk email: Jack@apexfieldservicellc.com
- Desk phone shown in the header: (360) 358-3303
- Nicholas: nhtrautman@gmail.com
- Jack uses his tablet for the desk only. The field phone is the other device.
- Company on the report and the logo: Apex Field Service LLC. The line under the logo is: See it, document it, and report it accurately.

## What the two sides do

A job goes from the desk to the field phone, then back to the desk. That is a handoff. The desk can reassign it. The field phone must keep working when there is no service, and send only when there is service. Once the file has been sent, no copy stays on the field phone.

The names allowed to open the phone are the Auth Users on the desk. Add the name and the email Jack will send work to.

## Live sites

- Desk: https://apex-jack-desk.vercel.app/
- Field phone site: https://apex-desk-eta.vercel.app/

The desk header is the AFS logo, then the words Jack's Desk to the right of it, then the phone number. The logo file is /brand/afs-wide.png. It is the wide purple and green AFS mark plus the words APEX FIELD SERVICE LLC. If the hostname matches nick or nicho, the title becomes Nicho's Desk. apex-jack-desk does not match, so it stays Jack's Desk.

The website already has that title in the page. A refresh does not install an app update.

Buttons on the desk: Auth Users, Settings, Refresh. Start a job can be kept on the desk or assigned. Kinds include process serve, survey, court, medical, and other. Levels are routine, rush, and same-day.

## Apps

Both apps are Android. A computer only saves the file. The file is a package. Clicking it on a computer opens it like a folder. Only the tablet or the phone can install it.

Do not uninstall first. Download, open the finished download, tap Install, then Open. If asked, allow installs from the browser. Install over the app already there. The signing key must stay the same or Android will refuse the update. The release key already exists. Do not put its password in a repo. Do not email the app file. Gmail bounces an attached APK as a Google terms violation. Send a link only.

Jack's Desk app:

- Package: com.apexfieldservice.jackdesk
- Latest built app: versionName 1.5, versionCode 6
- Page that stays open and explains the install: https://jacks-desk-install.vercel.app/
- File link, which only downloads: https://github.com/MajorTurkey/jacks-desk-update/releases/download/v1.5/Jacks-Desk.apk
- Releases: https://github.com/MajorTurkey/jacks-desk-update/releases/tag/v1.5
- Older releases on that repo: v1.3 and v1.4

1.5 does two things inside the installed app only. It puts Jack's Desk immediately to the right of the AFS mark, and it turns Sign and send into a Word file. The website was not changed. A refresh of the website does not do either thing.

Field phone app:

- Package: com.apexfieldservice.desk
- Last build recorded here: versionName 1.4, versionCode 27
- It loads the field site. It is the phone, not a page of instructions.
- It needs the camera and location. It must open with no service, hold the work, and send when service is back. Then the copy on the phone is gone.

## The Word report

Sign and send on the website still makes a short HTML file. Word opens that as a few lines of text and a black screen. That is the bug.

Jack's Desk 1.4 and 1.5 fix it only after the app is installed. The app watches the report download. If the download name contains report and ends in .eml, the app builds a real Word file (.docx) from the report text and the pictures, and downloads that instead. Pictures have to be in the report as images. The Word file is the attachment. It is not an HTML page.

If the tablet still has an older Jack's Desk, the report is still the broken one.

## Repos

- MajorTurkey/apex-desk: Jack's Desk. Private. Copyright only, plus this briefing.
- This repo, MajorTurkey/apex-phone: the field phone. Private. Same copyright.
- MajorTurkey/jacks-desk-update: public download page and the Jack's Desk APK. Branch master.
- Do not commit Jack's work into MajorTurkey/desk-phone-suite.

Copyright (c) 2026 Nicholas Trautman (also known as MajorTurkey). All rights reserved. Apex stays free.
