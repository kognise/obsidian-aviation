# Section 3. En Route Procedures
**61 min read**  
Source: [https://www.faa.gov/air_traffic/publications/atpubs/aim_html/chap5_section_3.html](https://www.faa.gov/air_traffic/publications/atpubs/aim_html/chap5_section_3.html)

<div>

**ARTCC Communications ^5-3-1**

1.  **Direct Communications, Controllers and Pilots.**
    1.  ARTCCs are capable of direct communications with IFR air traffic on certain frequencies. Maximum communications coverage is possible through the use of Remote Center Air/Ground (RCAG) sites comprised of both VHF and UHF transmitters and receivers. These sites are located throughout the U.S. Although they may be several hundred miles away from the ARTCC, they are remoted to the various ARTCCs by land lines or microwave links. Since IFR operations are expedited through the use of direct communications, pilots are requested to use these frequencies strictly for communications pertinent to the control of IFR aircraft. Flight plan filing, en route weather, weather forecasts, and similar data should be requested through FSSs, company radio, or appropriate military facilities capable of performing these services.
    2.  An ARTCC is divided into sectors. Each sector is handled by one or a team of controllers and has its own sector discrete frequency. As a flight progresses from one sector to another, the pilot is requested to change to the appropriate sector discrete frequency.
    3.  Controller Pilot Data Link Communications (CPDLC) is a system that supplements air/ground voice communications. The CPDLC's principal operating criteria are:
        1.  Voice remains the primary and controlling air/ground communications means.
        2.  Participating aircraft will need to have the appropriate CPDLC avionics equipment in order to receive uplink or transmit downlink messages.
        3.  En Route CPDLC Initial Services offer the following services: Altimeter Setting (AS), Transfer of Communications (TOC), Initial Contact (IC), and limited route assignments, including airborne reroutes (ABRR), limited altitude assignments, and emergency messages.
            1.  Altimeter settings will be uplinked automatically when appropriate after a Monitor TOC. Altimeter settings will also be uplinked automatically when an aircraft receives an uplinked altitude assignment below FL 180. A controller may also manually send an altimeter setting message.
                <div>

                <em>**NOTE-**</em>

                <em>When conducting instrument approach procedures, pilots are responsible to obtain and use the appropriate altimeter setting in accordance with [[Volume 2/F Air traffic and general operating rules/0097 Standard instrument procedures.md#§97.20   General.|14 CFR Section 97.20]]. CPDLC issued altimeter settings are excluded for this purpose.</em>

                </div>
            2.  Initial contact is a safety validation transaction that compares a pilot's initiated altitude downlink message with an aircraft's stored altitude in the ATC automation system. When an IC mismatch or Confirm Assigned Altitude (CAA) downlink time-out indicator is displayed in the Full Data Block (FDB) and Aircraft List (ACL), the controller who has track control of the aircraft must use voice communication to verify the assigned altitude of the aircraft, and acknowledge the IC mismatch/time-out indicator.
            3.  Transfer of communications automatically establishes data link contact with a succeeding sector.
            4.  Menu text transmissions are scripted nontrajectory altering uplink messages.
            5.  The CPDLC Message Elements for the Initial Capabilities rollout are contained in TBL 5-3-1 through TBL 5-3-19, CPDLC Message Elements, below.
                <div>

                <em>**NOTE-**</em>

                <em>The FAA is not implementing ATN B1; the ATN B1 column in the tables is there for informational purposes only.</em>

                </div>
2.  **ATC Frequency Change Procedures.**
    1.  The following phraseology will be used by controllers to effect a frequency change:
        <div>

        <em>**EXAMPLE-**</em>

        <em>(Aircraft identification) contact (facility name or location name and terminal function) (frequency) at (time, fix, or altitude).</em>

        </div>

        <div>

        <em>**NOTE-**</em>

        <em>Pilots are expected to maintain a listening watch on the transferring controller's frequency until the time, fix, or altitude specified. ATC will omit frequency change restrictions whenever pilot compliance is expected upon receipt.</em>

        </div>

        <em>
        <div>

        ***TBL 5-3-1*** **  
        Route Uplink Message Elements (RTEU)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>UM74 PROCEED DIRECT TO<br />
        (<span><em>position</em></span>)</p></td><td><p>UM74 PROCEED DIRECT TO<br />
        (<span><em>position</em></span>)</p></td><td><p>W/U</p></td><td><p>RTEU-2</p></td><td><p>Instruction to proceed directly to the specified position.</p></td><td><p>PROCEED<br />
        DIRECT TO<br />
        (<span><em>position</em></span>)</p></td></tr><tr class="even"><td><p>UM79 CLEARED TO (<span><em>position</em></span>) via (<span><em>route clearance</em></span>)</p></td><td><p>UM79 CLEARED TO (<span><em>position</em></span>) via (<span><em>route clearance</em></span>)</p></td><td><p>W/U</p></td><td><p>RTEU-6</p></td><td><p>Instruction to proceed to the specified position via the specified route.</p></td><td><p>CLEARED TO <span><em><br />
        (position) </em></span>VIA <span><em><br />
        (departure data[O])</em></span> <span><em>(en-route data)</em></span></p></td></tr><tr class="odd"><td><p>UM80 CLEARED <span><em>(route clearance)</em></span></p></td><td><p>UM80 CLEARED <span><em>(route clearance)</em></span></p></td><td><p>W/U</p></td><td><p>RTEU-7</p></td><td><p>Instruction to<br />
        proceed via the specified route.</p></td><td><p>CLEARED <span><em><br />
        (departure data[O])</em></span> <span><em>(en-route data)</em></span> <span><em><br />
        (arrival approach data)</em></span></p></td></tr><tr class="even"><td><p>UM83 AT <span><em>(position) </em></span>CLEARED <span><em>(route clearance)</em></span></p></td><td><p>N/A</p></td><td><p>W/U</p></td><td><p>RTEU-9</p></td><td><p>Instruction to proceed from the specified position via the specified route.</p></td><td><p>AT <span><em>(position)</em></span> CLEARED <span><em><br />
        (en-route data)</em></span> <span><em><br />
        (arrival approach data)</em></span></p></td></tr></tbody></table>

        <em>
        <div>

        <em>**TBL 5-3-2**</em>**  
        Route Downlink Message Elements (RTED)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>DM22 REQUEST DIRECT TO<br />
        (<span><em>position</em></span>)</p></td><td><p>DM22 REQUEST DIRECT TO<br />
        (<span><em>position</em></span>)</p></td><td><p>Y</p></td><td><p>RTED-1</p></td><td><p>Request for a direct clearance to the specified position.</p></td><td><p>REQUEST<br />
        DIRECT TO<br />
        (<span><em>position</em></span>)</p></td></tr></tbody></table>

        <em>
        <div>

        <em>**TBL 5-3-3**</em>**  
        Lateral Downlink Message Elements (LATD)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>DM59 DIVERTING TO <span><em>(position) </em></span>VIA <span><em>(route clearance)<br />
        Note 1. - H alert attribute<br />
        Note 2. - N<br />
        response attribute</em></span></p></td><td><p>N/A</p></td><td><p>N<sup>1</sup></p></td><td><p>LATD-5</p></td><td><p>Report indicating diverting to the specified position via the specified route, which may be sent without any previous coordination done with ATC.</p></td><td><p>DIVERTING TO <span><em>(position) </em></span>VIA <span><em>(en-route data)</em></span> <span><em>(arrival approach data[O])</em></span></p></td></tr><tr class="even"><td><p>DM60<br />
        OFFSETTING <span><em><br />
        (distance offset)</em></span> <span><em><br />
        (direction)</em></span> OF ROUTE<br />
        <span><em>Note 1. - H alert attribute<br />
        Note 2. - N<br />
        response attribute</em></span></p></td><td><p>N/A</p></td><td><p>N<sup>1</sup></p></td><td><p>LATD-6</p></td><td><p>Report indicating that the aircraft is offsetting to a parallel track at the specified distance in the specified direction off from the cleared route.</p></td><td><p>OFFSETTING <span><em>(specified distance)</em></span> <span><em>(direction)</em></span><br />
        OF ROUTE</p></td></tr><tr class="odd"><td><p>DM80 DEVIATING <span><em>(deviation offset)</em></span> <span><em>(direction)</em></span> OF ROUTE<br />
        <span><em>Note 1. - H alert attribute<br />
        Note 2. - N response attribute</em></span></p></td><td><p>N/A</p></td><td><p>N<sup>1</sup></p></td><td><p>LATD-7</p></td><td><p>Report indicating deviating specified distance or degrees in the specified direction from the cleared route.</p></td><td><p>DEVIATING <span><em>(specifiedDeviation)</em></span> <span><em>(direction)</em></span> OF ROUTE</p></td></tr></tbody></table>

        <div>

        <sup>1</sup> <em>ICAO Document 10037, Global Operational Data Link (GOLD) Manual has these values set to Y in their table.</em>

        </div>

        <em>
        <div>

        <em>**TBL 5-3-4**</em>**  
        Level Uplink Message Elements (LVLU)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>UM19 MAINTAIN <span><em>(altitude)<br />
        Note - Used for a single level</em></span></p></td><td><p>UM19<br />
        MAINTAIN <span><em>(level)</em></span></p></td><td><p>W/U</p></td><td><p>LVLU-5</p></td><td><p>Instruction to maintain the specified level or vertical range.</p></td><td><p>MAINTAIN <span><em>(level)</em></span></p></td></tr><tr class="even"><td><p>UM20 CLIMB TO AND MAINTAIN <span><em><br />
        (altitude)<br />
        Note - Used for a single level</em></span></p></td><td><p>UM20 CLIMB TO (<span><em>level</em></span>)</p></td><td><p>W/U</p></td><td><p>LVLU-6</p></td><td><p>Instruction that a climb to the specified level or vertical range is to commence and once reached is to be maintained.</p></td><td><p>CLIMB TO (<span><em>level</em></span>)</p></td></tr><tr class="odd"><td><p>UM23 DESCEND TO AND MAINTAIN <span><em><br />
        (altitude)<br />
        Note - Used for a single level</em></span></p></td><td><p>UM23 DESCEND TO (<span><em>level</em></span>)</p></td><td><p>W/U</p></td><td><p>LVLU-9</p></td><td><p>Instruction that a descent to the specified level or vertical range is to commence and once reached is to be maintained.</p></td><td><p>DESCEND TO (<span><em>level</em></span>)</p></td></tr><tr class="even"><td><p>UM36 EXPEDITE CLIMB TO <span><em>(altitude)<br />
        Note - This message element is equivalent to SUPU-3 plus LVLU-6 in Doc 4444.</em></span></p></td><td><p>N/A</p></td><td><p>W/U</p></td><td><p>LVLU-6</p></td><td><p>Instruction that a climb to the specified level or vertical range is to commence and once reached is to be maintained.</p></td><td><p>CLIMB TO (<span><em>level</em></span>)</p></td></tr><tr class="odd"><td><p>UM37 EXPEDITE DESCEND TO <span><em><br />
        (altitude)</em></span></p></td><td><p>N/A</p></td><td><p>W/U</p></td><td><p>LVLU-9</p></td><td><p>Instruction that a descent to the specified level or vertical range is to commence and once reached is to be maintained.</p></td><td><p>DESCEND TO (<span><em>level</em></span>)</p></td></tr><tr class="even"><td><p>UM38 IMMEDIATELY CLIMB TO <span><em><br />
        (altitude)<br />
        Note - This message element is equivalent to EMGU-2 plus LVLU-6 in Doc 4444.</em></span></p></td><td><p>N/A</p></td><td><p>W/U</p></td><td><p>LVLU-6</p></td><td><p>Instruction that a climb to the specified level or vertical range is to commence and once reached is to be maintained.</p></td><td><p>CLIMB TO (<span><em>level</em></span>)</p></td></tr><tr class="odd"><td><p>UM39 IMMEDIATELY DESCEND TO <span><em><br />
        (altitude)<br />
        Note - This message element is equivalent to EMGU-2 plus LVLU-9 in Doc 4444.</em></span></p></td><td><p>N/A</p></td><td><p>W/U</p></td><td><p>LVLU-9</p></td><td><p>Instruction that a descent to the specified level or vertical range is to commence and once reached is to be maintained.</p></td><td><p>DESCEND TO (<span><em>level</em></span>)</p></td></tr><tr class="even"><td><p>UM135 CONFIRM ASSIGNED ALTITUDE<br />
        <span><em>Note - NE response attribute</em></span></p></td><td><p>N/A</p></td><td><p>Y</p></td><td><p>LVLU-27</p></td><td><p>Request to confirm the assigned level.</p></td><td><p>CONFIRM ASSIGNED LEVEL</p></td></tr><tr class="odd"><td><p>UM177 AT PILOTS DISCRETION</p></td><td><p>N/A</p></td><td><p>NE</p></td><td><p>See Note</p></td><td><p>Request to confirm the assigned level.</p></td><td><p> </p></td></tr></tbody></table>

        <div>

        <em>**NOTE-**</em>

        <em>ICAO Document 10037, Global Operational Data Link (GOLD) Manual does not include this in its tables.</em>

        </div>

        <em>
        <div>

        <em>**TBL 5-3-5**</em>**  
        Level Downlink Message Elements (LVLD)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>DM6 REQUEST <span><em>(altitude)<br />
        Note - Used for a single level</em></span></p></td><td><p>DM6 REQUEST (<span><em>level</em></span>)</p></td><td><p>Y</p></td><td><p>LVLD-1</p></td><td><p>Request to fly at the specified level or vertical range.</p></td><td><p>REQUEST <span><em>(level)</em></span></p></td></tr><tr class="even"><td><p>DM9 REQUEST CLIMB TO<span><em><br />
        (altitude)</em></span></p></td><td><p>DM9 REQUEST CLIMB TO (<span><em>level</em></span>)</p></td><td><p>Y</p></td><td><p>LVLD-2</p></td><td><p>Request for a climb to the specified level or vertical range.</p></td><td><p>REQUEST CLIMB TO (<span><em>level</em></span>)</p></td></tr><tr class="odd"><td><p>DM10 REQUEST DESCENT TO <span><em><br />
        (altitude)<br />
        </em></span></p></td><td><p>DM10 REQUEST DESCENT TO (<span><em>level</em></span>)</p></td><td><p>Y</p></td><td><p>LVLD-3</p></td><td><p>Request for a descent to the specified level or vertical range.</p></td><td><p>REQUEST DESCENT TO (<span><em>level</em></span>)</p></td></tr><tr class="even"><td><p>DM38 ASSIGNED LEVEL <span><em>(altitude)<br />
        Note - Used for a single level</em></span></p></td><td><p>DM38 ASSIGNED LEVEL (<span><em>level</em></span>)</p></td><td><p>N</p></td><td><p>LVLD-11</p></td><td><p>Confirmation that the assigned level or vertical range is the specified level or vertical range.</p></td><td><p>ASSIGNED LEVEL (<span><em>level</em></span>)</p></td></tr><tr class="odd"><td><p>DM61 DESCENDING TO <span><em>(altitude)<br />
        Note - urgent alert attribute</em></span></p></td><td><p>N/A</p></td><td><p>N</p></td><td><p>LVLD-14</p></td><td><p>Report indicating descending to the specified level.</p></td><td><p>DESCENDING TO (<span><em>level single</em></span>)</p></td></tr></tbody></table>

        <em>
        <div>

        <em>**TBL 5-3-6**</em>**  
        Crossing Constraint Message Elements (CSTU)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>UM49 CROSS (<span><em>position</em></span>) AT AND MAINTAIN (<span><em>altitude</em></span>)<br />
        <span><em>Note 1. - A vertical range cannot be provided.<br />
        Note 2. - This message element is equivalent to CSTU-1 plus LVLU-5 in Doc 4444.</em></span></p></td><td><p>N/A</p></td><td><p>W/U</p></td><td><p>CSTU-1</p></td><td><p>Instruction that the specified position is to be crossed at the specified level or within the specified vertical range.</p></td><td><p>CROSS <span><em>(position)</em></span> AT <span><em>(level)</em></span></p></td></tr><tr class="even"><td><p>UM61 CROSS <span><em>(position) </em></span>AT AND MAINTAIN <span><em>(altitude)</em></span> AT <span><em>(speed)<br />
        Note 1. - A vertical range cannot be provided.<br />
        Note 2. - This message element is equivalent to CSTU-14 plus LVLU-5 in Doc 4444.</em></span></p></td><td><p>UM61 CROSS <span><em>(position) </em></span>AT AND MAINTAIN <span><em>(level)</em></span> AT <span><em>(speed)</em></span></p></td><td><p>W/U</p></td><td><p>CSTU-14</p></td><td><p>Instruction that the specified position is to be crossed at the level or within the vertical range, as specified, and at the specified speed.</p></td><td><p>CROSS <span><em>(position)</em></span> AT <span><em>(level)</em></span> AT <span><em>(speed)</em></span></p></td></tr></tbody></table>

        <em>
        <div>

        <em>**TBL 5-3-7**</em>**  
        Air Traffic Advisory Uplink Message Elements**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>UM154 RADAR SERVICES TERMINATED</p></td><td><p>N/A</p></td><td><p>R</p></td><td><p>ADVU-2</p></td><td><p><span><em>Advisory that the ATS surveillance service is terminated.</em></span></p></td><td><p>SURVEILLANCE SERVICE TERMINATED</p></td></tr></tbody></table>

        <em>
        <div>

        <em>**TBL 5-3-8**</em>**  
        Voice Communications Uplink Message Elements (COMU)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>UM117 CONTACT <span><em>(ICAO unit name)</em></span> <span><em>(frequency)</em></span></p></td><td><p>UM117 CONTACT <span><em>(unit name)</em></span> <span><em>(frequency)</em></span></p></td><td><p>W/U</p></td><td><p>COMU-1</p></td><td><p>Instruction to establish voice contact with the specified ATS unit on the specified frequency.</p></td><td><p>CONTACT<br />
        <span><em>(unit name)</em></span> <span><em><br />
        (frequency)</em></span></p></td></tr><tr class="even"><td><p>UM120 MONITOR <span><em>(ICAO unit name)</em></span> <span><em>(frequency)</em></span></p></td><td><p>UM120 MONITOR (<span><em>unit name)</em></span> <span><em>(frequency)</em></span></p></td><td><p>W/U</p></td><td><p>COMU-5</p></td><td><p>Instruction to monitor the specified ATS unit on the specified frequency. The flight crew is not required to establish voice contact on the frequency.</p></td><td><p>MONITOR <span><em><br />
        (unit name)</em></span> <span><em><br />
        (frequency)</em></span></p></td></tr></tbody></table>

        <em>
        <div>

        <em>**TBL 5-3-9**</em>**  
        Voice Communications Downlink Message Elements (COMD)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>DM20 REQUEST VOICE CONTACT <span><em>Note - Used when a frequency is not required.</em></span></p></td><td><p>N/A</p></td><td><p>Y</p></td><td><p>COMD-1</p></td><td><p>Request for voice contact on the specified frequency.</p></td><td><p>REQUEST VOICE<br />
        CONTACT<br />
        <span><em>(frequency)</em></span></p></td></tr></tbody></table>

        <em>
        <div>

        <em>**TBL 5-3-10**</em>**  
        Emergency/Urgency Uplink Message Elements (EMGU)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>Used in combination with LVLU-6 and LVLU-9, which is implemented in<br />
        FANS 1/A as:<br />
        <br />
        UM38 IMMEDIATELY CLIMB TO (<span><em>altitude</em></span>)<br />
        <br />
        UM39 IMMEDIATELY DESCEND TO (<span><em>altitude</em></span>)</p></td><td><p>N/A</p></td><td><p>N</p></td><td><p>EMGU-2</p></td><td><p>Instruction to immediately comply with the associated instruction to avoid imminent situation.</p></td><td><p>Immediately</p></td></tr></tbody></table>

        <em>
        <div>

        <em>**TBL 5-3-11**</em>**  
        Emergency/Urgency Downlink Message Elements (EMGD)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>DM55 PAN PAN PAN <span><em>Note - N response attribute</em></span></p></td><td><p>N/A</p></td><td><p>Y</p></td><td><p>EMGD-1</p></td><td><p>Indication of an urgent situation.</p></td><td><p>PAN PAN PAN</p></td></tr><tr class="even"><td><p>DM56 MAYDAY MAYDAY MAYDAY<span><em><br />
        Note - N response attribute</em></span></p></td><td><p>N/A</p></td><td><p>Y</p></td><td><p>EMGD-2</p></td><td><p>Indication of an emergency situation.</p></td><td><p>MAYDAY<br />
        MAYDAY<br />
        MAYDAY</p></td></tr><tr class="odd"><td><p>DM57 (<span><em>remaining fuel</em></span>) OF FUEL REMAINING AND<br />
        (<span><em>remaining souls</em></span>) SOULS ON BOARD<span><em><br />
        Note - N response attribute</em></span></p></td><td><p>N/A</p></td><td><p>Y</p></td><td><p>EMGD-3</p></td><td><p>Report indicating fuel remaining (time) and number of persons on board.</p></td><td><p><span><em>(remaining fuel)</em></span> ENDURANCE AND <span><em>(persons on board)</em></span> PERSONS ON BOARD</p></td></tr><tr class="even"><td><p>DM58 CANCEL EMERGENCY<br />
        <span><em>Note - N response attribute</em></span></p></td><td><p>N/A</p></td><td><p>Y</p></td><td><p>EMGD-4</p></td><td><p>Indication that the emergency situation is canceled.</p></td><td><p>CANCEL<br />
        EMERGENCY</p></td></tr></tbody></table>

        <em>
        <div>

        <em>**TBL 5-3-12**</em>**  
        Standard Response Uplink Message Elements (RSPU)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>UM0 UNABLE</p></td><td><p>UM0 UNABLE</p></td><td><p>N</p></td><td><p>RSPU-1</p></td><td><p>Indication that the message cannot be complied with.</p></td><td><p>UNABLE</p></td></tr><tr class="even"><td><p>UM1 STANDBY</p></td><td><p>UM1 STANDBY</p></td><td><p>N</p></td><td><p>RSPU-2</p></td><td><p>Indication that the message will be responded to shortly.</p></td><td><p>STANDBY</p></td></tr><tr class="odd"><td><p>UM3 ROGER</p></td><td><p>UM3 ROGER</p></td><td><p>N</p></td><td><p>RSPU-4</p></td><td><p>Indication that the message is received.</p></td><td><p>ROGER</p></td></tr></tbody></table>

        <em>
        <div>

        <em>**TBL 5-3-13**</em>**  
        Standard Response Downlink Message Elements (RSPD)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>DM0 WILCO</p></td><td><p>DM0 WILCO</p></td><td><p>N</p></td><td><p>RSPD-1</p></td><td><p>Indication that the instruction is understood and will be complied with.</p></td><td><p>WILCO</p></td></tr><tr class="even"><td><p>DM1 UNABLE</p></td><td><p>DM1 UNABLE</p></td><td><p>N</p></td><td><p>RSPD-2</p></td><td><p>Indication that the message cannot be complied with.</p></td><td><p>UNABLE</p></td></tr><tr class="odd"><td><p>DM2 STANDBY</p></td><td><p>DM2 STANDBY</p></td><td><p>N</p></td><td><p>RSPD-3</p></td><td><p>Indication that the message will be responded to shortly.</p></td><td><p>STANDBY</p></td></tr><tr class="even"><td><p>DM3 ROGER<br />
        <span><em>Note - ROGER is the only correct response to an uplink free text message.</em></span></p></td><td><p>DM3 ROGER</p></td><td><p>N</p></td><td><p>RSPD-4</p></td><td><p>Indication that the message is received.</p></td><td><p>ROGER</p></td></tr></tbody></table>

        <em>
        <div>

        <em>**TBL 5-3-14**</em>**  
        Supplemental Uplink Message Elements (SUPU)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>UM166 DUE TO TRAFFIC</p></td><td><p>N/A</p></td><td><p>N</p></td><td><p>SUPU-2</p></td><td rowspan="2"><p>Indication that the associated message is issued due to the specified reason.</p></td><td rowspan="2"><p>DUE TO<br />
        <span><em>(specified reason uplink)</em></span></p></td></tr><tr class="even"><td><p>UM167 DUE TO AIRSPACE RESTRICTION</p></td><td><p> </p></td><td><p> </p></td><td><p> </p></td></tr></tbody></table>

        <em>
        <div>

        <em>**TBL 5-3-15**</em>**  
        Supplemental Downlink Message Elements (SUPD)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>DM65 DUE TO WEATHER</p></td><td><p>DM65 DUE TO WEATHER</p></td><td><p>N</p></td><td><p>SUPD-1</p></td><td rowspan="2"><p>Indication that the associated message is issued due to the specified reason.</p></td><td rowspan="2"><p>DUE TO<br />
        <span><em>(specified reason downlink)</em></span></p></td></tr><tr class="even"><td><p>DM66 DUE TO AIRCRAFT PERFORMANCE</p></td><td><p>DM66 DUE TO AIRCRAFT PERFORMANCE</p></td><td><p> </p></td><td><p> </p></td></tr></tbody></table>

        <em>
        <div>

        <em>**TBL 5-3-16**</em>**  
        Free Text Uplink Message Elements (TXTU)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>UM169 (<span><em>free text</em></span>)</p></td><td><p>UM203 (<span><em>free text</em></span>)</p></td><td><p>R</p></td><td><p>TXTU-1</p></td><td><p> </p></td><td><p>(<span><em>free text</em></span>)</p><p><span><em>Note-M alert<br />
        attribute.</em></span></p></td></tr><tr class="even"><td><p>UM169 (<span><em>free text</em></span>) CPDLC NOT IN USE UNTIL FURTHER NOTIFICATION</p></td><td><p>N/A</p></td><td><p>R</p></td><td><p>See Note</p></td><td><p> </p></td><td><p>(<span><em>free text</em></span>)</p></td></tr><tr class="odd"><td><p>UM169 (<span><em>free text</em></span>)<br />
        “[facility designation]”<br />
        LOCAL ALTIMETER (for Altimeter Reporting Station)</p></td><td><p>N/A</p></td><td><p>R</p></td><td><p>See Note</p></td><td><p> </p></td><td><p>(<span><em>free text</em></span>)</p></td></tr><tr class="even"><td><p>UM169 (<span><em>free text</em></span>)<br />
        “[facility designation] LOCAL ALTIMETER MORE THAN ONE HOUR” OLD</p></td><td><p>N/A</p></td><td><p>R</p></td><td><p>See Note</p></td><td><p> </p></td><td><p>(<span><em>free text</em></span>)</p></td></tr><tr class="odd"><td><p>UM169 (<span><em>free text</em></span>)<br />
        DUE TO WEATHER</p></td><td><p>N/A</p></td><td><p>R</p></td><td><p>See Note</p></td><td><p> </p></td><td><p>(<span><em>free text</em></span>)</p></td></tr><tr class="even"><td><p>UM169 (<span><em>free text</em></span>)<br />
        REST OF ROUTE UNCHANGED</p></td><td><p>N/A</p></td><td><p>R</p></td><td><p>See Note</p></td><td><p> </p></td><td><p>(<span><em>free text</em></span>)</p></td></tr><tr class="odd"><td><p>UM169 (<span><em>free text</em></span>)<br />
        TRAFFIC FLOW MANAGEMENT REROUTE</p></td><td><p>N/A</p></td><td><p>R</p></td><td><p>See Note</p></td><td><p> </p></td><td><p>(<span><em>free text</em></span>)</p></td></tr></tbody></table>

        <div>

        <em>**NOTE-**</em>

        <em>These are FAA scripted free text messages with no GOLD equivalent.</em>

        </div>

        <em>
        <div>

        <em>**TBL 5-3-17**</em>**  
        Free Text Downlink Message Elements (TXTD)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>DM68 <span><em>(free text)<br />
        Note 1. - Urgency or Distress Alr (M)<br />
        <br />
        Note 2. - Selecting any of the emergency message elements will result in this message element being enabled for the flight crew to include in the emergency message at their discretion.</em></span></p></td><td><p>N/A</p></td><td><p>Y</p></td><td><p>TXTD-1</p></td><td><p> </p></td><td><p>(<span><em>free text</em></span>)<br />
        <span><em>Note - M alert<br />
        attribute.</em></span></p></td></tr></tbody></table>

        <em>
        <div>

        <em>**TBL 5-3-18**</em>**  
        System Management Uplink Message Elements (SYSU)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>UM159 ERROR <span><em>(error information)</em></span></p></td><td><p>UM159 ERROR <em>(error information)</em></p></td><td><p>N</p></td><td><p>SYSU-1</p></td><td><p>System-generated notification of an error.</p></td><td><p>ERROR <span><em>(error information)</em></span></p></td></tr><tr class="even"><td><p>UM160 NEXT DATA AUTHORITY <span><em>(ICAO facility designation)<br />
        Note - The facility designation is required.</em></span></p></td><td><p>UM160 NEXT DATA AUTHORITY <span><em>(facility)<br />
        Note - Facility parameter can specify a facility designation or no facility.</em></span></p></td><td><p>N</p></td><td><p>SYSU-2</p></td><td><p>System-generated notification of the next data authority or the cancellation thereof.</p></td><td><p>NEXT DATA AUTHORITY <span><em>(facility designation [O])</em></span></p></td></tr></tbody></table>

        <em>
        <div>

        ***TBL 5-3-19*** **  
        System Management Downlink Message Elements (SYSD)**

        </div>

        </em>
        <table style="width:100%;"><colgroup><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /><col style="width: 16%" /></colgroup><tbody><tr class="odd"><td colspan="3"><p><strong>CPDLC Message Sets</strong></p></td><td colspan="3"><p><strong>Operational Definition in PANS-ATM (Doc 4444)</strong></p></td></tr><tr class="even"><td><p><strong>FANS 1/A</strong></p></td><td><p><strong>ATN B1</strong></p></td><td><p><strong>Response</strong></p></td><td><p><strong>Message<br />
        Element<br />
        Identifier</strong></p></td><td><p><strong>Message Element Intended Use</strong></p></td><td><p><strong>Format for<br />
        Message Element Display</strong></p></td></tr><tr class="odd"><td><p>DM62 ERROR <span><em>(error information)</em></span></p></td><td><p>DM62 ERROR <span><em>(error information)</em></span></p></td><td><p>N</p></td><td><p>SYSD-1</p></td><td><p>System-generated notification of an error.</p></td><td><p>SYSD-1</p></td></tr><tr class="even"><td><p>DM63 NOT CURRENT DATA AUTHORITY</p></td><td><p>DM63 NOT CURRENT<br />
        DATA AUTHORITY</p></td><td><p>N</p></td><td><p>SYSD-3</p></td><td><p>System-generated rejection of any CPDLC message sent from a ground facility that is not the current data authority.</p></td><td><p>SYSD-3</p></td></tr><tr class="odd"><td><p>DM64 <span><em>(ICAO facility designation)<br />
        Note - Use by FANS 1/A aircraft in B1 environments.</em></span></p></td><td><p>DM107 NOT AUTHORIZED NEXT DATA AUTHORITY<span><em><br />
        Note - CDA and NDA cannot be provided.</em></span></p></td><td><p>N</p></td><td><p>SYSD-5</p></td><td><p>System-generated notification that the ground system is not designated as the next data authority (NDA), indicating the identity of the current data authority (CDA). Identity of the NDA, if any, is also reported.</p></td><td><p>SYSD-5</p></td></tr></tbody></table>
    2.  The following phraseology should be utilized by pilots for establishing contact with the designated facility:
        1.  When operating in a radar environment: On initial contact, the pilot should inform the controller of the aircraft's assigned altitude preceded by the words “level,” or “climbing to,” or “descending to,” as appropriate; and the aircraft's present vacating altitude, if applicable.
            <div>

            <em>**EXAMPLE-**</em>

            1.  <em>(Name) CENTER, (aircraft identification), LEVEL (altitude or flight level).</em>
            2.  <em>(Name) CENTER, (aircraft identification), LEAVING (exact altitude or flight level), CLIMBING TO OR DESCENDING TO (altitude of flight level).</em>

            </div>

            <div>

            <em>**NOTE-**</em>

            <em>Exact altitude or flight level means to the nearest 100 foot increment. Exact altitude or flight level reports on initial contact provide ATC with information required prior to using Mode C altitude information for separation purposes.</em>

            </div>
        2.  When operating in a nonradar environment:
            1.  On initial contact, the pilot should inform the controller of the aircraft's present position, altitude and time estimate for the next reporting point.
                <div>

                <em>**EXAMPLE-**</em>

                <em>(Name) CENTER, (aircraft identification), (position), (altitude), ESTIMATING (reporting point) AT (time).</em>

                </div>
            2.  After initial contact, when a position report will be made, the pilot should give the controller a complete position report.
                <div>

                <em>**EXAMPLE-**</em>

                <em>(Name) CENTER, (aircraft identification), (position), (time), (altitude), (type of flight plan), (ETA and name of next reporting point), (the name of the next succeeding reporting point), AND (remarks).</em>

                </div>

                <div>

                <em>**REFERENCE-**</em>

                <em> [[#^5-3-2|AIM, Paragraph 5-3-2]], Position Reporting </em>

                </div>
    3.  At times controllers will ask pilots to verify that they are at a particular altitude. The phraseology used will be: “VERIFY AT (altitude).” In climbing or descending situations, controllers may ask pilots to “<em>VERIFY ASSIGNED ALTITUDE AS (altitude)</em>.” Pilots should confirm that they are at the altitude stated by the controller or that the assigned altitude is correct as stated. If this is not the case, they should inform the controller of the actual altitude being maintained or the different assigned altitude.
        <div>

        <em>**CAUTION-**</em>

        <em> **Pilots should not take action to change their actual altitude or different assigned altitude to the altitude stated in the controllers verification request unless the controller specifically authorizes a change.**</em>

        </div>
3.  **ARTCC Radio Frequency Outage.** ARTCCs normally have at least one back‐up radio receiver and transmitter system for each frequency, which can usually be placed into service quickly with little or no disruption of ATC service. Occasionally, technical problems may cause a delay but switchover seldom takes more than 60 seconds. When it appears that the outage will not be quickly remedied, the ARTCC will usually request a nearby aircraft, if there is one, to switch to the affected frequency to broadcast communications instructions. It is important, therefore, that the pilot wait at least 1 minute before deciding that the ARTCC has actually experienced a radio frequency failure. When such an outage does occur, the pilot should, if workload and equipment capability permit, maintain a listening watch on the affected frequency while attempting to comply with the following recommended communications procedures:
    1.  If two‐way communications cannot be established with the ARTCC after changing frequencies, a pilot should attempt to recontact the transferring controller for the assignment of an alternative frequency or other instructions.
    2.  When an ARTCC radio frequency failure occurs after two‐way communications have been established, the pilot should attempt to reestablish contact with the center on any other known ARTCC frequency, preferably that of the next responsible sector when practicable, and ask for instructions. However, when the next normal frequency change along the route is known to involve another ATC facility, the pilot should contact that facility, if feasible, for instructions. If communications cannot be reestablished by either method, the pilot is expected to request communications instructions from the FSS appropriate to the route of flight.
        <div>

        <em>**NOTE-**</em>

        <em>The exchange of information between an aircraft and an ARTCC through an FSS is quicker than relay via company radio because the FSS has direct interphone lines to the responsible ARTCC sector. Accordingly, when circumstances dictate a choice between the two, during an ARTCC frequency outage, relay via FSS radio is recommended.</em>

        </div>
4.  **Oakland Oceanic FIR.** The use of CPDLC and ADS-C in the Oakland Oceanic FIR (KZAK) is only permitted by Inmarsat and Iridium customers. All other forms of data link connectivity are not authorized. Users must ensure that the proper data link code is filed in Item 10a of the ICAO FPL in order to indicate which satellite medium(s) the aircraft is equipped with. The identifier for Inmarsat is J5 and the identifier for Iridium is J7. If J5 or J7 is not included in the ICAO FPL, then the LOGON will be rejected by KZAK and the aircraft will not be able to connect.
5.  **New York Oceanic FIR.** The use of CPDLC and ADS-C in the New York Oceanic FIR (KZWY) is only permitted by Inmarsat and Iridium customers. All other forms of data link connectivity are not authorized. Users must ensure that the proper data link code is filed in Item 10a of the ICAO FPL in order to indicate which satellite medium(s) the aircraft is equipped with. The identifier for Inmarsat is J5 and the identifier for Iridium is J7. If J5 or J7 is not included in the ICAO FPL, then the LOGON will be rejected by KZWY and the aircraft will not be able to connect.

**Position Reporting ^5-3-2** The safety and effectiveness of traffic control depends to a large extent on accurate position reporting. In order to provide the proper separation and expedite aircraft movements, ATC must be able to make accurate estimates of the progress of every aircraft operating on an IFR flight plan.

1.  **Position Identification.**
    1.  When a position report is to be made passing a VOR radio facility, the time reported should be the time at which the first complete reversal of the “to/from” indicator is accomplished.
    2.  When a position report is made passing a facility by means of an airborne ADF, the time reported should be the time at which the indicator makes a complete reversal.
    3.  When an aural or a light panel indication is used to determine the time passing a reporting point, such as a fan marker, Z marker, cone of silence or intersection of range courses, the time should be noted when the signal is first received and again when it ceases. The mean of these two times should then be taken as the actual time over the fix.
    4.  If a position is given with respect to distance and direction from a reporting point, the distance and direction should be computed as accurately as possible.
    5.  Except for terminal area transition purposes, position reports or navigation with reference to aids not established for use in the structure in which flight is being conducted will not normally be required by ATC.
2.  **Position Reporting Points.** CFRs require pilots to maintain a listening watch on the appropriate frequency and, unless operating under the provisions of subparagraph c, to furnish position reports passing certain reporting points. Reporting points are indicated by symbols on en route charts. The designated compulsory reporting point symbol is a solid triangle ![A solid triangle symbol which indicates compulsory reporting points.](https://www.faa.gov/air_traffic/publications/atpubs/aim_html/images/aim_img_147.jpeg) and the “on request” reporting point symbol is the open triangle ![An open triangle symbol which indicates on request reporting points.](https://www.faa.gov/air_traffic/publications/atpubs/aim_html/images/aim_img_d70.jpeg). Reports passing an “on request” reporting point are only necessary when requested by ATC.
3.  **Position Reporting Requirements.**
    1.  **Flights Along Airways or Routes.** A position report is required by all flights regardless of altitude, including those operating in accordance with an ATC clearance specifying <em>“VFR-on-top,”</em> over each designated compulsory reporting point along the route being flown.
    2.  **Flights Along a Direct Route.** Regardless of the altitude or flight level being flown, including flights operating in accordance with an ATC clearance specifying “<em>VFR-on-top,”</em> pilots must report over each reporting point used in the flight plan to define the route of flight.
    3.  **Flights in a Radar Environment.** When informed by ATC that their aircraft are in “Radar Contact,” pilots should discontinue position reports over designated reporting points. They should resume normal position reporting when ATC advises “<em>RADAR CONTACT LOST”</em> or “<em>RADAR SERVICE TERMINATED.”</em>
    4.  **Flights in an Oceanic (Non-radar) Environment.** Pilots must report over each point used in the flight plan to define the route of flight, even if the point is depicted on aeronautical charts as an “on request" (non-compulsory) reporting point. For aircraft providing automatic position reporting via an Automatic Dependent Surveillance-Contract (ADS-C) logon, pilots should discontinue voice position reports.
        <div>

        <em>**NOTE-**</em>

        <em>ATC will inform pilots that they are in “radar contact”:  
        </em>

        1.  <em> when their aircraft is initially identified in the ATC system; and</em>
        2.  <em> when radar identification is reestablished after radar service has been terminated or radar contact lost.</em>

        <em> Subsequent to being advised that the controller has established radar contact, this fact will not be repeated to the pilot when handed off to another controller. At times, the aircraft identity will be confirmed by the receiving controller; however, this should not be construed to mean that radar contact has been lost. The identity of transponder equipped aircraft will be confirmed by asking the pilot to “ident,” “squawk standby,” or to change codes. Aircraft without transponders will be advised of their position to confirm identity. In this case, the pilot is expected to advise the controller if in disagreement with the position given. Any pilot who cannot confirm the accuracy of the position given because of not being tuned to the NAVAID referenced by the controller, should ask for another radar position relative to the tuned in NAVAID.</em>

        </div>
4.  **Position Report Items:**
    1.  **Position reports should include the following items:**
        1.  Identification;
        2.  Position;
        3.  Time;
        4.  Altitude or flight level (include actual altitude or flight level when operating on a clearance specifying VFR-on-top);
        5.  Type of flight plan (not required in IFR position reports made directly to ARTCCs or approach control);
        6.  ETA and name of next reporting point;
        7.  The name only of the next succeeding reporting point along the route of flight; and
        8.  Pertinent remarks.

**Additional Reports ^5-3-3**

1.  **The following reports should be made to ATC or FSS facilities without a specific ATC request:**
    1.  **<em>At all times.</em>**
        1.  When vacating any previously assigned altitude or flight level for a newly assigned altitude or flight level.
        2.  When an altitude change will be made if operating on a clearance specifying VFR-on-top.
        3.  When <em>unable</em> to climb/descend at a rate of a least 500 feet per minute.
        4.  When approach has been missed. (Request clearance for specific action; i.e., to alternative airport, another approach, etc.)
        5.  Change in the average true airspeed (at cruising altitude) when it varies by 5 percent or 10 knots (whichever is greater) from that filed in the flight plan.
        6.  The time and altitude or flight level upon reaching a holding fix or point to which cleared.
        7.  When leaving any assigned holding fix or point.
            <div>

            <em>**NOTE-**</em>

            <em>The reports in subparagraphs (f) and (g) may be omitted by pilots of aircraft involved in instrument training at military terminal area facilities when radar service is being provided.</em>

            </div>
        8.  Any loss, in controlled airspace, of VOR, TACAN, ADF, low frequency navigation receiver capability, GPS anomalies while using installed IFR-certified GPS/GNSS receivers, complete or partial loss of ILS receiver capability or impairment of air/ground communications capability. Reports should include aircraft identification, equipment affected, degree to which the capability to operate under IFR in the ATC system is impaired, and the nature and extent of assistance desired from ATC.
            <div>

            <em>**NOTE-**</em>

            1.  <em>Other equipment installed in an aircraft may effectively impair safety and/or the ability to operate under IFR. If such equipment (e.g., airborne weather radar) malfunctions and in the pilot's judgment either safety or IFR capabilities are affected, reports should be made as above.</em>
            2.  <em>When reporting GPS anomalies, include the location and altitude of the anomaly. Be specific when describing the location and include duration of the anomaly if necessary.</em>

            </div>
        9.  Any information relating to the safety of flight.
    2.  **When not in radar contact.**
        1.  When leaving final approach fix inbound on final approach (nonprecision approach) or when leaving the outer marker or fix used in lieu of the outer marker inbound on final approach (precision approach).
        2.  A corrected estimate at anytime it becomes apparent that an estimate as previously submitted is in error in excess of 2 minutes. For flights in the North Atlantic (NAT), a revised estimate is required if the error is 3 minutes or more.
2.  Pilots encountering weather conditions which have not been forecast, or hazardous conditions which have been forecast, are expected to forward a report of such weather to ATC.
    <div>

    <em>**REFERENCE-**</em>

    <em> AIM, Para 7-1-18, Pilot Weather Reports (PIREPs).  
    [[Volume 2/F Air traffic and general operating rules/0091 General operating and flight rules.md#§91.183   IFR communications.|14 CFR Section 91.183]](B) and (C). </em>

    </div>

**Airways and Route Systems ^5-3-4**

1.  Three fixed route systems are established for air navigation purposes. They are the Federal airway system (consisting of VOR and L/MF routes), the jet route system, and the RNAV route system. To the extent possible, these route systems are aligned in an overlying manner to facilitate transition between each.
    1.  The VOR and L/MF (nondirectional radio beacons) Airway System consists of airways designated from 1,200 feet above the surface (or in some instances higher) up to but not including 18,000 feet MSL. These airways are depicted on IFR Enroute Low Altitude Charts.
        <div>

        <em>**NOTE-**</em>

        <em>The altitude limits of a victor airway should not be exceeded except to effect transition within or between route structures.</em>

        </div>

        1.  Except in Alaska, the VOR airways are: predicated solely on VOR or VORTAC navigation aids; depicted in black on aeronautical charts; and identified by a “V” (Victor) followed by the airway number (for example, V12).
            <div>

            <em>**NOTE-**</em>

            <em>Segments of VOR airways in Alaska are based on L/MF navigation aids and charted in brown instead of black on en route charts.</em>

            </div>

            1.  A segment of an airway which is common to two or more routes carries the numbers of all the airways which coincide for that segment. When such is the case, pilots filing a flight plan need to indicate only that airway number for the route filed.
                <div>

                <em>**NOTE-**</em>

                <em>A pilot who intends to make an airway flight, using VOR facilities, will simply specify the appropriate “victor” airway(s) in the flight plan. For example, if a flight is to be made from Chicago to New Orleans at 8,000 feet, using omniranges only, the route may be indicated as “departing from Chicago-Midway, cruising 8,000 feet via Victor 9 to Moisant International.” If flight is to be conducted in part by means of L/MF navigation aids and in part on omniranges, specifications of the appropriate airways in the flight plan will indicate which types of facilities will be used along the described routes, and, for IFR flight, permit ATC to issue a traffic clearance accordingly. A route may also be described by specifying the station over which the flight will pass, but in this case since many VORs and L/MF aids have the same name, the pilot must be careful to indicate which aid will be used at a particular location. This will be indicated in the route of flight portion of the flight plan by specifying the type of facility to be used after the location name in the following manner: Newark L/MF, Allentown VOR.</em>

                </div>
            2.  With respect to position reporting, reporting points are designated for VOR Airway Systems. Flights using Victor Airways will report over these points unless advised otherwise by ATC.
        2.  The L/MF airways (colored airways) are predicated solely on L/MF navigation aids and are depicted in brown on aeronautical charts and are identified by color name and number (e.g., Amber One). Green and Red airways are plotted east and west. Amber and Blue airways are plotted north and south.
            <div>

            <em>**NOTE-**</em>

            <em>Except for G13 in North Carolina, the colored airway system exists only in the state of Alaska. All other such airways formerly so designated in the conterminous U.S. have been rescinded.</em>

            </div>
        3.  The use of TSO-C145 (as revised) or TSO-C146 (as revised) GPS/WAAS navigation systems is allowed in Alaska as the only means of navigation on published air traffic service (ATS) routes, including those Victor, T-Routes, and colored airway segments designated with a second minimum en route altitude (MEA) depicted in blue and followed by the letter G at those lower altitudes. The altitudes so depicted are below the minimum reception altitude (MRA) of the land-based navigation facility defining the route segment, and guarantee standard en route obstacle clearance and two-way communications. Air carrier operators requiring operations specifications are authorized to conduct operations on those routes in accordance with FAA operations specifications.
    2.  The jet route system consists of jet routes established from 18,000 feet MSL to FL 450 inclusive.
        1.  These routes are depicted on Enroute High Altitude Charts. Jet routes are depicted in black on aeronautical charts and are identified by a “J” (Jet) followed by the airway number (e.g., J12). Jet routes, as VOR airways, are predicated solely on VOR or VORTAC navigation facilities (except in Alaska).
            <div>

            <em>**NOTE-**</em>

            <em>Segments of jet routes in Alaska are based on L/MF navigation aids and are charted in brown color instead of black on en route charts.</em>

            </div>
        2.  With respect to position reporting, reporting points are designated for jet route systems. Flights using jet routes will report over these points unless otherwise advised by ATC.
    3.  **Area Navigation (RNAV) Routes.**
        1.  Published RNAV routes, including Q-Routes and T-Routes, can be flight planned for use by aircraft with RNAV capability, subject to any limitations or requirements noted on en route charts, in applicable Advisory Circulars, or by NOTAM. RNAV routes are depicted in blue on aeronautical charts and are identified by the letter “Q” or “T” followed by the airway number (for example, Q-13, T-205). Published RNAV routes are RNAV-2 except when specifically charted as RNAV-1. These routes require system performance currently met by GPS, GPS/WAAS, or DME/DME/IRU RNAV systems that satisfy the criteria discussed in AC 90-100A, U.S. Terminal and En Route Area Navigation (RNAV) Operations.
            1.  Q-routes are available for use by RNAV equipped aircraft between 18,000 feet MSL and FL 450 inclusive. Q-routes are depicted on Enroute High Altitude Charts.
                <div>

                <em>**NOTE-**</em>

                <em>Aircraft in Alaska may only operate on GNSS Q-routes with GPS (TSO-C129 (as revised) or TSO-C196 (as revised)) equipment while the aircraft remains in Air Traffic Control (ATC) radar surveillance or with GPS/WAAS which does not require ATC radar surveillance.</em>

                </div>
            2.  T-routes are available for use by GPS or GPS/WAAS equipped aircraft from 1,200 feet above the surface (or in some instances higher) up to but not including 18,000 feet MSL. T-routes are depicted on Enroute Low Altitude Charts.
                <div>

                <em>**NOTE-**</em>

                <em>Aircraft in Alaska may only operate on GNSS T-routes with GPS/WAAS (TSO-C145 (as revised) or TSO-C146 (as revised)) equipment.</em>

                </div>
        2.  Unpublished RNAV routes are direct routes, based on area navigation capability, between waypoints defined in terms of latitude/longitude coordinates, degree-distance fixes, or offsets from established routes/airways at a specified distance and direction. Radar monitoring by ATC is required on all unpublished RNAV routes, except for GNSS-equipped aircraft cleared via filed published waypoints recallable from the aircraft's navigation database.
        3.  Magnetic Reference Bearing (MRB) is the published bearing between two waypoints on an RNAV/GPS/GNSS route. The MRB is calculated by applying magnetic variation at the waypoint to the calculated true course between two waypoints. The MRB enhances situational awareness by indicating a reference bearing (no-wind heading) that a pilot should see on the compass/HSI/RMI, etc., when turning prior to/over a waypoint en route to another waypoint. Pilots should use this bearing as a reference only, because their RNAV/GPS/GNSS navigation system will fly the true course between the waypoints.
2.  Operation above FL 450 may be conducted on a point‐to‐point basis. Navigational guidance is provided on an area basis utilizing those facilities depicted on the enroute high altitude charts.
3.  **Radar Vectors.** Controllers may vector aircraft within controlled airspace for separation purposes, noise abatement considerations, when an operational advantage will be realized by the pilot or the controller, or when requested by the pilot. Vectors outside of controlled airspace will be provided only on pilot request. Pilots will be advised as to what the vector is to achieve when the vector is controller initiated and will take the aircraft off a previously assigned nonradar route. To the extent possible, aircraft operating on RNAV routes will be allowed to remain on their own navigation.
4.  When flying in Canadian airspace, pilots are cautioned to review Canadian Air Regulations.
    1.  Special attention should be given to the parts which differ from U.S. CFRs.
        1.  The Canadian Airways Class B airspace restriction is an example. Class B airspace is all controlled low level airspace above 12,500 feet MSL or the MEA, whichever is higher, within which only IFR and controlled VFR flights are permitted. (Low level airspace means an airspace designated and defined as such in the Designated Airspace Handbook.)
        2.  Unless issued a VFR flight clearance by ATC, regardless of the weather conditions or the height of the terrain, no person may operate an aircraft under VMC within Class B airspace.
        3.  The requirement for entry into Class B airspace is a student pilot permit (under the guidance or control of a flight instructor).
        4.  VFR flight requires visual contact with the ground or water at all times.
    2.  Segments of VOR airways and high level routes in Canada are based on L/MF navigation aids and are charted in brown color instead of blue on en route charts. <em>
        <div>

        ***FIG 5-3-1*** **  
        Adhering to Airways or Routes**

        </div>

        </em>![A graphic depicting an early turn and a turn at or after fix passage.](https://www.faa.gov/air_traffic/publications/atpubs/aim_html/images/aim_img_a07.jpeg)

**Airway or Route Course Changes ^5-3-5**

1.  Pilots of aircraft are required to adhere to airways or routes being flown. Special attention must be given to this requirement during course changes. Each course change consists of variables that make the technique applicable in each case a matter only the pilot can resolve. Some variables which must be considered are turn radius, wind effect, airspeed, degree of turn, and cockpit instrumentation. An early turn, as illustrated below, is one method of adhering to airways or routes. The use of any available cockpit instrumentation, such as Distance Measuring Equipment, may be used by the pilot to lead the turn when making course changes. This <em>is consistent</em> with the intent of [[Volume 2/F Air traffic and general operating rules/0091 General operating and flight rules.md#§91.181   Course to be flown.|14 CFR Section 91.181]], which requires pilots to operate along the centerline of an airway and along the direct course between navigational aids or fixes.
2.  Turns which begin at or after fix passage may exceed airway or route boundaries. FIG 5-3-1 contains an example flight track depicting this, together with an example of an early turn.
3.  Without such actions as leading a turn, aircraft operating in excess of 290 knots true air speed (TAS) can exceed the normal airway or route boundaries depending on the amount of course change required, wind direction and velocity, the character of the turn fix (DME, overhead navigation aid, or intersection), and the pilot's technique in making a course change. For example, a flight operating at 17,000 feet MSL with a TAS of 400 knots, a 25 degree bank, and a course change of more than 40 degrees would exceed the width of the airway or route; i.e., 4 nautical miles each side of centerline. However, in the airspace below 18,000 feet MSL, operations in excess of 290 knots TAS are not prevalent and the provision of additional IFR separation in all course change situations for the occasional aircraft making a turn in excess of 290 knots TAS creates an unacceptable waste of airspace and imposes a penalty upon the preponderance of traffic which operate at low speeds. Consequently, the FAA expects pilots to lead turns and take other actions they consider necessary during course changes to adhere as closely as possible to the airways or route being flown.

**Changeover Points (COPs) ^5-3-6**

1.  COPs are prescribed for Federal airways, jet routes, area navigation routes, or other direct routes for which an MEA is designated under 14 CFR Part 95. The COP is a point along the route or airway segment between two adjacent navigation facilities or waypoints where changeover in navigation guidance should occur. At this point, the pilot should change navigation receiver frequency from the station behind the aircraft to the station ahead.
2.  The COP is normally located midway between the navigation facilities for straight route segments, or at the intersection of radials or courses forming a dogleg in the case of dogleg route segments. When the COP is NOT located at the midway point, aeronautical charts will depict the COP location and give the mileage to the radio aids.
3.  COPs are established for the purpose of preventing loss of navigation guidance, to prevent frequency interference from other facilities, and to prevent use of different facilities by different aircraft in the same airspace. Pilots are urged to observe COPs to the fullest extent.

**Minimum Turning Altitude (MTA) ^5-3-7** Due to increased airspeeds at 10,000 ft MSL or above, the published minimum enroute altitude (MEA) may not be sufficient for obstacle clearance when a turn is required over a fix, NAVAID, or waypoint. In these instances, an expanded area in the vicinity of the turn point is examined to determine whether the published MEA is sufficient for obstacle clearance. In some locations (normally mountainous), terrain/obstacles in the expanded search area may necessitate a higher minimum altitude while conducting the turning maneuver. Turning fixes requiring a higher minimum turning altitude (MTA) will be denoted on government charts by the minimum crossing altitude (MCA) icon (“x" flag) and an accompanying note describing the MTA restriction. An MTA restriction will normally consist of the air traffic service (ATS) route leading to the turn point, the ATS route leading from the turn point, and the required altitude; e.g., MTA V330 E TO V520 W 16000. When an MTA is applicable for the intended route of flight, pilots must ensure they are at or above the charted MTA not later than the turn point and maintain at or above the MTA until joining the centerline of the ATS route following the turn point. Once established on the centerline following the turning fix, the MEA/MOCA determines the minimum altitude available for assignment. An MTA may also preclude the use of a specific altitude or a range of altitudes during a turn. For example, the MTA may restrict the use of 10,000 through 11,000 ft MSL. In this case, any altitude greater than 11,000 ft MSL is unrestricted, as are altitudes less than 10,000 ft MSL provided MEA/MOCA requirements are satisfied.

**Holding ^5-3-8**

1.  Whenever an aircraft is cleared to a fix other than the destination airport and delay is expected, it is the responsibility of ATC to issue complete holding instructions (unless the pattern is charted), an EFC time and best estimate of any additional en route/terminal delay.
    <div>

    <em>**NOTE-**</em>

    <em>Only those holding patterns depicted on U.S. government or commercially produced (meeting FAA requirements) low/high altitude en route, and area or STAR charts should be used.</em>

    </div>
2.  If the holding pattern is charted and the controller doesn't issue complete holding instructions, the pilot is expected to hold as depicted on the appropriate chart. When the pattern is charted on the assigned procedure or route being flown, ATC may omit all holding instructions except the charted holding direction and the statement<em> AS PUBLISHED; </em>for example, <em>HOLD EAST AS PUBLISHED. </em>ATC must always issue complete holding instructions when pilots request them.
3.  If no holding pattern is charted and holding instructions have not been issued, the pilot should ask ATC for holding instructions prior to reaching the fix. This procedure will eliminate the possibility of an aircraft entering a holding pattern other than that desired by ATC. If unable to obtain holding instructions prior to reaching the fix (due to frequency congestion, stuck microphone, etc.), then enter a standard pattern on the course on which the aircraft approached the fix and request further clearance as soon as possible. In this event, the altitude/flight level of the aircraft at the clearance limit will be protected so that separation will be provided as required.
4.  When an aircraft is 3 minutes or less from a clearance limit and a clearance beyond the fix has not been received, the pilot is expected to start a speed reduction so that the aircraft will cross the fix, initially, at or below the maximum holding airspeed.
5.  When no delay is expected, the controller should issue a clearance beyond the fix as soon as possible and, whenever possible, at least 5 minutes before the aircraft reaches the clearance limit.
6.  Pilots should report to ATC the time and altitude/flight level at which the aircraft reaches the clearance limit and report leaving the clearance limit.
    <div>

    <em>**NOTE-**</em>

    <em>In the event of two‐way communications failure, pilots are required to comply with [[Volume 2/F Air traffic and general operating rules/0091 General operating and flight rules.md#§91.185   IFR operations: Two-way radio communications failure.|14 CFR Section 91.185]].</em>

    </div>
7.  When holding at a VOR station, pilots should begin the turn to the outbound leg at the time of the first complete reversal of the to/from indicator.
8.  Patterns at the most generally used holding fixes are depicted (charted) on U.S. Government or commercially produced (meeting FAA requirements) Low or High Altitude En Route, Area, Departure Procedure, and STAR Charts. Pilots are expected to hold in the pattern depicted unless specifically advised otherwise by ATC.
    <div>

    <em>**NOTE-**</em>

    <em>Holding patterns that protect for a maximum holding airspeed other than the standard may be depicted by an icon, unless otherwise depicted. The icon is a standard holding pattern symbol (racetrack) with the airspeed restriction shown in the center. In other cases, the airspeed restriction will be depicted next to the standard holding pattern symbol.</em>

    </div>

    <div>

    <em>**REFERENCE-**</em>

    <em> [[#^5-3-8|AIM, Paragraph 5-3-8]] j2, Holding </em>

    </div>
9.  An ATC clearance requiring an aircraft to hold at a fix where the pattern is not charted will include the following information: (See FIG 5-3-2.)
    1.  Direction of holding from the fix in terms of the eight cardinal compass points (i.e., N, NE, E, SE, etc.).
    2.  Holding fix (the fix may be omitted if included at the beginning of the transmission as the clearance limit).
    3.  Radial, course, bearing, airway or route on which the aircraft is to hold.
    4.  Leg length in miles if DME or RNAV is to be used (leg length will be specified in minutes on pilot request or if the controller considers it necessary).
    5.  Direction of turn if left turns are to be made, the pilot requests, or the controller considers it necessary.
    6.  Time to expect further clearance and any pertinent additional delay information. <em>
        <div>

        ***FIG 5-3-2*** **  
        Holding Patterns**

        </div>

        </em>![A graphic depicting examples of holding patterns.](https://www.faa.gov/air_traffic/publications/atpubs/aim_html/images/aim_img_dde.jpeg) <em>
        <div>

        ***FIG 5-3-3*** **  
        Holding Pattern Descriptive Terms**

        </div>

        </em>![A graphic depicting holding pattern descriptive terms.](https://www.faa.gov/air_traffic/publications/atpubs/aim_html/images/aim_img_227.jpeg)
10. Holding pattern airspace protection is based on the following procedures.
    1.  **Descriptive Terms.**
        1.  **Standard Pattern.** Right turns (See FIG 5-3-3.)
        2.  **Nonstandard Pattern.** Left turns
    2.  **Airspeeds.**
        1.  All aircraft may hold at the following altitudes and maximum holding airspeeds: <em>
            <div>

            <em>**TBL 5-3-20**</em>**  
            **

            </div>

            </em>
            <table><tbody><tr class="odd"><td><p><strong>Altitude (MSL)</strong></p></td><td><p><strong>Airspeed (KIAS)</strong></p></td></tr><tr class="even"><td><p>MHA - 6,000'</p></td><td><p>200</p></td></tr><tr class="odd"><td><p>6,001' - 14,000'</p></td><td><p>230</p></td></tr><tr class="even"><td><p>14,001' and above</p></td><td><p>265</p></td></tr></tbody></table>

            <div>

            <em>**NOTE-**</em>

            <em>These are the maximum indicated air speeds applicable to all holding.</em>

            </div>
        2.  The following are exceptions to the maximum holding airspeeds:
            1.  Holding patterns from 6,001' to 14,000' may be restricted to a maximum airspeed of 210 KIAS. This nonstandard pattern will be depicted by an icon.
            2.  Holding patterns may be restricted to a maximum speed. The speed restriction is depicted in parenthesis inside the holding pattern on the chart: e.g., (175). The aircraft should be at or below the maximum speed prior to initially crossing the holding fix to avoid exiting the protected airspace. Pilots unable to comply with the maximum airspeed restriction should notify ATC.
            3.  Holding patterns at USAF airfields only - 310 KIAS maximum, unless otherwise depicted.
            4.  Holding patterns at Navy fields only - 230 KIAS maximum, unless otherwise depicted.
            5.  All helicopter/power lift aircraft holding on a “COPTER” instrument procedure is predicated on a minimum airspeed of 90 KIAS unless charted otherwise.
            6.  When a climb-in hold is specified by a published procedure (for example, “Climb-in holding pattern to depart XYZ VORTAC at or above 10,000.” or “All aircraft climb-in TRUCK holding pattern to cross TRUCK Int at or above 11,500 before proceeding on course.”), additional obstacle protection area has been provided to allow for greater airspeeds in the climb for those aircraft requiring them. A maximum airspeed of 310 KIAS is permitted in Climb-in-holding, unless a maximum holding airspeed is published, in which case that maximum airspeed is applicable. The airspeed limitations in [[Volume 2/F Air traffic and general operating rules/0091 General operating and flight rules.md#§91.117   Aircraft speed.|14 CFR Section 91.117]], Aircraft Speed, still apply.
        3.  The following phraseology may be used by an ATCS to advise a pilot of the maximum holding airspeed for a holding pattern airspace area.
            <div>

            <em>**PHRASEOLOGY-**</em>

            <em>(AIRCRAFT IDENTIFICATION) (holding instructions, when needed) MAXIMUM HOLDING AIRSPEED IS (speed in knots).</em>

            </div>

            <em>
            <div>

            ***FIG 5-3-4*** **  
            Holding Pattern Entry Procedures**

            </div>

            </em>![A graphic depicting holding pattern entry procedures.](https://www.faa.gov/air_traffic/publications/atpubs/aim_html/images/aim_img_576.jpeg)
    3.  **Entry Procedures.** Holding protected airspace is designed based in part on pilot compliance with the three recommended holding pattern entry procedures discussed below. Deviations from these recommendations, coupled with excessive airspeed crossing the holding fix, may in some cases result in the aircraft exceeding holding protected airspace. (See FIG 5-3-4.)
        1.  **Parallel Procedure.** When approaching the holding fix from anywhere in sector (a), the parallel entry procedure would be to turn to a heading to parallel the holding course outbound on the nonholding side for one minute, turn in the direction of the holding pattern through more than 180 degrees, and return to the holding fix or intercept the holding course inbound.
        2.  **Teardrop Procedure.** When approaching the holding fix from anywhere in sector (b), the teardrop entry procedure would be to fly to the fix, turn outbound to a heading for a 30 degree teardrop entry within the pattern (on the holding side) for a period of one minute, then turn in the direction of the holding pattern to intercept the inbound holding course.
        3.  **Direct Entry Procedure.** When approaching the holding fix from anywhere in sector (c), the direct entry procedure would be to fly directly to the fix and turn to follow the holding pattern.
        4.  While other entry procedures may enable the aircraft to enter the holding pattern and remain within protected airspace, the parallel, teardrop and direct entries are the procedures for entry and holding recommended by the FAA, and were derived as part of the development of the size and shape of the obstacle protection areas for holding.
        5.  **Nonstandard Holding Pattern.** Fix end and outbound end turns are made to the left. Entry procedures to a nonstandard pattern are oriented in relation to the 70 degree line on the holding side just as in the standard pattern.
    4.  **Timing.**
        1.  **Inbound Leg.**
            1.  At or below 14,000 feet MSL: 1 minute.
            2.  Above 14,000 feet MSL: 1<sup>1</sup>/<sub>2</sub> minutes.
                <div>

                <em>**NOTE-**</em>

                <em>The initial outbound leg should be flown for 1 minute or 1 <sup>1</sup>/<sub>2</sub> minutes (appropriate to altitude). Timing for subsequent outbound legs should be adjusted, as necessary, to achieve proper inbound leg time. Pilots may use any navigational means available; i.e., DME, RNAV, etc., to ensure the appropriate inbound leg times.</em>

                </div>
        2.  **Outbound leg** timing begins <em>over/abeam </em>the fix, whichever occurs later. If the abeam position cannot be determined, start timing when turn to outbound is completed.
    5.  **Distance Measuring Equipment (DME)/ GPS Along-Track Distance (ATD).** DME/GPS holding is subject to the same entry and holding procedures except that distances (nautical miles) are used in lieu of time values. The outbound course of the DME/GPS holding pattern is called the outbound leg of the pattern. The controller or the instrument approach procedure chart will specify the length of the outbound leg. The end of the outbound leg is determined by the DME or ATD readout. The holding fix on conventional procedures, or controller defined holding based on a conventional navigation aid with DME, is a specified course or radial and distances are from the DME station for both the inbound and outbound ends of the holding pattern. When flying published GPS overlay or stand alone procedures with distance specified, the holding fix will be a waypoint in the database and the end of the outbound leg will be determined by the ATD. Some GPS overlay and early stand alone procedures may have timing specified. (See FIG 5-3-5, FIG 5-3-6 and FIG 5-3-7.) [[01 Air Navigation/01 Navigation Aids#^1-1-17|See Paragraph 1-1-17]], Global Positioning System (GPS), for requirements and restriction on using GPS for IFR operations. <em>
        <div>

        ***FIG 5-3-5*** **  
        Inbound Toward NAVAID**

        </div>

        </em>![A graphic depicting the inbound leg toward NAVAID.](https://www.faa.gov/air_traffic/publications/atpubs/aim_html/images/aim_img_834.jpeg)
        <div>

        <em>**NOTE-**</em>

        <em>When the inbound course is toward the NAVAID, the fix distance is 10 NM, and the leg length is 5 NM, then the end of the outbound leg will be reached when the DME reads 15 NM.</em>

        </div>

        <em>
        <div>

        ***FIG 5-3-6*** **  
        Inbound Leg Away from NAVAID**

        </div>

        </em>![A graphic depicting the inbound leg away from NAVAID.](https://www.faa.gov/air_traffic/publications/atpubs/aim_html/images/aim_img_eea.jpeg)
        <div>

        <em>**NOTE-**</em>

        <em>When the inbound course is away from the NAVAID and the fix distance is 28 NM, and the leg length is 8 NM, then the end of the outbound leg will be reached when the DME reads 20 NM.</em>

        </div>
    6.  **Use of RNAV Distance in lieu of DME Distance.** Substitution of RNAV computed distance to or from a NAVAID in place of DME distance is permitted when holding. However, the actual holding location and pattern flown will be further from the NAVAID than designed due to the lack of slant range in the position solution (see FIG 5-3-7). This may result in a slight difference between RNAV distance readout in reference to the NAVAID and the DME readout, especially at higher altitudes. When used solely for DME substitution, the difference between RNAV distance to/from a fix and DME slant range distance can be considered negligible and no pilot action is required.
        <div>

        <em>**REFERENCE-**</em>

        <em> AIM Paragraph 1-2-3, Use of Suitable Area Navigation (RNAV) Systems on Conventional Procedures and Routes </em>

        </div>

        <em>
        <div>

        ***FIG 5-3-7*** **  
        Difference Between DME Distance From NAVAID & RNAV Computed Distance From NAVAID**

        </div>

        </em>![A graphic depicting the difference between DME distance from NAVAID & RNAV computed distance from NAVAID.](https://www.faa.gov/air_traffic/publications/atpubs/aim_html/images/aim_img_bab.jpeg)
    7.  **Use of RNAV Guidance and Holding.** RNAV systems, including multi-sensor Flight Management Systems (FMS) and stand-alone GPS receivers, may be used to furnish lateral guidance when executing a hold. The manner in which holding is implemented in an RNAV system varies widely between aircraft and RNAV system manufacturers. Holding pattern data may be extracted from the RNAV database for published holds or may be manually entered for ad-hoc ATC-assigned holds. Pilots are expected to be familiar with the capabilities and limitations of the specific RNAV system used for holding.
        1.  All holding, including holding defined on an RNAV or RNP procedure, is based on the conventional NAVAID holding design criteria, including the holding protected airspace construction. There are differences between the holding entry and flight track assumed in conventional holding pattern design and the entry and track that may be flown when RNAV guidance is used to execute holding. Individually, these differences may not affect the ability of the aircraft to remain within holding pattern protected airspace. However, cumulatively, they can result in deviations sufficient to result in excursions up to limits of the holding pattern protected airspace, and in some circumstances beyond protected airspace. The following difference and considerations apply when an RNAV system furnishes the lateral guidance used to fly a holding pattern:
            1.  Many systems use ground track angle instead of heading to select the entry method. While the holding pattern design allows a 5 degree tolerance, this may result in an unexpected entry when the winds induce a large drift angle.
            2.  The holding protected airspace is based on the assumption that the aircraft will fly-over the holding fix upon initial entry. RNAV systems may execute a “fly-by” turn when approaching the holding fix prior to entry. A “fly-by” turn during a direct entry from the holding pattern side of holding course may result in excursions beyond protected airspace, especially as the intercept angle and ground speed increase.
            3.  During holding, RNAV systems furnish lateral steering guidance using either a constant bank or constant radius to achieve the desired inbound and outbound turns. An aircraft's flight guidance system may use reduced bank angles for all turns including turns in holding, especially at higher altitudes, that may result in exceeding holding protected airspace. Use of a shallower bank angle will expand both the width and length of the aircraft track, especially as wind speed increases. If the flight guidance system's bank angle limit feature is pilot-selectable, a minimum 25 degree bank angle should be selected regardless of altitude unless aircraft operating limitations specify otherwise and the pilot advises ATC.
            4.  Where a holding distance is published, the turn from the outbound leg begins at the published distance from the holding fix, thus establishing the design turn point required to remain within protected airspace. RNAV systems apply a database coded or pilot-entered leg distance as a maximum length of the <em>inbound</em> leg to the holding fix. The RNAV system then calculates a turn point from the outbound leg required to achieve this inbound leg length. This often results in an RNAV-calculated turn point on the outbound leg beyond the design turn point. (See FIG 5-3-8). With a strong headwind against the outbound leg, RNAV systems may fly up to and possibly beyond the limits of protected airspace before turning inbound. (See FIG 5-3-9.) This is especially true at higher altitudes where wind speeds are greater and ground speed results in a wider holding pattern. <em>
                <div>

                ***FIG 5-3-8*** **  
                RNAV Lateral Guidance and Holding – No Wind**

                </div>

                </em>![A graphic depicting an RNAV-calculated turn point on the outbound leg beyond the design turn point with no wind.](https://www.faa.gov/air_traffic/publications/atpubs/aim_html/images/aim_img_bcb.jpeg)<em>
                <div>

                ***FIG 5-3-9*** **  
                RNAV Lateral Guidance and Holding – Effect of Wind**

                </div>

                </em>![A graphic depicting an RNAV-calculated turn point beyond the design turn point with a strong headwind against the outboung leg. RNAV systems may fly up to and beyond the limits of protected airspace before turning inbound.](https://www.faa.gov/air_traffic/publications/atpubs/aim_html/images/aim_img_d47.jpeg)
            5.  Some RNAV systems compute the holding pattern based on the aircraft's altitude and speed at a point prior to entering the hold. If the indicated airspeed is not reduced to comply with the maximum holding speed before this point, the computed pattern may exceed the protected airspace. Loading or executing a holding pattern may result in the speed and time limits applicable to the aircraft's current altitude being used to define the holding pattern for RNAV lateral guidance. This may result in an incorrect hold being flown by the RNAV system. For example, entering or executing the holding pattern above 14,000 feet when intending to hold below 14,000 feet may result in applying 1 ½ minute timing below 14,000 feet.
                <div>

                <em>**NOTE-**</em>

                <em>Some systems permit the pilot to modify leg time of holding patterns defined in the navigation database; for example, a hold-in-lieu of procedure turn. In most RNAV systems, the holding pattern time remains at the pilot-modified time and will not revert back to the coded time if the aircraft descends to a lower altitude where a shorter time interval applies.</em>

                </div>
        2.  RNAV systems are not able to alert the pilot for excursions outside of holding pattern protected airspace since the dimensions of this airspace are not included in the navigation database. In addition, the dimensions of holding pattern protected airspace vary with altitude for a charted holding pattern, even when the hold is used for the same application. Close adherence to the pilot actions described in this section reduce the likelihood of exceeding the boundary of holding pattern protected airspace when using RNAV lateral guidance to conduct holding.
        3.  Holding patterns may be stored in the RNAV system's navigation database and include coding with parameters defining how the RNAV system will conduct the hold. For example, coding will determine whether holding is conducted to manual termination (HM), continued holding until the aircraft reaches a specified altitude (HA), or holding is conducted until the holding fix is crossed the first time after entry (HF). Some systems do not store all holding patterns, and may only store patterns associated with missed approaches and hold-in-lieu of procedure turn (HILPT). Some store all holding as standard patterns and require pilot action to conduct non-standard holding (left turns).
            1.  Pilots are cautioned that multiple holding patterns may be established at the same fix. These holding patterns may differ in respect to turn directions and leg lengths depending on their application as an en route holding pattern, a holding pattern charted on a SID or STAR, or when used on an instrument approach procedure. Many RNAV systems limit the database coding at a particular fix to a single holding pattern definition. Pilots extracting the holding pattern from the navigation database are responsible for confirming that the holding pattern conforms to the assigned charted holding pattern in terms of turn direction, speed limit, timing, and distance.
            2.  If ATC assigns holding that is not charted, then the pilot is responsible for programming the RNAV system with the assigned holding course, turn direction, speed limit, leg length, or leg time.
            3.  Changes made after the initial execution may not apply until the next circuit of the holding pattern if the aircraft is in close proximity to the holding fix.
    8.  **Pilot Action.** The following actions are recommended to ensure that the aircraft remains within holding protected airspace when holding is performed using either conventional NAVAID guidance or when using RNAV lateral guidance.
        1.  Speed. When ATC furnishes advance notice of holding, start speed reduction to be at or below the maximum holding speed allowed at least 3 minutes prior to crossing the holding fix. If advance notice by ATC is not provided, begin speed reduction as expeditiously as practical. It is acceptable to allow RNAV systems to determine an appropriate deceleration point prior to the holding fix and to manage the speed reduction to the RNAV computed holding speed. If the pilot does not permit the RNAV system to manage the deceleration from the computed point, the actual hold pattern size at holding entry may differ from the holding pattern size computed by the RNAV system.
            1.  Aircraft are expected to enter holding at or below the maximum holding speed established [[#^5-3-8|in paragraph 5-3-8]] j 2(a) or the charted maximum holding speed.
                1.  All fixed wing aircraft conducting holding should fly at speeds at or above 90 KIAS to minimize the influence of wind drift.
                2.  When RNAV lateral guidance is used in fixed wing airplanes, it is desirable to enter and conduct holding at the lowest practical airspeed consistent with the airplane's recommended holding speed to address the cumulative errors associated with RNAV holding and increase the probability of remaining within protected airspace. It is acceptable to allow RNAV systems to determine a recommended holding speed <em>that is at or below the maximum holding speed. </em>
                3.  Helicopter holding is based on a minimum airspeed of 90 KIAS.
            2.  Advise ATC immediately if unable to comply with the maximum holding airspeed and request an alternate clearance.
                <div>

                <em>**NOTE-**</em>

                <em>Speeds above the maximum or published holding speed may be necessary due to turbulence, icing, etc. Exceeding maximum holding airspeed may result in aircraft excursions beyond the holding pattern protected airspace. In a non-radar environment, the pilot should advise ATC that they cannot accept the assigned hold.</em>

                </div>
            3.  Ensure the RNAV system applies the proper time and speed restrictions to a holding pattern. This is especially critical when climbing or descending to a holding pattern altitude where time and speed restrictions are different than at the present aircraft altitude.
        2.  Bank Angle. For holding not involving the use of RNAV lateral guidance, make all turns during entry and while holding at:
            1.  3 degrees per second, or
            2.  30 degree bank angle, or
            3.  25 degree bank angle, provided a flight director system is used.
                <div>

                <em>**NOTE-**</em>

                <em>Use whichever requires the least bank angle.</em>

                </div>
            4.  When using RNAV lateral guidance to conduct holding, it is acceptable to permit the RNAV system to calculate the appropriate bank angle for the outbound and inbound turns. Do not use flight guidance system bank angle limiting functions of less than 25 degrees unless the feature is not pilot-selectable, required by the aircraft limitations, or its use is necessary to comply with the aircraft's minimum maneuvering speed margins. If the bank angle must be limited to less than 25 degrees, advise ATC that additional area for holding is required.
        3.  Compensate for wind effect primarily by drift correction on the inbound and outbound legs. When outbound, triple the inbound drift correction to avoid major turning adjustments; for example, if correcting left by 8 degrees when inbound, correct right by 24 degrees when outbound.
        4.  Determine entry turn from aircraft heading upon arrival at the holding fix; +/- 5 degrees in heading is considered to be within allowable good operating limits for determining entry. When using RNAV lateral guidance for holding, it is permissible to allow the system to compute the holding entry.
        5.  RNAV lateral guidance may execute a fly-by turn beginning at an excessively large distance from the holding fix. Reducing speed to the maximum holding speed at least 3 minutes prior to reaching the holding fix and using the recommended 25 degree bank angle will reduce potential excursions beyond protected airspace.
        6.  When RNAV guidance is used for holding, pilots should be prepared to intervene if the turn from outbound leg to the inbound leg does not begin within a reasonable distance of the charted leg length, especially when holding is used as a course reversal HILPT. Pilot intervention is not required when holding in an ATC-assigned holding pattern that is not charted. However, notify ATC when the outbound leg length becomes excessive when RNAV guidance is used for holding.
11. When holding at a fix and instructions are received specifying the time of departure from the fix, the pilot should adjust the aircraft's flight path within the limits of the established holding pattern in order to leave the fix at the exact time specified. After departing the holding fix, normal speed is to be resumed with respect to other governing speed requirements, such as terminal area speed limits, specific ATC requests, etc. Where the fix is associated with an instrument approach and timed approaches are in effect, a procedure turn must not be executed unless the pilot advises ATC, since aircraft holding are expected to proceed inbound on final approach directly from the holding pattern when approach clearance is received.
12. Radar surveillance of holding pattern airspace areas.
    1.  Whenever aircraft are holding, ATC will usually provide radar surveillance of the holding airspace on the controller's radar display.
    2.  The controller will attempt to detect any holding aircraft that stray outside the holding airspace and will assist any detected aircraft to return to the assigned airspace.
        <div>

        <em>**NOTE-**</em>

        <em>Many factors could prevent ATC from providing this additional service, such as workload, number of targets, precipitation, ground clutter, and radar system capability. These circumstances may make it unfeasible to maintain radar identification of aircraft to detect aircraft straying from the holding pattern. The provision of this service depends entirely upon whether controllers believe they are in a position to provide it and does not relieve a pilot of their responsibility to adhere to an accepted ATC clearance.</em>

        </div>
    3.  ATC is responsible for traffic and obstruction separation when they have assigned holding that is not associated with a published (charted) holding pattern. Altitudes assigned will be at or above the minimum vectoring or minimum IFR altitude.
    4.  If an aircraft is established in a published holding pattern at an assigned altitude above the published minimum holding altitude and subsequently cleared for the approach, the pilot may descend to the published minimum holding altitude. The holding pattern would only be a segment of the IAP <em>if</em> it is published on the instrument procedure chart and is used in lieu of a procedure turn.
13. For those holding patterns where there are no published minimum holding altitudes, the pilot, upon receiving an approach clearance, must maintain the last assigned altitude until leaving the holding pattern and established on the inbound course. Thereafter, the published minimum altitude of the route segment being flown will apply. It is expected that the pilot will be assigned a holding altitude that will permit a normal descent on the inbound course.

</div>