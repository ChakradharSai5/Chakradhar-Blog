#OfficeNote
## HP Bypass
?
- HP bypass capacity 60% of steam flow
- **Startup mode**
    - Initially when the boiler O/L pressure (MSP ) < 6ksc
        - Opens to 20%
    - When MSP increased upto 6ksc 20%
    - After getting 6ksc, maintains 6ksc by opening upto 35%
    - After getting 35%, stays in at 35%, until 85ksc achieved
	    - during hot-startup interesting thing happens where, if the rate of rise is more than certain value, (Not sure how much), hp bypass though in start up mode opens more than 35%
	    - then what we do is, one person keeps the hp bypass in auto, at the same instant other selects startup mode
    - After 85ksc goes to External setpoint mode
- External setpoint mode:
    - Now external setpoiint given from CMC desk
    - After synch and and load increasing, BP valve closes
    - Once closes immediately it goes to Internal setpoint mode
- Internal setpoint mode
    - Once closes, Current MS Pr.+ 9.5ksc goes as set point so as to make the HPBP stay closed in running condition
- At boiler pressure 187.5ksc HP bypass goes to pressure control mode
    - That is in that mode simply setpoint changes to 187.5ksc and so HPBP gets opened
    - Only when the MS Pr. Drops below to 187.5ksc, HPBP closes and so enters DP control mode(or internal setpoint mode)
- Also it goes to Pressure control mode when MS Pr. Gradient goes beyond > 5ksc/minute
- In middle of lightup, came out of start up mode due to rate of MS pressure high, HPBP opened more than 35%, don't know wahta it is maintaining, so what we did is, took HPBP in manual, kept in auto and immediately kept in start up mode. So that it will stay in 35% open, upto 100ksc /not 85ksc as it is hot startup #UrgentThing
## LP Bypass
?
- LP Bypass
    - Upon receiving load rejection signal from electrical system turbine controller assumes control of TG set
    - It gives fast command for fast closure of HP/IP Cvs through position controller
    - Fast closure causes immediate decrease in HP first stage pressure
    - Pressure increases in MS and RH steams
    - These pressure changes sensed by HP and LP bypass and so opens
<!--SR:!2024-07-06,3,250-->