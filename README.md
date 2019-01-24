# DAC 2019 Design Contest

For general questions regarding this contest, please contact Jeff Goeders <jgoeders@byu.edu>.

## Setup PYNQ on your Ultra96 board

## Usage
The get started, users have to run the following command on the Ultra96 board:

```shell
cd /home/xilinx/jupyter_notebooks
sudo git clone https://github.com/jgoeders/dac_2019_contest.git
```
Remember the user name and password are both `xilinx` for super user.

After the above step is completed successfully, you will see a folder `dac_2019_contest` under your 
jupyter notebook dashboard.


## Folder Structure

1. overlay: This folder stores the overlay needed for the design. Usually it includes <teamname>.bit and <teamname>.tcl.

2. images: All the test images are stored in this folder.

3. python: This folder contains the python classes needed for the design, as well as the example notebook(s).

4. result: The results includes the coordinates of the resized pictures and the frame rate of each picture.
