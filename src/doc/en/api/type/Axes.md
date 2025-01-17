# Summary
Represents a set of coordinate axes that are considered active.

# Details

## Constructors

### `Axes.new(...)`
All components of Axes are initialized to false. A variable list of arguments is
received. The first 6 arguments are traversed. When an [Axis](enum:Axis) or
[NormalId](enum:NormalId) value is encountered, the component of Axes
corresponding to the value is set to true. Other values are ignored.

Value                                        | Component
---------------------------------------------|----------
[Enum.Axis.X](enum:Axis/X)                   | Enables the [X](#doc-x) component.
[Enum.Axis.Y](enum:Axis/X)                   | Enables the [Y](#doc-y) component.
[Enum.Axis.Z](enum:Axis/X)                   | Enables the [Z](#doc-z) component.
[Enum.NormalId.Right](enum:NormalId/Right)   | Enables the [X](#doc-x) component.
[Enum.NormalId.Top](enum:NormalId/Top)       | Enables the [Y](#doc-y) component.
[Enum.NormalId.Back](enum:NormalId/Back)     | Enables the [Z](#doc-z) component.
[Enum.NormalId.Left](enum:NormalId/Left)     | Enables the [X](#doc-x) component.
[Enum.NormalId.Bottom](enum:NormalId/Bottom) | Enables the [Y](#doc-y) component.
[Enum.NormalId.Front](enum:NormalId/Front)   | Enables the [Z](#doc-z) component.

## Components

### X
A boolean indicating whether the X axis is enabled.

### Y
A boolean indicating whether the Y axis is enabled.

### Z
A boolean indicating whether the Z axis is enabled.
