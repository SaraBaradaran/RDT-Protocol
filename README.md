# Reliable-Data-Transfer-Protocol


We have implemented a reliable data transfer protocol like TCP using raw socket. This protocol has been used in a hypothetical transportation system.
You can read more about how this transportation system works by reading the project file.


## Usage guide

### Requirements
* Python 3.4+

### Step 1: Download Python Code & Files
You can clone codes using the below command:
```
git clone https://github.com/SaraBaradaran/RDT-Protocol
```

### Step 2: Copy Text Files Into Current RDT-Protocol Directory
```
rm -rf RDT-Protocol/.git
cd RDT-Protocol

cp ./files/path.txt .
cp ./files/maps.txt .
cp ./files/balance.txt .
```

### Step 3: Change Scripts Permission
```
chmod +x ./script.sh
chmod +x ./script_ip.sh
```

You may have to modify ``wlp3s0`` in the `./script.sh` file according to your network interface. You can get your network interface using `ifconfig` command.

Finally, run `./script.sh` file.
