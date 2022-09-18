## So you want to Build a Pooly... Or some Pooly Parts
### A How-To
---

**Table of Contents**
- [TLDR](https://github.com/rdp3/pooly-assets/edit/main/pixel-pooly-assets/PoolyBuilder.md#tldr)
- [Layer Composition](https://github.com/rdp3/pooly-assets/edit/main/pixel-pooly-assets/PoolyBuilder.md#swooping-into-the-details)
- [How to Make an SVG into "Pixels"](https://github.com/rdp3/pooly-assets/edit/main/pixel-pooly-assets/PoolyBuilder.md#swooping-into-the-details)

---

#### **TLDR:**
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

#### The Layer Composition
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
This is usually the left wing holding an item or doing something.
It does not always need to be the wing, it could be some item next to Pooly or something else.
However, the designer needs to remember that some of the body art can have a wing open or tucked.

##### 5. Body Accessory Layer
The body accessory layer can be a number of different things, something around Pooly's neck, a shirt, pool inner tubes, or some other design over the front of pooly.
There is a lot of freedom in this layer as it's the top-most layer of the Pooly, the art can go well outside the bounds of the body, just realize the art will be on top of everything else in the NFT.

##### 6. Signal Layer
This layer remains transparent until there is a need for the Friends of Pooly to take action. This layer acts as a temporary signal layer so all NFTs display the same image for a period of time. This way we are all showing support together.

#### How Does an SVG become Pixels
Yes the V in SVG is for Vector, yes Pixel Pooly is blocky pixels. To do this there's a few steps to set up in your SVG editor. The first set of Pixel Pooly's were designed in Inkscape so the following explanation will utilize terminology from Inkscape.
- The SVG canvas should be 320 x 320 with the units set to pixel,
- For visual ease a grid should be turned on,
- The grid should have spacing of 10 pixels by 10 pixels, this gives the image a total of 32 pixels by 32 pixels,
- Snapping to the grid should also be turned on so each pixel is entire filled by the objects in the image,
- Once the image is designed, the objects in the image should be combined and converted to paths,
  - Note: combining objects will require some planning to ensure the image is layered appropriately. 
