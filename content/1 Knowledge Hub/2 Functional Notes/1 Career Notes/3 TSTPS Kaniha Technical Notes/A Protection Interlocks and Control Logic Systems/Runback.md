RUN BACK:
- Actually the logic is quite simple
    1. The steady state condition assumed is 2ID, 2FD, 2PA, 2 CEPs, 2 APHs,  4/5 Mills
    2. Now if any of these
        1. one ID to **325MW**
        2. One FD to **325MW**
        3. One PA to **325MW**
        4. Loss of two CEPs to **325MW**
        5. Loss of all CEPs to ***Boiler Minimum load**
        6. One APH to **325MW**
        7. Loss of a Mill "Side" causes by **70MW**
        8. Turbine Tripped to **300MW**
        9. MFT operated to **0MW**
    3. Run back rate default set at **87.5MW/minute**
    4. When runback acts Mill if running more than 3 mills, brings to 3 mills, by tripping top Mill/Mills/Mill sides, actually brings to 6 feeders, how many ever feeders running, top feeders.
    4. Unit may be running in whichever mode - CMC or BF, it trips to TF mode, causing Turbine to Initial pressure mode, so that Turbine CV gets full open causing max load possible at that time to be at disposal
    5. My understanding -
        A.  when  say some drive tripped and run back acted - Unit comes to TF if not already, and if already in CMC then Load SP of 325MW or 300MW or 0MW goes to Boiler master and in turn to Mill master causing to Mill demand signal to decrease
        B. Say unit not in CMC, then usually we keep mill master in manual and so, though the Load SP changes to 325MW, accordingly Boiler master changes, and that command goes to feedwater and air flow, but does not go to mills, as mill master is not in cascade mode boiler master command shall not go to Mills, so finally we have to manually decrease mill loading/ firing
        



