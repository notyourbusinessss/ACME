#########################################################
#                                                       #
#       Read-Me File: just generally talking about      #
#           how to travel through it and how to         #
#           see what is what!                           #
#                                                       #
#########################################################


    !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

     Make sure to fully extract the ZIP file (unlike Sam) before doing any of the following 

    !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!


        To unzip the file :
        
            on Windows :
                Right-click on the ZIP file and select "extract all"

            on Mac :
                Double or right-click the ZIP file and select "open"

            on Linux :
                you probably already know what you're doing have a nice day 




    #################################
    #                               #
    #   General intro to the file   #
    #       & contents              #
    #                               #
    #################################


        In the file you will now see two thing as follow 

            ./      <-  placement

                / Read-me.txt   <-  this is this file 
                / ACME          <-  this is the directory to the actual website 

        Open the ACME directory and you should now see the following : 

            ./ACME  <-  placement

                / Additional_Files  <-  directory/file with additional files the program will call
                / HTML              <-  directory/file with other contents of the wall that was scanned
                / ACME.HTML         <-  this is the page you would get after scanning the QR-Code 
                / ACME_FR.HTML      <-  the french version of website. can also be accessed VIA the website

    
    #########################
    #                       #
    #   Access the Webpage  #
    #                       #
    #########################

        To start the webpage you can do it several ways :

            The simplest option is to simply double-click it. If this doesn't work, try the second option: 
            Right-click the "ACME.HTML" file. 
            You should then get many options to pop up.
            Glide-over "open with" and click the web browser of your choice (although I do recommend Google Chrome).

            
    #########################################
    #                                       #
    #   Travel through it and how it works  #
    #                                       #
    #########################################

        To travel throughout the webpages and their functions, I recommend activating the inspector mode.
        If you do not know how to do so, you can right-click the page and then select "inspect."
        Doing so in Chrome will enable you to make the webpage be in the format of what a phone would display.

        Now you should be completely set up.
        If you opened the inspector view the code should now be on a window on your right. 

        Let's get through the website : 

            On the first page you should see the first lithograph, and if you scroll down, the description.
            The description should have the following sections in it describing the art itself :

                >   Title ( which should also be top most text )
                > Date of Creation
                > Medium 
                > Provenance 
                > Associated Genres 
                > Description 


            On the right of the picture should be an arrow. That arrow is used to travel to the next object on the right, until there   isn't one anymore.
            A similar arrow should appear on the left once the object is on the left of the current one.

            On top of the screen should be a menu bar with "ACME" written on the left and a small circle on the top right.
            If clicked th circle will open up a pop-up menu and give you the following :

            > The Collection
            > Francais
            > About Us
            > About the Project 
            > Contact
            > ACME

            Each of these options should be "clickable" so you're free to explore everything!



    #################################################
    #                                               #
    #   More in-depth view of the files contents:   #
    #                                               #
    #################################################


        #########################
        #   Additional_Files    #
        #########################

            placement:

                ./ACME/Additional_Files

            content: 
                
                / ACME_Budget.xlsx     
	        / ACME_Gantt.pdf	
                / ACME_Presentation.pdf	
                / Browser_Design.pdf
		/ Database_Format.png
                / Final_Paper.pdf
                / Mobile_Design.pdf

            Description : 

                "ACME_Budget.xlsx" is an Excel file with the budget of the project. 

                "ACME_Gantt.pdf" is the PDF of the Gantt chart showing the proposed work distribution over time.

                "ACME_Presentation.pdf" is the PDF of the presentation for the website.

                "Browser_Design.pdf" is the PDF to proposed schematics of the browser version.
		
		"Database_Formate.png" is a simplified version of the proposed structure for the SQL database.

                "Final_paper.pdf" is the proposal itself.

                "Mobile_Design.pdf" is the proposed design for the mobile version. 

        

        #############
        #   HTML    #
        #############

            placement:

                ./ACME/HTML

            Content:

                / AboutUs.html	
                / AboutUs_FR.html	
                / Files_Links.HTML
                / Files_links_FR.HTML
                / Index_2_FR.html	
                / Index_4.html	
                / Index_5_FR.html	
                / Index_7.html
                / AboutUs_FR.html	
                / Index_3.html	
                / Index_4_FR.html	
                / Index_6.html	
                / Index_7_FR.html
                / Index_2.html	
                / Index_3_FR.html	
                / Index_5.html	
                / Index_6_FR.html

            Description:

                These are general files. These are the files the webpage will call on to travel from art to art. Each "index" has a number which references the painting associated with it;
                for example the "index.html" found in the main doc will refer to index_2 and so on. 
                like so : 

                Index.HTML > < Index_2.HTML > < Index_3.HTML > < index_4.HTML > < index_5.HTML > < index_6.HTML > < index_7.HTML

                Each of them also call on their own French version, which itself can call on the other left or right objects as seen above. 
                Each can also call the "AboutUs.HTML" which is found in the pop-up menu, much like the the "files_links.HTML".
                

            







            


        