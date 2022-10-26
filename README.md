# Test-Case samples
Manual test cases for MyPhoneExplorer app

Title: Connect phone to pc
Summary: Check if the first connection between pc and phone can be established.
Preconditions: MyPhoneExplorer app must run on both devices.On the PC, "Phone with Google Android-OS" and "Connect via WiFi" options must be selected .On the phone, "WiFi active" must be selected and "WiFi-PIN": "1234" must be set. Both devices must be connected to the same Network (router).

Steps to reproduce:                                                    Expected results:
1. Open MyPhoneExplorer app on the pc and phone                        1. MyPhoneExplorer app runs on both devices
2. Press "File"=>"Connect" button from the menu-bar                    2. Connecting bar and a window requesting "PIN-Code" appears
3. Type the "1234" PIN-Code in the input field                         3. "PIN-Code" field accepts the input
4. 4. Press "Ok" button                                                4. "PIN-Code" window closes and a new window requesting a name input for the identified                                                                             phone appears
5. Type "Oneplus" name in the input field                              5. Name field accepts the input
6. 6. Press "Ok" button                                                6. Connection is established and syncronization starts automatically.
