# ElectriciansPack
Electricians Pack Mod for Satisfactory

####Phase_1:
  --Disconnect (1[i]-1[o]) 
	-"Emergency" Simple ( Disconnect / Connect 2 built in nodes)
  --Distribution Center(1[i]-n[o])
	-Master Switch for all Out[o] Nodes
	-Individual switches for out Nodes

  --Fix MWh vs MW text.

####Phase_2:

  --Power Meters(Volume & Rate of Power through that node only)

  --Fused Disconnect
	-Trip Locally & Keep Full Grid Alive
		(Can I treat this like a "powered" power Generator? ie. It generates the ammount of power per fuse?
                 This way I dont have to connect the in & out node directly)
	-New Fuse Item, Craftable
		-Values (10MW, 20MW, 100MW, 500MW, 1GW)
	-Craft expense based on capacity
  --Battery Back-Ups
	-eg. PowerWall Like
		- Treat like power plants but Timed or Capacity.
			No output if powered
####Phase_3:
  --Smart Disconnect
	-User Provided Custom Names
	-Specified Trip Notifications
	-Auto Reset (Attempt Interval)
  --Smart Control Hub
	-Like the MoarFactory Tablet
	-Building
	-Control Smart Meters
	-Show Volume, Rate, Condition at Smart Disconnects

####Phase_4:
  --Powered Conveyer
		ex. A Smelter has a power cable connected, 
                    powered conveyer means the connected/ downstream constuctor gets power
	-Passthrough: If building is powered by conveyer IN can powers conveyer OUT
		-Splitter
		-Merger
	-Injector: makes an otherwise Unpowered com
 

  --Conduit
	- Smaller Version of pipe, carries electricity
	- Wall & Ceiling mount

####Phase_5:
  --Cold Load Pick-Up Delay for Smart Meters
	-Used to prevent the 'Spike' upon power on of full grid

####Just For Fun / Maybe:
  --Proper EVs
	-EVSE
	-Only Rechargable at Chargepoints
	- 




