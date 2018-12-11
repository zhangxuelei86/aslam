# aslam: A\*SLAM Program

## (Under construction)

For more information see
[https://astar.ai](https://astar.ai).

The following steps are tested and passed in Ubuntu 16.04.

### 1. OpenCV Installation

Follow the steps in https://github.com/astar-ai/calicam.

### 2. Download Image Data

Make sure the uncompressed files are under the directory  /home/USER_NAME/data/astar_indoor

	cd
	mkdir data
	cd data
	wget http://astar.support/dotai/aslam_indoor.tar.gz
	tar xvf aslam_indoor.tar.gz

### 3. Download Program

	cd
	git clone https://github.com/astar-ai/aslam.git
	cd aslam
	chmod 777 ./aslam

### 3. Run

	./aslam

### 4. Operation

Plese refer to the **Operation** part of [**THIS DOCUMENT**](https://drive.google.com/open?id=1T_PiYxxNShu9rh6vtca9-kar4itFgyLR0am5_G2h0-s).
