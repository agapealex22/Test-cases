# Test Case samples<br>

## Manual test cases for MyPhoneExplorer app that I wrote previously.</br>
--------------------------------------------------------------------------
### Connect phone to PC</br>
**Summary:** Check if the first connection between pc and phone can be established.</br>
**Preconditions:** MyPhoneExplorer app must run on both devices. On the pc,"Phone with Google Android-OS" and "Connect via WiFi" options must be selected. On the phone. "WiFi active" must be selected 
and "WiFi-PIN":"1234" must be set. Both devices must be connected to the same network (router).</br>

**Steps to reproduce:**                                                                                              
1. Open MyPhoneExplorer app on the pc and phone                                                         
2. Press "File"=>"Connect" button from the menu-bar                                                      
3. Type the "1234" PIN-Code in the input field                                                                     
4. Press "Ok" button                                                                                                             
5. Type "Oneplus" name in the input field                                                                           
6. Press "Ok" button                                                                                                            

**Expected results:**
1. MyPhoneExplorer app runs on both devices
2. Connecting bar and a window requesting "PIN-Code" appears
3. "PIN-Code" field accepts the input
4. "PIN-Code" window closes and a new window requesting a name input for the identified phone appears
5. Name field accepts the input
6. Connection is established and syncronization starts automatically.

**Test data:** PIN-Code: "1234"</br>
**Status:** Passed</br>

-------------------------------------------------------------------------------------
### Call Contact</br>
**Summary:**Initializing a call using the desktop app.</br>
**Preconditions:**Connection between pc and phone must be established</br>

**Steps to reproduce:** 
1. Press "View" => "Contacts"=> "All" buttons from the menu bar
2. Select "Andrei Popescu"contact entry using the mouse and press "Call" button
3. Press "Dial" button

**Expected results:**
1. Contacts list appears
2. A window displaying"Andrei Popescu" contact details and "Dial" button appears
3. The phone starts dialing "Andrei Popescu" contact

**Test data:** "Andrei Popescu" contact</br>
**Status:** Passed

-----------------------------------------------------------------------------------
