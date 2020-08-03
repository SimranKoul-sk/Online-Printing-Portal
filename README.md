# Online-Printing-Portal

OBJECTIVE:
To develop a website for online printing, which is free of cost to use and with interactive user interface.
The make a system which is very simple in design and to implement. The system requires very low system resources and the system will work in almost all configurations. It has got following features:  
•	It will ensure data accuracy.   
•	Records will be efficiently maintained by DBMS.  
•	Users privacy will be taken care of 
To make an app which will allow the users to upload their documents online by selecting the nearest photocopy shops and make their work easy and less tedious.
The shopkeepers will also have a platform to be known and ideal when someone is in sudden need to a printout and accept the orders according to their requirements.

INTRODUCTION
This system is simple Android App based ordering system where user can upload the documents that they want to be photocopied through mobile itself mentioning all the details like colour, size, type and number of photocopies. On giving order it will be send to the selected photocopy shop. Owners have their own login website from where they will going to print according to the requirements of the customer. The shop-owner will be giving a suitable delivery date on which customer can collect their document.
This system is intended mainly for any users who want their document to photocopied but don't want to waste much time in process. It will be mainly used by students who frequently needs to have photocopy of their document. Apart from the intended audience, owing to the simplicity, it can be used by anyone else who knows how to use android mobile phone. It can be students, professors or any person.
This system will be used by students who are frequently in need of printing their documents . It saves time and labor that have to put for printing the document by simply providing users with a App that can be  used to select any photocopy-shop and type. Moreover shopkeepers are also benefited by this App as they can work according to their convenience by taking orders from customers.

This system is intended mainly for any users who want their document to photocopied but don't want to waste much time in process. It will be mainly used by students who frequently needs to have photocopy of their document. Apart from the intended audience, owing to the simplicity, it can be used by anyone else who knows how to use a android mobile phone. It can be students, professors or any person.
A detailed survey was done by our team on all the shops in and nearby VIT University. Along with that, the proposal has to be discussed with the shopkeepers. It will be an easier option for the shopkeepers as it will make their schedule more flexible and their working hours lesser. Also, the research included the distance of various printing and Xerox shops from VIT and their prices. After an extensive research on the shops in the locality, we boiled down to the following shops:
This system is intended mainly for any users who want their document to photocopied but don't want to waste much time in process. It will be mainly used by students who frequently needs to have photocopy of their document. Apart from the intended audience, owing to the simplicity, it can be used by anyone else who knows how to use a android mobile phone. It can be students, professors or any person.

SYSTEM MODEL
We are following Incremental Model for our project. 
Incremental Model is a process of software development where requirements are broken down into multiple standalone modules of software development cycle. 
Each iteration passes through the requirements, design, coding and testing phases. And each subsequent release of the system adds function to the previous release until all designed functionality has been implemented. 
 
The system is put into production when the first increment is delivered. The first increment is often a core product where the basic requirements are addressed, and supplementary features are added in the next increments. Once the core product is analyzed by the client, there is plan development for the next increment. 

Justification:  
Our first development phase will be completed by CAT-2, after which we can develop and add more functionalities to our project according to the clients' response and team's suggestions.  
At initial level a prototype will be developed. As the need for the system increases there will we newer model release according to the specific requirement. With the demand we will add more functionality to our model which will not only benefit the user but also make us to understand what user wants.  
The requirement of the complete system are clearly defined and understood with this model. However, some details can evolve with time so incremental model is best suited for our model ‘Online Printing System’. As for our project ‘Online printing system’ if we get more request from the customer then specific functionalities like discounts, courier service, colour printout etc. can be added. Incremental model fits best with our project as there might be some requirements that cannot be known beforehand and hence can be included in our project according to our customer's feedback.
Moreover, high risk and investments are involved with this project. So this calls for the feedback of the customers as it solely depends on their interaction with our project. That is the main reason we choose incremental model here.  
With each release our product will be better. It will have more features which will fulfil all the needs of the user. As the project is large and all the requirement are not know previously, it will evolve according to customer requirements increment that why incremental model fits best here. 

MODULES DESCRIPTION
DEVELOPED MODULES LIST 1 –
As we open the app, the splash screen appears, on which the Printerest icon is shown. 
After the splash screen, the login screen appears for the user to    login. The user can login by entering their phone number and    clicking on the submit button. After the user successfully logins, the user is provided with a side screen. This side screen provides the user with various options, like to place order, to check the status of the document uploaded for printing, the settings of the app and the about section.
DEVELOPED MODULES LIST 2 – 
Once we have selected the Place order option, the screen appears where we can place our order by uploading the required documents and also selecting other details like the color of the document we want, size, layout and the pages per sheet required. We also have to select the printing shop from the displayed list of nearby shops available. We have used Firebase as our database and as the storage medium for the app. All the details selected and the documents uploaded will directly get saved in the Firebase account.
We have created a web app for the shop-owners/shopkeepers through which they can directly access the documents and the details uploaded by the users. They can login through their phone numbers directly or the new users can create their accounts by the sign-up option available. The share data option of Firebase has been used to directly share the data from the admin account to the shopkeeper’s account. Through this, the shopkeepers will be able to access the entire data stored in the Firebase. 
DEVELOPED MODULES LIST 3 –
After the users have placed their orders, they can view the status of their documents uploaded for the printing in the status bar. The status bar will display the name of the document, the status of the order (waiting or completed) and the contact number of the Xerox shop. The user can also upload any more documents by clicking on the ‘ + ‘ icon given below in the screen. We have also developed a separate screen, called ‘Account’, where the user can edit (address and phone numbers) and view their details.

SUMMARY/CONCLUSION:
The market has been studied and accordingly we have worked on the requirements of the software. So an Application is developed for meeting the requirements. Couple of issues were raised in the software engineering section without solutions. These issues should be considered for complex applications and there need to be further research in the future on the issues that were raised. However, given the requirement of capturing and uploading functionality for the File Portal application, traditional software engineering may suffice. In deciding whether to develop a native application or web application, we as a developer have considered user experience as well as time and cost constraints to make the best choice. For native application platforms, Android is compared for two languages JAVA and Kotlin. Both platforms have advantages and the choice between the platforms will depend on the model of the application. User requirements and functionality is focussed in the application design to fulfil the needs of the user.

REFERENCE:
[1] Charland, A., and Leroux, B. 2011. Mobile Application Development: Web vs. Native. Communications of the ACM. ACM, v.54. n.5. DOI=10.1145/1941487.1941504.
[2] Grønli, T., Hansen, J., and Ghinea, G. 2011. A Cloud on the Horizon: The Challenge of Developing Applications for Android and iPhone. PETRA '11: Proceedings of the 4th International Conference on Pervasive Technologies Related to Assistive Environments. ACM.
[3] Forgue, M., and Hazael-Massieux, D. 2012. Mobile Web Applications: Bringing Mobile Apps and Web Together. Proceedings of the 21st international conference companion on World Wide Web (16-20 April). Lyon, France. DOI=10.1145/2187980.2188022.
[4] Goadrich, M. H., and Rogers, M. P. 2011. Smart Smartphone Development: iOS versus Android. SIGCSE '11: Proceedings of the 42nd ACM technical symposium on Computer science education. ACM.
[5] Jones, M., and Marsden, G. 2006. Mobile Interaction Design. John Wiley & Sons, Ltd.
[6] Jones, M., and Marsden, G. 2006. Mobile Interaction Design. John Wiley & Sons, Ltd.
[7] Wasserman, A. I. 2010. Software Engineering Issues for Mobile Application Development. FoSER '10: Proceedings of the FSE/SDP workshop on Future of software engineering research. ACM.
