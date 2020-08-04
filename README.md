# globalstarlink
A full-featured app to get the most out of tethering your Globalstar GSP-1600/1700 device to your computer.

Brandon Bourret - phatwares@cpan.org

If you have a Globalstar satellite phone (GSP-1600/1700) and a data cable to connect the phone to your computer, this app is for you!

Feature Overview:

Dashboard Panel - This area shows several status icons indicating your phone's current state.
 - Network Type (Analog, Terrestrial CDMA, Globalstar CDMA)
 - Network Name
 - Roaming Status
 - Signal Strength Meter
 - Current Call (Number and Duration)
 - New SMS Message Indicator
 - New Voicemail Indicator

SMS Panel - This area shows incoming SMS message information
 - Message number, date, time
 - Message content
 - Previous/Next/Delete message buttons
 - Text-to-speech

Device Status Panel - This area shows device connection status
 - Current program activity
 - Current date/time
 - Device status text
 - Connect/Disconnect modem (phone) button

Location/Constellation Panel - This area shows available second-gen Globalstar satellites based on your location
 - Update Globalstar constellation TLE data (network connection required)
 - Save your location (Lat degrees, Lon degrees, Elevation meters)
 - Available second-gen Globalstar satellites
  - Elevation degrees (height above horizon)
  - Azimuth degrees (compass direction)
  - Range kilometers (distance away from you)

Lite Messaging Client Panel - This area allows you to send text messages as SMS to Globalstar phones and regular emails (network connection required)
 - Section to input and save your email account credentials
  - Common email SMTP (Simple Mail Transfer Protocol) presets
  - Supports SSL and TLS
  - Email password is encrypted before it is saved on your local machine
 - Choose message type (SMS to Globalstar via email-to-SMS gateway, or regular email)
 - Recipient, subject (for regular email), and message body

NOTE FOR LINUX USERS: The app cannot poll the Serial Ports to connect to your device without super-user privileges. You will be prompted to enter
your super-user password each time you run the app.

This app (and all others I publish so far) are PORTABLE APPS. That means there is no need for installation because all the program assets (images, fonts,
.dll, and .so files) are packaged into the executable. Simply double-click and GO! Having said this, let me explain that some Windows users may get a
false positive warning about this app being a "Trojan". Why? Because when you execute the app, it unpacks all the aforementioned program assets into a
temporary folder on your computer. Therefore, some anti-virus apps falsely identify this as malicious "Trojan Horse" activity. Please rest assured that
this app is completely harmless - I would not put my real name on a malicious app.

I develop using ActivePerl (don't laugh, it's rapid development!) and "compile" with ActiveState's Perl Dev Kit (PDK).

Windows 32-bit: https://www.dropbox.com/s/3ziq9ae14d1epe0/GlobalstarLink.exe?dl=0

Linux 64-bit: https://www.dropbox.com/s/1rzjjs5fwnlrvem/GlobalstarLink?dl=0
