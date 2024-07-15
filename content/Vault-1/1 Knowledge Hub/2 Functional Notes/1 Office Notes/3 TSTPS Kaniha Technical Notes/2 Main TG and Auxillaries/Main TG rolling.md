

Rolling exact steps and notes related to that #pending 
- Main TG soaking will be done, if it is cold rolling, if the HP mean rotor termperture goes below 150DegC, then Turbine startup will be cold, and soaking speed is 1100rpm for 20mins
- Speed gradient depends on 
	- cold - gradient - 15% i.e 90rpm/min
	- warm - gradient- 50% i.e 300 rpm/min
	- hot - gradient 100% i.e 600 rpm/min
- Block load is 5% = 30 MW
- For rolling
	- MS temp. less than low logic
		- if HP inlet temp. LBA10CT010 XQ50 should be more than 33DegC of saturation steam temp. of corresponding steam pressure


## Modes in TG rolling

## Learnings

- When unit in turning gear mode, which means it is barring mode.
- Vacuum pulling and gland steam charging shall be done by putting turbine in by pass mode, that will be done by, 1. click on Fg auto , select off/manual
- 2. select bypass mode.
- 3. sequence starts and vacuum breaker closes and vacuum pump starts
- 4. at vaccum builds

## **What is prs synch**

- If it is selected then a relay gets activated, to synchroscope that we(Main TG) ready for synch
- That means we after getting 3000rpm at 85ksc and HPBP some 35-45% margin, we tell synchroscope that we are ready from our side for synch
- So the next step would be that synchroscope starts rotating and GCB gets closed after some time
### TG rolling
## **Turning gear mode**

• Will be in barring at 11rpm

## **Bypass mode**

- To pull vacuum, put it in bypass mode
- Ensure vacuum system, Gland steam system( and aux steam drain of gland steam inlet valve in open)
    - Min 150C required at gland steam aux inlet permissive
- Both vacuum pumps get started and gets loaded
- Vac breaker gets closed on its own
- Vac builds up to 200mmhg
- Then if everything ok, gland steam admission valves gets opened and builds pressure and you ensure GSE taking start, and Gland steam pressure improving to 0.005ksc. And temp. to around 170C
    - If gland steam to be charged manually
        - First open the vent valve before admission valve, and ensure temperature of 150C, and then, open the exhaust valve slightly and then open the admission valve, because if any water that is getting admitted, immediatley can escape thorugh exhaust valve
        - In stage-1 our TG is built in such a way, that sometimes people charge the gland steam without opening exhaust valve, but it's going fine
        - But same thing if done in stage-2 causes severe barring stalling
- (in gland steam scheme, admission side has manual valve in CV line not in MOV line)
- In this mode HPBP & LPBP will not open
    - LPBP in manual and tripped condition
- You can keep HPBP in start up mode causing it to open to 20%
- Reset LPBP causing it to open LPBP SV and I think to be kept in auto
- **Now after 85ksc and 370degC achieved** and rolling clearance available with 55deg saturation margin permissive
- Generator reset from the back side panels at generator panel, and ensure all generator alarms got reset
-  Now reset the main turbine, Resetting causes SV to open, ensure it with MAX 51, bcs it is the main oil that gets to opening of stop valves
## No load
- and then put it in Nload mode( which is basically no load without excitation)
    - in which rolling happens, and Cv opens and slowly speed increases to 3000rpm
## **No load with excitation**

- After reaching 3000rpm, kept in this mode, basically we build excitation, as while turbine rolling only we can generate excitation field, which goes to transformer and then from there as Excitation voltage
- Excitation breaker is closed
- In this you field breaker gets developed field and stuff
- They increase the voltage to 21kv around
- And then GCB is selected and ATRS is made on from the electrical panel that they operate manually with Check key
## **Kept in load mode**

- Then kept in Load mode, You have to give GO - a very important thing
- And then selection of prs synch will on two relays
- And selection of synch device on with enable another relay
- Then automatically synchroscope gets on
    - Provided key kept by emd and rotated

• Once synchroscope gets synched then load setpoint gets to some 17MW and then you have give and go on and increase load to aroung 50MW