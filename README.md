# pfx2pem

pfx2pem is a small bash script that converts pfx certificates to pem
encoded certificates. The script is able to handle certificates or
directories as input parameter. If a directory is given, every
pfx certificate in the directory is converted to a pem file that
is saved in a newly created ./pem folder. If a file is given,
the pem file will be created with the same name near the pfx file.


## Requirements

- OpenSSL
- Bash


## Usage

```
./pfx2pem ./dir/with/pfx/files

./pfx2pem sample_pfx_file.pfx
```

