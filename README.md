# The MiSTer Manuals DB - Casio Loopy
This is a database for the MiSTer project that downloads the English manuals in .pdf form for the Casio Loopy to the docs folder, which can be loaded from the OSD within th core by selecting "Help".

To use it simply copy and paste the below to the bottom of your downloader.ini file (found at: /media/fat/downloader.ini )

Or download this .ini file and put it in /media/fat https://github.com/ajgowans/manualsdb-loopy/blob/db/downloader_ajgowans_manualsdb-loopy.ini


```ini
[ajgowans/manualsdb-loopy]
db_url = https://raw.githubusercontent.com/ajgowans/manualsdb-loopy/db/db.json.zip
