# traffic_sign_NCS
traffic_sign detection using NCSDK v2.0

# NCSDK installation

1. clone repo and install :  
`git clone -b ncsdk2 http://github.com/Movidius/ncsdk && cd ncsdk && make install`  
reference: https://movidius.github.io/ncsdk/install.html

Note: As library ncapi2_shim dependency required for inference application, we use ncappzoo.
 
# setup repo and inference 

1. `git clone -b ncsdk2 https://github.com/movidius/ncappzoo`  
2. cd apps  
3. clone this repo(keep traffic_sign_NCS in apps directory)  
4. `python3 traffic_sign.py graph=traffic_sign_47`  

Note: Make sure NCS stick is inserted.