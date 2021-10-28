# BEGameMonitor

# CREDIT
All credit goes to the orginal creator of this tool : http://begm.sourceforge.net/

The purpose of this repository is to keep this amazing tool functional

# What is Battleground Europe Game Monitor?
BEGM is a third party external game monitoring utility for the MMO Battleground Europe (formerly World War 2 Online). It provides access to a wide range of information about the game in a friendly and easy to navigate format. It is designed for those that want to check out what’s been happening without having to start the game up or those that want to keep an eye on things while at work away from the action. It’s also useful for commanding officers that need to know what’s going on around them or anyone that needs that extra edge in battlefield intelligence while playing online.

Using BEGM you can keep track of significant game events including captures, attack objectives, firebase changes, brigade movements, and factory damage. It allows you to see at a glance what has been happening in the past couple of hours and where the current battles are. You can drill down to details on the facilities within a specific town or scroll around the game map to get the bigger picture. Factory bombers can see reports and graphs of the past 24 hours factory production and damage, from overall side summaries down to each individual factory. You can choose to be notified of important events or follow an attack with pop-up alerts – select the events you want to be notified for by a combination of town, country and event type (say, Antwerp, Germany, Spawnable Depot Captured).

# Features




* Game status window
  * Can be docked on left or right side of screen for easy access and alt-tabbing while in game
  * Sections can be expanded/collapsed and reordered, state is preserved between sessions
  * Drag edge to add extra columns, drag widgets between columns
  * Detatch widgets by dragged them out of the window
  * Can be set to launch on startup and/or start minimised
  * Multiple monitor support
  * Full screen support
  * Launch game menu with links to different modes (eg, offline, training, beta)
    * Includes server state and population
  * Spanish, German and French language support
  * Current campaign and day number
* Server status
  * Current server state (online, locked, etc)
  * Live server player population
  * Allied v Axis gauges for:
     * Player kills
    * Facility captures
    * Town ownership
    * Firebase ownership
    * Attacks objectives
  * Graphs of kills/captures over past hour
  * Current server configuration parameters
    * Ability to track changes made
* Recent events
  * Lists the last two hours of game events, including things such as:
    * Facilities captured or recaptured
    * Towns under attack, regained, captured, or control changed
    * Attack Objectives placed or withdrawn
    * Firebases blown
    * Brigades or division HQs deployed, moved or routed
    * Factories damaged, destroyed, repaired or halted/resumed production
  * Visible events can be filtered by category
  * New events are highlighted by time received
  * Event list sort order can be set in preferences
* Current attacks
  * Shows all towns that are or have been under attack, with their associated events
  * Allows you to subscribe to alerts for each attack
  * Town AO status and activity level indicator
  * Capture progress bar with ownership percentage of town
* Town status
  * Displays a detailed report on the status of a town
  * Current owner (time since last captured) and controller (time since last changed)
  * Contention status (time since contested/regained)
  * Attack Objective (time since placed, attacking brigade)
  * Activity level indicator
  * Town(s) where the attack is coming from
  * Capture progress bar, weighted by facility type
  * List of facilities including owner, how long held for, table & spawnable state
  * List of deployed brigades, how long they’ve been deployed, player that last moved them
  * List of linked towns, their owner, firebase state and distance
  * List of nearby bridges
* Game map
  * Pan/zoomable mini game map showing town ownership with:
    * Contention and Attack Objective status
    * Deployed brigade and airfield locations
    * Active firebases
    * Supply and Brigade links
    * Air grid
    * Frontlines
    * Attack arrows
    * Player activity
    * Country borders/names
  * Lat/long, grid cell reference, and name of town or firebase under cursor
  * Jump to town by name
  * Configure level of detail drawn on map
  * Select a town to view details on:
    * Friendly and enemy links
    * Number and type of facilities
    * Number and type of deployed units
    * Number of supply links (total and available)
    * Original owner
    * Lat/long location (with link to real town in Google Maps)
 * Town altitude in meters/feet
 * Selectable map size (optional plugin)
 * Set map as windows desktop wallpaper
 * Resizable when detatched from main window
* Factory status
 * Side summaries with output, average health, and production stats for past day/campaign
 * RDP cycle number, percent complete, estimated completion
 * Stats on each individual factory, including 24 hour damage and production graphs
 * Download factory data on startup optional for faster load time
* Order of battle
 * Browsable tree of the high command structure for each country and branch
 * Contains deployment location, time since last moved and by which player
 * Recently moved units are highlighted, routed units are greyed out
 * Redeploy countdown timers for both deployed and routed units
 * Move pending icon when there is a valid request awaiting completion
* Brigade status
 * Location of brigade in orbat
 * Division members
 * Deployment information
    * Current location
    * Time deployed
    * Last moved time and player
    * Redeployment timer
 * Command information
    * Brigade supply type
    * Commanding officer
    * Acting officer in charge
 * List of units stacked in the same location
 * Detailed 12-hour movement history, including failed attempts.
* Equipment
 * Browse the contents of each TOE (Table of Organisation and Equipment)
 * Supply numbers for each vehicle per RDP cycle (including next cycle)
 * Vehicle preview with rank requirements
 * Brigades that contain a specific vehicle and overall supply total
* Pop-up alerts
 * Choose which events to be notified of by combination of event type, town and country
 * Option to always alert on significant events regardless
 * May be postponed while fullscreen or idle (alerts shown on return)
 * Configurable position, next event delay, notification sound
 * Reshow last alerts menu option
* Networking
 * Configurable Wiretap server/port
 * Auto detects Internet Explorer proxy details, or override with your own
 * Supports proxy authentication, prompting and storing credentials using Windows Credential Management
 * Connection test allows you to see if your settings are correct
 * Auto retry of failed web requests
 * Network usage reporting (current session and total)
 * Low bandwidth usage:
    * Static metadata is cached locally and checked for updates hourly
    * Xml data is polled dynamically with only data since last poll downloaded
 * Clock skew from Wiretap server detection and correction
* Options
 * Configure network, startup, alert, event, map settings and more
 * All settings are stored per user
 * Reset sections to defaults
* Sleep mode
 * Reduced footprint with no network usage
 * Can be set to sleep after an idle timeout or when playing Battleground Europe (and wake up afterwards)
* Admin/Debugging
 * Log window and log file
 * Crash reporting
 * Ability to manually check for events
 * Ability to flush metadata cache
 * Optional version check on startup (once per day)
* Open source
 * Source code is available under the GNU General Public License v2 through SourceForge
 * Written in C#, ~78,000 lines, ~111 classes
 * In development since the release of Wiretap
 
 
 
