# parcels

### parcels transport calculation
- each particle is assigned a tranport at the start -> save that to release files
- do particle tracking
- define sections where you want to calculate the transport (by indices on dataset or coordinates)
- check time step, when particle first crosses section (index is larger or smaller depending on which side you come from)
- do this for all particles to get array of each particle that crossed a section
- transport for section is then sum over all particles per section and their assigned transport at the start
