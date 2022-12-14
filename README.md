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
$~~~~~~~~~~~~~~~~~~~~~~~$ Phone must have MyPhoneEplorer app installed and connection between devices must be active.</br>

**Steps to reproduce:**
1. Go to "Extras"=>"Restore backup"
2. Select the created backup file named "Oneplus 2022-08-11.mpb"
3. Click on "Restore backup" button
4. Click on "Close" button when prompted 

**Expected results:**
1. A OS window with saved backup location on the pc opens
2. A app window named "Restore backup" opens with all chekbox fields "Contacts","Call log","Events and tasks","Notes"and "SMS" selected
3. A loading bar appears displaying the "Current status"  of the files being restored
4. Restore is successfull

**Test data:** "Oneplus 2022-08-11.mpb" file, and data from "Contacts","Call log","Event and tasks","Notes" and "SMS"</br>
**Status:** Passed </br>

-----------------------------------------------------------------------------------------

### Creating files backup
**Summary:** Verifying that file backup is successful</br>
**Preconditions:** Connection between phone and pc must be active</br>

**Steps to reproduce:**
1. Go to "Extras" => "Create backup"
2. Press "Save" button
3. Press the "Files" checkbox and select the save location
4. Press "Create backup" button
5. Press "Close" button

**Expected results:**
1. Backup saving location folder on the pc opens
2. "Backup Oneplus 2022-08-11.mpb" file is created
3. Files for backup are being loaded
4. A loading bar appears, displaying the "Current status" of the files being processed
5. Window closes and files backup is successful

**Test data:** "Backup Oneplus 2022-08-11.mpb" file, all data from "files" category</br>
**Status:** Passed</br>

---------------------------------------------------------------------------------------------
### Restore files backup
**Summary:** Check if restoring backuped files is successful</br>
**Preconditions:** Files backup has to be previously made</br>
$~~~~~~~~~~~~~~~~~~~~~~~$ Connection between devices must be active.</br>
$~~~~~~~~~~~~~~~~~~~~~~~$ Data coresponding to files category has to be wiped from the phone</br>

**Steps to reproduce:**
1. Go to "Extras" =>"Restore backup"
2. Select the "Oneplus 2022-08-11.mpb" file coresponding to Files backup
3. Select the "Files" checkbox and press "Restore backup" button
4. Press "Close" button

**Expected results:**
1. Backup location folder on the pc opens
2. A app window named "Restore backup" opens
3. A loading bar appears displaying the "Current status" of the files being restored
4. Window closes and Files restore is successful

**Test data:** "Backup Oneplus 2022-08-11.mpb" file, all data from "files" category </br>
**Status:** Passed</br> 

--------------------------------------------------------------------------------------------

### Creating applications backup
**Summary:** Verifying that applications  backup works</br>
**Preconditions:** Connection between phone and pc must be active</br>

**Steps to reproduce:**
1. Go to "Extras"=>"Create backup"
2. Press "Save" button
3. Press the "Applications" checkbox and select the save location
4. Press "Create backup" button
5. Press "Close" button

**Expected results:**
1. Backup location folder on the pc opens
2. "Backup Oneplus 2022-08-11.mpb" file is created
3. Applications for backup are being loaded
4. A loading bar appears, displaying the "Current status"  of the files being processed
5. Window closes and applications backup is successful

**Test data:** "Backup Oneplus 2022-08-11.mpb" file, all data from "applications" category </br>
**Status:** Passed</br> 

---------------------------------------------------------------------------------------------------

### Restore applications backup
**Summary:** Checking if applications restore works</br>
**Preconditions:** Applications backup has to be previously created</br>
$~~~~~~~~~~~~~~~~~~~~$ Connection between phone and pc must be established</br>

**Steps to reproduce:**
1. Go to "Extras"=>"Create backup"
2. Press "Save" button
3. Press the "Applications" checkbox and select the save location
4. Press "Create backup" button
5. Press "Close" button

**Expected results:**
1. Backup location folder on the pc opens
2. "Backup Oneplus 2022-08-11.mpb" file is created
3. Applications for backup are being loaded
4. A loading bar appears, displaying the "Current status"  of the files being processed
5. Window closes and applications backup is successful

**Test data:** "Backup Oneplus 2022-08-11.mpb" file, all data from "applications" category </br>
**Status:** Passed</br> 

--------------------------------------------------------------------------------------------------

### Check "Memory status"
**Summary:** Check if "Memory status" functionality is displaying the same values as the phone</br>
**Preconditions:** Connection between phone and pc must be active</br>

**Steps to reproduce:**
1. Go to "View"=>"Other"=>"Memory status"
2. Compare displayed values like "Used","Free"and "Total" from "Memory status" with values from the phone

**Expected results:**
1. Memory status is displayed
2. All values coincide


**Test data:** "Used", "Free" and "Total" values displayed by "Memory status" and by the phone </br>
**Status:** Failed</br> 

---------------------------------------------------------------------------------------------------------

### Check "Monitor" functionality
**Summary:** Check if "Monitor" functionality is displaying accurate data</br>
**Preconditions:** Connection between phone and pc must be active</br>

**Steps to reproduce:**
1. Go to "View"=>"Other"=>"Monitor"
2. Compare battery percentage from "Monitor" functionality with battery percentage from the phone

**Expected results:**
1. "Monitor" functionality is displayed
2. Both devices are showing the same battery percentage


**Test data:** battery percentage displayed by "Monitor" functionality </br>
**Status:** Failed</br> 

-----------------------------------------------------------------------------------------------------------

### "Control phone" functionality
**Summary:** Check if the phone can be controled trough "Control phone/Screen mirroring" functionality</br>
**Preconditions:** Connection between phone and pc must be established via USB cable</br>

**Steps to reproduce:**
1. Go to "Extras" =>"Control phone/Screen mirroring" 
2. Press "START NOW" button on the phone
3. Give input to the phone using the mouse

**Expected results:**
1. A new window named "Load screenshot" is opened on the pc. On the phone side, a window with two buttons: "CANCEL" and "START NOW" opens, requesting access from the user.
2. Phone screen is mirrored on the pc
3. The phone responds accordingly

**Status:** Passed</br> 

-----------------------------------------------------------------------------------------------------------

### "Screen mirroring" functionality
**Summary:** Connection between phone and pc must be active</br>
**Preconditions:** Connection between phone and pc must be established</br>

**Steps to reproduce:**
1. Go to "Extras" =>"Control phone/Screen mirroring" 
2. Press "START NOW" button on the phone
3. Give input to the phone using the mouse

**Expected results:**
1. A new window named "Load screenshot" is opened on the pc. On the phone side, a window with two buttons: "CANCEL" and "START NOW" opens, requesting access from the user.
2. Phone screen is mirrored on the pc
3. The phone responds accordingly

**Status:** Passed</br> 

--------------------------------------------------------------------------------------------------------------














