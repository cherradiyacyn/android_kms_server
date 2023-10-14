# android_kms_server
Helpful scripts for MS products activation using Termux

## on Android
1. [Install F-droid](https://f-droid.org/en/)
1. [Install Termux](https://f-droid.org/en/packages/com.termux/)
1. Open Termux
1. Update Termux 
```apt-get update && apt-get upgrade -y```
1. Install Git 
```apt-get install -y git```
1. Get the IP address 
```ifconfig```
1. Clone the Repository 
```git clone https://github.com/cherradiyacyn/android_kms_server.git```
1. Launch KMS Server 
```
cd android_kms_server/termux_files
chmod 700 *
./kms_server_setup_script.sh
./kms_server_start_script.sh
```
# on Windows
1. Right-click "activation_file" > choose Edit > replace 127.0.0.1 with the IP address
1. Right-click "activation_file" > Run As Administrator
1. Wait...

# back to Termux
1. Stop the server 
```Ctrl+C```
1. Optionally 
```./kms_server_clear_script.sh```