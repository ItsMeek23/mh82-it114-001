<table><tr><td> <em>Assignment: </em> IT114 Chatroom Milestone4</td></tr>
<tr><td> <em>Student: </em> Meekat Hadi (mh82)</td></tr>
<tr><td> <em>Generated: </em> 12/13/2023 2:04:32 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-001-F23/it114-chatroom-milestone4/grade/mh82" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <p>Implement the features from Milestone3 from the proposal document:&nbsp;&nbsp;<a href="https://docs.google.com/document/d/1ONmvEvel97GTFPGfVwwQC96xSsobbSbk56145XizQG4/view">https://docs.google.com/document/d/1ONmvEvel97GTFPGfVwwQC96xSsobbSbk56145XizQG4/view</a></p>
</td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Client can export chat history of their current session (client-side) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot of related UI</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-12-13T18.32.17real%20export%20button.png.webp?alt=media&token=93171c53-a481-4b3e-8bed-f63db9ca3220"/></td></tr>
<tr><td> <em>Caption:</em> <p>Export UI that is used as a drop down menu in the chatroom<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add screenshot of exported data</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-12-12T23.38.48image.png.webp?alt=media&token=9e0dd7e5-e1ed-4bb7-b192-62c84b044157"/></td></tr>
<tr><td> <em>Caption:</em> <p>Exported chat of conversation from the chatroom. Some examples of bold, italics, and<br>underlining format is used with the text and with color as well. <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain how you implemented this</td></tr>
<tr><td> <em>Response:</em> <p>This was implemented by adding a UI feature named export and adding it<br>to the client box so the chat can exported. Once the export button<br>is clicked, the chat will be exported into a different file and saved<br>onto the user&#39;s device to be accessed with. In this scenario, the file<br>was .txt file which can also be modified. The messages were saved in<br>the ChatPanel.java file where the history of the messages were saved every time<br>a user inputs a message. GetChatHistory method was used to retrieve the messages<br>and stores it in lists of strings where then the chat history is<br>exported to a different file.&nbsp;<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Client's mute list will persist across sessions (server-side) </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot of how the mute list is stored</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-12-13T18.56.34image.png.webp?alt=media&token=3e4b286e-8204-4a6c-8ea3-ec327272a067"/></td></tr>
<tr><td> <em>Caption:</em> <p>How the mute list is stored<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot of the code saving/loading mute list</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-12-13T18.44.57image.png.webp?alt=media&token=55d217ab-4560-4ff2-9b5a-40dca8db522d"/></td></tr>
<tr><td> <em>Caption:</em> <p>When the mute list is created, it is applied to the ServerThread and<br>writes it to a file<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain how you implemented this</td></tr>
<tr><td> <em>Response:</em> <p>This was implemented by iterating the users in the clients that were muted<br>in the ServerThread file. After the user has been muted, the name is<br>stored and creates a list which will be written into a file to<br>be exported for later..&nbsp;<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Client's will receive a message when they get muted/unmuted by another user </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add a screenshot showing the related chat messages</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-12-13T18.24.02image.png.webp?alt=media&token=e62eec14-e21b-4826-a618-6a86b3413788"/></td></tr>
<tr><td> <em>Caption:</em> <p>Message shows that a person has been muted by a specific user<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add a screenshot of the related code snippets</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-12-13T18.40.40image.png.webp?alt=media&token=65a5f9df-8248-4395-8fe0-23e0f103ba5e"/></td></tr>
<tr><td> <em>Caption:</em> <p>How and when the mute and unmute message occurs<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain how you implemented this</td></tr>
<tr><td> <em>Response:</em> <p>This was implemented by creating 2 case statements where a user is either<br>muted or unmuted. If the user types /mute and then follows with the<br>desired name of the user that wants to be muted, the string message<br>will be detected where it will be into a list creating an array<br>of users that have been muted. If one person is muted, an array<br>list of one person will be created. If there are multiple users muted,<br>then the array list be as many as the users muted. For the<br>unmute feature, the user will have to type in /unmute and the user<br>will be taken out of the array list.&nbsp;<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> User list should update per the status of each user </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Add screenshot for Muted users by the client should appear grayed out</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-12-13T17.48.49image.png.webp?alt=media&token=e0855b39-8000-41c0-8217-7650701e60e4"/></td></tr>
<tr><td> <em>Caption:</em> <p>The user list shows who is muted by the client Me which has<br>been grayed out. <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Add screenshot for Last person to send a message gets highlighted</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-12-13T17.55.33image.png.webp?alt=media&token=537e117f-0114-4c9a-a9ef-d21a17736921"/></td></tr>
<tr><td> <em>Caption:</em> <p>Last person to send a message gets a bold highlighted message. Muted person<br>is excluded<br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-12-13T18.08.53image.png.webp?alt=media&token=55eb4bff-3bec-4f88-98a3-bc7d76df7591"/></td></tr>
<tr><td> <em>Caption:</em> <p>Last person to send a message gets a bold highlighted message. Muted person<br>is excluded<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Briefly explain how you implemented this</td></tr>
<tr><td> <em>Response:</em> <p>This was implemented by editing the RoomsPanel.java file where the string messages were<br>iterated using a while loop. I managed to only bold the message sent<br>by the last user as I had trouble changing the background to highlight<br>the message sent by the last person.<br></p><br></td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-001-F23/it114-chatroom-milestone4/grade/mh82" target="_blank">Grading</a></td></tr></table>
