# MDT Modified Files

In here, you'll find edited version of MDT files. 
Modification are done for fixing bugs or bringing up new functionalities.

## 6.3.8456.1000
Initial Release by Microsoft

## 6.3.8456.2000
Added capability to appply multiple instances of KB during Offline servicing.
This way, Servicing stack update can be applied separately from other packages on server 2016/2019 
without breaking Task sequence execution.

Affected files: [ZTIPatches.wsf](https://github.com/Diagg/MDT-Modified-Files/blob/master/ZTIPatches.wsf),[LTIApply.wsf](https://github.com/Diagg/MDT-Modified-Files/blob/master/LTIApply.wsf)

Full details: [MDT: unable to apply servicing stacks updates on Server 2016/2019](https://www.osd-couture.com/)

Release date: 07/26/2019
                
