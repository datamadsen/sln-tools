# sln-tools
A shell script with various visual studio solution functionality. Meant to make
it more comfortable to work with git bash and visual studio on windows.

# Installation
Place the script somewhere, for instance in `~/.utilities` and make an alias to
it in your shell's runtime configuration, for instance `alias
sln='sh ~/.utilities/sln-tools.sh` in your `.bash_profile`.

# Usage
* `sln open` opens the first sln file found in either the current directory or parents.

* `sln close` Close the visual studio instance for the solution in the current
	directory or parents.
