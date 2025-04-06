Made by: viv223345
Repository link: https://github.com/viv223345/Strata
Total hours so far: 32

- [x] I have a 3D printer or will be getting one before March 21st

# Strata

Strata, named after the geological layers, is a CoreXY 3D Printer, that focuses on speed and quality. It also supports 'extensions' via the extrusions on the right and left sides.

## Components

- **Dimensions**:
- **Frame**:
- **Joints**: Inside hidden corner brackets
- **Kinematics**: CoreXY
- **Extrusion**: Bowden
- **Motion System**: Linear rails
- **Bed**:
- **Bed Leveling System**: BLTouch
- **Hot End**:
- **Stepper Motors**: 
- **End Stops**: 
- **Power Supply**:
- **Main Board**: Pi 0 2W 
- **Printer Board**:
- **Firmware**: Klipper

## Time Tracking

### 30.03.2025 - Sunday

10:03 Installed FreeCAD and started [research](https://infill.hackclub.com/overview/getting-started).
12:14 No idea where to start - still doing research. On the infill slack, I noticed some people reccomending that the printhead be designed first, and then the rest - just to ensure it fits.
18:11 I've decided on a **CoreXY** printer.
18:44 Looking at the differences between a Direct Drive and a Bowden extruder.
19:43 Just watched [a video](https://www.youtube.com/watch?v=_ramiM3KHYE) regarding CoreXY printers. With what was said at 8:07 of the video, I've decided to go with the **Bowden** extruder mechanism.
21:14 I feel like I'm back at square one - especially since my CAD model doesn't even exist yet. The popularity of CoreXY and not XZ, YZ, etc. makes sense, thanks to [this comment](https://www.reddit.com/r/3Dprinting/comments/ckp5l2/comment/evpotr3/).
22:22 Decided on the name **Strata**.

Time Spent: 8 hours
	- Research: 8 hours
	- CAD: 0 hours
	
### 31.03.2025 - Monday

21:19 Looking at other printers for inspiration and motivation. Also, polar printers look really clean! But regarding function, they're a little handicapped.
21:56 After some [research](https://www.youtube.com/watch?v=sq_pG5EbtXQ), I'm thinking of using **linear rails**.

Time Spent: 1 hours
	- Research: 1 hours
	- CAD: 0 hours

Today wasn't very productive :(

### 02.04.2025 - Wednesday

17:36 Exploring the [RepRap Wiki](https://reprap.org/wiki/) - seems like it's gonna help a lot! Should've checked this out first.
18:49 Installing FreeCAD addons.

Time Spent: 3 hours
	- Research: 3 hours
	- CAD: 0 hours
	
### 03.04.2025 - Thursday

12:43 Started CAD of 30x30 Aluminium Extrusion

Time Spent: 7 hours
	- Research: 4 hours
	- CAD: 3 hours

### 04.04.2025 - Friday

08:01 I'm going to complete the printhead today. I'll start with the hotend and figure it as I go.
10:06 Everything's messed up. I'm starting from scratch.
11:08 Finished my 3030 aluminium extrusion sketch, and it works! Padded it and it looks nice :) My very first CAD model is complete! Not a great achievement though - there's a whole 3d printer left.
11:11 FREECAD CRASHED - all my progress is gone, goddamnit. I should've saved
12:35 Back on track. Recreated the model :)
13:44 Basic frame complete - now working on the joints.
14:19 Fixed overlapping ends - now I gotta add the actual joints
14:39 Looking at options for joints. Right now, I have:
	- Inside hidden corner brackets - Best for aesthetics
	- Right angled corner brackets -
	- T-Slot nuts + socket head screws
	- 90 Degree joining plates - Visible from the outside
15:00 - 19:00 Break
19:32 Forgot to note this down - I was thinking earlier, and I had a cool idea - 3D printed extensions that attach to the aluminium extrusions. These can be either functional (to hold nozzles), or purely decorative.
19:57 I think it might be cool to have **'evolutions'** for my printer - at first it's just a regular printer, but then it prints the parts for it to evolve. I'm thinking a natural design, with monstera leaves (they look cool imo)
20:08 There are so many joints - I'm confused
21:30 I've decided to use the **hidden corner brackets**. Thank you <3 [@Anicetus](https://hackclub.slack.com/team/U07GPJ6V3UZ) for the [help](https://hackclub.slack.com/archives/C08B7LF58TX/p1743785985209589?thread_ts=1743783687.629229&cid=C08B7LF58TX)! Changed dimensions accordingly.
21:41 - 22:19 Break
23:04 I've been doing some research. **Klipper** looks like the best option regarding firmware [^1](https://www.reddit.com/r/3Dprinting/comments/rfulww/comment/hog6dtc/) [^2](https://www.reddit.com/r/ender3v2/comments/18j4epk/comment/kdhnzxl/) [^3](https://reprap.org/wiki/Klipper).
23:15 **BLTouch** looks good for a bed leveling sensor [^1](https://www.reddit.com/r/klippers/comments/17vcerd/comment/k9ateoh/) [^2](https://www.reddit.com/r/Creality/comments/qeg3n4/comment/hhsrk7c/). An authentic one is really expensive though - about 90 AED, compared to a clone - just 20 AED
23:37 I've been looking for a good candidate for the printer board. Current options:
	- BTT SKR Mini E3 V3
	- BTT Octopus V1.1 (double the price of SKR mini, but allows for better upgrades such as triple Z bed leveling)
23:42 For the main board, I'll most likely go with the **Pi 0 2W**

Time Spent: 13 hours
	- Research: 7 hours
	- CAD: 6 hours

### 05.04.2025 - Saturday

09:07 I'm going to add the joints and then start with the printhead.
11:30 Added 4 extension holders to the frame.
13:07 Submitted PR to the hackclub/infill repo to add my printer to [config.yaml](https://github.com/hackclub/infill/blob/main/doc_update_script/config.yaml).

Time Spent: 4 hours
	- Research: 2 hours
	- CAD: 2 hours

### 06.04.2025

12:37 Got a [hotend model](https://grabcad.com/library/550c-hotend-from-china-rough-model-1) from GrabCAD.
13:59 GrabCAD [5020 fan model](https://grabcad.com/library/5020-blowerfan-gdstime-1) added.
14:45 Replaced the fan with a [Radial 5015](https://grabcad.com/library/radial-fan-5015-1).

Time Spent: 2 hours
	- Research: 0 hours
	- CAD: 2 hours
