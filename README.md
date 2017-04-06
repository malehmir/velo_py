# velo_py
This module calculates the velocity of three wave modes from given direction, stiffness and desinty inputs.
## Inputs
The elastic stiffenss matrix, density and the direction of the plane wave can be given to the system using **velo_py.read(input.in)**,where *input.in* contains these informations in text format.
## Output
The output file contains the sorted phase/group velocity of all three modes
## Example
import velo_py
- c,r,inc,azi=velo_py.read('input.in')
- v_phase=velo_py.phase(c,r,i,a)
- v_group=velo_py.group(c,r,i,a)


