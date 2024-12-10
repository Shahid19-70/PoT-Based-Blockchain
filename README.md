
The PoT-based blockchain LoRaWAN architecture aims to process the join procedure in the network servers instead of the join servers. For this, the join servers send their data (DevEUI associated with end devices authorized to connect to the network) to the network servers, which create blocks to compose the blockchain.

![PoT](https://github.com/user-attachments/assets/3dfeebe9-6544-4b09-bda2-2a2ee0c73f3b)

To implement the PoT based blockchain in  the LoRaWAN simulator we have provided an object-oriented implementation in python.

Usage
First install the requirements: pip install -r ./requirements/requirements.txt

To run the version with the blockchain (from the folder src): python ./main_{with;}_blockchain.py

N.B.: If you want to modify the positioning strategy or else, you have to modify the associated function in the right file. Like generate_Strat_Gateway in the file utils/Gateway.py.

Example
Check the file example.py to have a short example on how instantiate the simulaton

after installing the lorawan 1.1 simulator, you have to implement respective parts of the network in it as it is modified as per the PoT  blockchain simulation 
