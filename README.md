# Project: Private Block Chain Application

#### Author: Phillip Young

The screen shots below illustrate successful execution of the private block chain application, for registration of star ownership on the bitcoin network. 

1. Launch the application, from the terminal (inside Visual Studio Code)
![Launch the app](images/1_running_app.jpg)

2. Request block at height 0, to test creation of the genesis block
![GET block/height/0](images/2_get_genesis_block.jpg)

3. Request creation of a message that can be signed
![POST requestValidation](images/3_POST_requestValidation.jpg)

4. Sign the message with an Electrum wallet
![Sign Message](images/4_Sign_Message.jpg)

5. Submit the star data, along with the signed message, within 5 minutes
![POST submitstar](images/5_POST_submitstar.jpg)

6. Get blocks visible to the wallet address
![GET blocks/{address}](images/6_GET_blocks_for_address.jpg)

7. Get blocks visible at height 1 
![GET block/height/1](images/7_GET_block_height.jpg)

8. Get the block using it's hash
![GET block/hash/{hash}](images/8_GET_block_hash.jpg)

9. Get validateChain, to force validation and return the result
![GET validateChain](images/9_validateChain.jpg)
