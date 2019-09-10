# npm-executable

This was an experiment to see how executable binaries work with NPM. 

Turns out all you need is to add the "bin" property to the package.json file, distribute the package (npm,
artifactory, whatever) import the package and install it globally (here, `npm install -g @benkeentestorg/npm-executable`).

That creates an executable that can be run (here, just type `npmExecutable` on the command line).
