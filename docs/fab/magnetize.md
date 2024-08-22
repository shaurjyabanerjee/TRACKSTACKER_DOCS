---
title: KitLibrary
description: 

---
# **Magnetization**

## **Sourcing Magnets**

There are two different sizes of neodymium magnets you will need to insert into your 3D printed parts to create finished Tracks. These two sizes of magnets are at the very heart of TrackStacker.

- Neodymium Magnets ⌀8mm ↧3mm - Also known as Board Magnets, these are typically responsible for attaching each Track to the Play Surface.
- Neodymium Magnets ⌀6mm ↧2mm - Also known as Con Magnets, these are typically responsible for attaching Tracks to each other.

You can source small neodymium fridge magnets in these sizes from online stores in most countries. 

Beware of ceramic or ferrite magnets, though much cheaper than neodymium they are too brittle and magnetically weak to function properly in TrackStacker.

## **Setting Magnets**

You will need some tools to properly set your magnets. A dead blow hammer, a flat stable and solid work surface about 200mm x 200mm and a set of small pin punches will make the process of setting magnets much easier. This approach is usually fine for setting small quantities of magnets, but you may want to invest in a Vice or Arbor Press based setting system if you intend to fabricate LARGE quantities of Tracks.

Track Stacker is designed to use a tight friction fit for the magnets such that no adhesive is necessary in assembly. However, if you find your magnets falling out of their pockets in play due to poor 3D printer tolerances, you can use a small dab of gel superglue when setting your magnets to ensure longevity of the finished Track. 

---

## **Magnet Polarity**

Setting your magnets with the correct polarity is essential for your finished Tracks to pass the final Function Test with flying colors. Since magnet polarity is invisible, you will need a compass or Source of Truth tool to make sure the polarity of your Track Stacker set matches the polarity of other sets around the world. To make this process easy you can directly purchase a Source of Truth tool from the store, but if you are unable to purchase one, the procedure for determining and setting magnetic polarity yourself is described below.

There are broadly 4 different types of magnetization operations that you will need to carry out in order to fabricate your own Tracks. The general procedure for each is described below -

- ### **Con Magnet Polarization**

	Con Magnet polarization refers to the polarization of the ⌀6mm ↧2mm magnets on the mating face of each Track. These must always be polarized with the North face on the left and the South face on the right as shown in the image below.

- ### **Board Magnet Polarization**

	Board Magnet polarization refers to the polarization of the ⌀8mm ↧3mm magnets on the bottom (play surface) side of each Track. Board magnets should always be polarized with the South face out as shown in the image below. This ensures that Tracks function correctly with Z Supports and in Tracks that use Magnetic Detents or Springs. 


- ### **Z Support Polarization**

	Z Supports should always be polarized such that the wider square face of the support has the North face out, and the narrower round face has the South face out as shown in the image below.


- ### **Magnetic Spring Polarization**

	Some Tracks like [IB2], [IB4] and [DB2] use a magnetic spring configuration where the force of repulsion between two magnets is used to create the necessary spring force for a Track to operate correctly. This principle is used to create the resetting spring force in each of the Button Tracks.

	When magnetizing a Track with a magnetic spring in it, use the following procedure - 

	- First insert the Board magnets normally as specified in the 'Board Magnet Polarization' section above.
	- Then insert the single ⌀8mm ↧3mm magnet into the moving portion of the Track such that it **attracts** the magnets already in the fixed portion of the Track.
	- Insert the sliding portion of the Track into the fixed portion and check if the detent is operating correctly.
	- If the moving part reliably 'snaps' into each desired position then you know you have correctly magnetized the detent!


- ### **Magnetic Detent Polarization**

Some Tracks like [2T1] use a magnetic detent configuration where the force of attraction between two magnets to create the necessary indexing detent force. When magnetizing a Track with a magnetic spring in it, use the following procedure - 

---

## **Track Tooling**

Tooling files are provided to make pressing magnets into your Tracks easier. Here at TrackStacker Labs we use a modular press system for the magnetization of all Tracks. The Press uses a 15mm x 15mm matrix of M3 holes to attach Tooling to the Press Plate or Base plate as shown in the image below. 

You can create a similar setup using a vice or arbor press to generate the pressure needed if you would like to magnetize a large number of Tracks. The tooling files are provided as-is, but can be readily adapted to any pressure generating device with the use of a 15mm x 15mm matrix plate as an interface. 

!!! note 
	M3 heat-set inserts are recommended for your matrix plate so threads don't strip with repeated use!

There are several different models of tooling that are needed for the various different magnetization operations on particular Tracks. Sometimes different Tooling needs to be paired up to complete a particular magnetization operation. The general use cases of each are described below -

- ### **Single Con Press**

	The Single Con Press is the most commonly used Press Tool for Track Stacker magnetization. It can be used by itself to magnetize the Con Faces (⌀6mm ↧2mm magnets) of the following Tracks -

	- All Straight Tracks
	- The single side of [MD1]
	- The single side of [2T1] 
	- All single buttons and valves - [IB2], [IB4], [IVM]
	- LoveJoy


- ### **Dual Con Press**

	The Dual Con Press tool is used for magnetizing the Con Faces of Tracks that have dual, triple or quadruple Track inlets or outlets. It can be used by itself to magnetize the Con Faces of the following Tracks -

	- The double side of [MD1]
	- The double side of [2T1]
	- [DB2]
	- [CB]

---