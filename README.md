<h1>File Explorer & Active Directory Users and Computers (ADUC) – Map And Share A Network Drive Using A Network Path in Active Directory Users and Computers (ADUC)</h1>


<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Description</h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
This project goes over how to map and share a network drive using File Explorer and Active Directory Users and Computers. We will use File Explorer to add users and/or groups who will have access to the mapped drive.  In Active Directory Users and Computers, we will use a Network Path to share the mapped drive and add it to users and/or groups computers. 
</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Utilities Used</h2>
  
<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
 - <b>File Explorer & Active Directory Users And Computers</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
⏹️ Environments Used </h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
- <b>Windows 10 & Windows Server 2016</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
<h2>
⏹️ Project Walk-Through:</h2>
 <br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: FILE EXPLORER STEPS</b></span>  
<br/><br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Open: File Explorer.  Right-Click: The folder you want to map.  Click: Properties.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/86dLOzJ.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/0k1KZrm.png" height="50%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/ZhNewXs.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Security tab (top).  To add users or groups: Click: Edit and them.  NOTE: Anyone that is listed in the Security tab will automatically get this Mapped Drive.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/3Gd6hSr.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/dqVt47X.png" height="50%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/eO8A65P.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>•	NOTE: ACTIVE DIRECTORY USERS AND COMPUTERS STEPS</b></span>  
<br/><br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Open: Active Directory Users and Computers.  Find the User  (OR)  Group you want to have access to the drive. Right-Click: The result.  Click: Properties (bottom).  Click: Profile tab (top).  <a href="https://github.com/RashadHagen/ADUC-Find-Computer-User-Contact-Group-Printer-Shared-Folder-Organizational-Unit-Common-Que" style="font-family: Arial, sans-serif; font-size: 16px; font-weight: bold;">How To Find A User In Active Directory Users  (OR)  Group.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/W8OfYmv.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/hLXJ1On.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/A0RdjeO.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/MNITuvA.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>In the Profile tab, look for the Home folder section (middle-bottom).  Click: Connect.  Select: What drive letter you want to use for the drive.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/KTkelV3.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/uwRhDUA.png" height="50%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/cZiyCRg.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>In the To box (to the right of the drive letter), Type: The Network Path AND after the Network Path type:  \%username% (ex: \\DCSERVER2016KIS\Personal\%username% ).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/dxPcPZm.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/FKcgS5C.png" height="50%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/75Llsv9.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>In the To box (to the right of the drive letter), Type: The Network Path AND after the Network Path type:  \%username% (ex: \\DCSERVER2016KIS\Personal\%username% ).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/dxPcPZm.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/FKcgS5C.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Apply.  Click: OK.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/3dvKQyy.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/vtf1SXo.png" height="50%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/UFq5gQi.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>In File Explorer: When you open the folder you used for the Network Path, you will see a folder named with the username.  NOTE: Have the Windows OS client that just got the mapped drive added sign-out and then sign-in to Windows OS to see the new mapped drive.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/WJOFz1a.png" height="50%" width="100%" /></td>
    <td><img src="https://imgur.com/rhpzUE7.png" height="50%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/DOgUEWC.png" height="50%" width="100%" /></td>
  </tr>
</table>

<br /><br />
