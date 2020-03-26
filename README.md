## Serverless-Haskell-Stack-HIE (Haskell IDE Engine) DevContainer

### What is this?

This is a [DevContainer](https://code.visualstudio.com/docs/remote/containers) environment for Visual Studio Code.
Contains: 
    - Haskell compiler (GHC)
    - Stack builder
    - HIE (Haskell IDE Engine)
    - Nodejs and npm
    - Serverless framework 
    - Visual Studio Code extensions to set up a Haskell development environment

### How to use this?

Follow the [Getting Started](https://code.visualstudio.com/docs/remote/containers#_getting-started) instructions to configure your Visual Studio Code and Docker to use with DevContainers.

Place the `.devcontainer` directory in the root of your project, and the next time you load the project, Visual Studio Code will prompt to re-open the project in a container:

![image](https://user-images.githubusercontent.com/601206/73298150-7bfac580-4215-11ea-81d3-a8fabab98e30.png)

**Note**: building the container might take a few minutes until all dependencies have finished downloading.