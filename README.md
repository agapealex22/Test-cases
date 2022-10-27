Test-Case samples<br>
=====================================================================================================================================================
Manual test cases for MyPhoneExplorer app that i wrote previously.</br>
----------------------------------------------------------------------------------------------------------------------------------------------------------------

Title: Connect phone to pc</br>
Summary: Check if the first connection between pc and phone can be established.</br>
Preconditions: MyPhoneExplorer app must run on both devices. On the PC, "Phone with Google Android-OS" and "Connect via WiFi" options must be selected .On the phone, "WiFi active" must be selected and "WiFi-PIN": "1234" must be set. Both devices must be connected to the same Network (router).</br>
---------------------------------------------------------------------------------------------------------------------------------------------------------------

Steps to reproduce:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Expected results:
1. Open MyPhoneExplorer app on the pc and phone &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1. MyPhoneExplorer app runs on both devices
2. Press "File"=>"Connect" button from the menu-bar &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2. Connecting bar and a window requesting "PIN-Code" appears
3. Type the "1234" PIN-Code in the input field &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3. "PIN-Code" field accepts the input
4. Press "Ok" button  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4. "PIN-Code" window closes and a new window requesting a name input for the identified phone appears
5. Type "Oneplus" name in the input field&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  5. Name field accepts the input
6. Press "Ok" button &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 6. Connection is established and syncronization starts automatically.

----------------------------------------------------------------------------------------------------------------------------------------------------------------
Test data: PIN-Code: 1234
