<h1>SQL Injection Fundamentals Guide and Video</h1>

 ### [YouTube Demonstration](https://youtu.be/KTZWpXlehmY)

<h2>Description</h2>
SQL Injection with HTB Academy/CTF
<br />

<h2>Languages and Techniques Used</h2>

- <b>Structured Query Language</b>
- <b>SQL Injection</b>

<h2>Environments Used</h2>

- <b>Windows 10</b>
- <b>Oracle Virtual Box</b>
- <b>Kali Linux</b>
- <b>Burpsuite<b/>
- <b>Parrot OS</b>
- <b>Docker<b/>


<h2>Cyber Apocalypse 2023 - The Cursed Mission</h2>

 - <b>Hack the Box - CTF<b/>

<p align="center">
Getting an Error: <br/>
<img src="https://user-images.githubusercontent.com/125524019/226139261-8bb16396-4576-4a11-8355-9ed20df86025.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
Using burpsuite, I am able to gain an insight that normally would remain hidden and inaccessible. 
<br />
<br />
Understanding the error:  <br/>
<img src="https://user-images.githubusercontent.com/125524019/226140412-ad2b93a0-f476-4437-bfc7-79671f9d6fe2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
Knowing that I have access to the underlying error in the SQL syntax, I can experiment with the parameters until I understand exactly what is causing the error. In this case, it appears that double quotation marks " are the cause of the error.
<br />
<br/>
The Payload: <br/>
<img src="https://user-images.githubusercontent.com/125524019/226140737-7934400f-2f5f-4bde-8565-cd5f2ef85e03.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
The payload was a simple "OR 1 = 1" statement, followed by a comment that ignored everything that came after it.
<br/>
<br/>
Results: <br/>
<img src="https://user-images.githubusercontent.com/125524019/226141255-298c2583-3e4c-4414-b675-a9c095fde032.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p/>
<h2>HTB Academy</h2>

- <b>SQLI Fundamentals</b>
  - [HTB](https://academy.hackthebox.com/achievement/515854/33)

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
