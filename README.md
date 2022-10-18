This is a simple password hashing tool using hashlib for hashing a password

## Execution
`python hashing_passwords.py <password> [-t {sha256,sha512,md5}] `  
*Default hash-type is sha256*

## Example
```
$ python hashing_passwords.py mari
< hash-type : sha256 >
fbc835d2c63c85a2af298286581b9b77e8f1d5436a7ccbe391fceecce2a4729e
```

```
$ python hashing_passwords.py mari -t sha512
< hash-type : sha512 >
caf38a6a27837751e4e3739f5fbb2ebd7802f49e35a71e1a00ad541a8e66981b728abaac1f0f10dd4b25075d32b76360f8853f6791347d9c9a094675c77c56e2
```
