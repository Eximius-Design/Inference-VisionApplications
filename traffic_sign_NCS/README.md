# traffic_sign_NCS
traffic_sign detection using NCSDK v2.0

# NCSDK installation
`git clone -b ncsdk2 http://github.com/Movidius/ncsdk && cd ncsdk && make install`  
reference: https://movidius.github.io/ncsdk/install.html

Note: We use ncappzoo for inferene application for library dependence.

# setup repo

1. `git clone -b ncsdk2 https://github.com/movidius/ncappzoo`  
2. cd apps  
3. clone this repo(keep traffic_sign_NCS) in apps directory  
4. `python3 traffic_sign.py traffic_sign_47`  
