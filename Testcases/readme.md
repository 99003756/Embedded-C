# TEST PLAN FOR HIGH LEVEL REQUIREMENTS:
|**Serial Number**|**TEST ID**|**TESTING FUNCTION**|**EXPECTED INPUT**|**EXPECTED OUTPUT**|
| :- | :- | :- | :- | :- | 
|1|HLR_1|Sunroof Control|On pressing of pushbutton indicating the user wants the sunroof to be open.|The sunroof window opens|
|2|HLR_2|Wiper Control Feature|The moisture sensor senses the water and wiper should turn ON speed of the wiper can be varied.|The wiper should be turned ON.|


# TEST PLAN FOR LOW LEVEL REQUIREMENTS:
|**Serial Number**|**TEST ID**|**TESTING FUNCTION**|**EXPECTED INPUT**|**EXPECTED OUTPUT**|
| :- | :- | :- | :- | :- | 
|1|HLR_1_LLR_1|Sunroof Control|When the input Is 1 indicating sunroof must be turned ON|The blue LED will glow i.e. the GPIO pin 12 will be set.|
|2|HLR_1_LLR_2|Sunroof Control|When the input Is depressed indicating it must be turned OFF|The blue LED will stop i.e. the GPIO pin 12 will be reset..|
|3|HLR_2_LLR_3|Wiper Control|Moisture sensor senses water and should turn ON the wiper and it has 2 speed states medium and maximum speed  |The GPIO pin 12 will be set.
The GPIO pin 14 will be reset.|
|4|HLR_2_LLR_4|Wiper Control|There is no water on the windshield i.e. the moisture sensor does not sense any water |The GPIO pin 15 will be set.
The GPIO pin 12 will be reset.|


