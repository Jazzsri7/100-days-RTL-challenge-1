module sr_ff(s,r,clk,Q);
input s,r,clk;
output reg Q;
always@(posedge clk)
begin
	case({s,r})
	 2'b01 : Q=0;
	 2'b10 : Q=1;
	 2'b11 : Q=1'b0;
	 default : Q=Q;
	endcase
end 
endmodule
