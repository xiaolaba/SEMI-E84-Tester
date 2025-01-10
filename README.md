# SEMI-E84-Tester
basic knowledge and testing gauge

### E84 port of Semiconductor factory (FAB) used and LPT port of PC used
the same ISO4902 DB25 plug/socket, both are PARALLEL port  
![DB25_connector.JPG](DB25_connector.JPG)

### power supply & voltage and the port signal
LPT port uses +5V, TTL signal  
LPT port logic 1, 2V min
LPT port logic 0, 0.8V max

E84 port uses +24V +/-6V, 100mA max  
E84 port Signal ON is active_low, typ 10mA, 1.8V Max  
E84 port Signal OFF is active_high, typ 200uA, 18V Min  
