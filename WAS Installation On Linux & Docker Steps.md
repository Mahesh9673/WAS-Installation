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
**********************************************************************************************************************************************************+


**Configuration:**




**********************************************************************************************************************************************************+
SSL Configurations:-

Keystore : WebSphere/server personal certificate + private key
TrustStore: CA Certifcates that WebSphere trusts.(Root,Inter,third-party servers CA)



Security------>SSL certificate and key management---------->Key stores and certificates
	
CellDefaultKeyStore---> Personal Certificate----import---->
                                    Click on * Key store file
                                                   Key file name: Provide absolute path for keystore 
                                                   Type : jks/PKCS12
                                                   Key file password: password
                                                   And Click on >> Get Key File ALiases
                                                   (Then Alias we will see)--->Apply--->Next--->Finish--->Review------->save--->OK.

CellDefaultTrustStore---->signer certificate---Add--->
                                              Alias : Provide Alias Name
                                              FileName: Provide absolute path for keystore 
                                              --->Apply--->Next--->Finish--->Review------->save--->OK.



**Note:**

If We set the none (CellDefaultSSLSettings) for inbound/outbound setting [Security --->SSL certificate and key management---->Manage endpoint security configurations]

Then DMGR/JVM will take certificate from [Security --->SSL certificate and key management---->Key stores and certificates------------->CellDefaultKeyStore----->Personal certificates(it considers 1st certificate)

If we want to configure certificate individual level for (DMGR,node,cluster,JVM.nodegaent) then we can configure using below path:
                                          ** [Security --->SSL certificate and key management---->Manage endpoint security configurations]  **



(In our current environment we have kept none for CellDefaultSSLSettings in [Security --->SSL certificate and key management---->Manage endpoint security configurations] for inbound & outbound.

        And Also kept none for [  Security------>SSL certificate and key management----------> SSL configurations---------->CellDefaultSSLSettings ]

So All components will use automatically from  [Security-------->SSL certificate and key management------> Key stores and certificates-------> CellDefaultKeyStore-------> Personal certificates] that to 1st certificate.






**********************************************************************************************************************************************************+

JDBC Configuration:



Login to Console

Resources ---------->JDBC------------->Data Sources.

**Before Data Source we need to configure JDBC providers**

**Step1 : JDBC Driver**
make sure ORacle jdbc driver present on WAS server.
Download the version corresponding to the Java version running on your WAS instance (e.g., ojdbc8.jar for Java 8, or ojdbc11.jar for Java 11/17).

[appadmin@SAMUATAPP2 ~]$ find /Middleware14c/ -name ojdbc*
/Middleware14c/ojdbc8.jar
[appadmin@SAMUATAPP2 ~]$


**Step 2 : Create JDBC Provider**
Resources ---------->JDBC------------->JDBC Providers (select an appropriate scope e.g cell/Cluster)
OR node/server scope depending on your requirement.

Click--->New 
         For Oracle , select
                           Database Type: Oracle
                           Provider Type: Oracle JDBC Driver
                           Implementation Type: Connection Pool data source / ( XA DataSource)

If the Application performs(insert,update,commit)    then  use **Connection Pool data source**                    
If One transaction involves two resources :-                  -------->Oracle DB
                                                Transaction---|
                                                               ---------- MQ  (And other resources)

                              Then application might use (insert, send message to MQ, commit) thne use ** XA DataSource**
  Note : If something fails before commit, then transaction manager can rollback txn.)


                                                                             
Then Configure JDBC driver class path (ojdbc.jar path)
                     /Middleware14c/ojdbc8.jar

                     Click---Apply--->Next--->Finish--->Review------->save--->OK.




**Step 3: Create JAAS / j2C Authentication Alias:**
Security--->Global Security------>Java Authentication and Authorization Service-----> J2C authentication data----New-->
                                                   Alias: OracleDBAlias
                                                   User ID: {DB UserName}
                                                   Password: {Above User Password}

                               ----->Apply--->Review--save-->OK                                                                 



**Step 4: Create Data Source**

Resources ---------->JDBC------------->Data Sources--->New
                                   Data source name: APPDB
                                   JNDI name: jndi/APPDB
                                   ------>Next
                                            Select an existing JDBC provider --(Oracle JDBC Driver)
                                    ---------->Next
                                                  url: jdbc:oracle:thin:@//10.189.202.188:1522/QUICKUAT
                                    ---------->Next (select below security alias)

                 Security Alias :-
                                   1)Component-managed authentication alias:- Application provides the credentials when obtaining the connection.
                                   2)Mapping-configuration alias:- Used to map an application's resource/security identity to the configured authntication data.
                                   3)Container-managed authentication alias:- Websphere provides the DB credentials from j2c alias when creating the connection.
                                   4)Authentication alias for XA recovery (If u selected XA D.S):- used to recover a XA transaction after failure/restart.


                                   ---------->Next---------->Finish--->Review-->Save.

                                   


**********************************************************************************************************************************************************+
MQ Configuration:




**********************************************************************************************************************************************************+
JVM & DB tunning parameters :-































==================================================================
WebSpeher Installation Using Docker & Container



WebSpeher Installation Using Docker & Container:

Step 1:]  Pull the linux image from Docker HUB.

              docker pull registry.access.redhat.com/ubi8/ubi:latest
			  

Step 2:] Create & Run Container
               docker run -d  --name websphere-server -p 9043:9043  registry.access.redhat.com/ubi8/ubi:latest
       using above it is stopping immediately.
Run :   docker run -d   --name websphere-server   -p 9043:9043   registry.access.redhat.com/ubi8/ubi:latest   sleep infinity

Step 3:] Check Container is running . Go inside it. (docker ps -a)
            docker exec -it websphere-server /bin/bash
       Using above i cant able to access conainer prompt.
  
  I used : MSYS_NO_PATHCONV=1 docker exec -it websphere-server /bin/bash	   

Step 4:] Check OS

             cat /etc/os-release
			 
			 Create wasadmin user & provide sudo access to it & create directories.
			 
			            groupadd wasadmin
						useradd -g wasadmin -m -s /bin/bash wasadmin
						passwd wasadmin   (Set Password)
						
						mkdir -p /opt/IBM/InstallationManager
                        mkdir -p /opt/IBM/WebSphere
						mkdir -p /opt/IBM/Binaries/
						
						chown -R wasadmin:wasadmin /opt/IBM
						
Step 4:] Download Installation Manager Package on Local & copy it to Conainer.

          Download from IBM site.
Copy : docker cp "C:\Users\SBI\Downloads\agent.installer.linux.gtk.x86_64_1.10.1004.20260506_0701.zip" websphere-server:/opt/IBM/Binaries/


Step 5:] Install Installation Manager	
              cd /opt/IBM/Binaries/
               unzip agent.installer.linux.gtk.x86_64_1.10.1004.20260506_0701.zip	
         
               ./installc -acceptLicense -showProgress   -installationDirectory /opt/IBM/InstallationManager


[root@5abdfe59293c Binaries]# pwd
/opt/IBM/Binaries
[root@5abdfe59293c Binaries]# unzip agent.installer.linux.gtk.x86_64_1.10.1004.20260506_0701.zip


[root@5abdfe59293c Binaries]# pwd
/opt/IBM/Binaries
[root@5abdfe59293c Binaries]# ./installc -acceptLicense -showProgress   -installationDirectory /opt/IBM/InstallationManager
                 25%                50%                75%                100%
------------------|------------------|------------------|------------------|
............................................................................
Installed com.ibm.cic.agent_1.10.1004.20260506_0701 to the /opt/IBM/InstallationManager/eclipse directory.
[root@5abdfe59293c Binaries]# pwd
/opt/IBM/Binaries
[root@5abdfe59293c Binaries]#

[root@5abdfe59293c Binaries]# /opt/IBM/InstallationManager/eclipse/tools/imcl -version
Installation Manager (installed)
Version: 1.10.1.4
Internal Version: 1.10.1004.20260506_0701
Architecture: 64-bit
[root@5abdfe59293c Binaries]#


ListAvailbalePackages:

sudo /opt/IBM/InstallationManager/eclipse/tools/imcl listAvailablePackages -repositories https://www.ibm.com/software/repositorymanager/com.ibm.websphere.ND.v90 -long -prompt

JAVA:
sudo /opt/IBM/InstallationManager/eclipse/tools/imcl listAvailablePackages -repositories https://www.ibm.com/software/repositorymanager/com.ibm.java.jdk.v8 -long -prompt

Install:

sudo /opt/IBM/InstallationManager/eclipse/tools/imcl install com.ibm.java.jdk.v8_8.0.8071.20260813_0837 com.ibm.websphere.ND.v90_9.0.5029.20260827_1654 -repositories https://www.ibm.com/software/repositorymanager/com.ibm.java.jdk.v8,https://www.ibm.com/software/repositorymanager/com.ibm.websphere.ND.v90 -installationDirectory /opt/IBM/WebSphere/AppServer -acceptLicense -showProgress -prompt

DMGR(Profile Creation):

/opt/IBM/WebSphere/AppServer/bin/manageprofiles.sh -create -profileName DMGR01 -profilePath /opt/IBM/WebSphere/AppServer/profiles/DMGR01 -templatePath /opt/IBM/WebSphere/AppServer/profileTemplates/dmgr -nodeName Dmgr01Node -cellName AppSvr01 -hostname 5abdfe59293c -serverType DEPLOYMENT_MANAGER -enableAdminSecurity true -adminUserName wasadmin9 -adminPassword Mahesh123 -startingPort 9041

CWMBU0002I: The deployment manager profile template has been deprecated and replaced by the management profile template with a deployment manager server.
INSTCONFPARTIALSUCCESS: The profile now exists, but errors occurred. For more information, consult /opt/IBM/WebSphere/AppServer/logs/manageprofiles/DMGR01_create.log.
[wasadmin@5abdfe59293c ~]$



Node(Profile Creation):

/opt/IBM/WebSphere/AppServer/bin/manageprofiles.sh -create -profileName AppSrv01 -profilePath  /opt/IBM/WebSphere/AppServer/profiles/AppSrv01 -templatePath /opt/IBM/WebSphere/AppServer/profileTemplates/managed -nodeName AppSvr01Node -hostname 5abdfe59293c

INSTCONFPARTIALSUCCESS: The profile now exists, but errors occurred. For more information, consult /opt/IBM/WebSphere/AppServer/logs/manageprofiles/AppSrv01_create.log.
[wasadmin@5abdfe59293c ~]$


One issue is there now:

I have configured DMGR console port 9041(nonSSL) & 9042(SSL) But ,docker  port Mapping i already done on 9043 . Due to this i am not able access the console.

Now i have two choices.
                       1)Delete existing DMGR profile & create new DMGR profile again & mapp port as 9043 .
                       2) Create New image from ur container(DMGR Installed). & then create new conatiner with new images & mapp DMGR ports to it.


      I am going with 2nd option:
                    i) Create new image from conatiner.(All Installations will come)
								docker commit websphere-server websphere-learning:latest
					ii)Verify:
					            docker images | grep websphere-learning
                    iii)Stop the old container:
					             docker stop websphere-server
					iv)Start a new container with the correct ports:
                                 docker run -d   --name websphere-server-new   -p 9041:9041   -p 9042:9042   -p 9043:9043   -p 9044:9044   websphere-learning:latest   sleep infinity
                    v)then go to new container 
                               MSYS_NO_PATHCONV=1 docker exec -it websphere-server-new /bin/bash
                    vi) Start DMGR:
					            /opt/IBM/WebSphere/AppServer/profiles/DMGR01/bin/startManager.sh
								
								It thows error : UnknownHostException: 5abdfe59293c
                            It will fail beacuse while profile creation we have given the hostname . this current conainer is reffering that old container.
                    vii)  just add below entry in /etc/hosts & verify. (Add old container id & ip)
                          			172.17.0.2 5abdfe59293c
						verify : getent hosts 5abdfe59293c  ---------(it returns. If not returns anything need to check.)
					
					viii) Now start DMGR. it will start successful now.
					                /opt/IBM/WebSphere/AppServer/profiles/DMGR01/bin/startManager.sh
						

Now Go to chrome & type  " https://localhost:9042/ibm/console "  u are able to access WebSphere Console.

Note:  Now every time u need to use that old hostname. (addnode,syncnode etc.)

Add/Federate Node:



                       [wasadmin@c0579f7fd7ef bin]$ ./addNode.sh 5abdfe59293c 9044
                        ADMU0116I: Tool information is being logged in file
                                   /opt/IBM/WebSphere/AppServer/profiles/AppSrv01/logs/addNode.log
                        ADMU0128I: Starting tool with the AppSrv01 profile
                        Realm/Cell Name: <default>
                        Username: wasadmin9
                        Password:
                         CWPKI0309I: All signers from remote keystore already exist in local keystore.
                        ADMU0001I: Begin federation of node AppSvr01Node with Deployment Manager at
                                   5abdfe59293c:9044.
                        ADMU0009I: Successfully connected to Deployment Manager Server:
                                   5abdfe59293c:9044
                        ADMU0507I: No servers found in configuration under:
                                   /opt/IBM/WebSphere/AppServer/profiles/AppSrv01/config/cells/5abdfe59293cNode01Cell/nodes/AppSvr01Node/servers
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
                                   1052
                        
                        
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
                        [wasadmin@c0579f7fd7ef bin]$
                        

Start Sync Node :

After addnode.sh  Nodeagent will start .( we cant able to do sync Node If node agenet is up.)
Stop Node Agent & then run sync node:
                                        /opt/IBM/WebSphere/AppServer/profiles/AppSrv01/bin/stopNode.sh
										
										/opt/IBM/WebSphere/AppServer/profiles/AppSrv01/bin/syncNode.sh 5abdfe59293c 9044
										
										ADMU0116I: Tool information is being logged in file
                                                   /opt/IBM/WebSphere/AppServer/profiles/AppSrv01/logs/syncNode.log
                                        ADMU0128I: Starting tool with the AppSrv01 profile
                                        Realm/Cell Name: <default>
                                        Username: wasadmin9
                                        Password:
                                         ADMU0401I: Begin syncNode operation for node AppSvr01Node with Deployment
                                                   Manager 5abdfe59293c: 9044
                                        ADMU0016I: Synchronizing configuration between node and cell.
                                        ADMU0402I: The configuration for node AppSvr01Node has been synchronized with
                                                   Deployment Manager 5abdfe59293c: 9044


Now EveryTime is will ask password for sync Node,Start Node & Stop Node.

Password Less Configuration:
-------------------------------
                        cd  /opt/IBM/WebSphere/AppServer/profiles/AppSrv01/properties
						 
						 change below 2 properties file:
                         take backup before changing below files.
                         1)ipc.client.props                                                       2)soap.client.props 
                         
                         com.ibm.IPC.securityEnabled=false---->true                                   com.ibm.SOAP.securityEnabled=false---------true
                         com.ibm.IPC.loginUserid={username}                                           com.ibm.SOAP.loginUserid={username}   
                         com.ibm.IPC.loginPassword={password}                                         com.ibm.SOAP.loginPassword={password}
                         
			provide username & password in both files.
						 
EveryOne can see username & password form that file.

Encrypt the username & password using below commands:
-------------------------------------------------------
                        cd /opt/IBM/WebSphere/AppServer/profiles/AppSrv01/bin
                 ./PropFilePasswordEncoder.sh /opt/IBM/WebSphere/AppServer/profiles/AppSrv01/properties/ipc.client.props com.ibm.IPC.loginPassword -noBackup
                 ./PropFilePasswordEncoder.sh /opt/IBM/WebSphere/AppServer/profiles/AppSrv01/properties/soap.client.props com.ibm.SOAP.loginPassword -noBackup
      			


Same we can proceed fro DMGR profile Also:

Now It will not ask for password for any tasks(Stop DMGR,Stop Node,syncNode etc.)



											





