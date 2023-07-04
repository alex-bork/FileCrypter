# FileCrypter
This programm encryps and decrypts a file or an entire folder with AES256.

<b><font size=3>This program is distributed in the hope that it will be useful,
but without any warranty for its implementation!</font></b>

<br/>

## Usage
### <b>1. via Command Line</b>

<br/>
<u>Encryption</u>

If the file to be encrypted is in the same folder as the FileCrypter is, than use:

```cmd
    FileCrypter.exe encrypt <filename> <password> --local
```
or

```cmd
    FileCrypter.exe encrypt .\<filename> <password>
```

if not in the same folder, use the command as follows:

```cmd
    FileCrypter.exe encrypt <fullfilepath> <password>
```

<br/>
<u>Decryption</u>

For file decryption the rules are almost the same:

```cmd
    FileCrypter.exe decrypt <filename.fcrypt|fullfilepath.fcrypt> <password> (--local)
```
<b>Attention!</b> For decrypting a file the password must be the same as used for the encryption, otherwise the program ends with an error.

<br/>

### <b>2. via GUI</b>
\- is yet to be implemented \-

<br/>

## Versions

### 1.0.0
- Initial Verison

### 1.0.1
- Readme corrected
- Bugfix for --local parameter