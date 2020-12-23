# LTE-GTP-Simulator
GTPv2-C signaling simulator
https://github.com/nithinn/LTE-GTP-Simulator




The below example show S11 interface simulation between MME and SGW. The scenario simulates GTPv2-C signalling of a basic attach procedure.

**MME:**
```
./build/gsim --node=mme --scenario=scenario/mme_s11.xml
```


**SGW:**
```
./build/gsim --node=sgw --scenario=scenario/sgw_s11.xml
```
-------------------------------------------------------------------------------
The below example show S5 interface simulation between SGW and PGW. The scenario simulates GTPv2-C signalling of a basic attach procedure.

**SGW:**
```
./build/gsim --node=sgw --scenario=scenario/sgw_s5.xml
```

**PGW:**
```
./build/gsim --node=pgw --scenario=scenario/pgw_s5.xml
```
