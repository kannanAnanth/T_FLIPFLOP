# T_FLIPFLOP
![image](https://github.com/RESMIRNAIR/T_FLIPFLOP/assets/154305926/74140ea2-0b93-4ffc-b38b-527fb2ece133)
# Truth Table
![image](https://github.com/RESMIRNAIR/T_FLIPFLOP/assets/154305926/1d4afa40-166a-4690-ab1a-179948b9b550)
# Program
```
module t_ff(clk,q,rst,t);
input t,clk,rst;
output reg q;
always@(posedge clk)
begin
if(rst==1)
q=1'b0;
else
if(t==0)
q=q;
else
q=~q;
end
endmodule
```
# Output
![WhatsApp Image 2024-05-12 at 18 15 16_09124ffc](https://github.com/kannanAnanth/T_FLIPFLOP/assets/160721190/c51bf264-c205-4a21-8bc0-22528393cd6d)

# Result
The T_FlipFlop Output has Verified

