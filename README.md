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
**Summary:** Initializing a call using the desktop app.</br>
**Preconditions:** Connection between pc and phone must be established</br>

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
### Sending a SMS </br>
**Summary:** Check if sending a sms from the desktop app works </br>
**Preconditions:** The connection between phone and pc must be established </br>

**Steps to reproduce:** 
1. Go to "View"=>"Contacts"=>"All" in the menu bar
2. Select "Andrei Popescu" from the contact list using the mouse
3. Press "New message" button from the top menu bar
4. Input "test message" text in the message textbox
5. Press "Send" button

**Expected results:**
1. All contacts are displayed
2. "Andrei Popescu" contact is highlighted
3. A window with "Andrei Popescu" name, phone number and a message textbox opens
4. The field accepts test data
5. The message is  successfuly delivered

**Test data:** "Andrei Popescu" contact; "test message" input </br>
**Status:** Passed</br>

--------------------------------------------------------------------------------------
### Creating phone backup
**Summary:** Verifying if creating backup for "Contacts", "Call log", "Events and tasks", "Notes" and "SMS" is successful.</br>
**Preconditions:** Connection between phone and pc must be active </br>

**Steps to reproduce:**
1. Go to "Extras"=>"Create backup"
2. Select a save location folder on the pc and click "Save" button
3. Select "Contacts","Call log","Event and tasks","Notes" and "SMS" checkboxes
4. Click on "Create backup" button
5. Press "Close" button when prompted

**Expected results:**
1. A window opens prompting the user to select a save location on the pc
2. A file named "Backup Oneplus 2022-08-11" is created and a new window opens, allowing the user to select preferred data for backup 
3. Checkboxes are selected
4. A loading bar appears displaying the "Current status" of the files being processed 
5. Window closes and  backup is successfull

**Test data:** "Backup Oneplus 2022-08-11" file, and data from "Contacts","Call log","Event and tasks","Notes" and "SMS" </br>
**Status:** Passed</br>

---------------------------------------------------------------------------------------
### Restore phone backup
**Summary:** Checking if "Contacts","Call log","Events and tasks","Notes" and "SMS" restore is successful.</br>
**Preconditions:** Phone must be factory reset and all data wiped.</br>
&nbsp;&nbsp; Phone must have MyPhoneEplorer app installed and connection between phone and pc must be active.</br>







