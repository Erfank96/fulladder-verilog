module fulladder_testbench;

	// Inputs
	reg a;
	reg b;
	reg cin;

	// Outputs
	wire sum;
	wire carry;

	// Instantiate the Unit Under Test (UUT)
	fulladder_verilog uut (
		.a(a), 
		.b(b), 
		.cin(cin), 
		.sum(sum), 
		.carry(carry)
	);

	initial begin
		// Initialize Inputs
		a = 0;
		b = 0;
		cin = 0;

		// Wait 100 ns for global reset to finish
		#100;
      

		a = 1;
		b = 0;
		cin = 0;
		
		#100;
		
		a = 0;
		b = 1;
		cin = 0;
		
		#100;
		
		a = 0;
		b = 0;
		cin = 1;
		
		#100;
		// Add stimulus here

	end
      
endmodule
