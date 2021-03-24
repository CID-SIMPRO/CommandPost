# CommandPost
Command post simulator

## Basic interrogants:
- What is the mission (the big picture)?
- What are the required capabilities to conduct the mission successfully?
- What relations are necessary in order to support an orchestrated set of functions that provide the required capabilities?
- What systems can provide these functions, and do they support the necessary interfaces to other systems to allow for the required orchestration (i.e. being part of the required communications infrastructure as well as having the capability to provide and utilize required messages and formats)?
- What are my time constraints?

## Basic descriptions:
- The geospatial definition of the scenario
- A description of the environment, including terrain and weather, relevant to the scenario
- The definition of the mission and the means required to achieve the mission of the scenario
- The objectives that define the mission of the scenario on all relevant levels, which results in measures of merit on various levels, providing an objective hierarchy as known from systems engineering processes
- The events that will take place during the time the scenario is intended to span

## Questions

  ### Generals:
  - What do I know about the underlying entities, processes, and relations?
  - Where do I get the necessary data?
  - How do I manage aggregation and de-aggregation of information?
  - Are there solutions to similar problems available (including lessons learned)?

  ### Environment, terrain and weather
  - How environment, terrain and weather affects the simulation?
    - Day and night cycle
    - Terrain elevation
    - Surface type
    - Coverage (building, vegetations)
    - Hear sounds
    - Clouds, wind, temperatures (aircrafts)
    - Temperature, currents (naval)
  
  ### Land components
  - Standarize table of equipment (TOE) is needed?
    - Keep track of how much material will be assigned to each platform, such as different types of ammunition, fuel, etc
    - The number and type of weapon systems per unit are defined.
  -  How fast can a system move in different kinds of terrain?
    - Do we need parameters that capture their important characteristics regarding mobility and vulnerability ??
  - Direct and Indirect fire?
  -  Mine warfare needs to be taken into account as well?
  -  Are tactical lines going to be simulated?
   
   #### Basic description of land units
   • Infantry is made up of soldiers, sometimes modeled as squads, with handheld firearms, like rifles, machine guns, or even anti-tank missiles. They may be protected by body armor but, in general, are soft targets that should avoid direct fire without protection.
   • Infantry transportation is provided by off-road capable vehicles, like Jeeps or High Mobility Multipurpose Wheeled Vehicles. They are normally not armored and have only light weapons, like mounted machine guns.
   • Armored Fighting Vehicles, sometimes referred to as Infantry Fighting Vehicles or Mechanized Infantry Combat Vehicles, are light tanks designed to carry infantry into battle and provide fire support for them. They carry several soldiers that may be able to engage in battles while being in the tank and have light to medium weapon systems for direct fire.
   • Main Battle Tanks carry the main part of direct fire battles. They have strong armor and heavy weapons.
   • Mortars are high-angle-of-fire weapons that fire ammunition at a high angle so that it falls onto the enemy. Mortars come in several sizes, from small mortars that can be used and carried by infantries to bigger mortars that are part of the artillery.
   • Main artillery systems are howitzers and rocket launchers. Howitzers can be towed or self-propelled. As a rule, howitzers fire ammunition while rocket launchers, often MLRS, launch self-propelled rockets, but there are exceptions for modern howitzers.
   • Army aviation focuses most often on helicopters, often referred to as rotary wing aircraft, but also uses fixed wing aircraft. These are used mainly for transportation and air based fire support.
      ##### Agregated units:
      • combat or maneuver units (tanks, infantry, armored and infantry fighting vehicles, etc.)
      • fire support units (artillery, missile units, close air support, etc.)
      • combat engineers (obstacles and mine warfare, active and passive)
      • air defense (escorting air defense, air defense facilities, radar, etc.)
      • aviation (helicopters, fixed wing aircraft, unmanned air vehicles, etc.)
      • command and control (headquarters)
      • intelligence and reconnaissance (sensors and facilities)
      • communications and networks (infrastructure and systems)
      • logistics and supply (transportation and facilities)
      • maintenance and medical (in-field support and facilities)
      • nuclear, biological, and chemical (NBC) warfare
      • others
      
  ### Air components
  - Airports with their runways and shelters are of interest as well?
  - Air defense facilities are of particular interest as well?
  - Is the he methods of air space control going to be simulated?
  - What about the positive identification means as a method to identify an aircraft as friend or foe.
    #### Basic description of air units
    • Fighters for air-to-air combat
    • Bombers for air-to-ground combat
    • Transportation aircraft
    • Airborne operations
    • Command and control
    • Intelligence
    • Surveillance
    • Reconnaissance
    
  ### Naval components
- Airports with their runways and shelters are of interest as well?
- Air defense facilities are of particular interest as well?
- Is the he methods of air space control going to be simulated?
- What about the positive identification means as a method to identify an aircraft as friend or foe.
  #### Basic description of air units
  • Aircraft carriers that are deployable air bases on the sea. Their primary task is to deploy and recover naval air power, but they are also used to launch missiles.
  • Battle cruisers and battle ships provide the artillery firepower and missile launching capability of naval force.
  • Frigates and corvettes are normally used to protect battle ships and aircraft carriers, in particular against opposing submarines. They are also often used to protect merchant vessels against pirates or support convoys by providing basic protection. Special submarine hunters focus exclusively on battles against enemy submarines.
  • Destroyers and cruisers fulfill a similar role to frigates and corvettes, but their main weapon system is the torpedo.
  • Special vessels for sea mine warfare are mine sweepers and mine hunters. Some naval forces also use specially designed mine layers.
  • Tenders provide logistics and maintenance for the navy and its related systems.
  • Submarines are used for underwater warfare. They come in many roles and shapes, ranging from nuclear submarines that can remain under water for weeks to tactical small submarines for operations in littoral areas or shallow waters, like the Baltic Sea.
  • Hospital ships provide medical supply.
  
## JOINT OPERATIONS AND COMMAND AND CONTROL ????

### Necesary standards frameworks systems:
  #### Environmental data
   ##### SEDRIS: Synthetic Environment Data Representation and Interchange Specification
  - The Environmental Data Coding Specification (EDCS)
  - The Data Representation Model (DRM)
  - The Spatial Reference Model (SRM)
  - The SEDRIS Transmittal Format (STF)

## Core processes of combat modeling: shooting (combat), moving, looking (sensing), and communicating.
  ### Movement:
  - Explicit grid models 
  - Explicit patch models
  - Implicit mobility models (outdated)
  - Network models
  -- Are formations modeled??
  -- Casualties and casualty rates influence movement??
  ### Looking (Sensing):
  - Line of sight algorithms
  - High resolution sensing
  - Aggregate sensing
  - Reports
  - Uncertainty and Perception
  - Radar and sonar modeling
  - Inteligence, surveillance and reconnaissance
  ### Shooting (Combat):
  - Direct fire, Indirect fire and smart weapons
  - Entity level engagement and attrition models
    - Game-Based Point Systems
    - Hit, Kill, and Kill-when-Hit Probabilities
    - Damage Classes
      - movement kill
      - firepower kill
      - communication kill
      - sensors kill
      - catastrophic kill
  - Aggregate level engagement and attrition models
    - Classic Lanchester Models
    - Extended Lanchester Models
    - Heterogeneous and Stochastic Lanchester Models
    - Reserves and Logistics and Maintenance
    - Breakpoints
    - Epstein’s Model of Ground Warfare
    - Combat Power Scores
    - Intention-Based Modeling versus Effect-Based Modeling
  ### Communication
    - Command and control modeling
      - Command and control messages
      - INFORMATION AGE COMBAT MODEL (ICAM)
    - Communication modeling
  
    
  
    
