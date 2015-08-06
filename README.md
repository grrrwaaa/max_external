This is a template repository for making externals for Max/MSP/Jitter, intended to be copied or forked when starting development of new Max externals. It includes the Max SDK as a submodule. The structure of the repository matches the Max package format, such that it can be downloaded into Documents/Max 7/Packages.

# Creating a new external

The /source/example folder can be used as a template for an external, but will need renaming to match the intended external name, as follows:

## OSX:

1. open xcode project, rename it in the top-right explorer. It will rename the targets.
2. similarly, rename the example.cpp in the Xcode file explorer. 
3. search & replace "example" with the new name within example.cpp
4. build

## Windows: 

1. rename example.cpp to whatever you want
2. rename example.vcproj to match
3. open the vcproj and build