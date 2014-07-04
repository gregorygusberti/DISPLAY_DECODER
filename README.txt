This is a very simple 7 segment display decoder created in VHDL. 

The decoder have:
	- 4 bits data input.
	- 7 bits segments output.
	- blank input.
	- test input.
	- anode or decode capability.

1) When the blank input is high the decoder will turn all segments off.

2) Otherwise, when the test input is high the decoder will turn all segments on.

3) Otherwise, the decoder will decode the 4 bit data input and display the numeric value in decimal form.
 