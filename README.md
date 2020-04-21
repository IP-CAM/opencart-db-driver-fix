# opencart-db-driver-fix
Correction of a connection error in the database driver - display of login and password when the connection is broken. The issue occurs if the application can't connect to the database server (a large number of connections or the server was not found or was not accessible). Fixed error output login and password your database, even when disabled "display_errors_off" in hosting/server settings.
# Setup
1) Go to OpenСart Admin / Extensions / Extension installer
2) Upload the file of the purchase extension "security_fix.ocmod.xml"
3) Update your Modification cache by going to your OpenСart Admin / Extensions / Modifications and clicking "REFRESH" (blue button on top right)
