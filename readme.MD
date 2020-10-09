# FHIR R4 BR-Core Implementation Guide

## Introduction

Brazil's national profile.

## Prerequisites

You will need Ruby installed. 
If you're running this on windows, you can try https://rubyinstaller.org/downloads/
Then, once you have ruby installed, you will need Jekyll (A ruby gem) installed. 

So just

''gem install jekyll''

Finally, you will need the FHIR IG Publisher. It's available on:
https://github.com/HL7/fhir-ig-publisher

And you're ready to go.

### How to generate this profile

''java -jar publisher.jar -ini ig.ini''

And check the output folder.
