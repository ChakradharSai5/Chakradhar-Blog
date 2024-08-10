[[Mills]] #pending 
	- Permissive:
    - Hot PA pressure: 600mmwcl
- Tripping:
    - Hot PA pressure <400mmwc
- [[Turbine]]
	- Logic
		- From main TG 4 temp points in case of bearing temp. taken
		- But only 3 used to show in page
		- In that 2 out of 3 is for tripping


### PAPH Guide Brg and Support Brg LOP LOGIC
For both logic is that Temp H at 70 & HH at 75, and standby pump starts at HH

- **SAPH Guide Brg and Support Brg LOP:**
    - For both logic is that Temp H at 75 & HH at 80, and standby pump starts at HH

### • **SDCS LOGIC:**

### ANB

- Auto open if all below satisfy
    - No closing order
    - ANB CV closed
    - FST Pr Not HH
    - FST Level Not HH
- Closing order if any one of following
    - FST PR HH
    - FST Level HH
- Manually can be operated only when no closing order persists
- ANB CV 2.6-6.7

### AN

- Auto open generated if all of below conditions satisfy
    - No closing order exists
    - AN CV in closed condition
    - Emergency closing of ANB
- Auto closing if any one of below conditions satisfy
    - Cond Pr high >0.4abs. around 300mmhg
    - Start up flash tank temp>90c
    - Condenser pr and flash tank dp >0.7ksc
    - BLI >60% and
        - No emergency closing on ANB
        - ANB in auto
        - ANB Iso valve opened
- Note:For 4th condition first CV closes then ISo valve closes
    - ANCV 5.2-9.3
- Thumb rule: Always open, closes if any one of above conditions satisfy once closes to open CV should be in closed condition

### AA

- Auto open if both should satisfy
    - If no closing order
    - AA CV in closed condition
- Closing order exists if any one of following conditions
    - Condensor Pr high >0.4abs around 300mmhg
    - Start up flash tank temp>90c
    - Condenser pr and flash tank dp >0.7ksc
    - Sep pr >60ksc
- Note: while light up AA closes at sep pr 60ksc Only in 4th condition first cv closes then main v/v closes, remaining 3 conditions both closes at a time
- Thumb rule: always open, closes if any one of the above 4 conditions satisfied, once closes to open cv should be in closed condition
- AA CV 6.7-10.9