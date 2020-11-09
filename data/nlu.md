## intent:greet
- hey
- hello
- hi
- good morning
- good evening
- hey there
- ed
- wake up 
- I need your help


## intent:goodbye
- bye
- bye!
- goodbye
- see you around
- see you later
- by ed

## intent:affirm
- yes
- indeed
- of course
- that sounds good
- correct
- that's the one

## intent:deny
- no
- never
- I don't think so
- don't like that
- no way
- not really
- noope
- not this
- i'm not looking for this
- uh no

## intent:mood_great
- perfect
- very good
- great
- amazing
- wonderful
- I am feeling very good
- I am great
- I'm good

## intent:stop_dataRequest
- [stop](cancel) the request and [replace](cancel) it with [errors](warning_level) at 12:40 [instead](cancel)
- [find unread](newError_report) files [between](time_interval) last tuesday and tonight at 6:40
- can you [find unread](newError_report) files [between](time_interval) last tuesday and tonight at 6:40
- can you [change](cancel) that with [eror](warning_level) [between](time_interval) last tuesday and today
- [no replace](cancel) that with [new](newError_report) [error](warining_level)
- find [new](newError_report) [error](warining_level) [between](time_interval) last night and today at 6:50
- [cancel](cancel) that and [replace](cancel) it with [new files](newError_report) at 12:40
- please [replace](cancel) that with [new files](newError_report) at 12:40 [instead](cancel)
- [replace](cancel) that with [new files](newError_report) at 12:40 [instead](cancel)
- can you [change](cancel) that with [new files](newError_report) at 12:40 [instead](cancel)
- [i made a mistake](cancel) can you [cancel](cancel) the input
- [stop the request](cancel) please and [change](cancel) it with [unchecked logs](newError_report) [between](time_interval)
- wait i [gave you incorrect information](cancel) [cancel](cancel) it
- [replace input](cancel) with 12:45 and [error](warnig_level)
- [change my request](cancel) with [error](warining_level) at 12:34 
- [i made a mistake](cancel) can you [replace](cancel) it [errors](warning_level) [between](time_interval) 12:45 yesterday and the 14th of march at 12:45
- [replace my input](cancel) with [find new](newError_report) [eror](warning_level)[between](time_interval) 14th of may at 12:40 and yesterday at 12:45 pm
- [stop the search](cancel) and [replace](cancel) it with [unchecked logs](newError_report) at 12:30:40 pm yesterday
- find [find any new](newError_report) [between](time_interval) yesterday at 12:50 am and 1:40:50 pm [instead](cancel)
- [find unread](newError_report) [from](time_interval) 12:38:00 am last night to 8:34:12 pm today [instead](cancel)
- [replace that](cancel) with [error](warning_level) [between](time_interval) last night and this morning
- [on second thought](cancel) [change](cancel) that with [errors](warning_level) at 12:34 pm last night
- can you [change](cancel) that with [new](newError_report) at 12:23 at 12:45 pm
- can you please [replace](cancel) that with [eror](warning_level) [between](time_interval) last night at 14:40 am and 12:56 pm [instead](cancel)
- [replace it](cancel) it with 12:45 am yesterday 
- [replace](cancel) that with [errrors](warning_level) [between](time_interval) 22:40 am today at 6:45 tomorrow
- no search for [any new](newError_report) [eror](warning_level) [between](time_interval) yesterday at 12:40 am and today at 6:50 pm [instead](cancel)
## intent:mood_unhappy
- sad
- very sad
- unhappy
- bad
- very bad
- awful
- terrible
- not very good
- extremely sad
- so sad
- so sad!

## intent:bot_challenge
- are you a bot?
- are you a human?
- am I talking to a bot?
- am I talking to a human?

## intent:new_files
- can you [find any new](newError_report) [error](warning_level) to report  
- can you [find new](newError_report) [error](warning_level) in the database
- new [error](warning_level) in database 
- report on [error](warning_level)
- find me some [error](warning_level)
- find [error](warning_level)
- [fetch new](newError_report) [error](warning_level)
- i need you to look at files
- do you have any [unchecked logs](newError_report) today
- tell me is there a log i have [not cheked](newError_report)
- tell me are there [new](newError_report) logs i have [not cheked](newError_report) 

## intent:findLTgt_pointer
- find [error](warning_level) [before](spaceTimePointer) 8:40:3
- Find [error](warning_level) from [after] tuesday this week
- find [error](warning_level) that occured today [before](spaceTimePointer) 8:40:3
- find [error](warning_level) that occured yesterday [before](spaceTimePointer) 8:40:3
- can you look for [error](warning_level) that occured [before](spaceTimePointer) 7:20:3
- can you retreive logs that occured [after](spaceTimePointer) 25/12/2020
- Can you find [error](warning_level) from [after](spaceTimePointer) the 5th of March 2020
- Can you find [error](warning_level) from [after](spaceTimePointer) last saturday
- look for [error](warning_level) [after](spaceTimePointer) 1/2/2019 at 1:30:0


## intent:more_details
- can you [give me more](details) [details](details)
- can you [give me more](details) information
- can you gie me [more information](details) on that last error
- [More information](details) please
- [More](details) [details](details) please
- More information
- [More details](details)
- Can you [tell me more](details)
- Tell me [more](details)
- Give me [more details](details)
- Give me [more information](details)
- Give me [details](details)


## intent:find_errors_simple

- I need you to check the database for [errors](warning_level)
- Can you check the database for [errors](warning_level)
- find me [error](warning_level) that occured yesterday
- find [errror](warning_level) that occured yesterday at 6:40
- find [error](warning_level) before 8:40:3
- find [errror](warning_level) that occured today before 8:40:3
- find [error](warning_level) that occured yesterday before 8:40:3
- can you look for [error](warning_level) that occured before 7:20:3
- look for [error](warning_level) after 1/2/2019 at 1:30:0 
- can you retreive logs that occured after 25/12/2020 

## intent:find_errorsInterval
- can you find [error](warning_level) [between](time_interval) last night and this morning
- could you find [eror](warning_level) [between](time_interval) yesterday at 12:30 and 25 minutes ago
- please find [error](warning_level) [Between](time_interval) 25 september 2019 at 12:30 and 
- find [new](newError_report) [eror](warning_level) [between](time_interval) last monday at 12:45 and yesterday at 13:45
- retreive [ERRORS](warning_level) [from](time_interval) 12:45 pm tuesday and 1:30 am last night
- get me [errors](warning_level) [from](time_interval) 15:34:12 last night and today at 13:34:06
- fetch me [errrors](warning_level) [from](time_interval) 12:30 last night and now


## intent:find_errorsInterval_newCount
- search the database and [find any new](newError_report)[warnings](warning_level) [between](time_interval) now and last night at 12:45 am 
- search data for [new](newError_report) [errors](warning_level) [between](time_interval) last night monday at 6:45:00 and today and 12:45:12
- please check for any [new file](newError_report) in my data set [between](time_interval) monday at 6:30 pm and last monday at 11:45
- please check for [any new files](newError_report) in the database [between](time_interval) tuesday at 8:45 am and last night
- [new files](newError_report) [between](time_interval) 12:30 today and 9:45:00 am yesterday
- [find unread](newError_report) [from](time_interval) 12:38:00 am last night to 8:34:12 pm today
- [fetch new](newError_report) [from](time_interval) 12:45 pm now to 8:50 last monday
- can you fetch [unchecked logs](newError_report) [from](time_interval) the 3rd on july to the 16th of february last year 
- can you [fetch new error](newError_report) [From](time_interval) the 14th and the 15th at 6:45 pm 

## intent:find_newCount
- [new](newError_report)
- [find any new](newError_report) at 12:46 am
- [new file](newError_report)
- please [fetch error](newError_report) at 6:45 pm
- [fetch new error](newError_report) 
- [find new](newError_report) [warnings](warning_level) at 8:45
- [fetch new](newError_report) at 12:30 am
- find [unchecked logs](newError_report)
- can you [find unread](newError_report) [errors](warning_level)
- [find unread](newError_report) at 8:45:00 am
- look for [unread](newError_report) at 15:45 pm
- [any unread](newError_report)
- can look for [unchecked logs](newError_report) today
- Are there any [logs i haven't checked](newError_report)
- [unmarked](newError_report)
- Are there any [unmarked logs](newError_report) at 12:45:00 pm

## intent:mark_has_read
- can you mark these logs [as read](mark_read)
- please mark this log [as read](mark_read)
- Mark this log [as read](mark_read) 
- [mark as read](mark_read) the file
- [Mark as read](mark_read) 
- mark it [as read](mark_read)
- can you mark these logs [as read](mark_read)
- can you mark this [as read](mark_read)
- can you mark them [as read](mark_read)
- please mark this log [as read](mark_read)
- please mark these logs [as read](mark_read)
- Mark this log [as read](mark_read)
- Mark these [as read](mark_read)
- Mark them [as read](mark_read)
- [mark as read](mark_read) the file
- [Mark as read](mark_read)
- mark it [as read](mark_read)

## intent:inform
- [error](warning_level)
- [warning](warning_level)
- [checked log](checked_log)

## intent:extend_dataReturn
- show me [the first](extend) 5 files that you returned
- can you [show me the first](extend) 120 files from the other files
- [show me the last](extend) 125 files from the other results
- please [find the first](extend) 154 files 
- [show the top](extend)
- show [top](extend) 14 results
- find [top](extend) 10 files
- find [bottom](extend) 12 files
- [top](extend) 20 results
- [bottom](extend) 60 results
- show [botom](extend) 30 results
- [find the last](extend) 200 files
- show me [the top](extend) 400 files
- show me [the bottom](extend) 200 filles 
- can you show me [the last](extend) file in the 
- [find the last](extend) 400 results 
- [show me the bottom](extend) at 500 files  

## intent:thank
- thanks
- cheers
- ta
- thank you
- very helpfull

## synonym:error
- errors
- ERRORS
- eror
- errror
- errorr
- errrors

## synonym:warning
- warning
- Warnning
- Warnings
- Warnnings
- Wanings
- waning

## synonym:false
- new
- find any new
- fnd any new
- any new files
- new file
- new File
- new files
- fetch error
- fetch new error
- find new
- fetch new
- unchecked logs
- unchecked log
- find unread
- unread
- unred
- any unread
- any unrad
- any unred
- logs i haven't checked
- unmarked
- unmarcked
- unmarked logs

## synonym:between
- between
- Between 
- from
- From
- frm

## synonym:stop
- stop 
- stp
- i made a mistake
- cancel
- cancel last input
- i changed my mind
## synonym:top_result
- the first
- show me the first
- show me the frst
- find the first
- find the frst
- the top
- the tp
- show the top
- top
- tp

## synonym:bottom_result
- show me the last
- shw me th last
- shw me the last
- find the last
- the last
- show me the bottom
- bottom
- botom

## synonym:instead
- substitute
- substitute with
- substitut
- in place of
- in plce of
- on second thought
- on second thougt
- rather
- rather than
- change
- replace
- insstead

## synonym:after
- thereafter
- subsequently
- later than
- afterwards
- ensuing
- next
- succeeding

## synonym:before
- days past
- previously
- prior to
- up to know
- past
- since

## synonym:count
- amont
- amount
- amounT
- Amount
- Amont
- Amunt
- AmounT
- counT
- Cont
- amunt
- Count
- cont

## synonym:details
- detailss
- Detail
- detaiil
- detaills
- detaail
- detail
- dEtails
- dEtail

## synonym:information
- Informatioon
- info
- informatio
- Informations
- infomation
- informatiion
- Information
- informatioon
- Informatio
- informations
- Info
- Informatiion