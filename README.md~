#Developer's Guide

##Steps to download necessary tools and things

1. Open your terminal and put following command to run.

	`sudo apt-get install gettext`

2. Download any translation editor to open .po files.

3. you must have installed language pack inside your system. For doing that put following command in terminal.

	`sudo apt-get install language-pack-name`

###You can use any reference language to translate in your langauge,but you must know portable format of internationalization.

##Steps for translations

1. Find your .mo files inside /usr/share/locale/[language-code]
for Gujarati, gu_IN

2. Now copy any .mo file to other location.
3. Go to that file location via command line.
4. Put following command to generate .po file from .mo file.

	`msgunfmt [input_mo_filename].mo -o [output_po_filename].po`

	I recommend to give same name to po file which is name of mo file.

5. Now open .po file inside any editor and  translate in your way.
6. Go to .po file location and put following command to covert in .mo file so we can put inside /usr/share/locale/[your-language] to test out our translation.

	`msgfmt [input_po_filename].po -o [output_mo_filename].mo`

7. Put it in /usr/share/locale/[your-language]  and Log out your system.

8. Log in again and check out whether your translation applied or not.

------------------------
.mo file- machine object file

.po file- portable object file
####Please don't change any system files because it may fall into crash of any application.If translation doesn't appear then check for the permission given to the file(It must be 644).

Free to mail me at arpanchavdaeng[at]gmail.com