﻿# Mile.Project.Portable

[![NuGet Package](https://img.shields.io/nuget/vpre/Mile.Project.Portable)](https://www.nuget.org/packages/Mile.Project.Portable)

Portable parts of configurations for simplifying Visual Studio (MSBuild)
projects configurations.

Work In Progress

## Available MSBuild project options

If you want to disable all features from Mile.Project.Portable, please set the
following option.

```
<MileProjectDisableAllFeatures>true</MileProjectDisableAllFeatures>
```

If you want to enable project properties feature, please set the following
options.

```
<MileProjectEnableProjectProperties>true</MileProjectEnableProjectProperties>
<MileProjectCompanyName>TODO: Company Name</MileProjectCompanyName>
<MileProjectFileDescription>TODO: File Description</MileProjectFileDescription>
<MileProjectInternalName>$(TargetName)</MileProjectInternalName>
<MileProjectLegalCopyright>© TODO: Company Name. All rights reserved.</MileProjectLegalCopyright>
<MileProjectOriginalFilename>$(TargetName)$(TargetExt)</MileProjectOriginalFilename>
<MileProjectProductName>$(TargetName)</MileProjectProductName>
<MileProjectVersion>1.0.0.1</MileProjectVersion>
<MileProjectVersionTag>Preview 1</MileProjectVersionTag>
```

If you want to specify the embed manifest file, please set the following option.

```
<MileProjectEmbedManifestSourceFile>C:\Folder\Manifest.manifest</MileProjectEmbedManifestSourceFile>
```
