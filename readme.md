# AMI

## Packer

```bash
brew install packer
```

Packer takes JSON files for validaiton and building of images

```bash
packer validate example.json
```

```bash
packer build -var-file example.json
```

Packer will produce and save the image on aws.