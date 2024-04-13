## Build Image With Packer
After you created the code repository and copied the files above we can run the following commands to validate the code and build our image.

Validate the code:
```
packer validate -var-file=credentials.pkr.hcl  ubuntu-server-focal-docker.pkr.hcl
```

Execute the image-building process.
```
packer build -var-file=credentials.pkr.hcl  ubuntu-server-focal-docker.pkr.hcl
```