# Azure NetApp Files - Azure AI Video Indexer Connector

This project allows you to easily find video files on your Azure NetApp Files volumes and send them to Azure AI Video Indexer.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

1. Clone this repo: git clone https://github.com/seanluce/anf-azure-ai-vi-connector.git
2. Execute the script using PowerShell: ./anf-azure-ai-vi-connector.ps1

## Prerequisites

The script needs read access to your Azure subscription and access to your Azure NetApp Files SMB shares. It is recommended to run the script from an Azure virtual machine with a managed identity and joined to the same domain as your Azure NetApp Files volumes.

## Demo

Check out this video for a quick overview and demonstration: [Azure NetApp Files - Azure AI Video Indexer Connector](https://youtu.be/D_mCFWtXb3I?si=oULObl0gR2DJrTi7)

## Built With

* [Azure NetApp Files](https://azure.microsoft.com/en-us/services/netapp/)
* [Azure AI Video Indexer](https://www.videoindexer.ai/)
