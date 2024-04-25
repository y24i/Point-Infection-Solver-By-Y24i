Point Infection Solver version 1.3 newly published!!
This is a solver help making infection animation, generate wet map/ footprints/ marks/ dirt based on animation

Core Features:
1 both input 1 "infected geo" and input 2 "infect source points" support animation! 
2 visualize scattering points
3 [Falloff attribute] giving a spreading mask attribute
4 [Edge attribute] define the growing area
  it can help binding to your shader or for scatter density going to such as pyro source
5 adding noise to output attribute
6 cleanup output geometry by threshold values


limitation:
[Enable Polylines] not supporting animation input 1 geometry
Particles treated as input2 need more further test
this HDA not works in Unreal Engine based on limitations of Unreal-Houdini Engine

Future Feature:
stop infecting at a certain distance, or adviod infecting controlled by mask
making Polyline more dynamic and organic
