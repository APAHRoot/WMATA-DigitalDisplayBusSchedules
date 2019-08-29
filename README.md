# WMATA-DigitalDisplayBusSchedules
WMATA Metro Bus API interface for Bus arrivals at given stops. Intended for use with Pi-Signage (in tandem with their weather app [not reliant on it]), but should work as a basis for other applications too!

Licensed under Creative Commons as Attribution-NonCommercial-ShareAlike 4.0 International
    i.e you can use this in your own display solutions or as reference, but you can't sell it as a standalone or as a paid-to-add feature
    2019 Nathaniel Root and the Arlington Partnership for Affordable Housing
    
    This widget was designed for usage with PiSignage but should be generalizable to other implementations
    
    The simple WMATA Metrobus Real Time schedule tracker, for digital signage displays!
    Name undoubtedly needs work.
    
    This widget interfaces with WMATA's API (sign up here and make sure to subscribe on their products page to get a key https://developer.wmata.com/)
    Specifically their real time bus eta information, and uses it create a digital read out of incoming busses at specified bus stops.
    The current design is set for 4 bus stops on a 1920x1080 resolution (resolution not hard coded, just the display type that was in mind when built)
    with a weather widget being displayed on the left hand side (not included and not needed for this page to load properly).
    You can easily modify this to add additional bus stops being displayed at any one time through the style coding.
    Bus stop numbers modified in the java script section. You can find bus stop locations here: https://buseta.wmata.com/
    
    Have fun with it and hope this is helpful for someone out there!
    
    Shout out to https://www.taniarascia.com/how-to-connect-to-an-api-with-javascript/
    
    Last update: 2019-August-29
