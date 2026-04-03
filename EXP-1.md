# GENERATION OF STANDARD DISCRETE-TIME SIGNALS
# AIM:
To generate and plot standard discrete-time signals using MATLAB.
# APPARATUS REQUIRED:
•	Computer / Laptop
•	MATLAB software
# THEORY:
Discrete-time signals are signals defined only at integer values of time (n).
These signals are basic building blocks in Digital Signal Processing (DSP) and are used for system analysis, filtering, and signal modeling.
Standard discrete-time signals include:
	Unit Impulse
	Unit Step
	Ramp
	Exponential
	Sinusoidal
	Damped Sinusoidal
In MATLAB, discrete-time signals are represented using vectors and plotted using the stem() command.
 Standard Discrete-Time Signals
 
🔹 1. Unit Impulse Signal
δ(n)={■(1,&n=0@0,&n≠0)┤

🔹 2. Unit Step Signal
u(n)={■(1,&n≥0@0,&n<0)┤

🔹 3. Ramp Signal
r(n)=n⋅u(n)

🔹 4. Exponential Signal
x(n)=a^n

🔹 5. Sinusoidal Signal
x(n)=sin⁡(ωn)

🔹 6. Damped Sinusoidal Signal
x(n)=a^n sin⁡(ωn)

# ALGORITHM:
1.	Start the program
2.	Define the sample index n
3.	Generate each standard discrete-time signal
4.	Plot the signal using stem()
5.	Label the axes and title
6.	Stop the program

# MATLAB CODE:

<img width="402" height="687" alt="Screenshot 2026-03-31 145852" src="https://github.com/user-attachments/assets/554733a2-fd21-424e-95f9-bcaeb625636b" />
<img width="440" height="690" alt="Screenshot 2026-03-31 150946" src="https://github.com/user-attachments/assets/5c6802f1-d496-459a-8230-a0e6170b1e70" />


# OUTPUT GRAPH:

<img width="1022" height="694" alt="Screenshot 2026-03-31 143730" src="https://github.com/user-attachments/assets/612ee830-9c35-44ac-95b2-6c03738c7ff2" />
<img width="1032" height="684" alt="Screenshot 2026-03-31 143800" src="https://github.com/user-attachments/assets/60b495c2-4541-42e5-8eff-96eae9430a16" />
<img width="1011" height="683" alt="Screenshot 2026-03-31 143818" src="https://github.com/user-attachments/assets/11fa1193-0ed7-4de4-88f9-5fec0b428487" />
<img width="1018" height="690" alt="Screenshot 2026-03-31 143829" src="https://github.com/user-attachments/assets/778a9576-9d8b-4ba8-8efd-26776ca926c6" />
<img width="1016" height="684" alt="Screenshot 2026-03-31 143848" src="https://github.com/user-attachments/assets/69033c41-51f4-4359-b691-3bc8825f9d9e" />
<img width="1014" height="682" alt="Screenshot 2026-03-31 143903" src="https://github.com/user-attachments/assets/c163ad4e-68ba-4033-85b4-57687306a3b4" />

# Result :
Thus, standard discrete-time signals were successfully generated and plotted using MATLAB.



