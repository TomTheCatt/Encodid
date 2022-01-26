# Encodid
The source code for `Encodid` can be found [here](https://github.com/TomTheCatt/Encodid-Source). `Encodid` is designed to encrypt data that is impossible to decrypt unless the proper key is given. This key can be changed and shared with billions of possible combinations.

### Install
1. Download `Encodid` from Github as a `.zip` file. Extract all files to a desired directory.
2. Run `rewrite_key.exe` to rewrite the key in `key.txt`. The key is set to "0" and must be changed. A new and unique sequence will always be given.
3. Run `main.exe` to encode or decode text. `Encodid` automatically decodes a sequence if it can, otherwise it will encode it, allowing you, the user, to type anything into the intake, and expect the correct outtake.

### Keys
To share a key, simply upload the text file for others to download.

To create a new key, simply create `key.txt` if it does not already exist, and run `rewrite_key.exe`. It is noted that `key.txt` must remain in the same directory as `rewrite_key.exe`.

If you have someone else's key you want to use as your own, delete or store `key.txt` somewhere other than it's current directory. Add in the new key and rename it and it's extension `key.txt`.

### Uninstall
Simply delete the `Encodid` file containing all files relating to `Encodid`.
