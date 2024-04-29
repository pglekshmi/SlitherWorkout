# SlitherWorkout

#How to install slither
Begin with installing solc – Solidity compiler:

sudo apt install software-properties-common

sudo add-apt-repository ppa:ethereum/ethereum

sudo apt install solc

You should also install the solc-select. It is used for quick installation and switching between Solidity compiler versions.

Simply run pip3 install solc-select

After the solc and solc-select are installed with no errors, we can proceed to the Slither installation. It can be done in three ways:

Using Pip:

pip3 install slither-analyzer

Using GitHub:

git clone <https://github.com/crytic/slither.git> && cd slither

python3 setup.py install

Using Docker

docker pull trailofbits/eth-security-toolbox

We can check the installation by running slither - -version in your terminal. If the tool is installed properly, you’ll see the latest version – 0.9.2.

#Checking Smart Contract using Slither

slither Filename.sol

eg- slither Token.sol

