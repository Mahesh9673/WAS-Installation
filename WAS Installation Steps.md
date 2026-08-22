# WAS-Installation
WAS Installation






WAS Installtion :-


Step 1:Copy Binaries for IM , Java & Websphere  at below path:
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++


Installation Binaries:
------------------------

[appadmin@SAMUATAPP2 ~]$ cd /Middleware14c/essentials/
automate/ IM/       IM_1.10/  JAVA8/
[appadmin@SAMUATAPP2 ~]$ cd /Middleware14c/essentials/IM
[appadmin@SAMUATAPP2 IM]$
[appadmin@SAMUATAPP2 IM]$ ls -lrt
total 660
-rwxr-xr-x  1 appadmin appadmin 80385 Nov 23  2016 userinstc
-rwxr-xr-x  1 appadmin appadmin 80385 Nov 23  2016 userinst
-rwxr-xr-x  1 appadmin appadmin 80385 Nov 23  2016 installc
-rwxr-xr-x  1 appadmin appadmin 80385 Nov 23  2016 install
-rwxr-xr-x  1 appadmin appadmin 80385 Nov 23  2016 groupinstc
-rwxr-xr-x  1 appadmin appadmin 80385 Nov 23  2016 groupinst
-rwxr-xr-x  1 appadmin appadmin  9909 May 22  2024 readme.html
drwxr-xr-x 10 appadmin appadmin 73728 Nov 18  2024 plugins
drwxr-xr-x  2 appadmin appadmin  4096 Nov 18  2024 Offerings
drwxr-xr-x  3 appadmin appadmin  4096 Nov 18  2024 jre_11.0.23.20240702
-rwxr-xr-x  1 appadmin appadmin   367 Nov 18  2024 user-silent-install.ini
-rwxr-xr-x  1 appadmin appadmin   313 Nov 18  2024 userinst.ini
-rwxr-xr-x  1 appadmin appadmin   358 Nov 18  2024 userinstc.ini
drwxr-xr-x  2 appadmin appadmin  4096 Nov 18  2024 tools
-rwxr-xr-x  1 appadmin appadmin   360 Nov 18  2024 silent-install.ini
-rwxr-xr-x  1 appadmin appadmin 10718 Nov 18  2024 repository.xml
-rwxr-xr-x  1 appadmin appadmin   278 Nov 18  2024 repository.config
drwxr-xr-x  2 appadmin appadmin  4096 Nov 18  2024 native
drwxr-xr-x  2 appadmin appadmin  4096 Nov 18  2024 license
-rwxr-xr-x  1 appadmin appadmin   266 Nov 18  2024 install.xml
-rwxr-xr-x  1 appadmin appadmin   309 Nov 18  2024 install.ini
-rwxr-xr-x  1 appadmin appadmin   354 Nov 18  2024 installc.ini
-rwxr-xr-x  1 appadmin appadmin   311 Nov 18  2024 groupinst.ini
-rwxr-xr-x  1 appadmin appadmin   356 Nov 18  2024 groupinstc.ini
drwxr-xr-x 13 appadmin appadmin  4096 Nov 18  2024 documentation
-rwxr-xr-x  1 appadmin appadmin  4642 Nov 18  2024 con-disk-set-inst.sh
drwxr-xr-x  2 appadmin appadmin  4096 Jul 12 18:38 META-INF
drwxr-xr-x  3 appadmin appadmin  4096 Aug  6 20:37 p2
drwxr-xr-x  6 appadmin appadmin  4096 Aug  6 20:37 configuration
[appadmin@SAMUATAPP2 IM]$



WAS Binaries(Base Version 9.0.5):
------------------------------------
[appadmin@SAMUATAPP2 ~]$ cd /Middleware14c/essentials/automate/WASBase/
[appadmin@SAMUATAPP2 WASBase]$
[appadmin@SAMUATAPP2 WASBase]$ ls -lrt
total 464
-rw-r--r--  1 appadmin appadmin    292 Sep 10  2019 Copyright.txt
-rw-r--r--  1 appadmin appadmin  14602 Sep 10  2019 repository.xml
-rw-r--r--  1 appadmin appadmin     74 Sep 10  2019 repository.config
drwxr-xr-x  2 appadmin appadmin   4096 Sep 10  2019 plugins
drwxr-xr-x  2 appadmin appadmin  57344 Sep 10  2019 native
drwxr-xr-x  2 appadmin appadmin   4096 Sep 10  2019 lafiles
drwxr-xr-x 11 appadmin appadmin   4096 Sep 10  2019 readme
drwxr-xr-x  2 appadmin appadmin   4096 Aug  6 19:39 Offerings
drwxr-xr-x  3 appadmin appadmin   4096 Aug  6 19:39 atoc
drwxr-xr-x  2 appadmin appadmin 364544 Aug  6 19:39 files
-rwxr-xr-x  1 appadmin appadmin      0 Aug  6 20:43 was.repo.90501.nd.zip
[appadmin@SAMUATAPP2 WASBase]$
[appadmin@SAMUATAPP2 WASBase]$ pwd
/Middleware14c/essentials/automate/WASBase
[appadmin@SAMUATAPP2 WASBase]$

Java Binaries:
----------------

[appadmin@SAMUATAPP2 ~]$
[appadmin@SAMUATAPP2 ~]$ cd /Middleware14c/essentials/JAVA8/
[appadmin@SAMUATAPP2 JAVA8]$ ls -lrt
total 40
-rwxr-xr-x 1 appadmin appadmin    74 Apr 22  2019 repository.config
drwxr-xr-x 3 appadmin appadmin  4096 Apr 22  2019 atoc
drwxr-xr-x 2 appadmin appadmin  4096 Apr 22  2019 native
drwxr-xr-x 2 appadmin appadmin  4096 Apr 22  2019 Offerings
drwxr-xr-x 2 appadmin appadmin  4096 Apr 22  2019 ShareableEntities
-rwxr-xr-x 1 appadmin appadmin 13227 Apr 22  2019 repository.xml
drwxr-xr-x 2 appadmin appadmin  4096 Jul 23 15:31 files
-rwxr-xr-x 1 appadmin appadmin     0 Aug  6 20:44 sdk-8.0-5.35-all-prt1-installmgr.zip
-rwxr-xr-x 1 appadmin appadmin     0 Aug  6 20:44 sdk-8.0-5.35-all-prt2-installmgr.zip
-rwxr-xr-x 1 appadmin appadmin     0 Aug  6 20:44 sdk-8.0-5.35-all-prt3-installmgr.zip
[appadmin@SAMUATAPP2 JAVA8]$ pwd
/Middleware14c/essentials/JAVA8
[appadmin@SAMUATAPP2 JAVA8]$


Step 2: Install IM(Installation Manager)
++++++++++++++++++++++++++++++++++++++++++++

[appadmin@SAMUATAPP2 ]$cd /Middleware14c/essentials/IM
[appadmin@SAMUATAPP2 IM]$ pwd
/Middleware14c/essentials/IM
[appadmin@SAMUATAPP2 IM]$ ./userinstc -installationDirectory /Middleware14c/IBM/InstallationManager -acceptLicense -sP
                 25%                50%                75%                100%
------------------|------------------|------------------|------------------|
............................................................................
Installed com.ibm.cic.agent_1.10.1000.20241118_1329 to the /Middleware14c/IBM/InstallationManager/eclipse directory.
[appadmin@SAMUATAPP2 IM]$


Step 3 : ListPackages for(JAva & WAS)
+++++++++++++++++++++++++++++++++++++++++++++++++++++

[appadmin@SAMUATAPP2 ~]$
[appadmin@SAMUATAPP2 ~]$ cd /Middleware14c/IBM/InstallationManager/eclipse/tools/
[appadmin@SAMUATAPP2 tools]$
[appadmin@SAMUATAPP2 tools]$
[appadmin@SAMUATAPP2 tools]$ ./imcl listAvailablePackages -repositories /Middleware14c/essentials/automate/WASBase/
com.ibm.websphere.ND.v90_9.0.5001.20190828_0616
[appadmin@SAMUATAPP2 tools]$
[appadmin@SAMUATAPP2 tools]$
[appadmin@SAMUATAPP2 tools]$ ./imcl listAvailablePackages -repositories /Middleware14c/essentials/JAVA8/
com.ibm.java.jdk.v8_8.0.5035.20190422_0948
[appadmin@SAMUATAPP2 tools]$
[appadmin@SAMUATAPP2 tools]$
[appadmin@SAMUATAPP2 tools]$
[appadmin@SAMUATAPP2 tools]$


Step 4 : Install WAS 
++++++++++++++++++++++++++++++++++++++++++++++++++++

[appadmin@SAMUATAPP2 tools]$
[appadmin@SAMUATAPP2 tools]$
[appadmin@SAMUATAPP2 tools]$ ./imcl install com.ibm.websphere.ND.v90_9.0.5001.20190828_0616 com.ibm.java.jdk.v8_8.0.5035.20190422_0948  -repositories /Middleware14c/essentials/automate/WASBase/,/Middleware14c/essentials/JAVA8/ -installationDirectory /Middleware14c/IBM/WebSphere/AppServer -acceptLicense -sP
                 25%                50%                75%                100%
------------------|------------------|------------------|------------------|
............................................................................
Installed com.ibm.websphere.ND.v90_9.0.5001.20190828_0616 to the /Middleware14c/IBM/WebSphere/AppServer directory.
Installed com.ibm.java.jdk.v8_8.0.5035.20190422_0948 to the /Middleware14c/IBM/WebSphere/AppServer directory.
[appadmin@SAMUATAPP2 tools]$
[appadmin@SAMUATAPP2 tools]$
[appadmin@SAMUATAPP2 tools]$


Step 5: Create Profiles(DMGR & Node):-
++++++++++++++++++++++++++++++++++++++++++++++++++++++

           [Note :- Below are the templates , which we are going to use while profile creation:]

[appadmin@SAMUATAPP2 ~]$ ls -lrt /Middleware14c/IBM/WebSphere/AppServer/profileTemplates/
total 24
drwxr-xr-x 5 appadmin appadmin 4096 Aug  7 13:01 cell
drwxr-xr-x 5 appadmin appadmin 4096 Aug  7 13:01 dmgr
drwxr-xr-x 8 appadmin appadmin 4096 Aug  7 13:01 managed
drwxr-xr-x 8 appadmin appadmin 4096 Aug  7 13:01 secureproxy
drwxr-xr-x 8 appadmin appadmin 4096 Aug  7 13:01 management
drwxr-xr-x 8 appadmin appadmin 4096 Aug  7 13:01 default
[appadmin@SAMUATAPP2 ~]$
[appadmin@SAMUATAPP2 ~]$


DMGR(Profile Creation):
---------------------------

[appadmin@SAMUATAPP2 ~]$
[appadmin@SAMUATAPP2 ~]$
[appadmin@SAMUATAPP2 ~]$
[appadmin@SAMUATAPP2 ~]$ /Middleware14c/IBM/WebSphere/AppServer/bin/manageprofiles.sh -create -profileName DMGR01 -profilePath /Middleware14c/IBM/WebSphere/AppServer/profiles/DMGR01 -templatePath /Middleware14c/IBM/WebSphere/AppServer/profileTemplates/dmgr -nodeName Dmgr01Node -cellName AppSvr01 -hostname SAMUATAPP2 -serverType DEPLOYMENT_MANAGER -enableAdminSecurity true -adminUserName wasadmin9 -adminPassword Mahesh123 -startingPort 7001
CWMBU0002I: The deployment manager profile template has been deprecated and replaced by the management profile template with a deployment manager server.
INSTCONFSUCCESS: Success: Profile DMGR01 now exists. Please consult /Middleware14c/IBM/WebSphere/AppServer/profiles/DMGR01/logs/AboutThisProfile.txt for more information about this profile.
[appadmin@SAMUATAPP2 ~]$
[appadmin@SAMUATAPP2 ~]$

                  [Note :- 
                           templatePath :- to create DMGR profile need to provide dmgr template.
                           nodeName , cellName ,hostname :- Provide values Otherwise default values it will take(CN....)
                           serverType :- if u already provide dmgr template then this is optional.(No use provide or don't provide)
--------------------------------------------------------------------------------------------
                           enableAdminSecurity:- (This parameter is provided to login console with vaild username & password) / if u have not provided direct u can able to access (No login page)

If We want enable the login then also we can able to do.--->follow below steps to enable 

Step 1) Security--------->Global security---->click on *Enable administrative security  
          then  under--->User account repository (select Federated repositories) ---->Click Configure

Step 2) Create wasadmin user
            Users and groups----->Manage Users---->create--->
                                                            User ID: wasadmin
                                                            First Name: WebSphere
                                                            Last Name: Administrator
                                                            Password: <set password>
                                                            Confirm: <set password>

                                                      ------then click Create/OK

 
Step 3: Give wasadmin user Administrator Privileges'
           Users and Groups -------->Administrative user roles------>select 'wasadmin' assign 'Administrator'

Step 4) Apply and save
         Security ------>Global Security (Make sure *Enable administrative security )
          Click---->Apply ------>Save

Step 5: Restart DMGR (Test login)

------------------------------------------------------------------------------------------------------------------------------------

Validate :
-----------
[appadmin@SAMUATAPP2 ~]$ cat /Middleware14c/IBM/WebSphere/AppServer/profiles/DMGR01/logs/AboutThisProfile.txt
Application server environment to create: Management
Location: /Middleware14c/IBM/WebSphere/AppServer/profiles/DMGR01
Disk space required: 30 MB
Profile name: DMGR01
Make this profile the default: True
Node name: Dmgr01Node
Cell name: AppSvr01
Host name: CN.sbi.co.in
Enable administrative security (recommended): True
Administrative console port: 7001
Administrative console secure port: 7002
Management bootstrap port: 7003
Management SOAP connector port: 7004
Run Management as a service: False
[appadmin@SAMUATAPP2 ~]$
[appadmin@SAMUATAPP2 ~]$
[appadmin@SAMUATAPP2 ~]$



Node(Profile Creation):
---------------------------

[appadmin@SAMUATAPP2 profiles]$ /Middleware14c/IBM/WebSphere/AppServer/bin/manageprofiles.sh -create -profileName AppSrv01 -profilePath /Middleware14c/IBM/WebSphere/AppServer/profiles/AppSrv01 -templatePath /Middleware14c/IBM/WebSphere/AppServer/profileTemplates/managed -nodeName AppSvr01Node -hostname SAMUATAPP2
INSTCONFSUCCESS: Success: Profile AppSrv01 now exists. Please consult /Middleware14c/IBM/WebSphere/AppServer/profiles/AppSrv01/logs/AboutThisProfile.txt for more information about this profile.
[appadmin@SAMUATAPP2 profiles]$
[appadmin@SAMUATAPP2 profiles]$
[appadmin@SAMUATAPP2 ~]$
[appadmin@SAMUATAPP2 ~]$


              [Note :- for Node profile creation no need to provide cell name (after federaion/sync this node will automatically comes under DMGR cell)
                       Don't provide Cell name &  node profile name same]




Add/Federate Node:
-----------------------------------------------------------------------------------------------------
[appadmin@SAMUATAPP2 profiles]$
[appadmin@SAMUATAPP2 profiles]$ cd /Middleware14c/IBM/WebSphere/AppServer/profiles/AppSrv01/bin/
[appadmin@SAMUATAPP2 bin]$ ./addNode.sh SAMUATAPP2 7004
ADMU0116I: Tool information is being logged in file
           /Middleware14c/IBM/WebSphere/AppServer/profiles/AppSrv01/logs/addNode.log
ADMU0128I: Starting tool with the AppSrv01 profile
CWPKI0308I: Adding signer alias "CN=CN.sbi.co.in, OU=Root Certif" to local
           keystore "ClientDefaultTrustStore" with the following SHA digest:
           9C:95:66:9F:DD:54:0E:ED:32:76:62:0F:54:A7:C4:68:96:AF:A8:B0
Realm/Cell Name: <default>
Username: wasadmin9
Password:                                                                                                                                                                                                                                    CWPKI0309I: All signers from remote keystore already exist in local keystore.
ADMU0001I: Begin federation of node AppSvr01Node with Deployment Manager at
           SAMUATAPP2:7004.
ADMU0009I: Successfully connected to Deployment Manager Server: SAMUATAPP2:7004
ADMU0507I: No servers found in configuration under:
           /Middleware14c/IBM/WebSphere/AppServer/profiles/AppSrv01/config/cells/CNNode01Cell/nodes/AppSvr01Node/servers
ADMU2010I: Stopping all server processes for node AppSvr01Node
ADMU0024I: Deleting the old backup directory.
ADMU0015I: Backing up the original cell repository.
ADMU0012I: Creating Node Agent configuration for node: AppSvr01Node
ADMU0014I: Adding node AppSvr01Node configuration to cell: AppSvr01
ADMU0016I: Synchronizing configuration between node and cell.
ADMU0018I: Launching Node Agent process for node: AppSvr01Node
ADMU0020I: Reading configuration for Node Agent process: nodeagent
ADMU0022I: Node Agent launched. Waiting for initialization status.
ADMU0030I: Node Agent initialization completed successfully. Process id is:
           968346


ADMU0300I: The node AppSvr01Node was successfully added to the AppSvr01 cell.


ADMU0306I: Note:
ADMU0302I: Any cell-level documents from the standalone AppSvr01 configuration
           have not been migrated to the new cell.
ADMU0307I: You might want to:
ADMU0303I: Update the configuration on the AppSvr01 Deployment Manager with
           values from the old cell-level documents.


ADMU0306I: Note:
ADMU0304I: Because -includeapps was not specified, applications installed on
           the standalone node were not installed on the new cell.
ADMU0307I: You might want to:
ADMU0305I: Install applications onto the AppSvr01 cell using wsadmin $AdminApp
           or the Administrative Console.


ADMU0003I: Node AppSvr01Node has been successfully federated.
[appadmin@SAMUATAPP2 bin]$
[appadmin@SAMUATAPP2 bin]$


       [Note: After this node agent will start. stop node agent to run below command syncNode.sh]


Start Sync Node :
----------------------

[appadmin@SAMUATAPP2 bin]$ ./syncNode.sh SAMUATAPP2 7004
ADMU0116I: Tool information is being logged in file
           /Middleware14c/IBM/WebSphere/AppServer/profiles/AppSrv01/logs/syncNode.log
ADMU0128I: Starting tool with the AppSrv01 profile
Realm/Cell Name: <default>
Username: wasadmin9
Password:                                                                                                                                                                                                                                    ADMU0401I: Begin syncNode operation for node AppSvr01Node with Deployment
           Manager SAMUATAPP2: 7004
ADMU0016I: Synchronizing configuration between node and cell.
ADMU0402I: The configuration for node AppSvr01Node has been synchronized with
           Deployment Manager SAMUATAPP2: 7004
[appadmin@SAMUATAPP2 bin]$
[appadmin@SAMUATAPP2 bin]$



Login Console:
-------------------------

https://10.191.157.15:7002/ibm/console







*********************************************************************************************************************************************************************************************************************************

Uninstall WebSphere:-
====================

1)Delete Profiles:
---------------------
List Profiles:

cd /Middleware14c/IBM/WebSphere/AppServer/bin

./manageprofiles.sh -listProfiles

./manageprofiles.sh -delete -profileName  Dmgr01
./manageprofiles.sh -listProfiles
./manageprofiles.sh -delete -profileName Appsvr01


./manageprofiles.sh -validateRegistry
./manageprofiles.sh -validateAndUpdateRegistry
./manageprofiles.sh -validateRegistry

*******************************************************************************************************************************************

Delete WebSphere Product(Websphere,java & IM Packages):-
------------------------------------------------------

(Note :- Delete Java & Websphere package same time)

[appadmin@SAMUATAPP2 tools]$ sudo /Middleware14c/IBM/Installation_Manager/eclipse/tools/imcl listInstalledPackages
com.ibm.cic.agent_1.10.1000.20241118_1329
com.ibm.java.jdk.v8_8.0.5035.20190422_0948
com.ibm.websphere.ND.v90_9.0.5001.20190828_0616


[appadmin@SAMUATAPP2 tools]$ sudo /Middleware14c/IBM/Installation_Manager/eclipse/tools/imcl uninstall com.ibm.java.jdk.v8_8.0.5035.20190422_0948 com.ibm.websphere.ND.v90_9.0.5001.20190828_0616
Uninstalled com.ibm.java.jdk.v8_8.0.5035.20190422_0948 from the /Middleware14c/IBM/WebSphere/AppServer directory.
Uninstalled com.ibm.websphere.ND.v90_9.0.5001.20190828_0616 from the /Middleware14c/IBM/WebSphere/AppServer directory.
[appadmin@SAMUATAPP2 tools]$


Uninstall IM:
--------------
[appadmin@SAMUATAPP2 tools]$
[appadmin@SAMUATAPP2 tools]$ sudo /Middleware14c/IBM/Installation_Manager/eclipse/tools/imcl listInstalledPackages
com.ibm.cic.agent_1.10.1000.20241118_1329
[appadmin@SAMUATAPP2 tools]$
[appadmin@SAMUATAPP2 tools]$
[appadmin@SAMUATAPP2 tools]$ sudo /Middleware14c/IBM/Installation_Manager/eclipse/tools/imcl uninstall com.ibm.cic.agent_1.10.1000.20241118_1329
Uninstalled com.ibm.cic.agent_1.10.1000.20241118_1329 from the /Middleware14c/IBM/Installation_Manager/eclipse directory.
Imcl:
/tmp/cleanup10436772468355101653.tmp/cleanup11297823457636280043.sh
/Middleware14c/IBM/Installation_Manager
/root/var/ibm/InstallationManager
[appadmin@SAMUATAPP2 tools]$
**********************************************************************************************************************************************************+


