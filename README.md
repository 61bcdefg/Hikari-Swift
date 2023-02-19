# Hikari-Swift
This repo contains Hikari's Swift Ports. It's ideal for Xcode users to use this fork instead of the main repo since Swift's Clang mimics Apple's Clang's behaviour better than LLVM upstream.
# Building
We will use the branch ``swift-5.7.2-RELEASE``(will be added later) as an example. We assume this repo is cloned to ``~/Downloads/Hikari-Swift/``   
Now we can start building: 
```
cd ~/Downloads/Hikari-Swift/
./swift/utils/build-toolchain Hikari
```
It takes around a few hours to build the toolchain. If everything went well you should be able to find a zipped file under ``~/Downloads/Hikari-Swift/``, this is your toolchain. 

# Things to Note
- This forked version's Core is still licensed under the exact same AGPLV3 License as the main repo.
