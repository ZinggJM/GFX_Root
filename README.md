## GFX_Root Library: extracted root class of Adafruit GFX Library
as of 20.05.2020, by Jean-Marc Zingg

### Version 2.0.0
- reduced virtual methods to preserve code space
- class GFX_Root retains transaction support for class GFX_IO of library GFX_Extensions
- class GFX has no transaction support for minimal code space use
#### Version 1.8.2
- extract from Adafruit GFX Library version 1.8.2