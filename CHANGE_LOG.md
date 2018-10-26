# Wernher's Old Bits :: Change Log

* 2017-0529: 0.15b (TiktaalikDreaming) for KSP 1.3.0
	+ Zip method now zip
* 2016-0910: 0.14 (TiktaalikDreaming) for KSP 1.2.2
	+ Major update for Realism Overhaul config.
	+ Rework of the A-12 fuel tank to add volume so it can take enough fuel to enable the multistage A-12 to get something into orbit.
	+ I split the A-10 engine into the standard and a variant without vectoring vanes.  With the A-12's 50 A-10 engines, there's just no need for all the engines to gimbal.  Feel free to mix and match or just ignore the new engine.
	+ I'm still working on the ramjet, it's not really working properly just yet.  It should basically function if you're running RO without AJE.  But I need more time tweaking the AJE config.
* 2016-0901: 0.13 (TiktaalikDreaming) for KSP 1.1.3
	+ Added the fins for the A-11 and A-12 plus decouplers suited to the various stages.
	+ A bit more work on the meshes for the various bits and pieces.
	+ Added A-4b style fins for the A-4.
	+ Added A-6 ramjet.
	+ Fixed up A-4 nose chute, and re-used the chute to make a surface attachable chute for stage recovery.
* 2016-0818: 0.12 (TiktaalikDreaming) for KSP 1.1.3
	+ Added A-11 and A-12 stages.  There's no fins yet for them.
	+ Removed ability to surface attach to the A-10 engine, that was just there for before I'd built the A-10 fins, for testing.  But I've added surface attach to the A-10 and A-4 fins.
	+ None of the new parts have Real-Fuel or RSS config, so basically this update is stock only.
* 2016-0528: 0.11 (TiktaalikDreaming) for KSP 1.1.3
	+ Added in the A-10 and some A-4 variants (A-4b, A-6, A-9) including the manned A-4/9 cockpit.
	+ Resized the non-RSS versions to 64% rather than 50% on advice from NathanKell.
	+ Significantly fixed up most of the centres, mass, lift, and drag.
* 2016-0515: 0.10 (TiktaalikDreaming) for KSP 1.1.2
	+ Added first stage of the Redstone A-6 NAA-75-110 as four parts.
	+ Fuel tank; should be self explanatory
	+ Engine; again, fairly obvious
	+ Engine Shroud; This connects over the engine.  I kept this independent of the engine as with it, the engine is basically a cylinder, which is boring as.
	+ Fins; There's four of these on a historical Redstone rocket, and stack nodes let you attach four easily enough.  The fins are also surface attachable, for any other fin needs you might have.  They include the visual mesh for the control vanes that are more correctly part of the engine, but on the actual A-6 and A-7s was part of the fin mechanism.  There's no animation for the vanes, but once the engine's running, you can't really see them anyway.  BUT, the engine's thrust is actually split into 8, 4 of which correspond to a control vane and are "gimballed".  The other four are central.  This way, some (half) of the thrust is gimballed and the other half isn't.  And, by gimballing four points radially around the centre, gimballing can actually rotate, something normal gimballed engines can't do.  On the other hand, they stuck carbon vanes into the exhaust to achieve this, so it comes at the cost of less thrust, and fairly silly gimballing.  At some stage, I'll convert the A-4 to use this system of multi-gimbal, multi-thrust as well.
* 2016-0514: 0.9 (TiktaalikDreaming) for KSP 1.1.2
	+ Fixed fuel oxidizer ratios.
	+ Added extra colour schemes for those with firespitter core.
* 2016-0220: 0.8 (TiktaalikDreaming) for KSP 1.1.2
	+ Updated and fixed the A-10 engine, specifically because I noticed it was overwriting A-4 engine details if community resource pack was installed, but RealFuels wasn't.  Engine is also my updated mesh and so on.
	+ Also, logo for EMW changed to proto VonBraun logo interruptus
* 2016-0217: 0.7 (TiktaalikDreaming) for KSP 1.0.5
	+ No changelog provided
