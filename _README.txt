========================================
=========== IMPORTANT NOTICE ===========
========================================

Installation of the Windows language packs for Hindi and Bangla are necessary for Devanagari
and Bengali scripts to display correctly. If not installed, no text will be rendered.


========================================
====== LANGUAGE PACK INSTALLATION ======
========================================

(Windows):

    1 - Open Settings and navigate to "Time & language", then to "Language & region"

    2 - Using the "Add a language" button, install the language pack for Hindi and Bangla.


========================================
======= LOCALIZATION INSTALLATION ======
========================================

    1 - Find and open the directory War Thunder on your device. In typical installations it should look similar to this:

        C:\Program Files\War Thunder
        or 
        C:\Program Files\Steam\steamapps\common\War Thunder

    2 - Open the file titled "config.blk"

    3 - Navigate to the section in the blk for "debug". By default it should look like this:

        debug{
        screenshotAsJpeg:b=yes
        512mboughttobeenoughforanybody:b=yes
        }

    4 - Add the line "testLocalization:b=yes" within the brackets. It should look like this:

        debug{
        screenshotAsJpeg:b=yes
        512mboughttobeenoughforanybody:b=yes
        testLocalization:b=yes
        }

    5 - Save the config.blk file.

    6 - Boot the game.

    7 - In the War Thunder directory, a new folder named "lang" will appear. Copy all contents of the custom localization into that folder.
    When prompted to replace the "localization.blk" file, select "Yes".

    8 - In order to see the custom localization in effect, either change your language in the settings or reboot the game.