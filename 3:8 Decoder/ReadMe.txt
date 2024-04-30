Decoder is a combinational circuit that has ‘n’ input lines and maximum of 2n output lines. One of these outputs will be active High based on the combination of inputs present, when the decoder is enabled. That means decoder detects a particular code. The outputs of the decoder are nothing but the min terms of ‘n’ input variables lines, when it is enabled.

In this section, let us implement 3 to 8 decoder.

Boolean expressions:

y[1] = i[0] | i[1];
y[0] = i[0] | i[2];
