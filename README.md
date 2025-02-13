# DIGITAL-FILTER-DESIGN
*COMPANY NAME*: CODTECH IT SOLUTIONS
*NAME*: AKSHAYA GOLLAPELLY
*INTERN ID*: CT08PFT
*DOMAIN*: VLSI
*DURATION*: 4 WEEKS
*MENTOR*: NEELA SANTOSH
Description: This Verilog code implements a **4-tap FIR filter**, processing an **8-bit signed input (`x_in`)** and producing a **16-bit signed output (`y_out`)**. It uses four coefficients `{1, 2, 3, 4}` and a **shift register (`x[0]` to `x[3]`)** to store past inputs. On each clock cycle, new inputs shift in, and the filter computes output by multiplying inputs with coefficients and summing the results. The testbench generates a **50MHz clock**, applies various test inputs, and prints results using `$monitor`. The simulation runs with a step, ramp, and negative values to observe the filter’s response before stopping.
output:
![Image](https://github.com/user-attachments/assets/b81e5004-a378-4d14-882b-741e19d68758)
