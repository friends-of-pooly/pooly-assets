## So you want to Build a Pooly... Or some Pooly Parts
### A How-To
---

**Table of Contents**
- [TLDR](https://github.com/rdp3/pooly-assets/edit/main/pixel-pooly-assets/PoolyBuilder.md#tldr)
- [Layer Composition](https://github.com/rdp3/pooly-assets/edit/main/pixel-pooly-assets/PoolyBuilder.md#swooping-into-the-details)
- [How to Make an SVG into "Pixels"](https://github.com/rdp3/pooly-assets/edit/main/pixel-pooly-assets/PoolyBuilder.md#swooping-into-the-details)
- [Using the Wire Frame](https://github.com/rdp3/pooly-assets/edit/main/pixel-pooly-assets/PoolyBuilder.md#using-the-wire-frame)
- [What's Next](https://github.com/rdp3/pooly-assets/edit/main/pixel-pooly-assets/PoolyBuilder.md#whats-next)

---

#### **TLDR:**
A 320 x 320 SVG Wire Frame with examples is [here](pixel-pooly-assets/SVG/PoolyWireFrame.svg).

When compiling the NFT the Layers compile in the following order:
1. Body (which may include left/Right/Both Wings)
2. Head
3. Head Accessory
4. Left Wing
5. Body Accessory

---
#### **Swooping into the Details**

You'll find a 320 x 320 SVG file with a Wire Frame and Pixel Pooly Examples in this repo:
[Wire Frame](pixel-pooly-assets/SVG/PoolyWireFrame-Plain.svg)

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

#### Using the Wire Frame
The [Wire Frame](pixel-pooly-assets/SVG/PoolyWireFrame-Plain.svg) for Pixel Pooly has a lot of groups and layers in the SVG.
Some of these groups contain layers that are examples to experiment with and see how the layers for building a Pooly work. 
Each example layer should start with a number, this indicates the layer that trait is in the [Layer Composition](https://github.com/rdp3/pooly-assets/edit/main/pixel-pooly-assets/PoolyBuilder.md#swooping-into-the-details).

There will also be a Wire Frame group, this has a few layers in it that just provide an outline of where each of the traits layers in the layer composition exist. The Body Layer is a basic rectangle at the bottom center of the image, however staying in the bounds is not required, many body variations have wings or feet built into the Body Layer.
Same with the Head layer, staying within the bounds is not required, many of the craw designs on the head go outside the bounds, and a few variations explore Pooly with a turned head where much of the beak and craw are outside the bounds.

The other points are the connect points for the traits, so if wings or something else is to be added to either side of the body, they should overlap with the slim rectangles on either side of the body.
If something is designed to come our of the mouth of Pooly the single pixel point in the head is where the current traits come out of. 
It's not required to use this location, but this location will be the location that will always work for all designs.
If eyewear is design the eye locations are also provided.
For hat wear the top rectangle is provided where a hat currently overlaps with the head.
Most hats also extend past the head by one or two pixels on either side to help cover the craw but this is not required.

It's also not necessary that all traits are composed at once, use some of the examples as a base and build the one or two traits desired.
For instance if a designer just want to build a hat, just build the hat in the corresponding location, delete all the example groups and wire frame when completed, save the SVG as a new hat with a clever name and submit a pull request.

#### What's Next
Build your Pooly!
In time an SVG with all traits will be compiled so an artist will be able to bring their custome trait into the SVG and see how their trait interacts with the other traits.
🪶🛡️
