## Vyraxis
### Requires linuxcnc version 2.10 (master)
### Extra libraries required
sudo apt install python3-zmq\
sudo apt install python3-pyqtgraph
#### For viewing pdf and html documents
sudo apt install python3-pyqt5.qtwebengine\
sudo apt install python3-poppler-qt5
#### For array math for zlevel compensation
sudo apt install python3-numpy\
sudo apt install python3-scipy
#### For tool manager database functions
sudo apt install python3-PyQt5.QtSql\
sudo apt install sqlite3 libsqlite3-dev\
sudo apt install sqlitebrowser
## To copy Vyraxis to local machine
#### If git not installed
sudo apt install git
Create new folder ~/linuxcnc/configs/vyraxis\
cd linuxcnc/configs\
git clone https://github.com/persei802/Vyraxis vyraxis
#### These are simulation files. Replace .hal and .ini files with actual files to run a machine.
