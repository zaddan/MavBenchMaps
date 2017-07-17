# MavBenchMaps
To collect the map used for benchmarking.

to store a map in the repo: 
 - select the map from the content folder(located in the content broweser) in the unreal editor
 - right click and select Migrate.
 - pick a location to dump the migrated files
 - note that this might migrate multiple folders (which include meshes, warriors, ...)


to use a map in a project:
 - copy over all the folders for the map of intrest in the content folder of the project. 
 - note that you shouldn't copy over the top level folder in the repo, i.e. if these maps (and their related files and folders) are in a folder called motion_planning/blocks, only copy over the content of this folder to the 
   content folder of the project. 
