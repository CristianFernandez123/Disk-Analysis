# Disk Analysis with Autopsy

## Objective
 Get hands-on and use different features within Autopsy by analyzing a disk image from an ongoing investigation.

### Skills Learned

- Learn about Autopsy and its capabilities.
- Learn how to navigate and use Autopsy at a basic level.


### Tools Used
- Autopsy

## Steps

After opening and selecting the laptop image we want to analyze, we can configure what type of ingest modules we want.

![image](https://github.com/CristianFernandez123/Disk-Analysis-Lab/assets/161634608/3e179487-d84a-4d78-a274-2b486fec325e)

Once Autopsy is done ingesting all the data we can dive in retrieving all the information we want to acquire. I can see the operating system of the device under ‘Data Artifacts > Operating System Information’. The OS listed as ‘Program Name’: Windows 8.1 pro.

![image](https://github.com/CristianFernandez123/Disk-Analysis-Lab/assets/161634608/948138c9-4980-4858-abf7-185117efa5e3)

In the same section as above, towards the left of the table, we can see the Hostname listed as ‘Name’.

![image](https://github.com/CristianFernandez123/Disk-Analysis-Lab/assets/161634608/bd07a334-1ad0-4330-aca4-dec2ebdd18d8)

In this Lab, a  senior analyst asked to investigate a Web Download that happened on 2013-12-18 20:05:57 GMT. In the table on the right, we can see ‘Date Accessed’ and find the download that happened on that date and time.

![image](https://github.com/CristianFernandez123/Disk-Analysis-Lab/assets/161634608/8ba4bd2b-ca36-4f16-a8c0-d027545ddb13)

The senior analyst is also asking for a full URL of the file that was downloaded at 2013-12-18 03:02:50 GMT. In the same location, we can see the full URL in the column titled ‘URL’.

![image](https://github.com/CristianFernandez123/Disk-Analysis-Lab/assets/161634608/a6da2d66-482f-449c-b337-e1a972d5a8b0)

We have been tasked to also find the full path for the file Pier.jpg. We can utilize .lnk files to help us identify when files have been accessed, and where they are stored. In the ‘Recent Documents’ section, we can find the Pier.lnk file, which is used to represent Pier.jpg. We now have the file path.

![image](https://github.com/CristianFernandez123/Disk-Analysis-Lab/assets/161634608/de7852c7-6a7e-4c42-b4b9-8ebfdf0d14b0)

We have also been tasked to find what time the OS account was accessed. In the ‘OS Accounts’ section, we can see every local user that is on this computer. At the bottom we can see the Administrator account, giving us the time it was last accessed.

![image](https://github.com/CristianFernandez123/Disk-Analysis-Lab/assets/161634608/5e3a8370-1bb6-436c-b662-65b4effeb14c)
