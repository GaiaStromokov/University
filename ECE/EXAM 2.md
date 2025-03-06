
# Op amp
![[op amp.png]]

INPUT
- Voltage Follower: $V_{out}=V_{in}$
- Non-Inverting Amplifier: $V_{out}=(1+\dfrac{r_{2}}{r_{1}})V_{in}$
- Inverting Amplifier: $V_{out}=-V_{in}* \dfrac{r_{2}}{r_{1}}$
- Summer: $V_{out}=-(\dfrac{r_{3}}{r_{1}} V_{1}+\dfrac{r_{3}}{r_{2}}V_{2})$
- Instrumentation Amplifier: $V_{out}=(1+\dfrac{2r_{1}}{r_{g}}) \dfrac{r_{3}}{r_{2}} (v_{in+}-V_{in-})$
# Math
- $i_{C}=C \dfrac{dv_{c}}{dt}$
- $v_{C}=\dfrac{1}{C} \int^t_{0} i_{C}~dt+v_{C}(0)$
- Series: $C_{eq}=\frac{1}{\dfrac{1}{c_{1}}+\dfrac{1}{c_{2}}+\dfrac{1}{c_{3}}+\dots}$
- Parallel: $C_{eq}=C_{1}+C_{2}+C_{3}+ \dots$
- RC time constant: $\tau=RC$
___
- $v_{L}=L \dfrac{di_{L}}{dt}$
- $i_{L}= \dfrac{2}{L} \int^t_{0}v_{L}~dt+i_{L}(0)$
- $E_{L}=\dfrac{1}{2} Li_{L}^{2}$ (joules)
- Series: $L_{eq}=L_{1}+L_{2}+L_{3}+\dots$
- Parallel: $L_{eq}=\frac{1}{\dfrac{1}{L_{1}}+\dfrac{1}{L_{2}}+\dfrac{1}{L_{3}}+\dots}$
- RL time constant: $\tau=\dfrac{L}{R}$

___
# After a long time
- Resistors: no change
- Capacitor -> open circuit (break)
- inductor -> short circuit (wire)
- Voltage sourcez: no change
- Current source: no change

# Energy Formula
$W_{C}=\dfrac{1}{2}CV^2$
$W_{C}=energy(joules)$
$C=Capacitance(farads)$
$V=voltage(volts)$
$W_{L}=\dfrac{1}{2}LI^2$

___
$C_{1}=10 \mu F=10*10^{-6}$
$C_{2}=2\mu F=2*10^{-6}$
$L_{1}=0.5mH=0.5*10^{-3}$
$L_{2}=4mH=4*10^{-3}$
$V_{c_{1}}=18$
$V_{c_{2}}=10.8V$
$E_{C_{1}}=\dfrac{1}{2}(10*10^{-6})(18^2)=1.62mJ$
$E_{C_{2}}=\dfrac{1}{2}(2*10^{-6})(10.8^2)=0.11664mJ$
