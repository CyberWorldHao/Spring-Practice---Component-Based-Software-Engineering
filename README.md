 ```                                                                                                             
      ABOOK       KCODAB    ODABOOK           ABO       OOKCODABOO      OOKCOD       DABOOK    BOOKCO   OOK    
    CODABOOKCO   OOKCODAB   CODABOOKC        ODABO      BOOKCODABOO    ABOOKCOD     CODABOOK   ABOOK    BOO    
   OKC   BOOKC  ABOO  ODAB  KCODABOOKC       CODAB      ABOOK   ABO   ODAB  KCOD   OKCO  BOOK   ABO    DA      
  BOO     BOOK  DAB    ODA  OKCO   OOKC     OKCODA        BOO   DAB   COD    KCO   OOK    BOO   DAB   CO       
  ABO          CODA    CODA  OKC   BOOK     OOK ODA       ABOOKCODA  OKCO    OKCO ABOO    ABOO  ODABOOK        
  DA           KCOD    KCOD  OOK    BOO    ABOOKCODA      DABOOKCODA OOKC    OOKC DABO    DABO  CODABOO        
  OD            KCO    OKC   BOO   DABO    DABOOKCOD      ODABOOKCODA OOK    BOO   DAB    ODA   KCODABO        
  CO       OD   OKC    OOK  DABO  CODAB   CODA   KCOD     COD    KCOD BOO    ABO   ODA    COD   OKC  ABO       
  KCO     KCO   OOKC  ABOO CODABOOKCODA   KCO     KCO     KCODABOOKCO ABOO  ODAB   CODA  OKCO   OOK  DAB       
   KCODABOOKC    OOKCODAB  KCODABOOKCO  BOOKCO   OOKCOD BOOKCODABOOK   ABOOKCOD     CODABOOK   ABOOK ODABOOK   
    KCODABO       OOKCOD   OKCODABOO    ABOOKC   BOOKCO ABOOKCODABO     ABOOKC       CODABO   ODABOO CODABOO   
```

*********************************************************************************************
* COMPANION CODE FOR THE BOOK “Component Oriented Development & Assembly – CODA Using Java” *
* AUTHORS – Piram Manickam, Sangeetha S, Subrahmanya S V                                    *
* REFERENCE – http://www.codabook.com                                                       *
* CODE CONTRIBUTORS – Vishal Verma, Shikhar Johari, Soumya Bardhan, Rohit Jain,		    *
*                     Karthika Nair, Vibhuti Pithwa, Vaasavi Lakshmi                        *
********************************************************************************************* 


1. The zip file you downloaded contains this README file and the binaries for the section 3.4 of the book.

2. To execute the binary, unzip the contents of the zip file into a local folder on your machine, let us name this folder - 'AgeCalculator'. The folder would contain following files:

	- AgeCalculatorSpring.jar
	- AgeCalculatorSpringClient.jar
	- README.txt


Getting the required libraries:
-------------------------------

1. First create a folder - 'lib' inside the folder - 'AgeCalculator'.
 
2. You would need SPRING LIBRARIES to run the project. You can download the latest version of Spring binaries from their website - 'http://www.springsource.org/spring-framework'. Once the download is complete, extract the zip file to '/lib' folder. The lib folder should directly contain the JAR files, without any sub-folder.
                  
3. Secondly, you would need Apache Commons Logging library. You can download the latest version from Apache website - 'http://commons.apache.org/proper/commons-logging/download_logging.cgi'. Extract the downloaded zip archive to the '/lib' folder. Again, the lib folder should directly contain the JAR files.

4. Now, check to see that your folder has following structure:

        AgeCalculator --+-- AgeCalculatorSpring.jar
                        +-- AgeCalculatorSpringClient.jar
                        +-- lib -+
                                 |
                                 +-- All the Spring JARs
                                 +-- Apache Commons Library JARs.


Running the program
-------------------

1. The program can be run from your OS console window provided the Java Runtime Environment is installed and configured. 

2. From the command prompt, navigate to the folder - 'AgeCalculator'.

3. Run the following command to start execution of the program:

      java -cp ./*;lib/* agecalculatorspringclient.AgeCalculatorSpringClient

4. Use the Age Calculator program as guided.

*********************************************************************************************
* COMPANION CODE FOR THE BOOK “Component Oriented Development & Assembly – CODA Using Java” *
* AUTHORS – Piram Manickam, Sangeetha S, Subrahmanya S V                                    *
* REFERENCE – http://www.codabook.com                                                       *
* CODE CONTRIBUTORS – Vishal Verma, Shikhar Johari, Soumya Bardhan, Rohit jain,		    *
*                     Karthika Nair, Vibhuti Pithwa, Vaasavi Lakshmi                        *
*********************************************************************************************  

1. The zip file you downloaded contains this README file and the source code for the example in Section 3.4 of the book (in Eclipse project format).

2. You can import and execute the projects from Eclipse IDE using steps given below. Alternatively, you can inspect the source code by exploring *.java files inside the zip file. 


Importing Eclipse Project
-------------------------

1. Choose 'File->Import' menu from Eclipse. 

2. From the 'Import' pop-up dialog window, select 'Existing Projects into Workspace' under 'General'.  Click on 'Next' button.

3. In the next screen, choose the option 'Select archive file', and select the downloaded zip file. 

4. Eclipse scans the zip file and displays the following projects available for import:
	- 'AgeCalculatorSpring'
	- 'AgeCalculatorSpringClient'

5. Select both the options, and click on 'Finish' button.

6. Both the projects gets added to your Eclipse workspace.


Setting up the required libraries
----------------------------------

1. First you need to add the SPRING LIBRARIES to the project. You can download the latest version of Spring binaries from their website - 'http://www.springsource.org/spring-framework'. After you download the JARs, extract it to a local folder, let the folder name be - 'Spring Framework'.

2. Follow the steps below to add the JARs to the project build path:

	- Go to 'Window' -> 'Preferences'
	- Go to 'Java' -> 'Build Path' -> 'User Libraries'
	- On the 'User Libraries' section that opens, click on 'New' to add new user library.
	- Give the user library name - 'Spring'. Click on 'OK'.
	- Now, click on the button - 'Add External JARs' from the right panel.
	- Browse to the folder - 'Spring Framework', and select all the JAR files in that folder.
	- Click on 'Open'. All the JAR files will now get added to the user library.
                  
3. Now, you would need Apache Commons Logging library. Download the latest version from Apache website - 'http://commons.apache.org/proper/commons-logging/download_logging.cgi'. After you download the JARs, extract it to a local folder, let the folder name be - 'Commons Logging'.

4. Follow the steps as in 'Step - 2' above, to create a new user library, and add the JAR files to it.

5. Now, to add the newly created libraries to your project: 
	- Right-click on the project - 'AgeCalculatorSpring'.
	- Go to 'Build Path' -> 'Configure Build Path'. 
	- Go to 'Libraries' tab. Click on 'Add Library' button from the right panel. 
	- Select 'User Library'. Click on 'Next'. 
	- Select the check box - 'Spring'. Click on 'Finish'. Then click on 'OK'. The user library will get added to your project.

6. Similarly, add the user library to the project - 'AgeCalculatorSpringClient'.


Executing the Application
-------------------------
       
1. Right click on the project - 'AgeCalculatorSpringClient' under 'Project Explorer' window in Eclipse.

2. From the context pop-up menu, select 'Run as' -> 'Java Application' option.

3. Use the Age Calculator program as guided.

 

Spring Framework version 5.3.9
=====================================================================================

To find out what has changed since earlier releases, see the release notes at
https://github.com/spring-projects/spring-framework/releases.

Please consult the documentation located within the 'docs/spring-framework-reference'
directory of this release and also visit the official Spring Framework home at
https://spring.io/projects/spring-framework.

There you will find links to the issue tracker and other resources.

See https://github.com/spring-projects/spring-framework#readme for additional
information including instructions on building from source.
