# WunderSys: an Achaean ServerSide Curing System
(originally developed by Nemutaur)

See https://dl.dropboxusercontent.com/u/6980966/ServersideSystem/index.html for most of the system details. This github project is for collaborative development (or development period until Nemutaur gets back to this). The current intent is to not duplicate any documentation here.

### For Developers:
The process for building WunderSys.xml for commit is:
1. Export WunderSys sub-folders (not top level) for each aliases, scripts, and triggers (each to separate xml files.
2. Make a copy of base.xml.
3. For each aliases.xml, scripts.xml, and triggers.xml, remove all xml outside of and including the <Script/Alias/TriggerPackage> tags.
4. Ctrl+A to select the remaining contents, then copy and paste in the appropriate section of the base.xml copy.
5. Replace WunderSys.xml with the base.xml copy containing the appropriate packages.
