# Finite element software for calculating fluid flow and heat transport for seamounts 

# V.C. Manea, E. G. Sewell, M. Manea, S. Yoshioka, N. Suenaga and E. J. Moreno


#  Here we make fully available our Fortran codes for the scientific community and papers treating similar topics for hydrothermal circulation related with seamounts. These codes can all be run with one of the free PDE2D versions (www.pde2d.com). The PDE2D program benchmark_2D.f, available as supplementary file, can be used to compute temperature, pressure and flow for a simple 2-D simulation with uniform permeability. axi_benchmark_k1.f is an asymmetrical model with a constant permeability k1 = 1E-15 m^2, and  axi_benchmark_k1_k2.f can be used for asymmetrical simulation with a layered permeability structure, k1 = 1E-15 m^2 and k2 = 1E-14 m^2. EOS_pure_water.dat contains density, dynamic viscosity and specific heat calculated as a function of P-T for the EOS of pure water. Grizzly_Bare_Seamount.f solves hydrothermal circulation for the Grizzly Bare seamount. EOS_seawater.dat contains density and viscosity calculated based on the EOS for seawater with a salinity of 3.5%. Grizzly_Bare_Postprocessing.m is a MATLAB code that reads in the output files from the Grizzly_Bare_Seamount.f program. It also reads the observed heat flow data stored in Grizzly_Bare_Heat_Flow_data_Left_side.dat and Grizzly_Bare_Heat_Flow_data_Right_side.dat and lithological boundaries (Grizzly_Bare_surface.dat, Grizzly_Bare_sediments_basalt_limit.dat, Grizzly_Bare_top_basement.dat). All Fortran PDE2D codes provided here are reusable and also easily extensible to a wide range of problems related with hydrothermal circulation in seamounts. 

# Highlights

# 1) We use the flexible finite element suite of codes PDE2D to solve the coupled equations of continuity, Darcy, and energy conservation.
# 2) We write a new piece of software based on PDE2D and pass several benchmarks, we calculate using finite elements flow, temperature and pressure distribution inside seamounts of arbitrary shapes and complex (2D or axisymmetric) geometries. 
# 3) We present a numerical axisymmetrical model tailored to the real geometry of the Grizzly Bare seamount, and obtain a good correlation between our predictions and in-situ available observations.
 


