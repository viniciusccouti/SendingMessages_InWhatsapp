# SendingMessages_InWhatsapp
 This code has the main goal to automate messages that need to be send in WhatsappWeb without being too automated, in a sense that Whataspp could block your account, since they usually do not like it this kind of automation.

 For this you can use a xlsx file ( In this case Envios-COMfones) with a list of names,message, numbers and if you want a name of a file that you wish to send. You have to place this xlsx file in the folder "arquivos" in order to insert if is needed. In this exercise we used as a example a image named "photo-image". 

Then using pandas to read the xlsx file in Jupyter Notebook, we can use selenium and its elements such as xpath and ID to find what we need to click or adress a information in order to send a message. The main purpose of this exercise is to train selenium elements.

For this example works you need the files: SendingMessage_Whatsapp(attached here) , a file with the same columns as Envios-COMfones and also a folder named arquivos with the image that you want. Remember to inser the name of this image in the column C of the xlsx file.
