Download Link: https://assignmentchef.com/product/solved-hw3-improve-hdl-code-for-delay-performance
<br>
Note: Some of the following problems are extensions to the problems you have solved in HW2. You may reuse your source codes as the basis.

<strong>Problem 1)</strong>

A FIR filter output, ‘y’ can be defined by the following equation:

Here, ‘y’ is the filter output, ‘x’ in the input signal and ‘b’ is the filter coefficients. ‘N’ is the filter order. The higher the value of N is, the more complex the filter will be.

Given the following code segment of a  a 4 tap FIR Filter.




<ol>

 <li>Read the above FIR implementation, draw the filter diagram. Your answer should be something like</li>

 <li>Simulate the above code segments, submit the snapshot of waveform.</li>

 <li>Outline your method to estimate the throughput, latency, and the timing of this FIT filter accordingto logic diagram.</li>

 <li>Use Vivado to simulate the design, use real numbers to compute the throughput, latency, and thetiming of this FIT filter.</li>

 <li>To save energy, rewrite the code by rolling-up the design, now you are required to use only 1 FF and1 multiplier.</li>

 <li>Submit the logic diagram of your new design.</li>

 <li>Use Vivado to simulate this roller-up design, use real numbers to compute the throughput, latency,and the timing of this FIT filter.</li>

 <li>Compare the results of (e) and (d), summarize the differences.</li>

</ol>