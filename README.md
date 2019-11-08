# Operation Manual


## Linux(ubuntu) node

### installation

 Download the executable program for the linux version:

 https://github.com/vasblock/VASChain/raw/master/ubuntu-14.zip

 https://github.com/vasblock/VASChain/raw/master/ubuntu-16.zip

 https://github.com/vasblock/VASChain/raw/master/ubuntu-18.zip

 Installation and running dependencies: 

```bash
curl -sL https://github.com/vasblock/VASChain/raw/master/env.sh | sudo -E bash -
```

  Execute the program using vaschaind/vaschain-cli using the terminal command window
  If you want to run the program more conveniently, you can copy the executable to /usr/lib and use chmod to delegate it, you can use the vaschaind/vaschain-cli program in any directory.

#### start up

` ./vaschaind` 

#### Excuting an order

` ./vaschain-cli command `

#### Stop node

` ./vaschain-cli stop `

#### Connect to the specified node at startup

```bash
./vaschaind -addnode=ip:port
```

## mac node

### installation

 Download https://github.com/vasblock/VASChain/raw/master/mac.zip
 Unzip mac.zip and enter
 Execute the program using vaschaind/vaschain-cli using the terminal command window

#### start up

` ./vaschaind` 

#### Excuting an order

` ./vaschain-cli command `

#### Stop node

` ./vaschain-cli stop `

#### Connect to the specified node at startup

```
./vaschaind -addnode=ip:port
```


## window node

### installation

Download https://github.com/vasblock/VASChain/raw/master/win.zip
Unzip win.zip and enter
Execute the program using vaschaind.exe/vaschain-cli.exe using the cmd command window

#### start up

` vaschaind.exe ` 

#### Excuting an order

` vaschain-cli.exe command `

#### Stop node

` vaschain-cli.exe stop `

#### Connect to the specified node at startup

```
vaschaind.exe -addnode=ip:port
```

After startup, the sync block will start and the RPC service will be started (how to use the command to view the developer guide documentation).
