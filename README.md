# DevTestProd

This template shows how to customize an existing template to suit your needs.  For more information, see the blog post at <a href="http://blogs.msdn.com/b/kaevans/archive/2015/07/05/azure-resource-manager-templates-with-visual-studio-2015.aspx">http://blogs.msdn.com/b/kaevans/archive/2015/07/05/azure-resource-manager-templates-with-visual-studio-2015.aspx</a>

This template deploys the following resources:
<ul><li>storage account</li><li>vnet with 3 subnets</li><li>6 network interfaces</li><li>6 virtual machines (size D1)</li></ul>


Click the button below to deploy

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fkaevans%2FDevTestProd%2Fmaster%2FDevTestProd%2FTemplates%2FLoadBalancedVirtualMachine.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>


Template parameters:

| Name   | Description    |
|:--- |:---|
| virtualNetworkName | The name of the virtual network |
| adminUserName | Name of the admin user    |
| adminPassword| Password for the admin user |
| imagePublisher | Publisher for the image (default is MicrosoftWindowsServer) |
| imageOffer | Image offer (default is WindowsServer) |
| imageSKU | SKU for the image (default is 2012-R2-Datacenter) |
| vmStorageAccountContainerName | Container name for the VHDs in storage (default is vhds) |
| newStorageAccountName | Name of the storage account to use |
| vmSize | The size of the VM (Standard_D1) |





