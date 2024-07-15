## **COMMERCIAL ASPECTS:**

- WHAT YOU HAVE TO UNDERSTAND MAINLY HERE ARE TWO THINGS:
    - 1. AFC
    - 2. DSM- Deviation Settlement Mechanism
- 2. DSM:
    
    - In 2022 CERC did many experiments, in the middle they removed incentive linked to freq stabilization to the sellers, which created a huge problem in managing the grid frequency stabilizing.
    - So after multiple trials they have formulated the below way that i am going to tell now, effective fro 2023 08 Feb
    - There is something called NRCD normal rate of charges of deviation which is
        - = highest of [ the weighted average ACP of the DAM/RTM of all the Power Exchanges] for that time block: subject to a ceiling of Rs 12 per kWh
    - For us reference charge rate= energy charge rate RCR=ECR
    - First, remember the rule that for any deviation from SG, there is a pool called Deviation and Ancillary Service Pool account, and that account gets either seller pays in it, or seller gets paid by grid into it.
        - Ideally**(means freq=50.00Hz**) suppose if i am seller and i generate more than SG, for that deviation i shall get paid 100%ECR, that much money gets deposited in that DASP account, as I have generated extra power and it is only fair that I should get back amount how much ever it costed me(ECR) for generating that deviation.
        - Same way ideally**(means freq=50.00Hz**) suppose i generate less than SG, i will pay in to 100%ECR DASP account, as actually i did not spend that much amount while generating power., so it is only fair that i should pay back grid how much ever(ECR) I saved while not generating that deviation power.
    - Now CERC gave us this “Ideal” margin as 49.95-50.03Hz, if freq is between this I can generate more than SG or less than SG, I gain or lose nothing.
    - BUT if freq goes less than 49.95Hz or more than 50.03Hz, then depending on whether i generate more or less than SG, I shall be incentivised or penalized.
    - And this is done exactly as follows
        - 1. If freq 49.95-49.90Hz
            
            - If AG>SG
                - As I have generated more, I should get paid and “ideally”, at 100%ECR, but since its good for grid grid pays me 120%RCR
            - If AG<SG
                - AS I have generated less, I should pay back grid and “Ideally”, at 100%ECR, but since its bad for grid, I should pay back 150% RCR
        - 2. If freq <49.90
            
            - If AG>SG
                - 150%RCR shall be paid by grid to pool
            - If AG<SG
                - 200%RCR shall be paid by us to pool
        - 3. If freq 50.05-50.03Hz
            
            - If AG>SG
                - 50% RCR shall be paid by grid to pool (50% RCR loss )
            - If AG<SG
                - 75% RCR shall be paid by us to pool (25% profit)
        - 4. If freq > 50.05Hz
            
            - If AG>SG
                - Nothing will be paid by grid to pool, so total ECR is loss
            - If AG<SG
                - 50% ECR shall be paid by us to pool 50% is profit
    - IF freq is between 49.95-50.03Hz, deviation should stay within 10%, as long as it is in 10% of SG, AG>SG or AG<SG, we will be paid RCR, or we will payback RCR, so no loss and no gain
        - If it goes beyond 10%
            - If AG>SG
                - Get paid nothing, so loss=ECR (the fuel cost that you burnt)
            - If AG<SG
                - You have to pay at 120% NRCD (so loss=120% NRCD-ECR)
        - If it goes beyond 15%
            - If AG>SG
                - Gets paid nothing, so loss=ECR(the fuel cost that you burnt)
            - If AG<SG
                - You have to pay at 150% NRCD(so loss=150%NRCD-ECR)