# Loadcenter Guide

## Receiving

!!! tip "Receiving the building"

    - Remove shipping protection from the outside of the building
    - Ensure there is nothing obstructing the exhaust dampers
    - Ensure the intakes can be opened
    - Ensure the filters are free of debris
    - Check for any damage to the exterior of the building

For optimal performance, Upstream Data recommends orienting the building parallel to prevailing wind directions.
For even more performance, we also suggest placing the unit on piles, or raised framework.

When placing multiple loadcenters near each other, we suggest at least 8ft between the outside walls.

## Grounding

All loadcenters must be bonded to ground prior to operation, either:

- To an existing ground system on site, or
- a new ground which complies with the electrical code in your jurisdiction.

!!! danger
    Improper or missing grounding can result in electrical issues, instability, and serious damage to components.
    
    Failure to properly ground the loadcenter will void your warranty.
    

## Shrouds and recirculation

All modern loadcenters come with fold-out shrouds which are used to deflect heat away from the intakes,
and can be configured to recirculate heat during winter months.
These shrouds should be folded out, and screwed in place with Tek screws prior to operation.

??? info "Older loadcenters"
    On some older loadcenters, the shrouds come disassembled.
    Upon receiving them, they will need to be assembled, using Tek screws and an impact driver.
    
    !!! warning
        Remember to use gloves and PPE when working around sharp metal edges.

    To assemble them, follow this process:

    1. Lay the outer casing out flat, with the flanges for screwing facing down.
    2. Put the sliding heat recirculation holder in place inside of it.
        The slot for the heat recirculation slider should be just outside of the metal of the casing.
    3. Screw the casing and slider holder together to attach them.
    4. Add the deflectors, starting at the bottom. They should all face
        away from the slider. Screw these to the casing to secure them.

        !!! note
            Some building have 4 deflectors per shroud, other have 5.
            Split the deflectors up as needed to ensure each shroud has the same amount of deflectors.

    5. Insert the heat deflector slider.
 
        ![Deflector assembly](images/deflectors.png){ .fix-png }
        /// caption
        Deflector Assembly Steps
        ///

    6. Attach the shrouds to the building, with the top shroud deflectors facing up, and the bottom deflectors facing down.

        ![Deflector attachment](images/attaching-deflectors.png){ .fix-png width="20%" }
        /// caption
        Deflector Attachment Direction
        ///


## Installing Miners

Your loadcenter may come with laser cut inserts, depending on what type of miners you are using:

- [x] Bitmain ntminer X19 series
- [ ] Bitmain Antminer X21 series
- [x] MicroBT Whatsminer
- [x] Canaan Avalonminer
- [x] Other (Contact Us)

Before installing miners, place the inserts into the shelves, with the metal flanges facing toward the outside of the building.

![Miner inserts](images/inserts.svg){ .fix-png width="50%" }
/// caption
Miner Inserts
///


!!! tip "Shelving Miners"
    1. Place the miner on the shelf.
    2. Slide the miner all the way to the back. The body of the miner should press against the insert, or the shelf lip (for X21 series miners).

## LoadSync™ setup

LoadSync™ should be powered via a UPS, which is included inside the loadcenter. There are also cables included with the UPS to connect it to LoadSync™.

!!! tip "Connecting the UPS and LoadSync™"
    1. Connect the supplied cords to the black "battery" sockets on the back of the UPS.
    2. Place the UPS either on the floor, or on the provided shelf (if applicable).
    3. Connect the other end of the cables to LoadSync™, one to the bottom of the panel, the other to the exposed cable end.

## Internet

The easiest way to connect internet to the loadcenters is with Starlink.

Internet is routed in via a port on the top of the LoadSync™ panel.

=== "Starlink"

    !!! tip "Connecting Internet"
        1. Use the provided adaptor cable to power the Starlink modem from the UPS.
        2. Run the ethernet cable from the Starlink modem to the input port on top of LoadSync™.

    !!! warning "Changing the Subnet"
        It is recommended that you change which subnet your Starlink modem is configured to.
    
        The default is `192.168.1.1/24`, which is very common in residential routers, and can cause overlaps.
        If the subnet in the loadcenter overlaps with your local subnet, some features of LoadSync™ (such as the Tailscale integration) may not work properly.

=== "LTE Modem"

    !!! tip "Connecting Internet"
        1. Use the provided adaptor cable to power the LTE modem from the UPS.
        2. Run the ethernet cable from the LTE modem to the input port on top of LoadSync™.
        3. Connect the small end of the coax adaptor cable to the `main` port on the modem.
        4. Connect the large end of the coax adaptor cable to the lightning arrestor, mounted to the wall.
        5. Connect the large coax cable to the other end of the lightning arrestor.
        6. Route the large coax cable out of the building using the provided 1" nipple on the wall.
        7. Attach the other end of the large coax cable to the provided antenna.
        8. Mount the antenna on the mast, and mount the mast to the building.
        9. Insert the SIM card into the modem in slot 1.

        For help with configuring the APN if needed, please [contact us](#contact-us).
        

=== "Other"
    
    !!! tip "Connecting Internet"
        1. If needed, use the provided adaptor cable to power your router from the UPS.
        2. Run the ethernet cable from the router to the input port on top of LoadSync™.

## Startup

=== "Hash Huts"

=== "Hash Generators"
    
    !!! warning "Prior to startup"

        Before progressing to the startup procedures:

        - Check for any loose or damaged components that may have occurred during shipping.
        - Uncap and assemble the exhaust.
        - Ensure that the correct size gas line is being used and has been inspected and approved for use.
        - Connect the gas line to the gas intake on the outside of the building.
        - Check that input pressure is correct (5PSI minimum to 25PSI maximum).
        - Ensure all manifolds are corectly set.
        - Check coolant levels and add 50/50 premix as required.
        - Check engine oil levels and add 15W-40 low ash oil if needed.
        - Ensure there is 6oz-8oz (8-12in W.C) after the regulator.
        - Purge the the fuel line of any air.
        - Double check for any fuel leaks.
        - Open 1 1/4" or 2" gas valva at the rear of the engine.

    !!! tip "Startup"
        
        Ensure all electrical crcuit breakers are in the off/open position.
        This includes breakers in auxilary panels.

        === "Dynagen"
            
            1. Press the "Off" button on the Dynagen controller.
            2. Allow the engine to warm up to operating temperature.
            3. Check fuel pressures to ensure stability.
            4. Once the engine is at operating temperature, it will ramp up to full RPM automatically.
            5. Check fuel pressures again to ensure stability at full RPM.
            6. Adjust household regulator if needed.

        === "DeepSea"

            1. Press the "Off" button.

## Contact Us

For all sales inquiries, please contact our sales department:

- [sales@upstreamdata.com](mailto://sales@upstreamdata.com)

For questions or concerns regarding the loadcenter or its components, please contact our support team:

- [support@upstreamdata.com](mailto://support@upstreamdata.com)

!!! tip
    New loadcenters come with a "Contact Us" QR code on the nameplate, which will include the serial number in the email.
    This is the best way to contact us for support inquiries, as it gives us the necessary information to help you.

You can also contact us through our website, [upstreamdata.ca](https://upstreamdata.com).

*[UPS]: Uninterruptible Power Supply