Install fonts for MacOS users by running the following command below

This git serves as a host for the fonts

#CD into the primary font location for macOS
cd ~/Library/Fonts && { 
    #curl to download the font
    curl -L -O 'FontWebLink'
    #return to primary directory
    cd -; }
    

For the full script, see:
https://github.com/dsimotas/FontInstall/blob/main/FontInstaller.sh
