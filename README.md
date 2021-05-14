# Circuit-Path-Enumeration
- Considering combinational logic circuit (biparted graph) as adjacent list and enumerate all the paths from input to output.
- Visualise gate-level verilog code as a directed graph. 
- Networkx library was used to draw the graphs

- Input: Verilog file with Gate Level Modelling

- Output: All paths from input to output of the circuit described by the Verilog file and the exported graph



# Technologies Used:
 Networkx // for graph algorithms
 Python
 Verilog

# Usage
```
python3 main.py <path-to-the-verilog-file>

```

# Output 
Enumerated paths and graphical representation of Full Adder
<img width="1469" alt="Output Graph(FA)" src="https://user-images.githubusercontent.com/60811574/118265285-8c03ea80-b4d6-11eb-8f44-73c39f4390d6.png">

Enumerated paths and graphical representation of 4x1 Multiplexer
<img width="1575" alt="Output Graph(4x1MUX)" src="https://user-images.githubusercontent.com/60811574/118265317-a211ab00-b4d6-11eb-8c2a-a6e70e47d890.png">

