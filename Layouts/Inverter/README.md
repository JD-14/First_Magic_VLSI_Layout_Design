# CMOS Inverter Layout

## 1) CMOS schematic:
![img](/Images/Inv_s.jpg)

## 2) Magic VLSI Layout:
![img](/Images/Inverter.png)

## 3) Extracted Netlist from Layout:
> * NGSPICE file created from inverter_gate.ext - technology: sky130A
>
> * Top level circuit inverter_gate
>
> X0 Y A vdd vdd sky130_fd_pr__pfet_01v8 ad=2.856e+11p pd=2.2e+06u as=2.924e+11p ps=2.22e+06u w=680000u l=150000u
> 
> X1 Y A gnd gnd sky130_fd_pr__nfet_01v8 ad=1.932e+11p pd=1.76e+06u as=1.638e+11p ps=1.62e+06u w=420000u l=150000u
> 
> .end
