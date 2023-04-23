# Disclaimer
You are solely responsible for ensuring the secure configuration and operation of this script, including but not limited to protecting it from unauthorized access by third parties. Failure to do so may result in the loss of your private keys, XENFTs or other cryptocurrencies stored in your account. You should exercise caution and only run this script on a secure workstation or server.
By using this script, you acknowledge that you understand the inherent risks associated with running this script and that you agree to use this script at your own risk.
The creator of this script will not be held liable for any damages, loss of funds, or other negative consequences that may result from you or any third party using this script.
You are solely responsible for any actions taken using this script, and for securing your private keys and other sensitive information.
This script is provided 'as is,' and the creator makes no warranty, express or implied, of any kind.

# Details
XENFT Minting Bot on Polygon

Based on the below repo by Jozef Jarosciak but on Polygon instead of Ethereum. All credit goes to Jozef for writing the original code. Consider donating to him in the link at the bottom of the ReadMe.

https://github.com/JozefJarosciak/xenft-creator

# Configuration

Line 22 - Choose how many VMUs you want

Line 23 - Choose the term

Line 24 - Choose how many to mint (they run consecutively, not concurrently)

Line 28 - If you want max term, leave as true, if you want the term on line 23, put False

Line 31 - Choose the gas threshold you want to mint under. It will check its under the threshold for 3 consecutive pings (10 seconds) before minting.

Line 42 - If you have your own RPC endpoint, you can replace the Polygon one with that. This one works fine for me.

Line 48, replace with your wallet address (inside the ‘’)

Line 52 - The script does not store your private key. Instead, it will ask you to paste it each time you run the script, so it isn’t hardcoded.


# Running the Script

Download Python 3.9 from https://www.python.org/downloads/release/python-390/

Install Python 3.9 and then run the below package installs:

Pip3 install ‘requests==2.28.1’

Pip3 install ‘web3==5.31.1’

Pip3 install pycoingecko

Now to run the actual script, use the below command:

Python3.9 xenft-creator.py

Enjoy :)




# HOW CAN YOU HELP?
- **Donate**: ETH donations are much appreciated: https://xen.pub/donate/
- **Coders**: Please enhance the below script! Nothing would make me happier than seeing this script being adopted and enhanced by the community.

# LICENSE
The code is available under the **MIT license** - https://github.com/JozefJarosciak/xenft-creator/blob/main/LICENSE
