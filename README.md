# MouseCaptureVideo
This is a Visual Basic program based on Direct Show. It captures the frames from incoming video  
and creates an output video mpeg file constructed from the captured frames.
It works well with the USB capture card and Black Magic Intensity pro. Based on some
preliminary tests the USB card produces less delay and possibly better result.  

Instructions:  
Download the repo to your local drive.  
Unzip it.  
Go to
...\CapSample_mpeg\CapSample\bin  
Get your system ready including the connections to the capture card.  
Double click on CapSample.exe  

Select USB if USBcard used.  
![image1](https://user-images.githubusercontent.com/48537944/227679880-27d03d36-59ba-405b-8c53-99144cc9bf3c.png)  

Select Decklink video if Intensity Pro used.  
![image5](https://user-images.githubusercontent.com/48537944/227723784-474c6527-fa2f-4260-96c0-4fa2d69cb008.png)  

Set the following settings  
![image2](https://user-images.githubusercontent.com/48537944/227679928-3e0c1b34-5cd5-4c31-8293-b10e7d557af1.png)  


You should get the capture window.  
![image3](https://user-images.githubusercontent.com/48537944/227680025-126055a4-788a-47b6-abe1-70534802acf1.png)  


Do not run Start  
Click the Frame button manually to see if the second window starts displaying the captured frame.
The new video will be created in the capture folder and the fraem will be addeed to it.  
Keep the cursor on the frame button and run the scanner.  
![image4](https://user-images.githubusercontent.com/48537944/227680205-6e525100-1c7e-43da-ab57-e4e268ea5539.png)  


Once done just close the application.   

This is a first release and most of the settings are hardcoded.  
The next releases should include more features.   
Feel free to post your questions and suggestions to the 8mm forum.  

