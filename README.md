# Cloud Computing Architecture Lab 4 Inter VNet Connectivity

This repository preserves Guided Lab 4 from my **Cloud Computing Architecture** course, CISY 5183. The exercise focused on building and connecting Azure virtual-network environments.

## Lab focus

- Separate core and manufacturing virtual networks.
- Subnet design and network-interface deployment.
- Virtual-machine deployment through ARM templates.
- Azure Bastion for administrative connectivity.
- Inter-VNet connectivity and cloud network troubleshooting.
- Branch-based submission and infrastructure-export practice.

## Repository status

The default branch contains the instructor starter ARM template. My `lab04-jf` branch preserves the submission attempt and exported-file structure. The exported template remained at the `Generating template...` placeholder and the parameters file is empty, so this repository should be viewed as an incomplete course lab rather than a finished deployment.

I am retaining it publicly because it documents the learning process and the architecture I was working toward, even though the final export was not completed.

## Security note

The starter template accepts the administrator password as an ARM `secureString`; no password value is committed. Any future deployment should review authentication, network-security groups, VM images, Azure API versions, and current Bastion guidance.
