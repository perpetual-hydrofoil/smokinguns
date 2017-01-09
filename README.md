This is a complete install of Smoking Guns 1.1 for Linux (git as of Jan 8, 2017),
including all optional maps and packs available as of that date, compiled for 64-bit Linux.

HOW TO INSTALL:
===============

 1. Extract the release 1.1-1 tarball to /usr/local/games/smokinguns/:

        curl -L https://github.com/jamiesonbecker/smokinguns/releases/download/v1.1-1/smokinguns.tar.gz | \

            sudo tar -zxC /usr/local/games/


 2. You may need to:

        sudo apt-get install libsdl-dev libfreetype6-dev libgl1-mesa-dev

    or, perhaps on fedora:

        sudo dnf install libsdl-devel libfreetype6-devel libgl1-mesa-devel

    or other  redhat platform (just quessing)

        sudo yum install libsdl-devel libfreetype6-devel libgl1-mesa-devel

 3. Finally, execute:

    sudo ln -sf /usr/local/games/smokinguns/smokinguns.desktop /usr/share/applications/smokinguns.desktop

 4. Finished - it should be in your games menu!


If any steps are missing, please click "edit" on this file up above.
