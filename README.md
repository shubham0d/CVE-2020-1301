# CVE-2020-1301
POC exploit for SMBLost vulnerability (CVE-2020-1301)

## Affected version
Refer here: https://portal.msrc.microsoft.com/en-US/security-guidance/advisory/CVE-2020-1301

## Steps to reproduce
* Make sure SMB/CIFF service feature is turned on target.
* SMB1 must be supported by target. Refer here: https://docs.microsoft.com/en-us/windows-server/storage/file-server/troubleshoot/detect-enable-and-disable-smbv1-v2-v3
* Target must have C:\ driver shared

## Running the exploit
`exploit.py -t <target> -u <username> -p <password>` 
<br/>
username and password are not required in case of target machine has no credentials set. 

## Outcome
Will cause BSOD (Blue screen of death)
<br/>
***Code execution comming soon.***

## Source and Credits
https://airbus-cyber-security.com/diving-into-the-smblost-vulnerability-cve-2020-1301/

## POC video
<a href="http://www.youtube.com/watch?feature=player_embedded&v=zVHsKPwtPo4" target="_blank"><img src="http://img.youtube.com/vi/zVHsKPwtPo4/0.jpg" 
alt="POC video" width="240" height="180" border="10" /></a>
