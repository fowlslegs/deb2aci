# deb2aci

Deb2aci works like aptitude, but instead it downloads the deb packages with all their dependencies
and installs them into the ACI image.

It remembers each dependency in annotation to the resulting image manifest.

```
# outputs nginx.aci
deb2aci nginx nginx.manifest
```

