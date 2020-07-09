## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot
  
## default fall
* bot_challenge
  - utter_default
  
## outlook closed
* outlook_issue
  - utter_outlook_issue
* outlook_closed
  - utter_outlook_closed
* outlook_xml_error
  - utter_outlook_xml_error
* outlook_word
  - utter_outlook_word
* outlook_excel
  - utter_outlook_excel
* outlook_powerpoint
  - utter_outlook_powerpoint
  
## printer queue
* printer_issue
  - utter_printer_issue
* printer_queue
  - utter_printer_queue
* printer_spooler
  - utter_printer_spooler
  
## System issue
* system
  - utter_system
* Temp_file_C
  - utter_Temp_file_C
* low_memory
  - utter_low_memory
* adobe_issue
  - utter_adobe_issue
* system_slow
  - utter_system_slow
* account_locked
  - utter_account_locked
* critix_issue
  - utter_critix_issue
* browser_issue
  - utter_browser_issue
* internet_explorer
  - utter_internet_explorer

## List of all category
* all_category
  - utter_all_category
  
## outlook
* outlook_category
  - utter_outlook_category
  
## printer
* printer_category
  - utter_printer_category
  
## system
* system_category
  - utter_system_category
  
## system slow
* system_slow_category
  - utter_system_slow_category

