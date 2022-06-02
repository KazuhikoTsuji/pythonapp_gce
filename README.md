# pythonapp_gce

## Prerequirement

### Install software on the VM instance

```bash
sudo apt-get update
```

```
$ sudo apt-get install git
```

```
$ sudo apt-get install python3-setuptools python3-dev build-essential
```

```
$ curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
```

```
$ sudo python3 get-pip.py
```

### Verify Python installation

```
$ python3 --version
$ pip3 --version
```

## Run a simple web server.

```
$ sudo python3 server.py
```

## Run a simple Python application that lists Compute Engine instances.

```
$ sudo pip3 install -r requirements.txt
```

```
$ python3 list-gce-instances.py <PROJECT_ID> --zone=<YOUR_VM_ZONE>
```
