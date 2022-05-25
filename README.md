# cmake-project-template
### _A Modern CMake Template_
_**cmake-project-template**_ is a modern and standardized CMake template that utilizes multiple directories as well as different types of library source layouts!

## Features
- Utilizes _The Pitchfork Layout_
    - Includes all types of library source layouts:
        - Seperate/Merged Header Placement
        - Seperate/Merged Test Placement
- Documentation and explanations for directories 
- Multiple types of `CMakeLists.txt`

## Understanding the layout
For virtually all projects, they are a few key components:
+ Compilable source files
+ Public headers
+ Private headers
+ Source files containing entry points (main() functions)
+ Documentation files
+ Tests
+ Samples and examples
+ External libraries which have been embedded within the project structure
+ "Add-ons" to the source (e.g. language bindings, optional plugins, platform bindings)\\

go over terminology

layout in physical v. logical terms

project files and directories

library source layout
+ header
+ test

modules & submodules

build systems

why cmake?

## How-to-use
Now that you've read up on the purpose of all the directories for the layout, you can choose which one best suites your needs. There are 4 different branches, one for each of the 4 combinations:
- **Both** Seperate Header and Test Placement
- Merged Header **but** Seperate Test Placement
- Merged Test **but** Seperate Header Placement
- **Both** Merged Header and Test Placement

Simply change the branch to the one you want to use, and click `Use this template`

If you need to change to a different library source layout, e.g. from merged to seperate, there is a `CHANGING.md` on instructions from changing to any library source layout!

[//]: # (to use: [test])
[tes]: <https://github.com/moral-g>
