AC
dB
Filters
Bode Plots
LC Resonant circuits
Diodes
___
Amplitude = peak
Period=time to repetition
$f=\dfrac{1}{T}$
$w=2\pi f$ (rad/sec)
$x(t)=Amp*\cos(wt*\phi)$
___
DB $<=>$ $\dfrac{V}{V}$
$\dfrac{V}{V}=20\log_{10}(\dfrac{V_{out}}{V_{in}})dB$
___
$R\implies R$
$C\implies \dfrac{1}{CS}$ $[\dfrac{1}{Gjw}]$
$L \implies SL$ $[jwl]$
Fourier: $s=jw$





___
# Bode plots
$H(s)=\dfrac{100k*s}{(s+1)(s+1k)}=\dfrac{100ks}{(s+1)(1k)(\dfrac{s}{1k+1})}=\dfrac{100s}{(s+1)(\dfrac{s}{1k}+1)}$
Zero: Origin (1 zero)
Poles: (1,1k)

starting value: $20\log_{10}[\dfrac{100(.1)}{\sqrt{1^2+.1^{2}}*\sqrt{\dfrac{.1}{1k}^2}+1^2}]=19.9\bar{9}=20$
___
## Diode
$I_{d_{1}}+I_{1}=I_{d_{2}}$
$I_{d_{1}}=\dfrac{11.3-v_{0}}{2k}$
$I_{1}=\dfrac{14-v_{0}}{1k}$
$I_{dL}=\dfrac{v_{0}-(-11.3)}{2k}$
$\dfrac{11.3-v_{0}}{2000}+\dfrac{14-v_{0}}{1000}+\dfrac{v_{0}+11.3}{2000}$
$v_{0}=7$
$I_{d_{1}}=\dfrac{11.3-7}{2k}=2.15$
$I_{d_{2}}=\dfrac{7-(-11.3)}{2000}=9.5$