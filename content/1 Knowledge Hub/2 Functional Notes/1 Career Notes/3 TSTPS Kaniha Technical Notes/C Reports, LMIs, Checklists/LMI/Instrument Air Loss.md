- **DM plant is having a separate Instrument Air**
    
    - Compressor and receiver tank. Instrument air requirement for DM plant and CPU regeneration plant are directly supplied from the DM plant instrument air header near compressor house 
    - #pending - below drawing to be done in excalidraw
    - 

![[T4yoN1Z - Imgur.jpg]]

# **POSSIBLE REASONS FOR TOTAL FAILURE OF INSTRUMENT AIR SUPPLY:**

- Failure of **Control supply** for all air compressors:
    - IF BOTH SECTIONS OF COMPRESSOR SERVICE SWGR become dead, The alternate source of control supply to compressors is provided from Ash Water MCC Sec B
    - COMPRESSOR SERVICE SWGR Sec-A/B are supplied from CWPH SERVICE SWGR Sec-A/B which are charged from 11 KV 1UB (Unit # 1) and 2UB (Unit # 2) buses through 11/0.415 KV transformers.
    - After R&M of compressor house and CW pump house, now the control supply of compressors are not extended from Compressor service switchgear. **Now, control supply for compressors are supplied from a 24V DCDB, located at CW pump house**. This DCDB is getting power from 2 chargers, supplied from CW MCC section A/B. this DCDB is also having battery backup
        - During, failure of total 24V CW DCDB both section,
            - running compressors will continue to run, but standby compressors could not be started.
            - All control and protection will not work
            - display at UCB will not be available
- Loss of equipment cooling water supply (ECW) for compressors:
    - Normal ECW pressure at compressor house is maintained at 5.0 to 6.0 ksc (inlet).
    - can be connected to DMCW system of any of the 2 units of Stage-1.

# **ACTION TO RESTORE INSTRUMENT AIR**

- interconnection line to Stage-2 instrument air system with isolating valves at both ends, If the instrument air pressure drop in Stage-2 is severe, Stage-1 / 2 Instrument Air interconnecting V/V must be closed at either end to prevent drop in Stage-1 Instrument Air as tripping on 3.5Ksc
- IF LOSS OF DMCW ALREADY SAID AS ABOVE ALSO
    - Run 3rd DMCW if required
    - other than the main DMCW One separate DMCW line from UNIT #2 for IAC3 and PAC2, . So IAC3 and PAC2 has two sources, – one is from common header 2nd one from separate header from Unit#2.

# **PROBLEMS IN OPERATION IN CASE OF INSTRUMENT AIR  FAILURE:**

- most of the critical equipment will remain stay put, so status quo is likely to be maintained
    
- BUT SOME IMPORTANT POINTS
    
    - No oil burner can be taken in service as oil nozzle valves (HFO & LDO)will remain Closed during air fail . Also HOTV/HORV/LOTV will close on air fail condition.
    - hot air / cold air dampers, mixed air/ cold air gates remain stay put, If mill running- temp can't be controlled, if mill trips- temp rises.
    - Spray control valves will remain stay put, if required e reduce load
    - SADC will remain stay put, if any mill or oil burner is taken out DP will maintain low, For proper combustion more air flow is to be given.
    - Burner Tilt will remain stay put
    - **Seal air fan discharge damper will close on air supply fail,** but , seal air control damper remain open on air fail condition.
    - n TDBFP / MDBFP RCV will open in the event of air failure.
    - De-aerator level CV remain stay put
    - **Hot well level normal/ emergency make up and spill level control valve remain stay put, so level operation with manual valves**
    - Low load control valve will stay put
    - CEP recirculation valves wills will open on air fail
    - GSC minimum recirculation valve will open on instrument air failure
    - HP / LP heater level control valves - emergency level CV (air-to-close type) will open, while normal level CV (air-to-open type) will stay put, except for LPH-1 where its normal / emergency CV will open in air supply failure.
    - DMCW inlet / outlet DP control valve will remain stay put. This valve is air-to-open type. In the event of any air leakage in the valve operating mechanism, the valve will close and may cause high pressure in DMCW pump discharge. In that case, it’s bypass valve is to be opened to maintain pressure.
    - Soot Blower PCVs will close on air fail
    - MDBFP motor cooling water, LO cooling water, HO cooling water r isolating valve will close on air fail
    - Turbine Gland Steam admission valve will open and gland steam exhaust valve will close on air failure, Gland steam temperature control valve will also open on air failure, use manual valve to control temperature, gland steam pressure can be controlled through exhaust bypass valve,
- **NOTE:**
    
    **Although the instrument air operated equipment which are designed to remain stay put on instrument air failure, in case of leakage from the operating mechanism itself, e.g. power cylinder, diaphragm etc. the stay put condition may get disturbed. This may cause process parameters to go out of control leading to damage to equipments /machine, SO MFT GIVEN AT INST AIR LOW 3.5KSC**