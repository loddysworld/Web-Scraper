<h1>Web Scraper🪛</h1>


<h2>Description</h2>
In this Walkthrough I will show you how to build a Web Scrapper in a super simple way using Video Studio and node.js!
A web scraper is a tool used to extract data from a quickly and accurately without the manual labor of scrolling through and grabbing the data yourself.
In our demonstration we will be using https://www.theguardian.com/uk as the example page to pull data from.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Node.js</b> 
- <b>Visual Studio</b>
- <b>nodemon</b>
- <b>axios</b>
- <b>cheerios</b>
- <b>express</b>

<h2>Walk-through:</h2>

<p align="center">
Open your choice of Text Editing application (I use Visual Studio but there are other applications you may use as well; all preference), and create a new folder labeled "Web Scraper". We are going to save our work in this folder and use this directory in future steps.<br/>
<img src="https://i.imgur.com/K38kx59.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
If you haven't already, please install node.js. This is a free open-source javascript environment that can run on multiple Operating systems.
We will be using this tool to write our javascript and create our server. Also, install ‘npm i nodemon -g’ as well.<br/>
<img src="https://i.imgur.com/T8gD10a.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
After install, next open your terminal and run "npm init". This command creates a package.json file to store our application we will be building. Hit enter till you see the file created in your editor application.
<br />
<br/>
<img src="https://i.imgur.com/ZDLS8AR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/hyVvL0K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now create a new file and name it "index.js". This will be our "main" file as listed in our package.json.  <br/>
<img src="https://i.imgur.com/Fby2Pmq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next, we are going to install three dependencies to our project. The dependencies are called 'Express, Axios, and Cheerios'. We will visit "https://www.npmjs.com" to receive the installation code for each.
NPM is an open-source repository with pre-built code that users have uploaded for free. If you are looking for more information, please feel free to do your research on the site or
checking other youtube guides regarding the service.<br/>
<img src="https://i.imgur.com/JrO9ijC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now search for the listed dependencies (Express, Axios, and Cheerios) and copy the installation code to the side into your terminal and press enter. 
Repeat these steps for all 3 dependencies.<br/>
<img src="https://i.imgur.com/fhUI0bj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/S9lRvDq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After each installation, you should see all 3 dependencies show up under your package.json with their name and version. Now note, when you installed Express there was another file created called "package-lock.json".
This is automatically installed since we installed the dependency. We will not do anything with this folder unless you are insterested in changing the version of the dependency you are using.<br/>
<img src="https://i.imgur.com/I8DIozf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next, we are going to write a start script. In the command line 'package.json', create "start": "nodemon index.js" as shown below.<br/>
<img src="https://i.imgur.com/w7p2Hwv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Our next step is to head to our 'index.js' file and create our script to run associated with the script above. Copy the syntax below as shown; this will start a server for the application and listen to the specified port and hear any changes made.<br/>
<img src="https://i.imgur.com/M38bEBL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
<br />
<br />
Open your terminal and run "npm run start". This will start our application and server we've created. You should get the following response.<br/>
<img src="https://i.imgur.com/zA3TJXX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Z6ZfVhb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now head back to your 'index.js' file and copy the following syntax as shown below. This will be where we will plug in our URL and attributes we are looking for.<br/>
<img src="https://i.imgur.com/mjOAKcT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Now in this demonstration we will be using https://www.theguardian.com/uk as our test site to pull information from. I am going to plug in the 'URL' and the 'class' that im looking for. To find the correct attributes, you will need to inspect the web page
to pull the correct information.<br/>
<img src="https://i.imgur.com/AaGBjx8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
<img src="https://i.imgur.com/InDIeLq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
<br />
<br />
Now that we have input all the necessary information, lets run "npm run start" again. You should receive the following information back.
As you can see it compiled all the requested information in the syntax and created a list! I hope this was helpful in you creating your own beginning Web scraper!<br/>
<img src="https://i.imgur.com/lGqC7Cj.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/eyLRSPc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
