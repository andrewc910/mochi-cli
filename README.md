# Mochi-CLI

> **Deprecated in favor of Amber's plugin system**

Mochi-cli makes installation easy. This shard is not meant to go into your project repo. Clone, compile, run the command you need & delete.

Each module of mochi requires a migration, several views, controllers, etc. This cli will generate the files you need depending on the ORM you are using. 

## Installation

```
git clone https://github.com/andrewc910/mochi-cli
cd mochi-cli
make && sudo make install
```

## Usage

Granite:

  ```
  mochi generate module_name
  ```

Jennifer: 

  ```
  mochi generate module_name jennifer
  ```

Module Names: authenticable, confirmable, trackable, recoverable, omniauthable, invitable, lockable

## Bug Reports

This cli handles a sizeable amount of files & templates. If you notice a typo causing an error in a file that was generated, please open an issue or PR. 
