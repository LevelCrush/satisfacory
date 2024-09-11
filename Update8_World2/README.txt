WARNING: This directory may include the save data of multiple Satisfactory servers
run on this system.

If viewing this directory from AMP’s ADS File Manager/SFTP, you will see the
save data of all Satisfactory servers run on this system, other than those run by
AMP in Docker.

You will see the same save data if viewing this directory from AMP’s File Manager/SFTP
for a particular Satisfactory instance that is NOT run in Docker.

If viewing this directory from AMP’s File Manager/SFTP for a particular Satisfactory
instance that IS run in Docker, you will only see the save data of that instance.

You can also use the ADS File Manager/SFTP to view the save data of a Satisfactory
instance that is run in Docker by navigating to the following directory in the
instance’s datastore: .virtualhome/.config/Epic/FactoryGame/Saved/SaveGames.

The save data for a specific instance is linked to its port (as part of the
ServerSettings file name) and its session name (as part of the autosave file names
in the server subdirectory).

Save data will not be automatically deleted when a non-Docker Satisfactory server is
removed, so you may need to delete the ServerSettings file and/or autosave files
if later creating a new Satisfactory server with the same port and/or session name.

Take care when managing files in this directory or its subdirectory!