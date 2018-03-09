# DAC 2018 Design Contest

For general questions regarding this contest, please contact Xinyi Zhang <xinyizhang@pitt.edu>.

## Usage
The get started, users have to run the following command on PYNQ-Z1 board:

```shell
cd /home/xilinx/jupyter_notebooks
sudo git clone https://github.com/yunqu/dac_2018.git
```
Remember the user name and password are both `xilinx` for super user.

After the above step is completed successfully, you will see a folder `dac_2018` under your 
jupyter notebook dashboard.


## Folder Structure

1. overlay: This folder stores the overlay needed for the design. Usually it includes <teamname>.bit and <teamname>.tcl.

2. images: All the test images are stored in this folder)

3. python: This folder contains the python classes needed for the design, as well as the example notebook(s).

4. result: The results includes the coordinates of the resized pictures and the frame rate of each picture.

## 12/06/2017 update

Redundant variables in DACSDC.py were moved.

Function "storeResultsToXML" in DACSDC.py is revised.

Please ignore object "boat9" and "group4" in the training dataset. They will be deleted from the latest training dataset.

## 01/05/2018 update

Revised python classes and polished notebooks.

## 01/18/2018 update

Updated the overlay: (1) changed to use HP port for DMA transfer, (2) enlarged the FIFO depth, (3) updated the 
DDR memory parameters, and (4) updated DMA configuration parameters. 

