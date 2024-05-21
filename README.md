# D_FLIPFLOP
# AIM
To simulate and synthesis of D_flipflop using vivado 2023.2
# APPARATUS REQUIRE
Vivado 2023.2
# PROCEDURE
STEP:1 Start the vivado software, Select and Name the New project.

STEP:2 Select the device family, device, package and speed.

STEP:3 Select new source in the New Project and select Verilog Module as the Source type.

STEP:4 Type the File Name and module name and Click Next and then finish button.

Type the code and save it.

STEP:5 Select the run simulation and then run Behavioral Simulation in the Source Window and click the check syntax.
STEP:6 Click the simulation to simulate the program and give the inputs and verify the outputs as per the truth table.

STEP:7 compare the output with truth table.
# CIRCUIT DIAGRAM
![image](https://github.com/kanipakajeevana/D_FLIPFLOP/assets/170450203/2529e86b-cd18-40c5-afda-cc4ed8bf54fc)
# TRUTH TABLE
![image](https://github.com/kanipakajeevana/D_FLIPFLOP/assets/170450203/ca119546-7762-4e66-b252-c2976af9e2d2)
# PROGRAM
module dff(d,clk,rst,Q);
input d,clk,rst;
output reg Q;
always @(posedge clk)
begin
if(rst==1)
Q=1'b0;
else
Q=d;
end
endmodule
# OUTPUT
![image](https://github.com/kanipakajeevana/D_FLIPFLOP/assets/170450203/61bf02b5-f665-49ae-82ac-1344a41b9a02)
# RESULT
Thus the simulation and synthesis of D_flipflop using vivado 2023.2 is successfully executed and verified.












