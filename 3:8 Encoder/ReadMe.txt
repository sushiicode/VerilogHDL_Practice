Decoder is a combinational circuit that has ‘n’ input lines and maximum of 2n output lines. One of these outputs will be active High based on the combination of inputs present, when the decoder is enabled. That means decoder detects a particular code. The outputs of the decoder are nothing but the min terms of ‘n’ input variables lines, when it is enabled.

In this section, let us implement 3 to 8 decoder using 2 to 4 decoders. We know that 2 to 4 Decoder has two inputs, A1 & A0 and four outputs, Y3 to Y0. Whereas, 3 to 8 Decoder has three inputs A2, A1 & A0 and eight outputs, Y7 to Y0.

We can find the number of lower order decoders required for implementing higher order decoder using the following formula.

Required number of lower order decoders =m2/ m1
Where,

m1 is the number of outputs of lower order decoder.

m2 is the number of outputs of higher order decoder.

Here, m1 = 4 and m2 = 8. Substitute, these two values in the above formula.

Required number of 2 to 4 decoders= 8/4 = 2
