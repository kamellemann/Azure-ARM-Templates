# VM Scale Set von einem Gallery Image in ein bestehendes Virtual Network und einen Application Gateway inkl. Chef Extension innerhalb der VM

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fkamellemann%2FAzure-ARM-Templates%2Fmaster%2Fazuredeploy.json" target="_blank">
<img src="https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/deploytoazure.png"/>
</a>

## Prerequisites

To deploy this template, you will need:
 * Bestehendes Virtual Network
 * Bestehenden Application Gateway
 * Chef Server

In the parameters, you will need to take note of:
 * Name der RG des Virtuial Network
 * Name des Subnets
 * Name der RG des Application Gateway
 * Name des Backend Pool für die VMs
 * Chef URL

## Deployment steps

Einfach "Deploy to Azure" klicken

## Usage

#### Connect

Für den Zugriff auf die VMs wird ein JumpServer oder ein Site2Site VPN benötigt. Externer Zugriff ist nicht möglich.

## Notes
