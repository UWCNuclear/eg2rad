# Converting-the-MIDAS-MTsort-output-spectra-matrices-into-Radware-format

To convert the MIDAS *.E spectrum to RADWARE format Download the eg2rad program from one of the link below: https://drive.google.com/file/d/1kCLeMyB6jBkXqIY8WUTADSko-j47QwBB/view?usp=sharing wget http://kaleidoscope.tlabs.ac.za/public/RADWARE/eg2rad 
Make it executable, put the path of where the eg2rad is located on the .bashrc script.
If installing on Ubuntu, then download the supporting packages sudo apt-get install lib32ncurses5 lib32z1 libx32stdc++6 libstdc++6 lib32stdc++6 
Reboot the computer and then eg2rad should work 
How to use the eg2rad:
open the terminal in the folder or directory where the spectra are located. 
Type eg2rad *.E
