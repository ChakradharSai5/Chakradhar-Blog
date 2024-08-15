---
date: "true"
---
- For MLDB there are two sources each from SSS-A & SSS-B
- For welding DB single source only from SSS-A
- **To put MDBFP & TDBFP in auto**
    - after loading TDBFP , make sure both suction flow maintaining around same value then put TDBFP remote permissive ok, then put TD in auto, later put MD scoop in auto. now you can give SP from FW station in manual. [[Pni]]

- - **LPBP protection checking**
    - [[1 Knowledge Hub/2 Functional Notes/1 Career Notes/3 TSTPS Kaniha Technical Notes/LPBP]] tripping on spray water pr low is in switch 
- - [[Service air pressure]]
    - goes to only GGG, APH air motors and now atomizing of LDO. & instrument air to only valve operation
- Unit 2 [[Overhauling]] around 9200 joints in 2022
- - •While putting[[ TG in barring]]
    - if FG kept in auto and given stop sequence whole barring including LOP, JOP will stop, which is dangerous, So to stop barring, FG to be taken in manual and only barring motor to be selected and stop command to be given to motor. In this case only the barring motor will stop & JOP & LOP will be running; also to start barring motor put FG in auto and start the sequence.
- - **Machining of [[Generator]] motor:**
    - In Unit #2 [[Overhauling]], rotor taken out *did* OH and then kept again back inside, while being taken out, I have observed rotor has very **less** *clearance* to jiggle to take out, so what they did is- there are two metal hooks on floor, they tied a big chain to rotor and ran these chains through hooks, with pulleys man slowly pulled it out, parallelly eot crane gave support while it is being hold while being taken out
    - After OH when rotor kept inside, rotor is to be machining for proper sitting of brushes on it, to put brushes-as they said- requires perfect circle, so they did machining like lathe, for this they will run barring motor for some time to do machining and stop the barring motor to measure the dia and **then** again they will put in barring to do machining, this continues for hours together.
- - [[MFT]] [[Pni]]
    - If BLI > 65%,
        - One BFP 20sec
    - If BLI < 65%
        - No BFP 10sec
- 415V [[UPS]] supply taken from USS-A and USS-B, UPS-1 and UPS-2 #pending 
- Stress limit is at 60%, if it goes below 60% can load further [[Main TG rolling]]
- during [[Main TG rolling]] At 1900rpm, to some rpm HPTs critical speed, so only IPCV will be used for increasing speed of Turbine #pending 
- [[Main TG]] overspeed exact rules #pending 
- How many exact safety valves are there for our de-aerator and what is their set point #pending 
- Revision plan for giving DC is #pending 
	- If you give DC declared in this block, the revision gets effect in next 7 th block(including this block), if this block is even
	- If this is odd block, DC gest effect from 8th block (including this block)
- Oil injection in [[TDBFP overspeed test]]  #pending - how is it similar to [[safety valve lifting]] or trevy setting
- [[- HP Bypass]] #pending 
- [[- LP Bypass]] #pending 
- Passivation of boiler at 12ksc, after or during [[Overhauling]] #pending 
- After [[Overhauling]]they trip unit on RH protection [[Pni]] logic why is it so?? #pending 
	*this is for checking*
- 100% [[BMCR]] is 560MW as mentioned in CLCS document
- [[BID]] 0-100% = 0-600MW, mentioned in CLCS document
-  I think #pending [[BLI]] is nothing but steam flow, as mentioned in ST-1 Pni document for SDCS
- As per scheme [[FG VAM]] AC CT make up is from clarified(main) and service water(alternate), but when clarified is not available, Service water makeup will not be sufficint, so temporary tapping available taken from Fire hydrant
- All ASPH series water pumps sealing is from 
	- main source: clarified water
	- alternate: fire hydrant
- AC CT makeup of main unit
	- main source: clarified
	- alternate: fire hydrant water
- When putting in Nload without exication, no need to press go see if stpes incense , if not then press go
- Water flushing from separators or de-aerators involves taking samples and measuring chemical parameters. However, only parameters within a specific range can be measured accurately. Turbidity must be below 5 for other parameters to fall within the measurable range; otherwise, they will be out of range.
- HRH vents that is connected to RH outlet header I think, is being used for maintaining normal pressure at RH tube leakage welding, as too much air sucking, or air coming out will not help for welding by BMD
	- so to do that, what we do is, we close all RH drains connected that is at 48mtr or 5.5mtr master drain and atmospheric drains, and we close or open RH vents at RH outlet header, as `opening that RH header vent will suck the air, and closing the vent will throw the air out`, so what we do is we kept one close and open- but note that both are in series, so passing. 
-
-  
-  **Temp increase for TDBFP aux steam source**:  so recently when we charged aux steam source for TDBFP, as we need steam temperature to be more than 55DegC which usually takes some time, that day it seems it is taking longer than usual, so we thought as flow is very limited which is through atmospheric drain, the temp. increasing very slowly, we searched for any other drains from that aux prds header, finally it took us long.
	- but when we charged aux prds to de-aerator pegging source temp. improved quite quickly suggesting the steam flow that was necessary for rapid increase is huge
- **MDBFP suction became steam** recent flushing of boiler with MDBFP running and draining from separator, MDBFP tripped with sound from booster pump and suction flow and pressure got drastically decreased,
	- however later we deduced that as somebody reduced de-aerator pegging steam pressure to around 1ksc, or lesser to get chemicals parameters quickly.
		- as condensate flow to de-aerator is at lower temperature, the overall temp of water in deaerator came down below 100DegC and so as expected, stem formation happened at MDBFP suction resulted in pumping action of steam resulted in sudden pressure drop and suction flow drop and severe sound
	- of course incidentally, MDBFP suction strainer also found to have with lot of waste(resin- that's [[Unit stopping due to ACC high]] story)
- During shut down, we wait till complete depressurization of boiler to kill the vacuum, as it goes in parellel with CRH pressure being not avilable for gland steam also to hold the vacuum. but meanwhile we should not charge the gland steam from aux prds as some temperature of 300 Deg C  issue #pending 
- In recent this resin passing- [[Unit stopping due to ACC high]], after overhauling they did not remove the commisioning strainer in two CEPs and one TDBFP, both CEPs got choked while unit running, but TDBFP didn't get choke, I suspected why, after this [[Unit stopping due to ACC high]], checked and found tthat it's suction strainer got damaged that is there is a big hole in strainer, leading to passing of wtaer freely, it seems that it got so much choked and so got burst open makin hole in strainer


# all below this need to be reviewed for repetetion and placed on respective places

- **Cold water flushing**
    
    - at the end of OH, cold water flushing is one to ensure to flush out all the dust and tissue waste developed while welding, that is done whit CEP running sending water to deaerator and then from deaerator to boiler with MDBFP, from there to separator, from separator to condenser through AA/AN valves.
    - It is observed that with 200tph AA found to be at 14% open
- **While CEP isolation**
    
    - thrust bearing water isolation not required if work not related to bearing inspection, bcs that is a closed system
- **To take a MOT centrifuge in service**,
    
    - first ensure suction valve is closed, it is ok if discharge valve is open. Then close the sludge tank drains. Now start seperator motor. while separator motor running, open seal water slowly, observe in view glass, if you find water coming from view glass, close the seal water. And slowly open I/L valve(if discharge is clsoed open discharge also very slowly). Adjust I/L &O/L valve so that we get around 4000 in flow indicator. and discharge pr maintains around ksc
- • **MDBFP of stage-1** start up
    
    - SOV closes after MD-c starting with a delay of 10sec, to make sure starting current die down.
- **FCNRV**
    
    - Ex-2 FCNRV is found to be in closed condition, found from LPH-2 inlet pressure maintaining low, later, PTW issued to TMD and they have attended inside bellow damage, for that isolation done with upstream MOV closing. Later after PTW cancellation, FCNRV power supply normalized but it did not open, later it is found that air supply to that FCNRV is in isolated condition, later C&I rectified it and it got opened.
- **Learnings during mini overhauling:**
    
    - 1. As 11kv buses 2UA and 2UB charged with St-1 during mini OH, and also 1UB also loaded, as UT-1B not availabl
    - 2. To keep St-1 load minimum while lightup U1 MD-c kept in manual, and in U#2 lightup only one set of id and fd fans taken I/s, and unit syched
    - 3. After synch first one of the buses c/o done to unit load, and after around 50mw another bus also changed to unit load
    - 4. And then remaining id and fd, both pa and then purged and then mill taken i/s
    - 5. Then unit -1 mdbfp kept in auto
- **Learning on HPCV and IPCV operation:**
    
    - 1. During mini OH I have seen full opened HPCV and IPCV, there is one pilot and one main valve
        
        - Pilot valve operates with control oil from EHC
        - Main valve operates with power oil from direct Control fluid pump
- • **Learning on MSP Min op set on DCS CMC Page:**
    
    - We can use MSP min set point variation for closing HPBP while HPBP in external sp mode
        - i.e we can increase msp min sp 85 to 86 to 87 and slowly let hpbp close, and as soon as it closes, hpbp goes to internal sp mode and turbine to ip mode.
    - But we CANNOT decrease MSP min set point variation for opening of HPBP as this is a minimum block sp, the command that goes out takes actual one as that higher than this.
    - **Note**: minimum block means max of all inputs will go out
    
- 1 hfo gun hour= around 2kl consumption
    
- 1 ldo gun hour = around 2.kl consumption with 8ksc, as mentioned in technical dairy
    
- Cst 1m = around 80T
    
- Coal scanner freq 5Hz
    
- Oil scanner freq 30Hz
    
- BID 0-100% = 0-600MW
    
- 43mtr has access to conveyor belts in boiler
    
- MDBFP-C should be started directly without taking it in manual, to get it loaded to current feed water requirement.
    
- Feedwater flow shown in main parameters page is at just after FRS so = TD-A suction+ TD-B Suction- RH spray flow
    
    - Feedwater point shown in FW master is evaporator flow that too after SH flow tapping taken form ECO outlet
- HFO 1mtr = 378kl
    
- LDO 1MTR= 78kl
    
- For APC in stage-1
    
    - 5.75% if tdbfp,
    - 0.8 if tube mill, and
    - 0.5 if idct so total **7.05**
        - but for stage-2 5.75+0.5 so total **6.25**
- • **Learning from hydrotest incident:**
    
    - Filling done with CEP discharge and pr increased to 30ksc,
        - Found water coming from MS atm drain l & r meaning passing of MS V L & R
        - Found water coming from CRH atm drain of common CRH line but not from upstream CRH NRV atm drain meaning passing of HPBP or HPBP spray valve, but CRH NRV able to hold i.e. no passing of CRH NRV
        - . So later both MS SV opened and closed and HPBP spray manual valves tightened, water from drains slightly decreased
        - Later MD-C taken I/S with first IBV opened and charged and then Main MOV opened
        - Rate of rise can be >0.5ksc/min up to MSP<100ksc, after MSP>100ksc , rate of rise should be <0.5ksc.
- **TDBFP OS LEVER MECHANISM:**
    
    - the lever that we pull for generating trip oil, is inside mechanism is in such a way that like tick- tick pen, when once gets inside it generates trip oil and locks itself, so by remving back the lever trip oil don’t trip.
    - Also at the other end of this lever part, there exists a curvature kind of thing which in turn connected to
- **TDBFP ISOLATION**
    
    - TDBFP casing temp usually maintains around 175C and after stopping the TDBFP, and decoupling of booster pump, and closing of suction valve, casing temp decreases at the rate of 5-6 deg per hour. So it will take around 10-12 hours to reach 110C and so pump can be drained
    - impulse chamber temp usually maintains at around 290C and just after stopping decreased to 275, and drop at a rate of around 7-9 deg per hour, and so to reach 120 deg takes around 19 hours.
- • **UNIT-1 ID FAN STOPPING LEARNING:**
    
    - we took MDBFP just in case if after load reduction if HP pressure comes below 7.5ksc, which may lead to trip to TDBFP.
    - MDBFP loaded and TDBFP unloaded kept in only recirculation.
    - TDBFP with only recirculation loading i.e, 300Tph, exhaust temp increased up to 90C and got stable around the same. It did not trip on exh temp hh as expected.
    - and HP Pr also did not come below 7.5kcs, infact it maintained around —--------
    - Load decrased to around 300MW, first FD unloaded maintaining 1100Tph, later ID unloaded.
    - as per procedure with FD around 1100Tph, with load at 300MW, draft should be negative, but due to duct leakages, draft maintaining positive, still we kept positive around 10mmwcl and BMD
- •  **As only one series in service for a long time**,
    
    - and so sump level got full, 100 both. Unit -2 fly ash completely stopped, i.e no vacuum pump running for more than 1 hour. and satish from Gen shift told we can run more than 2 hrs without fly ashing. but we ran only 1 hour.
- tdbfp suction discharge DT tripping in stage-1 is along with suction flow low exact logic to be known from prasanth tripaty #pending
    
- IAC and PAC scheme
    
    ![Untitled](https://prod-files-secure.s3.us-west-2.amazonaws.com/94325ba9-d7c6-4aaa-a384-0aa70ea079a3/05b864b5-06eb-4a5d-a760-308a1ae90d4d/21323.jpg)
    
- **Stage-1 IAC found unloading at 8ksc**
    
    - but this pressure is at local guage, not that is shown here in DCS, and that gets reset, that is we get permissive to take it again at 7.3ksc
- **For large HT switchgears**
    
    - we have to actually dead the bus and then charge it again is what happening in stage-1 as stage-1 logic of trip selection is not available or any other reason it is not clear, but for LT trip selection is there accordingly, changeover happens,but in HT usually bus is made dead and then charged again
- **VACCUM IN STAGE-1**
- ![[p4j4STu.png]]
- **OFFSITE ash handling:**
    
    - • Indure company 15cr package
- Startup txr-1 changeover source from 220kv main bus to transfer bus changeover was being done, while doing that it is noticed that,
    
    - When 220kv breaker of st-1 side got tripped and proper changeover did not happen, because of that downstream breakers to SA and SB bus got tripped
    - In electrical there is a protections that in a transformer if HT breaker of any transformer trips , LT also trips , but NOT vice versa, it is called upstream—downstream breaker logic
- • Unit-1 got tube leakage dated18-08-23, but before identifying tube leakage an interesting thing happened
    
    - Suddenly Ms and HRH both single limb temperature dropped severely to some 275deg and draft increased to –6mmwcl and stayed
    - **Important thing to note here is immediately load was reduced to 275MW , technical minimum. This is to be remembered**
    - Usually variation in MS or HRG huge variations cause leakage in waterwall, and HTRH leakage happens usually due to erosion
- • Vacuum pump found to auto start at 640mmhg in TG ABB system, and usually from the TG ABB system Vacuum in mmhg is 9mmhg higher from DCS vac mmhg value
    
- Capability test done at MS pressure 170ksc at turbine inlet, which is said to be rated pressure at turbine inlet
    
    - Unit 1 able to get 503MW
    - Unit-2 able to get 512 MW
- Stage-1 2023-24 seasonal peak times
    
    - HD season 2023-24 :April '23 to June '23
    - LD season 2023-24 : July '23 to Mar '24
    - Peak hour
        - Aug 2000 to 2400
        - Sept 1900 to 2300
- Stage-2 seasonal peak times
    
    - HD April '23, Feb & Mar '24
    - LD May '23 to Jan '24
- Scanner frequency:
    
    - Coal scanner 30Hz
    - Oil scanner 5Hz
    - Minimum intensity required for sensing of flame 35%
- ACDB
    
    - ACDB -------------------> Turbine ACDB both sec A & Sec B 12.5mtr
        - --------------------> Boiler ACDB Sec A & Sec B 27mtr
        - ----------------------> Station ACDB Sec A & Sec B 3.5mtr
- Battery scheme in Stage-1 units:
    
    - 390V DC battery for UPS chargers at 8.5mtr SWAS room
    - 24V DCS battery
    - 220V DCDB battery charger one from EMCC, one from USS at 3.mtr swgr, and battery bank at 3.5mtr
    - 24V TG charger one from TACDB and one from EMCC at 12.5mtr swgr and battery bank at 12.5 mtr
        - As told by phani sir EMD, currently there is no 48V charger setup, but supply taken with 24V in series
- Vibration limits
    
    - Decouple 20/2 normal limit
    - After Coupling 40/6.4 normal limit
- Resistance for rotor earth fault protection logic
    
    - Normal resistance maintains 35k ohm
    - Resistance 25k 5 sec alarm
    - Resistance 5k 1sec trip
- Shut down time HPBP handling:
    
    - When load is conveniently less, say presssure around 95ksc, take HPBP in manual and open it slightly and I think parellely take unit in MW controller, now keep HPBP in auto , but as soon as you keep in auto, immediatley put it in External SP mode
    - Now what this does, is as external SP will give continously 85ksc, this HPBP will try to maintain 85ksc by slighlty opening/closing, preferably opening as closing causes to go Turbine into IP mode
    - So now maintain boiler loading such a way that ms pressure is greater than 90ksc and now you decrease load set point in mw controller so that to maintain 85ksc, let HPBP slightly open.
    - Now continously decrease boiler loading and perallely load sp, and continue to maintain 85ksc at T intlet, just remember don't let HPBP close.
    - later when load is around 70MW, you can trip the Turbine
- Ash pond Sec-B isolated, charged though bus coupler, during big switchyard PTW 220kv. not sure
    
- Before overhauling starts welding DB, AC MLDB, DC lighting DB PTW will be taken as during overhauling this is required and this PTW cannot be taken during overhauling
    
- ASS Fluid coupling oil pump and GB oil pump alternate supply provided
    
- To reduce APC St-1 raw water P/p-1 , 3,5 I think need to be stopped
    
- Light up learnings:
    
    - AT around 100ksc, FW 071 to be opened
    - To put Feed water in auto the main thing is see that
- CRH pressure shown in boiler is the pressure of steam that is going to the boiler, but CRH pressure shown in TG log is the pressure at HP Turbine inlet, so before turbine rolling CRH pressure of boiler side can be seen as HP bypass is open, Turbine side CRH pressure is shown zero
    
- After OH, MS Silica did not come in range for turbine rolling, so what they did is they decreased overall steam flow
    
    - by taking out oil guns, causing MS Pr to drop slightly causing HP bypass to close slightly to maintain 85ksc,
    - They said by decreasing steam flow it will cause MS Silica to decrease,
    - Kind of a trade off is less margin in HP bypass
- During overhaulig light up LP bypass trip
    
    - because of less margin in CEP discharge pressure, D/A control valve not opened further, so hotwell level increased to almost 1500, causing to LP Bypass to trip
    - led to HRH pressure drastically increased to around 50ksc
    - so immediately we decreased hotwell
        - and then after hotwell level high reset, LPBP made reset
        - ensured LPBP stop valves opening, then took LPBP CV in manual and opened slowly upto previous opening around 30%
        - when HRH pressure reached around 12ksc, kept in auto
- during light up
    
    - Hot well temp increased and so ANB slightly opened to 10percent, as AN is in auto to maintain level, now AN will close slightly , causing less steam to go to hotwell, and so temperature of hotwell decreases
- Main TG overspeed checking, with ashok sir
    
    - what happened is during
- As stage-1 and stage-2 have different beneficiaries, I guess because of that St-1 ERLDC and ST-2 SRLDC
    
- 220kv Total Switchyard PTW
    
    - all buses, main bus-1 and bus-2 and transfer PTW issued to EMD, to put extra tapping for FGD power taking, FGD transformer I think
    - for that, they needed completed all three buses shut down and isolation
- TD-B barring stopped at bearing temperature 45DegC, and then lube oil system stopped to facilitate maintenance work but bearing temp. found increasing to 67DegC, around 20DegC
- - Generator voltage will be measured every week at two ends, one at excitor end and one at generator and turbine end to see any resistance- usually will be i think will be megaohms
    - resistance between direct touching rotating shaft using brush and earth by connecting a small brush to long stick and touching shafft from distant
- Deluge valve has a supply of 24V, i think will be seen by TG 24V
- Fire hydrant pump-1 is in Unit-5
- **Mill tripping**
	- Ignition loss and trip requires 3/4 vote loss and feeder ins stop condition
- DM Plant has its own instrument air compressor air system & receiver tank for DM plant and CPU regeneration plant
- Paph air motor bypass valve rubber passing, once opened that valve, when closing, air is passsing, but same line upstream isoalation valve if closed, and opeend, then this valve is holding, this happening becasue a rubber gasket in first isolation valve is passing and so able to close properly when there is no pressure of air.
- Feeder tripping on ZSS is in 30sec of non acting of swithces, of both swtiches has to act

- Some diaphragm in IAC_3 and PAC-2 problem casuing it to not load, once unloads, what exactly is diagphram and how it works and how is it in LP turbine also, what do they mean when they say it breaks #pending 
LIGHT up random learnings:
- TDBFP gives 100Tph roughly at 1000rpm, during rolling this has be confirmed
- Gland steam changeover done at 40ksc Ms pressure from AUx to CRH
- APH puppet valve supply is from the CESB APH module itself
- APH puppet valve operates at 3.5ksc, if puppet valve continously opens diagphram gets damaged #pending 
- Flame not sensing and if PA flow > 50Tph no mill tripping ?? #pending 
- ANB kept in auto at around 80MW, now opening at 30% with level being maintainied in auto
- suction valve passing is found by noticing that after isolation, even with suction valve closing, drain pipe found sucking so it is concluded

### Module modification for better safety in TSTPS
- Recently nov 2023, some LT modules PTW taken by EMd, to change the scheme of fuses and isolator,  
- As currently, while fuses being taken out, the scheme is in such a way, that fuses directly come in contact with phase supply even with isolater off, that is , from supply side first fuses comes and then it goes to isolator 
- So now they are simply reversing it,. For safe isolation and normalization
### Vacuum pump command in St-1 TSTPS
- Vacuum pump command in TG is in a SR flip flop type way, so it is a KIND of a continuous command,  

- Vertical strainer drain of TDBFP is going to TG flash tank at 8.5Mtr
- there is an oil gun cleaning line from steam in 32Mtr or 45Mtr, hat is used for oil gun cleaning
- DG-2 level should be maintained above 85%

### Cold junction compensation
- Temperature probesif CJC wasa not on, it compensates temperature value to show exact value if it is off, it will show atmospheric temperature added say around 30DegC extra added


In stage-1 we have gravimetric feeders so we don't have load cell, and we need to caliberate like some kg/ 60sec like that


