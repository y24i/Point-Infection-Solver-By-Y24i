Point Infection Solver version 1.3 newly published!!
This is a solver help making infection animation, generate wet map/ burning/ spreading/ footprints/ marks/ dirt masks based on animation.


*Core Features:

1. main input "infected geo" and option input "infect source points" support animation! 

2. visualize scattering points

3. [Falloff attribute] giving a spreading mask attribute

4. [Edge attribute] define the growing area
  it can help binding to your shader or being treaded as pyro source

5. adding noise to output attribute

6. cleanup output geometry by threshold values


*limitation:

1. [Enable Polylines] not supporting animation input 1 geometry

2. Particles treated as input2 need more further test

3. this HDA not works in Unreal Engine based on limitations of Unreal-Houdini Engine


*Future Feature:

1. stop infecting at a certain distance, or adviod infecting controlled by mask

2. making Polyline more dynamic and organic
