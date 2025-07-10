# Eclipse Renesas QE Devkit

This plugin is an aggregation plugin that contains the development plugins used for Renesas QE development.

## Include Plugins
[OpenExplorer](https://github.com/tlcsdm/eclipse-openexplorer)  
[Eclipse Copyright](https://github.com/tlcsdm/eclipse-copyright)  
[Fullscreen](https://github.com/tlcsdm/eclipse-fullscreen)  
[IconPreview](https://github.com/tlcsdm/eclipse-iconpreview)  
[ResourceBundle Editor](https://github.com/tlcsdm/eclipse-rbe)  
[UCDetector](https://github.com/tlcsdm/ucdetector)  
[Eclipse Renesas Config Editor](https://github.com/tlcsdm/eclipse-renesas-config-editor)
[Eclipse Minimap](https://github.com/tlcsdm/eclipse-minimap)

## Build

This project uses [Tycho](https://github.com/eclipse-tycho/tycho) with [Maven](https://maven.apache.org/) to build. It requires Maven 3.9.0 or higher version.

Dev build:

```
mvn clean verify
```

Release build:

```
mvn clean org.eclipse.tycho:tycho-versions-plugin:set-version -DnewVersion=2.0.0 verify
```

## Install

1. Add `https://raw.githubusercontent.com/tlcsdm/eclipse-renesas-qe-devkit/master/update_site/` as the upgrade location in Eclipse.
2. Download from [Jenkins](https://jenkins.tlcsdm.com/job/eclipse-plugin/job/eclipse-renesas-qe-devkit)

