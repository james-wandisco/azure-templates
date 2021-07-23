# azure-templates

### On linux

download azcli

- [Install azcli](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli).

login to azure

`az login`

Know/Choose your resource group

`az group list -o table | grep hughes`

Create VM with your choosen template.

`az group deployment create --resource-group <my-resource-group> --template-uri https://github.com/james-wandisco/azure-templates/blob/main/ubuntu-MyVNET-tomcat.json`


Example

`az group deployment create --resource-group SUPPORT-james.hughes5 --template-uri https://github.com/james-wandisco/azure-templates/blob/main/ubuntu-MyVNET-tomcat.json`


`Tags: Linux, Ubuntu, Java, TomCat` 


### Reference Materials
- [Azure Virtual Machines](https://azure.microsoft.com/services/virtual-machines/).
- [Azure Linux Virtual Machines documentation](https://docs.microsoft.com/azure/virtual-machines/linux/)
- [Azure Windows Virtual Machines documentation](https://docs.microsoft.com/azure/virtual-machines/windows/)
- [Template reference](https://docs.microsoft.com/azure/templates/microsoft.compute/allversions)
- [Quickstart templates](https://azure.microsoft.com/resources/templates/?resourceType=Microsoft.Compute&pageNumber=1&sort=Popular)
- [Microsoft Learn Modules for Linux VMs](https://docs.microsoft.com/learn/browse/?term=linux%20Virtual%20Machine)

