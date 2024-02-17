| Skills Measured | Percent of Exam |
| --- | --- |
| [Secure Windows Server on-premises and hybrid infrastructures](#1) | 25-30% |
| [Implement and manage Windows Server high availability](#2) | 10-15% |
| [Implement disaster recovery](#3) | 10-15% |
| [Migrate servers and workloads](#4) | 20-25% |
| [Monitor and troubleshoot Windows Server environments](#5) | 20-25% |

🔳[110] Needs to be Studied
📚[0] Read the Docs
⏹[0] Did at Work
✅[0] Studied and did Hands-On Testing

# <a name="1"></a>Secure Windows Server on-premises and hybrid infrastructures

## Secure Windows Server operating system

### 🔳 Configure and manage Exploit Protection
*Resources:* <br />
[Enable exploit protection | Microsoft Docs](https://learn.microsoft.com/en-us/microsoft-365/security/defender-endpoint/enable-exploit-protection?view=o365-worldwide)
### 🔳 Configure and manage Windows Defender Application Control
*Resources:* <br />
[Windows Defender Application Control management with Configuration Manager | Mircosoft Docs](https://learn.microsoft.com/en-us/mem/configmgr/protect/deploy-use/use-device-guard-with-configuration-manager)
### 🔳 Configure and manage Microsoft Defender for Servers
*Resources:* <br />
[Plaan your Defender for Servers deployment | Microsoft Docs](https://learn.microsoft.com/en-us/azure/defender-for-cloud/plan-defender-for-servers)
### 🔳 Configure and manage Windows Defender Credential Guard
*Resources:* <br />
[Configure Credential Guard | Microsoft Docs](https://learn.microsoft.com/en-us/windows/security/identity-protection/credential-guard/configure)
### 🔳 Configure SmartScreen
*Resources:* <br />
[Microsoft Defender SmartScreen | Microsoft Docs](https://learn.microsoft.com/en-us/windows/security/operating-system-security/virus-and-threat-protection/microsoft-defender-smartscreen/)
### 🔳 Implement operating system security by using Group Policies
*Resources:* <br />
[Security baselines | Microsoft Docs](https://learn.microsoft.com/en-us/windows/security/operating-system-security/device-management/windows-security-configuration-framework/windows-security-baselines)

## Secure a hybrid Active Directory infrastructure

### 🔳 Configure password policies
*Resources:* <br />
[Best Practices for Securing Active Directory | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/plan/security-best-practices/best-practices-for-securing-active-directory)
### 🔳 Enable password block lists
*Resources:* <br />
[Turorial: Configure custom banned passwords for Microsoft Entra password protection | Microsoft Docs](https://learn.microsoft.com/en-us/entra/identity/authentication/tutorial-configure-custom-password-protection)
### 🔳 Manage protected users
*Resources:* <br />
[Appendix C: Protected Accounts and Groups in Active Directory | Microsft Docs](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/plan/security-best-practices/appendix-c--protected-accounts-and-groups-in-active-directory)
### 🔳 Manage account security on an RODC
*Resources:* <br />
[Read-Only Domain Controllers Step-by-Step Guide | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-r2-and-2008/cc772234(v=ws.10))
### 🔳 Harden domain controllers
*Resources:* <br />
[Securing Domain Controllers Against Attack | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/plan/security-best-practices/securing-domain-controllers-against-attack)
### 🔳 Configure authentication policy silos
*Resources:* <br />
[Guidance about how to configure protected accounts | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/manage/how-to-configure-protected-accounts)
### 🔳 Restrisct access to domain controllers
*Resources:* <br />
[Appendix H: Securing Local Administrator Accounts and Groups | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/plan/security-best-practices/appendix-h--securing-local-administrator-accounts-and-groups)
### 🔳 Configure account security
### 🔳 Manage AD built-in administrative groups
*Resources:* <br />
[Appendix B: Privileged Accounts and Groups in Active Directory | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/plan/security-best-practices/appendix-b--privileged-accounts-and-groups-in-active-directory)
### 🔳 Manage AD delegation
*Resources:* <br />
[Kerberos Constrained Delegation Overview | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/jj553400(v=ws.11)) <br />
[Enable computer and user to be trusted for delegation | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn221977(v=ws.11))
### 🔳 Implement and manage Microsoft Defender for Identity
*Resources:* <br />
[What is Microsoft Defender for Identity? | Microsoft Docs](https://learn.microsoft.com/en-us/defender-for-identity/what-is)

## Identify and remediate Windows Server security issues by using Azure Services

### 🔳 Monitor on-premises servers and Azure IaaS VMs by using Microsoft Sentinel
*Resources:* <br />
[Find your Microsoft Sentinel data connector | Microsoft Docs](https://learn.microsoft.com/en-us/azure/sentinel/data-connectors-reference)
### 🔳 Identify and remediate security issues on-premises servers and Azure IaaS VMs by using Microsoft Defender for Cloud
*Resources:* <br />
[What is Microsoft Defender for Cloud? | Microsoft Docs](https://learn.microsoft.com/en-us/azure/defender-for-cloud/defender-for-cloud-introduction)

## Secure Windows Server networking

### 🔳 Manage Windows Defender Firewall
To get some basic details in PowerShell `Get-NetFirewallProfile`

*Resources:* <br />
[Configure rules with group policy | Microsoft Docs](https://docs.microsoft.com/en-us/windows/security/threat-protection/windows-firewall/best-practices-configuring)
### 🔳 Implement domain isolation
*Resources:* <br />
[Restrict Server Access to Members of a Group Only | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/jj717267(v=ws.11))
### 🔳 Implement connection security rules
*Resources:* <br />
[Create an Authentication Request Rule | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/jj717283(v=ws.11))

## Secure Windows Server storage

### 🔳 Manage Windows Bitlocker Drive Encryption (BitLocker)
One of the requirements is that you need the EFI partition seperate from the main OS partition (and if it is UEFI it needs to be formated FAT32), to verify that you are good you can run `BdeHdCfg.exe -driveinfo`

*Resources:* <br />
[BitLocker Frequently Asked Questions (FAQ) | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/hh831507(v=ws.11))
### 🔳 Manage and recover encrypted volumes
*Resources:* <br />
[BitLocker Recovery Guide | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn383583(v=ws.11))
### 🔳 Enable storage encryption by using Azure Disk Encryption
*Resources:* <br />
[Data encryption models | Microsoft Docs](https://learn.microsoft.com/en-us/azure/security/fundamentals/encryption-models)
### 🔳 Manage disk encryption keys for IaaS virtual machines
*Resources:* <br />
[Overview of managed disk encryption options | Microsoft Docs](https://learn.microsoft.com/en-us/azure/virtual-machines/disk-encryption-overview)

# <a name="2"></a>Implement and Manage Windows Server high availability

## Implement a Windows Server failover cluster

### 🔳 Implement a failover cluster on-premises, hybrid, or cloud-only
*Resources:* <br />
[Share an Azure managed disk | Microsoft Docs](https://learn.microsoft.com/en-us/azure/virtual-machines/disks-shared) <br />
[Create and deploy virtual machines in an availability set using Azure Powershell | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/azure/virtual-machines/windows/tutorial-availability-sets)
### 🔳 Create a Windows failover cluster
*Resources:* <br />
[Create a failover cluster | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/failover-clustering/create-failover-cluster)
### 🔳 Stretch cluster across datacenters or Azure regions
*Resources:* <br />
[Stretch Cluster Replication Using Shared Storage | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/storage/storage-replica/stretch-cluster-replication-using-shared-storage) <br />
[Cluster to Cluster Storage Replication Cross-Region in Azure | MIcrosoft Docs](https://learn.microsoft.com/en-us/windows-server/storage/storage-replica/cluster-to-cluster-azure-cross-region)
### 🔳 Configure storage for failover clustering
*Resources:* <br />
[Failover clustering hardware requirements and storage options | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/failover-clustering/clustering-requirements) <br />
[Failover Clustering Hardware Requirements and Storage Options | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/jj612869(v=ws.11))
### 🔳 Modify quorum options
*Resources:* <br />
[Configure and manage quorum | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/failover-clustering/manage-cluster-quorum)
### 🔳 Configure network adapters for failover clustering
*Resources:* <br />
[Network Interface on a Clustered Node | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-r2-and-2008/dd354058(v=ws.10))
### 🔳 Configure cluster workload options
*Resources:* <br />
[Failover Clustering in Windows Server and Azure Stack HCI | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/failover-clustering/failover-clustering-overview) <br />
[Clustered Services and Applications | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-r2-and-2008/dd337817(v=ws.10))
### 🔳 Configure cluster sets
*Resources:* <br />
[Deploy a cluster set | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/failover-clustering/cluster-set)
### 🔳 Configure Scale-Out File servers
*Resouces:* <br />
[Scale-Out File Server for application data overview | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/failover-clustering/sofs-overview)
### 🔳 Create an Azure witness
*Resources:* <br />
[Deploy Cloud Witness for a failover cluster | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/failover-clustering/deploy-cloud-witness)
### 🔳 Configure a floating IP address for the cluster
*Resources:* <br />
[Clustering Information on IP Address Failover | Microsoft Docs](https://learn.microsoft.com/en-us/troubleshoot/windows-server/high-availability/cluster-information-ip-address-failover)
### 🔳 Implement load balancing for the failover cluster
*Resources:* <br />
[Virtual machine load balancing | Microsoft Docs](https://learn.microsoft.com/en-us/azure-stack/hci/manage/vm-load-balancing)

## Manage failover clustering

### 🔳 Implement cluster-aware updating
*Resources:* <br />
[Cluster-Aware Updating overview | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/failover-clustering/cluster-aware-updating)
### 🔳 Recover a failed cluster node
*Resources:* <br />
[High Availability troubleshooting documentation for Windows Server | Microsoft Docs](https://learn.microsoft.com/en-us/troubleshoot/windows-server/high-availability/high-availability-overview)
### 🔳 Upgrade a node to Windows Server 2022
*Resources:* <br />
[Cluster operating system rolling upgrade | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/failover-clustering/cluster-operating-system-rolling-upgrade)
### 🔳 Failover workloads between nodes
*Resources:* <br />
[Failover Clustering | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-r2-and-2008/dd353290(v=ws.10))
### 🔳 Install Windows updates on a cluster node
*Resources:* <br />
[Cluster-Aware Updating advanced options and updating run profiles | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/failover-clustering/cluster-aware-updating-options)
### 🔳 Manage failover clusters using Windows Admin Center
*Resources:* <br />
[Manage Failver Clusters with Windows Admin Center | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/manage/windows-admin-center/use/manage-failover-clusters)

## Implement and manage Storage Spaces Direct

### 🔳 Create a failover cluster using Storage Spaces Direct
*Resources:* <br />
[Storage Spaces Direct overview | Microsoft Docs](https://learn.microsoft.com/en-us/azure-stack/hci/concepts/storage-spaces-direct-overview)
### 🔳 Upgrade a Storage Spaces Direct node
*Resources:* <br />
[Upgrade a Storage Spaces Direct cluster to Windows Server 2019 | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/storage/storage-spaces/upgrade-storage-spaces-direct-to-windows-server-2019)
### 🔳 Implement networing for Storage Spaces Direct
*Resources:* <br />
[Deploy Storage Spaces Direct on Windows Server | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/storage/storage-spaces/deploy-storage-spaces-direct#step-2-configure-the-network)
### 🔳 Configure Storage Spaces Direct

# <a name="3"></a>Implement disaster recovery

## Manage backup and recovery for Windows Server

### 🔳 Back up and restore files and folders to Azure Recovery Services Vault
*Resources:* <br />
[Back up Windows Server files and folders to Azure | Microsoft Docs](https://learn.microsoft.com/en-us/azure/backup/backup-windows-with-mars-agent) <br />
[Restore files to Windows Server using the MARS Agent | Microsoft Docs](https://learn.microsoft.com/en-us/azure/backup/backup-azure-restore-windows-server)
### 🔳 Install and manage Azure Backup Server
*Resources:* <br />
[What's new in Microsoft Azure Backup Server (MABS)? | Microsoft Docs](https://learn.microsoft.com/en-us/azure/backup/backup-mabs-whats-new-mabs) <br />
[Install and upgrade Azure Backup Server | Microsoft Docs](https://learn.microsoft.com/en-us/azure/backup/backup-azure-microsoft-azure-backup)
### 🔳 Back up and recover using Azure Backup Server
*Resources:* <br />
[Back up Azure VMs in a Recovery Services vault | Microsoft Docs](https://learn.microsoft.com/en-us/azure/backup/backup-azure-arm-vms-prepare)
### 🔳 Manage backups in Azure Recovery Services Vault
*Resources:* <br />
[Get improved backup and restore performance with Azure Backup Instant Restore capability | Microsoft Docs](https://learn.microsoft.com/en-us/azure/backup/backup-instant-restore-capability)
### 🔳 Create a backup policy
*Resources:* <br />
[Create Azure Recovery Services backup policies using REST API | Microsoft Docs](https://learn.microsoft.com/en-us/azure/backup/backup-azure-arm-userestapi-createorupdatepolicy)
### 🔳 Configure backup for Azure VM using the built-in backup agent
*Resources:* <br />
[Deploy and manage backup to Azure for Windows Server/Windows Client using PowerShell | Microsoft Docs](https://learn.microsoft.com/en-us/azure/backup/backup-client-automation)
### 🔳 Recover VM using temporary snapshots
*Resources:* <br />
[Backup and disaster recovery for Azure managed disks | Microsoft Docs](https://learn.microsoft.com/en-us/azure/virtual-machines/backup-and-disaster-recovery-for-azure-iaas-disks)
### 🔳 Recover VMs to new Azure VMs
*Resources:* <br />
[How to restore Azure VM data in Azure portal | Microsoft Docs](https://learn.microsoft.com/en-us/azure/backup/backup-azure-arm-restore-vms)
### 🔳 Restore a VM

## Implement disaster recovery by using Azure Site Recovery

### 🔳 Configure Azure Site Recovery networking
*Resources:* <br />
[Manage VM network interfaces for on-premises disaster recovery to Azure | Microsoft Docs](https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-manage-network-interfaces-on-premises-to-azure)
### 🔳 Configure Site Recovery for on-premises VMs
*Resources:* <br />
[Prepare network mapping for Hyper-V VM disaster recovery to Azure | Microsoft Docs](https://learn.microsoft.com/en-us/azure/site-recovery/hyper-v-vmm-network-mapping)
### 🔳 Configure a recovery plan
*Resources:* <br />
[Create and customize recovery plans | Microsoft Docs](https://learn.microsoft.com/en-us/azure/site-recovery/site-recovery-create-recovery-plans)
### 🔳 Configure Site Recovery for Azure VMs
*Resources:* <br />
[About networking in Azure VM disaster recovery | Microsoft Docs](https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-about-networking)
### 🔳 Implement VM replication to secondary datacenter or Azure region
*Resources:* <br />
[Enable Azure VM disaster recovery between availability zones | Microsoft Docs](https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-how-to-enable-zone-to-zone-disaster-recovery)
### 🔳 Configure Azure Site Recovery policies
*Resources:* <br />
[Use Azure Policy to set up Azure Site Recovery | Microsoft Docs](https://learn.microsoft.com/en-us/azure/site-recovery/azure-to-azure-how-to-enable-policy)

## Protect virtual machines by using Hyper-V replicas

### 🔳 Configure Hyper-V hosts for replication
*Resources:* <br />
[Set up Hyper-V Replica | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/virtualization/hyper-v/manage/set-up-hyper-v-replica)
### 🔳 Manage Hyper-V replica servers
### 🔳 Configure VM replication
### 🔳 Perform a failover
*Resources:* <br />
[Demonstrate replication and planned failover | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/hh831759(v=ws.11))

# <a name="4"></a>Migrate servers and workloads

## Migrate on-premises storage to on-premises servers or Azure

### 🔳 Transfer data and share
### 🔳 Cut over to a new server using Storage Migration Services (SMS)
*Resources:* <br />
[How cutover works in Storage Migration Service | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/storage/storage-migration-service/cutover)
### 🔳 Use Storage Migration Services to migrate to Azure VMs
*Resources:* <br />
[Storage Migration Service overview | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/storage/storage-migration-service/overview)
### 🔳 Migrate to Azure file shares
*Resources:* <br />
[Migrate to SMB Azure file shares | Microsoft Docs](https://learn.microsoft.com/en-us/azure/storage/files/storage-files-migration-overview)

## Migrate on-premises servers to Azure

### 🔳 Deploy and configure Azure Migrate appliance
*Resources:* <br />
[Set up an appliance with a script | Microsoft Docs](https://learn.microsoft.com/en-us/azure/migrate/deploy-appliance-script)
### 🔳 Migrate VM workloads to Azure IaaS
*Resources:* <br />
[Migrate Hyper-V VMs to Azure | Microsoft Docs](https://learn.microsoft.com/en-us/azure/migrate/tutorial-migrate-hyper-v?tabs=UI)
### 🔳 Migrate physical workloads to IaaS
*Resources:* <br />
[Set up an appliance for physical servers | Microsoft Docs](https://learn.microsoft.com/en-us/azure/migrate/how-to-set-up-appliance-physical)
### 🔳 Migrate by using Azure Migrate
*Resources:* <br />
[Add migration tools | Microsoft Docs](https://learn.microsoft.com/en-us/azure/migrate/how-to-migrate)

## Migrate workloads from previous versions to Windows Server 2022

### 🔳 Migrate IIS
*Resources:* <br />
[Migrate a Web Site from IIS 6.0 to IIS 7 or above | Microsoft Docs](https://learn.microsoft.com/en-us/iis/publish/using-web-deploy/migrate-a-web-site-from-iis-60-to-iis-7-or-above)
### 🔳 Migrate Hyper-V hosts
*Resources:* <br />
[Hyper-V: Migration Options | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn486792(v=ws.11))
### 🔳 Migrate RDS host servers
*Resources:* <br />
[Migrate Remote Desktop Services to Windows Server 2012 R2 | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn479239(v=ws.11))
### 🔳 Migrate DHCP
*Resources:* <br />
[Migrate DHCP Server to Windows Server 2012 R2 | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn495425(v=ws.11))
### 🔳 Migrate print servers
*Resources:* <br />
[Migrate Print and Document Services to Windows Server 2012 | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/jj134150(v=ws.11))

## Migrate IIS workloads to Azure

### 🔳 Migrate IIS workloads to Azure Web Apps
*Resources:* <br />
[Migrate your .NET web app or service to Azure App Service | Microsoft Docs](https://learn.microsoft.com/en-us/dotnet/azure/migration/app-service)
### 🔳 Migrate IIS workloads to containers
*Resources:* <br />
[Containerize a .NET Core App | Microsft Docs](https://learn.microsoft.com/en-us/virtualization/windowscontainers/quick-start/building-sample-app)

## Migrate an AD DS infrastructure to Windows Server 2022 AD DS

### 🔳 Migrate AD DS objects, including users, groups and Group Policies using AD Migration Tool
*Resources:* <br />
[Best Practices for Active Directory Migration | Microsoft Docs](https://docs.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-r2-and-2008/cc974412(v=ws.10)) <br />
[Explore the Active Directory Migration Tool | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/active-directory-domain-services-migration/5-explore-active-directory-migration-tool/)
### 🔳 Migrate to a new Active Directory forest
*Resources:* <br />
[Interforest Active Directory Domain Restructure | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-r2-and-2008/cc974335(v=ws.10)) <br />
[Active Directory Domain Services migration | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/active-directory-domain-services-migration/)
### 🔳 Upgrade an existing forest
*Resources:* <br />
[Upgrade domain controllers to a newer version of Windows Server | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/deploy/upgrade-domain-controllers)

# <a name="5"></a>Monitor and troubleshoot Windows Server environments

## Monitor Windows Server by using Windows Server tools and Azure services

### 🔳 Monitor Windows Server using Performance Monitor
*Resources:* <br />
[Windows Server performanace troubleshooting documentation | Microsoft Docs](https://learn.microsoft.com/en-us/troubleshoot/windows-server/performance/performance-overview)
### 🔳 Create and configure Data Collector Sets
*Resources:* <br />
[Creating Data Collector Sets | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-r2-and-2008/cc749337(v=ws.11))
### 🔳 Monitor servers and configure alerts by using Windows Admin Center
*Resources:* <br />
[Monitor servers and configure alerts with Azure Monitor from Windows Admin Center | Microsoft Docs](https://learn.microsoft.com/en-us/windows-server/manage/windows-admin-center/azure/azure-monitor)
### 🔳 Analyze Windows Server system data by using System Insights
*Resources:* <br />
[System Insights overview | Microsft Docs](https://learn.microsoft.com/en-us/windows-server/manage/system-insights/overview)
### 🔳 Manage event logs
*Resources:* <br />
[Event Logs | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-r2-and-2008/cc722404(v=ws.11)) <br />
[Manage and monitor Windows Server event logs | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/manage-monitor-event-logs/)
### 🔳 Deploy Azure Monitor agents
*Resources:* <br />
[Azure Monitor Agent overview | Microsoft Docs](https://learn.microsoft.com/en-us/azure/azure-monitor/agents/agents-overview)
### 🔳 Collect performance counters to Azure
*Resources:* <br />
[Data collection rules in Azure Monitor | Microsoft Docs](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/data-collection-rule-overview)
### 🔳 Create alerts
*Resources:* <br />
[Create or edit a log alert rule | Microsoft Docs](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/alerts-create-log-alert-rule)
### 🔳 Monitor Azure VMs by using Azure diagnostics extension
*Resources:* <br />
[Azure Diagnostics extension overview | Microsoft Docs](https://learn.microsoft.com/en-us/azure/azure-monitor/agents/diagnostics-extension-overview)
### 🔳 Monitor Azure VMs performance by using VM Insights
*Resources:* <br />
[Overview of VM insights | Microsoft Docs](https://learn.microsoft.com/en-us/azure/azure-monitor/vm/vminsights-overview)

## Troubleshoot Windows Server on-premises and hybrid networking <sup><sup>[Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/troubleshoot-premises-hybrid-networking/)</sup></sup>

### 🔳 Troubleshoot hybrid network connectivity
*Resources:* <br />
[Microsoft Azure Virtual Network Troubleshooter package | Microsoft Docs](https://learn.microsoft.com/en-us/troubleshoot/azure/general/sdp3fdcb6045-5616-45b4-bb68-0bd11081c184-vnet)
### 🔳 Troubleshoot on-premises connectivity
*Resources:* <br />
[Windows Server networking troubleshooting documentation | Microsoft Docs](https://learn.microsoft.com/en-us/troubleshoot/windows-server/networking/networking-overview)

## Troubleshoot Windows Server virtual machines in Azure

### 🔳 Troubleshoot deployment failures
*Resources:* <br />
[VM deployment issues | Microsoft Docs](https://learn.microsoft.com/en-us/troubleshoot/azure/virtual-machines/welcome-deployment-troubleshooting) <br />
[Troubleshoot VM deployment | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/troubleshoot-windows-server-virtual-machines-azure/2-troubleshoot-vm-deployment)
### 🔳 Troubleshoot booting failures
*Resources:* <br />
[Troubleshoot Azure Virtual Machines boot errors | Microsoft Docs](https://learn.microsoft.com/en-us/troubleshoot/azure/virtual-machines/boot-error-troubleshoot) <br />
[Troubleshoot VM startup | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/troubleshoot-windows-server-virtual-machines-azure/3-troubleshoot-vm-startup)
### 🔳 Troubleshoot VM performance issues
*Resources:* <br />
[Troubleshoot VM performance | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/troubleshoot-windows-server-virtual-machines-azure/6-troubleshoot-vm-performance/)
### 🔳 Troubleshoot VM extension issues
*Resources:* <br />
[Troubleshoot VM extensions | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/troubleshoot-windows-server-virtual-machines-azure/4-troubleshoot-vm-extensions/)
### 🔳 Troubleshoot disk encryption issues
*Resources:* <br />
[Azure Disk Encryption for Windows VMs | Microsoft Docs](https://learn.microsoft.com/en-us/azure/virtual-machines/windows/disk-encryption-overview)
### 🔳 Troubleshoot storage
*Resources:* <br />
[Troubleshoot VM Storage | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/troubleshoot-windows-server-virtual-machines-azure/7-troubleshoot-vm-storage/ )
### 🔳 Troubleshoot VM connection issues
*Resources:* <br />
[Troubleshoot VM conectivity | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/troubleshoot-windows-server-virtual-machines-azure/5-troubleshoot-remote-vm-connections/)

## Troubleshoot Active Directory

### 🔳 Restore objects from AD recycle bin
*Resources:* <br />
[What's New in AD DS: Active Directory Recycle Bin | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-r2-and-2008/dd391916(v=ws.10)) <br />
[Recover objects from the AD recycle bin | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/troubleshoot-active-directory/2-recover-objects-from-active-directory-recycle-bin/)
### 🔳 Recover Active Directory database using Directory Services Restore mode
*Resources:* <br />
[Recover the AD DS database | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/troubleshoot-active-directory/3-recover-active-directory-domain-services-database/)
### 🔳 Recover SYSVOL
*Resources:* <br />
[Restoring and Rebuilding SYSVOL | Microsoft Docs](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-server-2008-r2-and-2008/cc816596(v=ws.10))
### 🔳 Troubleshoot Active Directory replication
*Resources:* <br />
[Troubleshoot AD DS replication | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/troubleshoot-active-directory/5-troubleshoot-active-directory-domain-services-replication/)
### 🔳 Troubleshoot Hybrid authentication issues
*Resources:* <br />
[Troubleshoot hybrid authentication issues | Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/troubleshoot-active-directory/6-troubleshoot-hybrid-authentication-issues/)
### 🔳 Troubleshoot on-premises Active Directory
*Resources:* <br />
[Troubleshoot domain controller deployment | Microsoft Docs](https://learn.microsoft.com/en-us/troubleshoot/windows-server/identity/troubleshoot-domain-controller-deployment)
