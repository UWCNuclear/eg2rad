# To convert the MIDAS .E spectrum to RADWARE format

Download the eg2rad program from this repository or the link below:

    wget http://kaleidoscope.tlabs.ac.za/public/RADWARE/eg2rad

Unzip the executable, put the path of where the eg2rad is located on the .bashrc script.

If installing on Ubuntu, download the supporting packages:

    sudo apt-get install lib32ncurses5 lib32z1 libx32stdc++6 libstdc++6 lib32stdc++6 

Reboot and eg2rad should work.

Have eg2rad as alias in your .bashrc file as: alias eg2rad='path of where the eg2rad is' i.e. '~/Downloads/eg2rad'


# How to use the eg2rad

Open the terminal in the folder or directory where the Midas spectra are located and type:

    eg2rad filename.E
