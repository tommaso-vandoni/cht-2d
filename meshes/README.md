# Meshes for CHT-2D
### List of the meshes used to test cht-2d:

### cht-2d-rectangle: 
>- L = 0.2 m
>- t = 0.025 m
>- H = 0.075 m
>- t+H = 0.1 m

>>**Note**: dimensions of the following meshes: 
>- 'cht-2d-rectangle.msh'
>- 'cht-2d-rectangle-structured.msh'

### cht-2d-rectangle-slim 
> L = 0.2 m
> t = 0.025 m
>1. H = 0.0375 m
>2. t+H = 0.0625 m

>>**Note**: dimensions of the following meshes: 
>1. 'cht-2d-rectangle-slim.msh'
>2. 'cht-2d-rectangle-slim-refined.msh'

## On global numbering of faces of the boundary:
The numbering of the facet/domain tags will follow this convention (for all meshes, independently on the dimension): 
>> **Facets Tags:**
>- Inlet fluid: 8
>- Inlet solid: 9
>- Inlet all: 10
>- Outlet fluid: 11
>- Outlet solid: 12
>- Outlet all: 13
>- Top: 14
>- Bottom: 15
>- Interface: 16
>> **Domain tags**
>- Fluid domain tag: 17 
>- Solid domain tag: 18
>
>
>



