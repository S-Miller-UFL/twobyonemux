this is a simple 2x1 mux where you can specify the width of the inputs and output

it consists of 3 inputs:
1. in_inputone
2. in_inputtwo
3. in_sel

it consists of 1 output
1. out_output

when in_sel is logical low (0), in_inputone is sent through the output.
when in_sel is logical high (1), in_inputtwo is sent through the output.