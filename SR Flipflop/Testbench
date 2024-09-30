module sr_ff_tb();
	reg s,r,clk;
	wire Q;

//instantiation and port declaration
	sr_ff DUT(.s(s),.r(r),.clk(clk),.Q(Q));

//clock generation
	initial 
	 begin
	  clk=1;
	  forever #5 clk=~clk;
	end

//stimulus generation
	initial 
	begin
	 {s,r}=2'b10;
	 #10;
	 {s,r}=2'b01;
	 #10;
	 {s,r}=2'b11;
	 #10;
	 {s,r}=2'b00;
	 #10;
	 {s,r}=2'b10;
	 #10;
	 $finish;
	 end
endmodule
