module jk_ff(j,k,clk,Q);
input j,k,clk;
output reg Q;
always@(posedge clk)
begin
	case({j,k})
	 2'b01 : Q=0;
	 2'b10 : Q=1;
	 2'b11 : Q=~Q;
	 default : Q=Q;
	endcase
end 
endmodule
