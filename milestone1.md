<table><tr><td> <em>Assignment: </em> It114 Milestone1</td></tr>
<tr><td> <em>Student: </em> Meekat Hadi (mh82)</td></tr>
<tr><td> <em>Generated: </em> 10/23/2023 6:19:30 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-001-F23/it114-milestone1/grade/mh82" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <ol><li>Create a new branch called Milestone1</li><li>At the root of your repository create a folder called Project if one doesn't exist yet</li><ol><li>You will be updating this folder with new code as you do milestones</li><li>You won't be creating separate folders for milestones; milestones are just branches</li></ol><li>Create a milestone1.md file inside the Project folder</li><li>Git add/commit/push it to Github (yes it'll be blank for now)</li><li>Create a pull request from Milestone1 to main (don't complete/merge it yet, just have it in open status)</li><li>Copy in the latest Socket sample code from the most recent Socket Part example of the lessons</li><ol><li>Recommended Part 5 (clients should be having names at this point and not ids)</li><li><a href="https://github.com/MattToegel/IT114/tree/Module5/Module5">https://github.com/MattToegel/IT114/tree/Module5/Module5</a>&nbsp;<br></li></ol><li>Fix the package references at the top of each file (these are the only edits you should do at this point)</li><li>Git add/commit the baseline</li><li>Ensure the sample is working and fill in the below deliverables</li><ol><li>Note: The client commands likely are different in part 5 with the /name and /connect options instead of just connect</li></ol><li>Get the markdown content or the file and paste it into the milestone1.md file or replace the file with the downloaded version</li><li>Git add/commit/push all changes</li><li>Complete the pull request merge from step 5</li><li>Locally checkout main</li><li>git pull origin main</li></ol></td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Startup </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot showing your server being started and running</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-10-23T21.40.57image.png.webp?alt=media&token=24c79fe7-1b2e-4173-a932-1af59789c8c3"/></td></tr>
<tr><td> <em>Caption:</em> <p>The Server is listening to the port from the command line as show<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add screenshot showing your client being started and running</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-10-23T21.42.26image.png.webp?alt=media&token=94a81626-eda8-4d2a-9df0-3c286a284956"/></td></tr>
<tr><td> <em>Caption:</em> <p>The client has connected to the server successfully. <br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-10-23T21.43.23image.png.webp?alt=media&token=9c80c50b-f95b-4fd7-a6fc-d8d439f6fdba"/></td></tr>
<tr><td> <em>Caption:</em> <p>The Server states that the client has connected successfully<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain the connection process</td></tr>
<tr><td> <em>Response:</em> <p>The connection process works by using sockets to connect the client and server<br>together successfully. The server and client&#39;s sockets will connect to each other where<br>both the client and socket can communicate together. The server and client can<br>write commands but the client reads the input commands from socket server first<br>and then replies with a command of its own back to the server<br>where the server socket reads the input commands from the client socket. In<br>order to conect both the server and client sockets, both connections must be<br>turned by typing javac &quot;name of package&quot;.&nbsp;<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Sending/Receiving </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot(s) showing evidence related to the checklist</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-10-23T21.49.37image.png.webp?alt=media&token=054f82b3-960e-4522-9c81-3d85f17b5cd8"/></td></tr>
<tr><td> <em>Caption:</em> <p>First client connecting the server (Meekat)<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-10-23T21.50.26image.png.webp?alt=media&token=c8c4ec69-c915-45e2-a6a7-1eb3dc0e906f"/></td></tr>
<tr><td> <em>Caption:</em> <p>Second client connected to the server (Nick)<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-10-23T21.52.02image.png.webp?alt=media&token=5636d9ef-8779-4b7a-8756-048858a32b8c"/></td></tr>
<tr><td> <em>Caption:</em> <p>Both clients are sending messages to each other where the server sends the<br>message to all clients in the same room.<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-10-23T22.00.18image.png.webp?alt=media&token=06fa15ce-6504-43bf-8b6f-66f2d19cedbd"/></td></tr>
<tr><td> <em>Caption:</em> <p>Shows one client (Nick) creating their room and trying to communicate with the<br>other client but the server does not send this message to that client<br>(Meekat)<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Briefly explain how the messages are sent, broadcasted (sent to all connected clients), and received</td></tr>
<tr><td> <em>Response:</em> <p>When the two clients are connected to the server, they are put in<br>a room together, in this case would be the lobby. When a client<br>sends a message, this message gets passed through the ServerThread to read what<br>type of command is putting put in by either of the two clients.<br>This is where the message is received and sent to the Room aka<br>the Lobby and relayed to other client.&nbsp;<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Disconnecting / Terminating </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot(s) showing evidence related to the checklist</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-10-23T22.02.24image.png.webp?alt=media&token=3925a235-1eaa-40c7-84b5-641451098831"/></td></tr>
<tr><td> <em>Caption:</em> <p>Shows client disconnecting from the server but the server is still up<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-10-23T22.05.49image.png.webp?alt=media&token=6c060aaf-3003-4c5a-843b-b8bc0b7cc22a"/></td></tr>
<tr><td> <em>Caption:</em> <p>Server terminates with client disconnecting from the server<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Briefly explain how the various disconnects/terminations are handled</td></tr>
<tr><td> <em>Response:</em> <p>When its time for the clients to leave the Rooms from communication, the<br>client types in the command /disconnect to disconnect the client socket from the<br>server socket. The server is still running so the client disconnect doesnt crash<br>the server or the client itself. As long as the server is online,<br>the client socket is free to connect or disconnect at anytime to the<br>socket server.&nbsp;<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add the pull request for this branch</td></tr>
<tr><td> <a rel="noreferrer noopener" target="_blank" href="https://github.com/ItsMeek23/mh82-it114-001/pulls">https://github.com/ItsMeek23/mh82-it114-001/pulls</a> </td></tr>
<tr><td> <em>Sub-Task 2: </em> Talk about any issues or learnings during this assignment</td></tr>
<tr><td> <em>Response:</em> <p>I learned how to connect the server and client sockets together in this<br>project. Learning about the basics will be vital especially for future milestones that<br>will require more work. My favorite topic Ive learned so far.&nbsp;<br></p><br></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-001-F23/it114-milestone1/grade/mh82" target="_blank">Grading</a></td></tr></table>
