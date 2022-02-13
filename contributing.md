Contribution Guidelines
=======================

How to Help
-----------
1. **Add missing builds** - the hardest and most important work here is adding missing builds. Please review the list in the readme and recreate any that are missing in Bricklink's Studio program. It is a simple tool that can be learned quickly even if you do not have prior 3D modeling experience.
2. **Review existing builds** - Take a look at existing builds and compare them to source materials to make sure they are as accurate as possible. If you notice any inaccuracies, you can open an issue. Also if you notice any reference materials which would help are missing, feel free to add them. If you are a Studio expert, you may also notice that parts are colliding / not perfectly aligned in some builds and are encouraged to correct such issues.
3. **(Expert only) Write tool to automate rendering** - Currently contributors have to manually generate after making any changes to `.io` files. This is error prone as they may forget to re-render after changes. There may also be disparities in render settings leading to inconsistent renders. If anyone could write a tool to automatically generate renders with consistent settings that would improve efficiency and help ensure consistency across builds.

Adding a build
--------------
1. Create a new directory in `builds/`
2. Give the directory a name. If there a canon name for your build please use that otherwise come up with something descriptive.
3. Within the directory, create a sources folder and include any referenced materials there. Make sure to name files and folders such that others can discern what the source was.
5. Put your Bricklink Studio `.io` file in the directory. Make sure to generate a render and include it also.
6. Create a `readme.md` and include notes about any questionnable build choices or remaining work. See the readme files in other build directories for examples.
7. Edit the builds table in the repository's main readme file to include your new build.
8. Submit a pull request with your changes.

Suggesting changes
------------------
If you notice something in this repository you believe is inaccurate, please open an issue with details. Make sure to include your references if they are not already in the repository. Keep in mind that some build decisions are best guesses and your correction may only be adopted if there is consensus that it would result in a more accurate build.