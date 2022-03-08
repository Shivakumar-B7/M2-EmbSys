# Test plan and output

## TEST PLAN 

|Test ID|Description|Input|Expected output|Actual Output|Passed or not|
|:------:|:----------------------|:---------------------|:--------------------|:-------------------|:---|
|HLR1|Door motor|Data from ardunio |door Shall open|door shall open|Passed|
|HLR2|Buttons|On|Should send cabin to floor where button is pressed|sends cabin to floor where button is pressed|Passed|
|HLR3|Level Sensor| 0v or 5v|Should send lift to desired floor|sends lift to desired floor| Passed|
|HLR4|Buzzer|Data from ardunio |Buzzer Sound|Buzzer Sound|Passed|
|HLR5|SERVO motor|command from ardunio |should change position of cabin|changing the position of cabin|Passed|
|HLR6|Keypad switch|press any key (P,1,2,3)|Should send cabin to the floor where key is pressed|sends cabin to the floor where key is pressed|Passed|


