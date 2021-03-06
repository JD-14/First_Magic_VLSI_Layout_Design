# CMOS NAND Layout

## 1) CMOS schematic:
![img](/Images/NAND_s.jpg)

## 2) Magic VLSI Layout:
![img](/Images/NAND.png)

## 3) Extracted Netlist from Layout:
* NGSPICE file created from NAND_gate.ext - technology: sky130A

* Top level circuit NAND_gate

> X0 vdd A n0 vdd sky130_fd_pr__pfet_01v8 ad=1.0268e+12p pd=7.1e+06u as=4.216e+11p ps=2.6e+06u w=680000u l=150000u
> 
> X1 n0 A n1 gnd sky130_fd_pr__nfet_01v8 ad=2.394e+11p pd=1.98e+06u as=2.604e+11p ps=2.08e+06u w=420000u l=150000u
> 
> X2 n1 B gnd gnd sky130_fd_pr__nfet_01v8 ad=0p pd=0u as=3.78e+11p ps=3.48e+06u w=420000u l=150000u
> 
> X3 output n0 vdd vdd sky130_fd_pr__pfet_01v8 ad=2.856e+11p pd=2.2e+06u as=0p ps=0u w=680000u l=150000u
> 
> X4 n0 B vdd vdd sky130_fd_pr__pfet_01v8 ad=0p pd=0u as=0p ps=0u w=680000u l=150000u
> 
> X5 output n0 gnd gnd sky130_fd_pr__nfet_01v8 ad=1.932e+11p pd=1.76e+06u as=0p ps=0u w=420000u l=150000u
> 
> .end
