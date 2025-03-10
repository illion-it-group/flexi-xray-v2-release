## v2.2.1
- Fixed doctor first name last name order
- Fixed detach patient button hover text

---

## v2.2.0
- Fixed build dependencies
- Fixed service communication (`XRayService`)
- Removed `.pdb` files from the build
- Added doctor and clinic information to `XRayMessage`
- Added folder watch `StopAllWatcher` method to `XRayService`
- Added `--shutdown` parameter to shut to folder watchers
- Added folder watcher shutdown on failure
- Added `DTX Studio` application support
- Added `Inno Setup` install script
- Better exception handling
- Added `FolderWatcherGUI` WPF application
  - It can be display the currently selected patient name
  - Deselect the patient (and stop the folder watcher)
  - Hide and Show the highlight window
  - Added a tray icon with a menu

---

## v2.1.0
- Initial commit
