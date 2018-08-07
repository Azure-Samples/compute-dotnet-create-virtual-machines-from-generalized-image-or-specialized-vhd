---
services: Compute
platforms: dotnet
author: anuchandy
---

# Getting started on creating virtual machines from generalized image or specialized VHD in C# #

          Azure Compute sample for managing virtual machines -
           - Create a virtual machine
           - Deallocate the virtual machine
           - Generalize the virtual machine
           - Capture the virtual machine to create a generalized image
           - Create a second virtual machine using the generalized image
           - Delete the second virtual machine
           - Create a new virtual machine by attaching OS disk of deleted VM to it.


## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/compute-dotnet-create-virtual-machines-from-generalized-image-or-specialized-vhd.git

    cd compute-dotnet-create-virtual-machines-from-generalized-image-or-specialized-vhd

    dotnet restore

    dotnet run

## More information ##

[Azure Management Libraries for C#](https://github.com/Azure/azure-sdk-for-net/tree/Fluent)
[Azure .Net Developer Center](https://azure.microsoft.com/en-us/develop/net/)
If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.