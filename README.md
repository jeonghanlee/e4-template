# e4-template

This is the working repository for e4-template.

## what is e4?

e4 is the simple ioc application within e3. It doesn't have any source files needed to be compiled. It only has the following components:

```
template 
db (Db)
cmds
opi
proto
```

## Thoughts?

* Use the Standard EPICS Building System
* Download the same way e3 module, change the revision, and install them into INSTALLATION_PATH
* can be searchable within one siteIOC path, so create a link to point with name and version
* 