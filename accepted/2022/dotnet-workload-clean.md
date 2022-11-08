## dotnet workload clean

Add `dotnet workload clean` command. The function of this command would be to reset the manifests to be identical to the manifests obtained with a clean .NET SDK install of the same version.

This would only clean the manifests in the manifest folder with the corresponding version as the version of the .NET SDK that ran the clean command. 

## dotnet workload clean -all

Add `dotnet workload clean --clear`. The funcion of this command would be to delete all corresponding workload information on the machine.
This includes all manifest folders, references to workloads, registry keys, and temp files. 
