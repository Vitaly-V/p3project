# App based on Laravel framework

The app can be deployed automatically using phing.
Run the command from the project root directory:
PATH_TO_YOUR_PHING/bin/phing -f build/build.xml -DfullPath=/var/www/installFolderName -Ddb.password=123 -Ddomain=example.com