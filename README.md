Configure
==========

### create dirs
```bash
mkdir -p /workspace/lcpconfig/lcpdb/
mkdir -p /workspace/lcpconfig/lcpfiles/master
mkdir -p /workspace/lcpconfig/lcpfiles/encrypted
```
cp config.yaml "$GOPATH/bin/config.yaml"

creating a password file is http://www.htaccesstools.com/htpasswd-generator/. The htpasswd file format is e.g.:

Creating Systemd Service Files
===============================

## Copy the .service File

```bash
sudo cp systemd/* /etc/systemd/system/
```
## Start the Services
```bash
sudo service lcpserver start
sudo service lsdserver start
sudo service lcp-frontend start
```


## Check status the Services

```bash
sudo service lcpserver status
sudo service lsdserver status
sudo service lcp-frontend status
```

## Stop the Services
```bash
sudo service lcpserver stop
sudo service lsdserver stop
sudo service lcp-frontend stop
```
