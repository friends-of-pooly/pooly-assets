## So you want to Build a Pooly... Or some Pooly Parts
### A How-To
---

**TLDR:**
A 320 x 320 SVG Wire Frame with examples is here (add link when loaded).

When compiling the NFT the Layers compile in the following order:
1. Body (which may include left/Right/Both Wings)
2. Head
3. Head Accessory
4. Left Wing
5. Body Accessory

---
#### **Swooping into the Details**

You'll find a 320 x 320 SVG file with a Wire Frame and Pixel Pooly Examples in this repo:
<link>

Before diving into the SVG, let's go over how a Pooly is compiled. 
All the art is on-chain, so when you call the NFT to look at it, it's compiled right then and there.
But it's compiled in a series of 6 layers, so some traits end up on top of others, sometimes this looks great, sometimes it looks fun.

##### 1. Body Layer
The body layer is usually just a rectangle at the bottom center of the frame, this is the first layer as it will have most of the other layers *attach* to it. 
This layer can also include the left and/or right wing.
Generally speaking if a right wing is included in your Pooly it's included on the Body Layer.
This is because some traits are right-facing so the right wing is most likely to have something layered on top of it.

##### 2. Head Layer
The head layer is the largest trait and can come in a variety of shapes, but should fill most of the center of the frame.
The head usually has a pair of eyes, beak, and a craw.
One eye is required and it should be in the right-eye location as some traits interact with this location (monocle).
Similarly there is one location the beak needs to be in contact with as some traits interact with this location (bubble pipe).

##### 3. Head Accessory Layer
This layer is composed of hats, glasses, and items that interact with the mouth.
**Hats** should generally cover the top two pixels of Pooly's head.
It's optional to have the hat cover some or all of the craw.
**Glasses** have not yet been created as an accessory but there are some pre-existing in the Head Layer.
**Mouth Parts** need to original from a single pixel on the right corner of the *standard* Pooly beak.
Beaks can vary but it should be understood that a Head Accessory like the bubble pipe may be selected to come out of the design.

##### 4. Wing Accessory Layer


##### 5. Body Accessory Layer
