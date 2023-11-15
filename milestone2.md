<table><tr><td> <em>Assignment: </em> IT114 Chatroom Milestone 2</td></tr>
<tr><td> <em>Student: </em> Meekat Hadi (mh82)</td></tr>
<tr><td> <em>Generated: </em> 11/15/2023 5:44:35 PM</td></tr>
<tr><td> <em>Grading Link: </em> <a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-001-F23/it114-chatroom-milestone-2/grade/mh82" target="_blank">Grading</a></td></tr></table>
<table><tr><td> <em>Instructions: </em> <p>Implement the features from Milestone2 from the proposal document:&nbsp; <a href="https://docs.google.com/document/d/1ONmvEvel97GTFPGfVwwQC96xSsobbSbk56145XizQG4/view">https://docs.google.com/document/d/1ONmvEvel97GTFPGfVwwQC96xSsobbSbk56145XizQG4/view</a></p>
</td></tr></table>
<table><tr><td> <em>Deliverable 1: </em> Payload </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Payload Screenshots</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-11-15T22.00.07image.png.webp?alt=media&token=30d7f9fd-98c7-48e5-803a-d6fcd6cf3b01"/></td></tr>
<tr><td> <em>Caption:</em> <p>Payload Code with comments and ucid + date shown. <br></p>
</td></tr>
</table></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 2: </em> Server-side commands </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Show the code for the mentioned commands</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-11-15T21.59.43image.png.webp?alt=media&token=5297eb66-c8c1-4f38-85d2-7e5254a5beef"/></td></tr>
<tr><td> <em>Caption:</em> <p>Code for /roll and /flip in the payload type  alongside UCID and<br>date. Use if else statements to determine rolling dice and flipping coin with<br>string commanfs<br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Explain the logic/implementation of each commands</td></tr>
<tr><td> <em>Response:</em> <p>/Roll was done by doing a if else statement where if the command<br>/roll is written in the terminal by the client, a random number will<br>generate to roll the dice. Both formats apply for rolling the dice.<div><br></div><div>/Flip works<br>by also incorporating it into the else if statement where once the client<br>types in /flip, a random number is generated between 0 and 1 where<br>if the the result is 0, the coin is heads. If its 1,<br>the coin is tails using the String message.&nbsp;</div><br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 3: </em> Text Display </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707773-e6aef7cb-d5b2-4053-bbb1-b09fc609041e.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Show the code for the various style handling via markdown or special characters</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-11-15T22.19.17image.png.webp?alt=media&token=c3775f92-3a40-419c-a579-57434e8831ca"/></td></tr>
<tr><td> <em>Caption:</em> <p>Code for various styles handling such as Italics, bold, underline or color of<br>font. This is done by using string messages using if statements. <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 2: </em> Show source message and the result output in the terminal (note, you won't actually see the styles until Milestone3)</td></tr>
<tr><td><table><tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-11-15T22.26.59image.png.webp?alt=media&token=e1c5b36f-63cc-4769-bc2a-1975dd820e9d"/></td></tr>
<tr><td> <em>Caption:</em> <p>Source message of the input command <br></p>
</td></tr>
<tr><td><img width="768px" src="https://firebasestorage.googleapis.com/v0/b/learn-e1de9.appspot.com/o/assignments%2Fmh82%2F2023-11-15T22.30.12image.png.webp?alt=media&token=cfadd6b2-b83a-4866-9077-6695d5d3ff19"/></td></tr>
<tr><td> <em>Caption:</em> <p>This is the output of the input command with the modified characters that<br>display the HTML characters. <br></p>
</td></tr>
</table></td></tr>
<tr><td> <em>Sub-Task 3: </em> Explain how you got each style applied</td></tr>
<tr><td> <em>Response:</em> <p>By using string messages, each style was applied by implemented where if the<br>text contained&nbsp; a certain character, the string will detect the message input and<br>replace the overall text to apply each style. Using if statements, if &quot;**&quot;<br>was typed, the text would replace the ** with a &lt;b&gt; html tag<br>to indicate it is bold. For italics and underline it would be &quot;*&quot;<br>and &quot;_&quot; which would be replaced with &lt;i&gt; and &lt;u&gt; html tags in<br>the output. Once the UI is implemented in Milestone 3, these HTML tags<br>will not appear in the terminal but will be applied in the UI.<br>For the color, this was the same as well where using either colors<br>of Red, blue, green, or yellow, whenever an input string of any of<br>those colors are in the input, the html tag of those colors will<br>replace the text.&nbsp;<br></p><br></td></tr>
</table></td></tr>
<table><tr><td> <em>Deliverable 4: </em> Misc </td></tr><tr><td><em>Status: </em> <img width="100" height="20" src="https://user-images.githubusercontent.com/54863474/211707795-a9c94a71-7871-4572-bfae-ad636f8f8474.png"></td></tr>
<tr><td><table><tr><td> <em>Sub-Task 1: </em> Include the pull request for Milestone2 to main</td></tr>
<tr><td>Not provided</td></tr>
</table></td></tr>
<table><tr><td><em>Grading Link: </em><a rel="noreferrer noopener" href="https://learn.ethereallab.app/homework/IT114-001-F23/it114-chatroom-milestone-2/grade/mh82" target="_blank">Grading</a></td></tr></table>
