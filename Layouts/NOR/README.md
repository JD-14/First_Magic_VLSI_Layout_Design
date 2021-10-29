# CMOS NAND Layout

## 1) CMOS schematic:
![img](/Images/NOR_s.jpg)

## 2) Magic VLSI Layout:
![img](/Images/NOR.png)

## 3) Extracted Netlist from Layout:
* NGSPICE file created from NOR_gate.ext - technology: sky130A


* Top level circuit NOR_gate

> X0 n1 B vdd vdd sky130_fd_pr__pfet_01v8 ad=5.168e+11p pd=2.88e+06u as=6.664e+11p ps=4.68e+06u w=680000u l=150000u
> 
> X1 n0 A n1 vdd sky130_fd_pr__pfet_01v8 ad=5.032e+11p pd=2.84e+06u as=0p ps=0u w=680000u l=150000u
> 
> X2 output n0 vdd vdd sky130_fd_pr__pfet_01v8 ad=2.856e+11p pd=2.2e+06u as=0p ps=0u w=680000u l=150000u
> 
> X3 gnd A n0 gnd sky130_fd_pr__nfet_01v8 ad=6.889e+11p pd=5.82e+06u as=3.192e+11p ps=2.36e+06u w=420000u l=150000u
> 
> X4 output n0 gnd gnd sky130_fd_pr__nfet_01v8 ad=1.932e+11p pd=1.76e+06u as=0p ps=0u w=420000u l=150000u
> 
> X5 n0 B gnd gnd sky130_fd_pr__nfet_01v8 ad=0p pd=0u as=0p ps=0u w=420000u l=150000u
> 
> .end
