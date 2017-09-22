# ORB_SLAM For Mac OS

09/21/17 Update: maintained for OSX 10.12, XCode 9

## Dependency
Install `cmake` so that you can make the `/Thirdparty` first.

🚨Notice: `g2o` requires `Eigen`, better `3.2.10`

## How to Build:

1. Download this repository from github:

     ` $ cd ~/Downloads`
      
      `$ git clone https://github.com/rancheng/ORB_SLAM_OSX_AR.git`
      
      `$ cd ./ORB_SLAM_OSX_AR`
      
     ` $ open`
      
2. In the folder, open: `/Xcode/ORB_SLAM2.xcworkspace`
 note: it's the *xcworkspace* file

3. Copy the `/Data` folder into `Users/Data` root folder in case of different user configuration
4. Build `ORB_SLAM` target first, then Build `Mono_AR_Test` target ( Build inside `xcode` )


## TODO: 
- Integrate Pangolin and async rendering support on Mac.


Enjoy it.

      


