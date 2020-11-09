## happy path + find_error_simple and interval (warnLvl, date, time) <!-- retreive error simple -->
* greet
   - utter_greet
* find_errors_simple
   - action_infoCheck
* affirm   
   - action_search_database
* thank
   - utter_goodbye

## happy path find_error_simple + interval + but show_extend_result
* affirm 
   - action_search_database
* extend_dataReturn
   - utter_extendResult
   - action_extend_result
* thank 
   - utter_goodbye

## handle extend result 

* extend_dataReturn
   - utter_extendResult
   - action_extend_result

## handle extend result + new search

* extend_dataReturn
   - utter_extendResult
   - action_extend_result
* find_errors_simple

## handle extend result + deny show

* extend_dataReturn
   - utter_extendResult
   - action_extend_result
* deny
   - utter_no_problem

## unhappy path + find_error_simple and interval, wrong entities extracted 
* find_errors_simple
   - action_infoCheck
* deny
   - utter_reEnterInfo

## unhappy path + find_error_simple, user changed their mind after data returned <cancel request>(either no time or warning_level), collected mandatory field
* stop_dataRequest
   - action_infoCheck
* affirm 
   - action_search_database
* stop_dataRequest
   - action_infoCheck

## unhappy path + find_error_simple, user changed their mind <cancel request>(either no time or warning_level), collected mandatory field
* find_errors_simple
   - action_infoCheck
* stop_dataRequest
   - action_infoCheck
* affirm 
   - action_search_database

## unhappy path + find_error_simple, user changed their mind <cancel request>(either no time or warning_level), collected incorrect fields
* find_errors_simple
   - action_infoCheck
* stop_dataRequest
   - action_infoCheck
* deny
   - utter_reEnterInfo

## unhappy path + find_error_simple, user changed their mind <cancel request>(either no time or warning_level), collected correct field
* find_errors_simple
   - action_infoCheck
* stop_dataRequest
   - action_infoCheck
* affirm
   - action_search_database

## affirm handling

* affirm
   - action_search_database

## user deny extracted entities info (re-enter info test)
* deny
   - utter_reEnterInfo

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## thank
* thank
  - utter_no_problem


## mark log as checked after data returned

* affirm   
   - action_search_database
* mark_has_read
   - action_mark_read
* thank
   - utter_no_problem

## mark has read simple handling
* mark_has_read
   - action_mark_read   

## handle action more_details
* affirm   
   - action_search_database
* details
   - action_more_details
* thank
   - utter_no_problem



## more details
* extend_dataReturn
   - utter_extendResult
   - action_extend_result
* details
   - action_more_details
* thank
   - utter_no_problem
## handle more details after data return
* affirm   
   - action_search_database

## handle action more details (simple)
* findLTgt_pointer
  - action_infoCheck
* affirm
  - utter_LtGtpointer 
  - actionFindBeforeAfter 
* details
   - action_more_details 

## find new errors count simple

* find_newCount
  - action_count_errors

## find new errors count + query 

* find_newCount
  - action_count_errors
* find_errors_simple 
  - action_infoCheck

## find new errors count + after action search database

* affirm   
   - action_search_database
* find_newCount
  - action_count_errors
* find_errors_simple
  - action_infoCheck   

## find errror before after start conv
* greet
   - utter_greet
* findLTgt_pointer
  - action_infoCheck
* affirm  
  - utter_LtGtpointer 
  - actionFindBeforeAfter 



## find errror before after start conv + wrong info returned
* greet
   - utter_greet
* findLTgt_pointer
  - action_infoCheck
* deny
   - utter_reEnterInfo  

## find errror before after start conv + change mind

* findLTgt_pointer
  - action_infoCheck
* affirm  
  - utter_LtGtpointer 
  - actionFindBeforeAfter
* stop_dataRequest
   - action_infoCheck
* affirm
  - utter_LtGtpointer 
  - actionFindBeforeAfter          

## find error before or after
* findLTgt_pointer
  - action_infoCheck
* affirm  
  - utter_LtGtpointer 
  - actionFindBeforeAfter 
## find error before or after(after data search) 
* affirm   
   - action_search_database
* findLTgt_pointer
  - action_infoCheck
* affirm  
  - utter_LtGtpointer
  - actionFindBeforeAfter 
  

## find error before or after ()  
* find_newCount
  - action_count_errors
* find_errors_simple
  - action_infoCheck   
* findLTgt_pointer
  - action_infoCheck
* affirm  
  - utter_LtGtpointer  
  - actionFindBeforeAfter