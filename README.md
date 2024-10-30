<h1>Linux File Permissions</h1>

<h2>Description</h2>

#### Overview
The research team at my organization needed to update the file permissions for specific files and directories within the projects directory. The current permissions did not reflect the appropriate level of authorization, which is crucial for maintaining system security.

#### Tasks Completed

1. **Check File and Directory Details**:
   - Reviewed existing file and directory permissions to identify inconsistencies.

2. **Change File Permissions**:
   - Removed write access for "other" users from the file `project_k.txt`, as the organization determined that no external users should have write permissions.

3. **Modify Permissions on Hidden File**:
   - Adjusted permissions for the archived file `project_x.txt`, ensuring that only the user and group had read access while preventing any write access.

4. **Change Directory Permissions**:
   - Restricted access to the `drafts` directory so that only the user `researcher2` had execute permissions, ensuring that no other users could access this directory or its contents.

#### Outcome
These updates successfully aligned the file and directory permissions with organizational security policies, enhancing overall system security and protecting sensitive research data.


<br />


<h2>Languages and Utilities Used</h2>

- <b>Linux</b> 

<h2>Environments Used </h2>

- <b>Quick Lab</b>
- <b>Google Cybersecurity Program</b>

<h2>Program walk-through:</h2>

<p align="center">
Used Linux commands to determine the existing permissions set for a specific directory in the file system and change file permission on project_k.txt:  <br/>
<img src="https://imgur.com/RzUlHlo.png" height="80%" width="80%" alt="Linux File Permissions"/>
<br />
<br />
Used Linux commands to change the permissions on hidden file project_x.txt:  <br/>
<img src="https://imgur.com/4iYFN3N.png" height="80%" width="80%" alt="Linux File Permissions"/>
<br />
<br />
Used Linux commands to change the file directory permissions on project_x.txt:  <br/>
<img src="https://imgur.com/Gz3xQyA.png" height="80%" width="80%" alt="Linux File Permissions"/>
<br />
<br />

  
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
