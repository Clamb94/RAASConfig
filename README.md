## vRAAS for MSFS

Our vRAAS system provides runway awareness and advisory features similar to real-world systems.  
All functions behave **exactly** like the real ones and can be disabled if desired.

- vRAAS works on all airports (including 3rd party add-ons)
- vRAAS works with all aircraft
- Text Display on PFD/ND (see notes below)
- No setup required
- Auto-Updating
- Auto-download of aircraft-specefic configurations
- Female/Male voices
- Fully customizeable
- Auto-start and auto-close option
- Minimize-to-tray and minimized-on-startup available
- No measurable fps impact
- Any windows sound output device selectable
- Working self-test

Limitations:
- Text Display on PFD/ND is experimental and may get disabled/broken by future MSFS updates
- Due to MSFS limitations, the **_TOO FAST_** callout is only available on some aircraft

**MSFS 2024:**
vRAAS has been tested with the MSFS 2024 Tech Alpha and everything worked fine.
Until we can test the final version, we cannot gurantee that all vRAAS feature will be working in MSFS 2024.

## Aircraft compatiblity list

Generally, vRAAS audio calls work with all aircraft, including 3rd party addons.
However, some features require additional configuration or fine-tuning.
The following aircraft will work perfectly without any configuration from your side.

**vRAAS Audio**: Audio calls, generally available for all aircraft
**vRAAS Display**: In-Game RAAS text messages displayed on PFD or ND 

| Developer                 | Aircraft                   	| vRAAS Audio 	| vRAAS Display | NOTE 	|
|---------------------------|----------------------------|:----------:|:------------:|------|
| FlyByWire                   | A320neo                    |      ✅     	|       ✅      |1)      	|
| Fenix                       | A319/A320/A321             |      ✅     	|       ✅      |1)      	|
| FlightSimStudio FSS         | E170/E175/E190(F)/E195(F)  |      ✅     	|       ✅      |      	|
| FlightSimStudio FSS         | B727                       |      ✅     	|       ❌      |1) No displays to show vRAAS Text. |
| Horizon Simulations         | B787                       |      ✅     	|       ✅      |      	|
| IniBuilds A306F             | A306F                      |      ✅     	|       ✅      |1)      	|
| iFly			              | 737-MAX8                   |      ⚠️     	|       ⚠️      |1) RAAS included in aircraft. vRAAS disabled by default.       	|
| Leonardo                    | MADDOX X                   |      ✅     	|       ✅      |      	|
| LatinVFR                    | A330-900neo                |      ✅     	|       ✅      |1)      	|
| Headwind Simulations        | A330neo					   |      ✅     	|       ✅      |      	|
| Microsoft / Default         | A310                       |      ✅     	|       ✅      |1)      	|
| Asobo / Default             | B747-8i                    |      ✅     	|       ✅      |1)      	|
| Asobo / Default             | A320neo                    |      ✅     	|       ✅      |1)      	|
| Asobo / Default             | CJ4                        |      ✅     	|       ✅      |1)      	|
| Asobo / Default             | Citation Longitude         |      ✅     	|       ✅      |1)      	|
| Asobo / Default             | C208 Grand Caravan         |      ✅     	|       ✅      |1)      	|
| PMDG                        | B737 (ALL VARIANTS)        |      ✅     	|       ✅      |      	|
| PMDG                        | B777                       |      ✅     	|       ✅      |      	|
| ProSim                      | B738                       |      ✅     	|       ❌      |1) vRAAS cannot access ProSim Display. |

1\) **_TOO FAST_** callout during approach is currently not available for this aircraft due to missing data from add-on.

Your favourite aircraft is not listed? Feel free to send a request on our Discord!

## Available Callouts

### Ground Operations

1. **Approaching Runway (on Ground)**  
   Informs when approaching a runway during taxi operations.  
   **_“APPROACHING RUNWAY 25 LEFT”_**

2. **On Runway**  
   Confirms runway location when the aircraft is lining up on the runway.  
   **_“ON RUNWAY 25 LEFT”_**

3. **Takeoff Flaps Configuration**  
   Advises if lining up on a runway without a valid flaps setting for takeoff.  
   **_“ON RUNWAY 25 LEFT. FLAPS! FLAPS!_**

4. **Extended Hold on Runway**  
   Cautions the crew if the aircraft holds on the runway for an extended time.  
   **_“ON RUNWAY 25 LEFT. ON RUNWAY 25 LEFT._**

5. **Insufficient Runway Length on Ground**  
   Warns of insufficient runway length for takeoff.   
   **_“ON RUNWAY 25 LEFT. 500 METERS/FEET REMAINING”_**

6. **Short Runway Takeoff Warning**  
   Alerts when the remaining runway length is shorter that the nominal runway length.  
   **_“SHORT RUNWAY! SHORT RUNWAY!”_**

7. **Distance Remaining (Reject Takeoff)**  
   Announces runway distance remaining after a rejected takeoff.  
   **_“1500 ... 1200 ... 900 ...”_** (meters or feet)

8. **Taxiway Takeoff (Advisory)**  
   Advises when the aircraft is not on a runway and accelerating for takeoff.  
   **_“ (CAUTION!) ON TAXIWAY! ON TAXIWAY!”_**
### Approach and Landing

10. **Approaching Runway (Landing)**  
    Informs when the aircraft is approaching a runway during landing.  
    **_“APPROACHING 25 LEFT”_**

11. **Approaching Short Runway**  
    Runway length is less than nominal landing runway length.  
    **_“APPROACHING 25 LEFT, 1400M AVAILABLE”_**

12. **Short Runway Landing**  
    Aircraft is on final approach to a short runway.  
    **_“CAUTION SHORT RUNWAY, SHORT RUNWAY!”_**

13. **Taxiway Landing**  
    Warns if the aircraft is not lined up with a runway on landing.  
    **_“CAUTION TAXIWAY! CAUTION TAXIWAY!”_**

14. **Distance Remaining (Landing & Rollout)**  
    Announces the remaining runway distance during landing and rollout.  
    **_“ONE THOUSAND, FIVE HUNDRED”_** (METERS/FEET REMAINING)

### In-Flight Approach Warnings

15. **Landing Flaps Not Set**
    Warns if landing flaps have not been set.  
    **_“FLAPS, FLAPS”_**

17. **Too High on Approach**  
    Alerts the crew if the aircraft is too high on the approach path.  
    **_“TOO HIGH, TOO HIGH”_**

18. **Too Fast on Approach**  
    Warns if the aircraft is approaching too fast for a safe landing.   
    **_“TOO FAST, TOO FAST”_**

19. **Unstable Approach**  
    Alerts of an unstable approach due to improper speed, flaps setting or approach angle.  
    **_“UNSTABLE, UNSTABLE”_**

20. **Long (or Deep) Landing**  
    Warns if the aircraft has touched down far from the runway threshold, reducing available stopping distance.  
    **_“LONG LANDING, LONG LANDING”_** or **_“DEEP LANDING, DEEP LANDING”

### Altimeter and Setting Alerts

21. **Altimeter Setting (Climb + Descend)**  
    Warns if the altimeter is not set properly.  
    **_“ALTIMETER SETTING”_**
