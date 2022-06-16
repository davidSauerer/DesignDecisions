# Setup of co-working desk
* Date: 2022-05-24

# Context and Problem Statement
I am living in two places at the moment. In my main department I have a home office in place. For the second one I am
sharing it with my girlfriend. She needs a place to learn online and for me, it is an office space mainly. In addition, we
want to use this place to game and for Video editing.

As base, we have normal Desk out of wood from Ikea and two existing chairs in cheaper quality. We use two
windows laptops and one Macbook. The room we want to build up this co-working desk is in a WG with an extra room, which could
be used also by one of use if we are too noisy (during meetings).

With this ADR we want to decide on a setup fitting to the most of our needs. It is important to know that this co-working desk
will be developed step by step (agile setup), so we will take decisions step by step and implement them before we take new
design/architecture decisions. This leads to all the issues we know from agile project, but also brings up there positives sides.
If we detect here issues, we will also mention them in the decision outcome.

# Remarks

# Decision Driver
We rate the Decision Drivers by School grades (1 best and 6 worst)

| Decision Driver       | Importance |
|-----------------------|------------|
| Low initial costs     | 2          | 
| Ergonomic and health  | 1          | 
| Gaming                | 4          | 
| Video editing         | 3          | 
| Office Working        | 2          | 
| Usable for Studying   | 3          | 
| Design and Clean look | 2          | 
| Usable parallel       | 3          |

# Decision Outcome
* For the **Amount of Monitors** we decide for **Option M:1**, because of the costs and better fitting to our Decision Driver. We could upgrade
to a tow monitor setup later if needed.

## Considered Options

### Amount of Monitors
The assumption is that more screen space would enable more efficiency for the most use-cases.
#### Option M:1
This option is about to use only one bigger Monitor for the co-working office.
#### Positive on this option
* Less Costs
* Desk is cleaner
* Empty Space on the Desk left (usable for other things)
* One bigger monitor is better for video editing
#### negative on this option
* One fits all solution needed (Fewer choices)
* 2nd person needs to work on pure laptop for sure
* Does not allow parallel use

### Option M:2
This option is about to use two monitors for the co-working office.
#### Positive on this option
* Easier to split windows on different screen
* Could use different screens for different use-cases
* Could exchange one monitor by better fitting and keeping the old one
* Second person could use the 2nd monitor (parallel use)
#### negative on this option
* Desktop is more filled (less space fo other things)
* More expensive for monitors (2 Monitors cost more than 1) more or better equipment needed (desktop stands, cables and docking station)
* More cables to manage (messy look)
* More technical complexity (maintenance effort by replacing parts or finding issues)
* Half of the time no need of this working efficiency (inefficient)

### Option M:3
This option is about to use only the laptop build in monitor.
#### Positive on this option
* Lowest costs possible
* Clean Desktop (nice look)
* Lowest maintenance Effort

#### negative on this option
* Not efficient for working
* Not efficient for studying
* Not efficient for video editing
* Use case of Gaming hard limited
* Need of Laptop stand for ergonomic and also then limited
* Does not allow parallel use

### Docking station

#### Option D:1
This option is about to use no docking station at all.
##### Positive on this option
* Low costs
* Less maintenance
* No Issues with FPS limitation

##### negative on this option
* Connection to other Laptop would require switch all cables all the time
* More mess on the desk because of more cables
* Fewer possibilities to connect extra gear (external drives, headsets, speakers) because of limited ports

#### Option D:2
This option is about to use a docking station

##### Positive on this option
* One cable as connection (power + data) what leads to clean look
* Laptops are easy to switch
* More possibilities to connect extra gear (external drives, headsets, speakers)

##### negative on this option
* Expensive solution
* Frames per second are often limit to 60hz
* One gear more which need to be maintained and could have issues (complexity raised)

#### Option D:3
This option is about to use a USB-C Monitor with an extra USB Hub if needed.

#### Positive on this option
* No big extra costs for "Docking station"
* One cable setup could be reached
* Frames per second not limited
* Complexity and maintenance are low

#### negative on this option
* Usage of two monitors in future is limited (macOS not supporting chaining, or no one cable setup possible)
* Not supporting wide range of ports (mostly usb and aux only). Could be fixed with additional USB Hub.
* Limits the monitors which are usable (USB-C) needed
