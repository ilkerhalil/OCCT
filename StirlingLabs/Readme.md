# According to OpenCascade

OCCT documents that some 3rd Party files need to be customised in order to build OCCT, which is obviously difficult to do in a GitHub Action.  So we pre-customised the files and just copy them over to build.  This is obviously not ideal so if you have a better plan, ideally one that avoids messy manual comparisons when upgrading the dependencies, please create a PR.

Anyway, this directory contains those files, customised according to https://github.com/StirlingLabs/OCCT/blob/autoBuildLibrary/dox/build/build_3rdparty/building_3rdparty.md