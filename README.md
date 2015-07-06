# DevTestProd
# Domain join sample

This template demonstrates domain join to a private AD domain up in cloud. 
It creates one DC VM, one other VM and joins it to the domain.

This template deploys the following resources:
<ul><li>storage account</li><li>vnet</li><li>public ip</li><li>load balancer</li><li>a DC virtual machine</li><li>and another virtual machine</li></ul>


Click the button below to deploy

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fkaevans%2Fdevtestprod%2Fmaster%2Fdevtestprod%2Ftemplates%2FLoadBalancedVirtualMachine.json" target="_blank">
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





