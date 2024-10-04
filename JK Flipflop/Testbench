module jk_ff_tb();
	reg j,k,clk;
	wire Q;
	
	jk_ff DUT(.j(j),.k(k),.clk(clk),.Q(Q));
	
	initial 
	 begin
	  clk=1;
	  forever #5 clk=~clk;
	end
	  
	initial 
	begin
	 
	 {j,k}=2'b10;
	 #10;
	 {j,k}=2'b01;
	 #10;
	 {j,k}=2'b11;
	 #10;
	 {j,k}=2'b00;
	 #10;
	 {j,k}=2'b11;
	 #10;
	 {j,k}=2'b10;
	 #10;
	 {j,k}=2'b01;
	 #10;
	 $finish;
	 
	end
endmodule
