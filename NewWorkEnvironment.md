# Introduction #

First of all, _speechOO_ give up the _corujaJNI_ directly, now it uses another layer for java called by _JLaPSAPI_. This API follows _JSAPI_ documentation. Then, it has some specials procedures to work and take a look on requirements needed.

# Details #

Download the speechoo code using subversion.

## JLaPSAPI ##

The installation instructions of _JLaPSAPI_ are in this site(just in Portuguese for while). Just follow all steps.
http://www.laps.ufpa.br/falabrasil/jlapsapi

## Netbeans ##

Then install Netbeans 6.8(you must use this version!) Java SE.
http://netbeans.org/downloads/6.8/index.html

Follow instructions as shown on two links below to install **Openoffice plugin** for _Netbeans_.

**Obs**: Use libreoffice-dev and libreoffice instead of Openoffice.

http://ccsl.ime.usp.br/cogroo/maven/extensoes_broo/index.html#Intro

http://ccsl.ime.usp.br/cogroo/maven/extensoes_broo/index.html#Exercise_0

**Obs**: you will need to find the installation directory, probally on Ubuntu would be _/usr/share/libreoffice_ or _/usr/share/local/libreoffice_ or _/opt/libreoffice_ , those are some chances.

Download the project using svn(you need to install with apt-get install subversion). On Source tab, there is a command start with **svn**. Type it on your terminal, on the directory that you want to save, to download.

Import the project on a directory like this one _{relative directory}/trunk/SpeechOO. Then you will see many erros, just go to the project properties>libraries.
At next you remove the broken reference to brOffice3.2 and add the Libreoffice3.x. Finally add_JLaPSAPI_and_JSAPI_JARs which are inside the lib folder of the project._

"OK! I made everything you said and one error continues". Take easy! Just click with the right button of the mouse on the project and _create OXT_. Now everything is fine!

On the link below has some tutorials for Libreoffice extensions. Try them to better know how this stuff works.

http://ccsl.ime.usp.br/cogroo/maven/extensoes_broo/index.html#Exercise_1

Suggestions or help: hugo.santos@itec.ufpa.br