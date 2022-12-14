# VL.Devices.SpaceMouseHID

Use [3DConnexion™](https://3dconnexion.com) SpaceMice in vvvv gamma via HID instead of their driver.
Uses [HidLibrary](https://github.com/mikeobrien/HidLibrary) by [Mike O'Brien](https://www.mikeobrien.net/). 

Tested only with [SpaceMouse Wireless®](https://3dconnexion.com/us/product/spacemouse-wireless/).
Either connected through the Universal Receiver (PID C652) or via  USB-cable (PID C62E).

But should work also with SpaceMouse Compact® (PID C635)

Will only work properly if the 3DConnexion™ driver isn’t active, 
so either uninstall or otherwise make sure it is not running (remove it from autostart for example).

### Sponsored by 
### [Studio JHH](https://www.hansen.ch/)


## Using the library
In order to use this library with VL you have to install the nuget that is available via nuget.org. For information on how to use nugets with VL, see [Managing Nugets](https://thegraybook.vvvv.org/reference/hde/managing-nugets.html) in the VL documentation. As described there you go to the commandline and then type:

    nuget install VL.Devices.SpaceMouseHID


Try it with vvvv, the visual live-programming environment for .NET  
Download: http://visualprogramming.net

### License

### [MIT](https://github.com/bj-rn/VL.Devices.SpaceMouseHID/blob/master/LICENSE)
  

