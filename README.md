Club de Othello XO
==================

Club Othello XO is an educational game developed for the platform Sugar of the XO laptops. It is intended for visually impaired children with the aim at allowing them to learn spatio-temporals concepts.

<img alt="Front" src="http://activities.sugarlabs.org/en-US/sugar/images/t/412/1267827982" />

The Club
--------
The game uses the metaphor of a club of Othello (or Reversi) players for guiding the children's learning process.

<img alt="Front" src="http://activities.sugarlabs.org/en-US/sugar/images/t/414/1268073473" />

Installation
------------

For running Club de Othello it is required to have Sugar 0.92 or less. Sugar is pre-installed in all laptop XO. In case  you are not propietary of a laptop XO you can run Sugar in a virtual machine. 

1.*Having a laptop XO with Sugar 0.92 or less*

* Open Browser activity
* Go to [Club de Othello web page](activities.sugarlabs.org/en-US/sugar/addon/4286) and download Club de Othello activity
* After the downloading finished, go to the Journal activity and click on the Club de Othello icon

2.*Not having a laptop XO*

* Install [virtual box](https://www.virtualbox.org/)
* **Two ways:**
  + <i>Easy and Short</i>
    - [Download](https://www.dropbox.com/s/vn7fyumnpdh9fud/sugar-dextrose3.vdi) an already prepared virtualbox image with Sugar 0.92 and Club de Othello.
  + <i>Hard and Long</i>
    - [Download](http://build.activitycentral.com/pc/dx3pc-ng131.zd.disk.img.tar.gz) a compressed image of Sugar 0.92
    - Using a unix/linux terminal execute `tar zxvf dx3pc-ng131.zd.disk.img.tar.gz`
    - Later execute `VBoxManage convertfromraw -format VDI dx3pc-ng131.zd.disk.img dx3pc-ng131.zd.disk.vdi` to convert the       compressed image to a virtual box compatible image (.vdi)
    - Create a new virtual box machine using Virtual Box GUI. When asking for the creation of the virtual hard disk, choose 'existing hard disk' and then pick 'dx3pc-ng131.zd.disk.vdi'
    - Finishing with the creation of the virtual machine and start it.
    - After Sugar started follow the abovementioned procedure: <i>Having a laptop XO with Sugar 0.92 or less</i>
