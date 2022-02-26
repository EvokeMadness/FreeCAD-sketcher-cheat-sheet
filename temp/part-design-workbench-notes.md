# Part Design Workbench Notes

February 21, 2022

# Authors

Allie Gonzales

# Goal

Describe Constructive Solid Geometry (CSG) modeling in an understandable and tool agnostic way.

# Part Design Workbench

- Generally used in Mechanical Design
- Solids are constructed using sketches
	+ Sketches are two dimensional and planar
		* Sketches must be a closed figure to construct solid geometry
- First operation is additive
- Following operations are attached to existing geometry
- Operations and features are organized starting from the first operation to the most recent operation.

# Four Basic Constructive Operations of Solid Modeling

1. Extrude
	1. Requires a direction or line
2. Revolve
	1. Requires an axis, edge, or datum line (and angle?)
3. Sweep
	1. Requires an line, edge, datum line, or wire/path
4. Loft
	1. Requires two or more sketches. Shape and scale of geometry between the sketches are interpolated.

---

- Operations may be additive or subtractive
	+ Subtractive operations require solid geometry to cut or remove material
- Sketches may be attached to an existing Face
	+ This face must be *planar*
- Sketches may reference an existing Edge

# Basic Applied Features

- Fillet and Chamfer
	+ Applied to an Edge
	+ Can add or remove material depending on the edge's location and adjacent faces
- Pattern or Array

# Datums or References

- Basic geometry
	+ Point or Vertex
		* 'Vertex' or Vertices are points where two or more Lines meet
	+ Line, Edge, or Axis
	+ Face/Plane
	+ LCS or Local Coordinate System. Similar to Ordinate Dimensioning.

# TO DO

- What is a closed figure?
	+ What is and isn't a closed figure?
- Extrude, Boss, Add, Pad.
- 