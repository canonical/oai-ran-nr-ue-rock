# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:oai-ran-nr-ue_2.1.1_amd64.rock docker-daemon:oai-ran-nr-ue:2.1.1
docker run -d oai-ran-nr-ue:2.1.1
```
