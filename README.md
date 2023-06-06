# Gigabyte
## General information
This repository was created to contain relevant helpful scripts and any additional tools or information that can assist others in managing their Gigabyte backdoor mitigation plans.

## Windows Based Platforms
Eclypsium has released a PowerShell script to Github that can assist in determining whether a system is impacted. 

The script compares the motherboard model to the list of models known to be impacted. It also checks the Windows filesystem for the presence of the GigabyteUpdateService.exe executable and, if found, compares the SHA256 hash against the list of hashes seen by Eclypsium.

The script does not require administrative permissions to run, but it does require that the PowerShell ExecutionPolicy be configured to allow running scripts.

# If you encounter any issues please report them and we will try our best to assist you as soon as we can.