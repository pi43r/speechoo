# Introduction #

Manual to build the Coruja package in Linux systems.


# Julius #

Inside the folder LaPSAPI, you have a folder called julius-4.1.4. Build it executing:

./configure
make

**PATCH:** had to modify Makefile.in libjulius and libsent to include -fPIC to the CPPFLAGS. _Should investigate how to avoid it_.

Verify if Julius was correctly built. Open julius-4.1.4/julius and try ./julius

# CorujaJNI Project #

~~The LaPSAPI is a project for Eclipse C++ IDE, you can just import it into your workspace (it is important to see that you need the julius folder). Once you have imported the project you can just compile it. LaPSAPI is a project of a Shared Library to control Julius.~~ >> we are not using it for now

For each plattform, open CorujaJNI project in Eclipse C++ IDE and build it. For now only the Debug version is working. Save the build results (.so, .dll) for later.