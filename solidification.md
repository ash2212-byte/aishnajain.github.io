# CFD Investigation of Solidification during Single Crystal Growth and Transitional Turbulence Using PANS Models 

## Overview
The work focused on conducting Computational Fluid Dynamics (CFD) research on solidification dynamics, crystal growth methods, and turbulence modeling. The work involved solving classic benchmark problems and investigating solidification in pure tin as well as binary alloy solidification. Additionally, the study covered numerical simulations of thermal and solutal buoyancy, single-crystal growth mechanisms, and turbulent flow structures in cavities.

## My Role
- Created 2D cavity and axisymmetrical domain geometries, generating structured coarse and fine meshes in Ansys.
- Configured pressure-based solvers, energy equations, Boussinesq approximations, species transport, and enthalpy-porosity models in ANSYS Fluent.
- Turbulence Modeling: Implemented transient flow simulations using URANS and Partially-Averaged Navier-Stokes (PANS) formulations.
- Utilized Text User Interface (TUI) commands, developed User-Defined Functions (UDFs), and extracted heat transfer and flow pattern data.
  
## Tools Used
- Ansys Workbench
- Ansys Fluent
- TecPlot
- OriginPro
  
## Results
- Buoyancy-Driven Convection: Modeled thermal fluid circulation between heated (500 K) and cooled (300 K) vertical walls, confirming flow resolution accuracy on refined grid setups.
- Pure Tin Solidification: Tracked liquid fraction contours and phase interface evolution across time intervals (0.07 hr to 1.462 hr) using the Enthalpy-Porosity model.
- Czochralski Crystal Growth: Simulated continuous casting in a 2D axisymmetrical bowl under steady and unsteady regimes, resolving central mushy zone formation during crystal withdrawal.
- Binary Alloy Solidification: Evaluated solutal buoyancy and macro-segregation in Pb-10%Sn alloy over 40 seconds using Lever rule properties and species transport models.
-  Lid-Driven Cavity Turbulence: Applied URANS and PANS parameters ($f_k=0.6, 0.8; f_\epsilon=1.0$) to capture complex vortex structures while balancing computational efficiency between DNS and RANS approaches.
  
## Images
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/f6b4326a-24d4-48f2-9809-46ca9fbdf81d" width="400" height="250"><br>
      <b>Contour of liquid fraction for pure tin solidification in a square cavity with temperature gradient at time 0.529 h </b>
    </td>
  
    
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/61475deb-5def-48c7-ae4f-000fb8accb88" width="400" height="250"><br>
      <b>Liquid fraction contour under unsteady conditions during Czochralski Growth Process</b>
    </td>
    
  </tr>
</table>
