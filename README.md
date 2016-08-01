# ![powerclilogo](https://cloud.githubusercontent.com/assets/6964549/17082247/44e1392e-517f-11e6-9cbe-9efa0277deaa.png) PowerCLi Repo
## VMware Scripts & Modules

### <ins>[Copy-VMNotes2CompDescr.ps1</ins>] (https://github.com/rgel/PowerCLi/blob/master/Copy-VMNotes2CompDescr.ps1)

###### <b>[How to copy VMware VM Notes to Computer/AD Computer Account Description</b>] (http://www.ps1code.com/single-post/2015/12/14/How-to-copy-VMware-VM-Notes-to-ComputerAD-Computer-Account-Description)

### <ins>[Kickstart-VMHostIMM.ps1</ins>] (https://github.com/rgel/PowerCLi/tree/master/Kickstart)

###### <b>[Kickstart ESXi hosts on IBM/Lenovo servers without PXE using PowerShell</b>] (http://www.ps1code.com/single-post/2015/08/27/Kickstart-ESXi-hosts-on-IBMLenovo-servers-using-PowerShell)

### <ins>[Get-IBMVMHostWarranty.ps1</ins>] (https://github.com/rgel/PowerCLi/blob/master/Get-IBMVMHostWarranty.ps1)

###### <b>[Create enterprise-wide input file for IBM multiple warranty lookup using PowerShell</b>] (http://www.ps1code.com/single-post/2016/1/13/How-to-create-enterprisewide-input-file-for-IBM-multiple-warranty-lookup-web-service-using-PowerShell)

### <ins>[Vi-Module.psm1</ins>] (https://github.com/rgel/PowerCLi/tree/master/Vi-Module)

To install this module, drop the entire '<b>Vi-Module</b>' folder into one of your module directories.

The default PowerShell module paths are listed in the `$env:PSModulePath` environment variable.

To make it look better, split the paths in this manner `$env:PSModulePath -split ';'`

The default per-user module path is: `"$env:HOMEDRIVE$env:HOMEPATH\Documents\WindowsPowerShell\Modules"`.

The default computer-level module path is: `"$env:windir\System32\WindowsPowerShell\v1.0\Modules"`.

To use the module, type following command: `Import-Module Vi-Module -Force -Verbose`.

To see the commands imported, type `Get-Command -Module Vi-Module`.

For help on each individual cmdlet or function, run `Get-Help CmdletName -Full [-Online][-Examples]`.

#### <b><ins>Vi-Module Cmdlets:</ins></b>

|No|Cmdlet|Description|
|----|----|----|
|1|<b>[Get-RDM</b>] (http://www.ps1code.com/single-post/2015/10/16/How-to-get-RDM-Raw-Device-Mappings-disks-using-PowerCLi)|Report all VM with their RDM disks|
|2|<b>[Convert-VmdkThin2EZThick</b>] (http://www.ps1code.com/single-post/2015/11/05/How-to-convert-Thin-Provision-VMDK-disks-to-Eager-Zeroed-Thick-using-PowerCLi)|Inflate thin virtual disks|
|3|<b>[Find-VcVm</b>] (http://www.vmgu.ru/news/vmware-vcenter-how-to-find-powered-off)|Search VCenter VM throw direct connection to group of ESXi hosts|
|4|<b>[Set-PowerCLiTitle</b>] (http://www.ps1code.com/single-post/2015/11/17/ConnectVIServer-deep-dive-or-%C2%ABWhere-am-I-connected-%C2%BB)|Write connected VI servers info to PowerCLi window title bar|
|5|<b>[Get-VMHostFirmwareVersion</b>] (http://www.ps1code.com/single-post/2016/1/9/How-to-know-ESXi-servers%E2%80%99-BIOSFirmware-version-using-PowerCLi)|Get a Firmware version and release date of your ESXi hosts|
|6|<b>[Compare-VMHostSoftwareVib</b>] (http://www.ps1code.com/single-post/2016/1/10/How-to-compare-installed-VIB-packages-between-two-or-more-ESXi-hosts)|Compare installed VIB packages between two or more ESXi hosts|
|7|<b>[Get-VMHostBirthday</b>] (https://cloud.githubusercontent.com/assets/6964549/12399803/c8439dfa-be24-11e5-8141-09199caa301e.png)|[Get ESXi hosts' installation date. Thanks to <i>Magnus Andersson</i> for his [idea] (http://vcdx56.com/2016/01/05/find-esxi-installation-date/)|
|8|<b>[Enable-VMHostSSH/Disable-VMHostSSH</b>] (http://www.ps1code.com/single-post/2016/02/07/How-to-enabledisable-SSH-on-all-ESXi-hosts-in-a-cluster-using-PowerCLi)|Enable/Disable SSH on all ESXi hosts in a cluster|
|9|<b>[Set-VMHostNtpServer</b>] (http://www.ps1code.com/single-post/2016/03/10/How-to-configure-NTP-servers-setting-on-ESXi-hosts-using-PowerCLi)|Set `NTP Servers` setting on ESXi hosts|
|10|<b>[Get-Version</b>] (http://www.ps1code.com/single-post/2016/05/25/How-to-know-any-VMware-object%E2%80%99s-version-Use-GetVersion)|Get VMware Virtual Infrastructure objects' version info: `VM`, `ESXi Hosts`, `VDSwitches`, `Datastores`, `VCenters`, `PowerCLi`, `License Keys`|
