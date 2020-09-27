# Blockchain

#HomeWork 18 Blockchain

•  Create a new project directory for your new network. Call it whatever you want!
•  Create a "Screenshots" folder inside of the project directory.
 
•  Created accounts for two (or more) nodes for the network with a separate datadir for each using geth.  
   * ./geth --datadir node1 account new
    * ./geth --datadir node2 account new
 
•  Ran puppeth, named my network “kalenHW”, and selected the configure new genesis block. See screenshot part 1
•  I choose Clique (Proof of Authority) consensus algorithm.
•  Paste both of my account addresses from the first step one at a time into the list of accounts to seal.  
•  Paste them again in the list of accounts to pre-fund. There are no block rewards in PoA, so you'll need to pre-fund.  
•  You can choose no for pre-funding the pre-compiled accounts (0x1 .. 0xff) with wei. This keeps the genesis cleaner.  
•  Complete the rest of the prompts, and when you are back at the main menu, choose the "Manage existing genesis" option.  
•  Export genesis configurations. This will fail to create two of the files, but you only need networkname.json.  
•  I did delete the kalenhw-harmony.json file.
•  Screenshot the puppeth configuration once complete and save it to the Screenshots folder.

 
•  Initialize each node with the new kalenhw.json with geth.
 
