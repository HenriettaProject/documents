Instrument Support Agreement for Henrietta


# Instrument Description
Henreitta is an installable instrument for the Swope f/7 back focus. It uses the observatory guider package for guiding. Henrietta comes with its own instrument rotator. It is kept cold via liquid nitrogen (LN2) with a large tank internal to the instrument. It contains a variety of electronics (Lakeshore, Galil, ethernet hub, and Archons) to run the instrument. A Mac is used to control Henrietta.

The Henrietta Instrument Team is led by Nick Konidaris at Carnegie Observatories, and he's the primary contact. 

We intend for Henrietta to be a facility instrument on Swope. 


# Configuration

The port is the Swope back focus f/7, attached to the guider package. No changes to baffles or sub-aperture corrector are needed. Henrietta uses the standard Swope Guiding package. A series of documents and estimates was written to generate a counterweight plan, and swapping between the CCD camera and Henrietta should be straightforward.

Henrietta is about 800 lbs, and maybe about 1 meter long.

The equipment on Henrietta includes:
- Lakeshore Cryogenic Temperature Controller
- Galil controller
- Archon controller
- Ethernet hub
- DLI Network power switch

We also provide:
- One large vacuum pump
- Flexible plumbing to connect LN2 from the small tank to Henrietta.
- A solenoid circuit to help fill the instrument.

In the office:
- One mac mini computer running all software. TBC - Will the Mac Mini go in the Computing Rack, or in the observing room? If it goes into the rack, do we need to bring a shelf? (For Lionel + William). The Mac Mini will connect via No Machine to the Observing Workstation.
- Software provided
  - Rotator control
  - Instrument control
  - Does Swope have the ability to use Observing Catalog Format? If not, it should. (TBC - William / Christoph)
  - Hardhats for the Galil, Lakeshore, DLI, and Archon


# Service Requirements
- Power on the Telescope
  - 235 W of 110 V AC power, "clean" with UPS Backup. Our power usage is based on the total power that the instruments could use.
    - Archon: 100 W
    - Lakeshore: 100 W
    - Galil: 16 W (TBC)
    - Network switch: 15 W (TBC)
    - DLI: 4 W
  - Compressed air
  -   Clean air suitable for pneumatics
  -   Clean, dry air for keeping front window dry
- Liquid Nitrogen
  - ~22 psi liquid nitrogen for filling

# Routine Support

- Routine Maintenance
  - Filling with LN2
    - We request daily fills of LN2 in the morning. 
  - When observers are using Henrietta
    - typical support for the telescope. Staff should monitor for any major issues. Staff will have enough knowledge of engineering "hard hats" to do lightweight debugging and restartin of servers.
  - When Henreitta is in storage
    - We request that Henreitta stored with a thick tarp cover. In that configuration, nothing should happen to Henrietta. Maybe occassional dusting is requested.
  - Replacement of the pumping station tip seal- if LCO is capable, we request yearly replacement of the tip seal, or when we see insuficient backing pressure.

- Routine Instrument Changes
  - We'll work with the LCO staff to optimzie the process as per any requests. Our suggestion is the following:
  - Pumping
    - A turbo pumping station will be provided. The station will come with various bellows that can be attached using typical KF-50 fittings.
    - Henreitta will require two days of pumping before cooling. The instrument's pressure can be monitored via grafana.
  - Cooling
    - Cooling is a bit more complicated. Once the dewar is at the appropriate pressure, LCO staff will run a script to dose LN2 in a pre-prescribed fashion (fill for 20 s every few minutes.) Because Solenoid valves can fail open, we request that the temperature cooldown be monitored for a valve failure. Note, the script will only run during a reasonable local time (9:30a - 4:30p?). Before starting the script the next morning, we request a one-hour pump down.
  - Power up
    - The instrument will be powered up via the DLI. Because the Archon cannot be run warm, we request the Archon power switch be turned off.
- Software
  - We intend to connect Henrietta to the Observatory's database and Grafana.

# Troubleshooting and Repair

## Subsystems Serviceable by Observatory Staff
- Vacuum pumping station, bellows, KF50 connectors, and so forth. The observatory can vacuum pump and cool the instrument.
- Electronics rack: Repalcement of standard power cables, network cables, and so forth. Replacement of the Network Power Switch (DLI), the Network hub, and so forth is OK.
- Installation: The observatory can install the instrument using the provided instrument cart and alignment pins.

## Subsystems Servicable by Instrument Team
- Dewar interior
- Archon controller
- Alignment screws.


# Support Provided by the Instrument TEam

- Point of contact: Nick Konidaris (npk@carnegiescience.edu)
- Mailing list: henrietta@mailman.carnegiescience.edu
- Remote help provided: Complete manual for the instrument
- Nick Konidaris and Jason Williams will be travelling to the observatory often, and we're happy to chat with the LCO team!

## Training
- Nick and Jason will provide support and training as needed.
- Nick and Jason will share the data reduction pipeline on GitHub


# Handling and Storage Fixtures
- Description: The Henrietta handling cart is already at LCO. Henreitta will be shipped with all necessary straps and bolts to be handled. The cart will be used to store Henrietta.
- We request that a cover be made for Henrietta.


## Transportation on the Mountain
- Henrietta can be moved around the mountain using the standard careful procedures that LCO uses to move instruments.

# Special Provisions

## Use of clean room
Occassionally, we anticipate needing to change slit masks, filters, and or grisms, or perform light maintenance of Henrietta. For that, we request the ability to use the clean room. Based on seeing the clean room, we believe Henrietta will easily fit in the clean room. Performing such work will be orchestrated with the LCO engineering team.




  
