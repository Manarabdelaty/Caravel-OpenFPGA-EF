# Caravel-OpenFPGA-EF

The repo contains the FPGA layout integration with the [Caravel](https://github.com/efabless/caravel.git) chip.
Thee layout is an 8x8 FPGA fabric generated using [OpenFPGA](https://github.com/lnis-uofu/OpenFPGA) and hardened using [OpenLANE](https://github.com/efabless/openlane). 

# Caravel Integration

### Verilog View

The 8x8 fpga interface to the managent area can be found at [fpga_top.v]() . The fabric is conncted to the managemtent area logic analyzer and wishbone bus. 

### GDS View

<p align=”center”>
<img src="doc/images/Caravel-FPGA.png" width="40%" height="40%">
</p># To Do

# To Do

1. Functional and Gate-level verification
3. DRC and LVS checks
