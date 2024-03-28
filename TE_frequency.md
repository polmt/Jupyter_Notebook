Πόλωση  ηλεκτρομαγνητικού κύματος

```python
%matplotlib inline
import matplotlib.pyplot as plt
import numpy as np
```

Να εκφραστεί η συχνότητα f(GHz) σε σχέση με το cβ(10^9) για τους 3 πρώτους ρυθμούς αποκοπής.
$$ ω^2=ω_m^2+c^2β^2 \\
ω_m=\frac{mπc}{D} \\
f=\frac{\sqrt((\frac{mπc}{D})^2+(cβ)^2)}{2π} \\
ω_1=\frac{1πc}{D} \\
ω_2=\frac{2πc}{D} \\
ω_3=\frac{3πc}{D} \\
c=299.792.458(\frac{m}{s})\\D=18(cm) $$

```python
c = 299792458
ω_1 = np.pi*c/0.18
ω_2 = 2*np.pi*c/0.18
ω_3 = 3*np.pi*c/0.18
print (ω_1)
print (ω_2)
print (ω_3)

cβ = np.linspace(-35, 35, 1000)
f_1 = (np.sqrt(ω_1**2+(cβ*10**9)**2))/(2*np.pi*10**9)
f_2 = (np.sqrt(ω_2**2+(cβ*10**9)**2))/(2*np.pi*10**9)
f_3 = (np.sqrt(ω_3**2+(cβ*10**9)**2))/(2*np.pi*10**9)
# print (f_1)
# print (f_2)
# print (f_3)

cβ = np.linspace(-35, 35, 1000)
f_1 = (np.sqrt(ω_1**2+(cβ*10**9)**2))/(2*np.pi*10**9)
f_2 = (np.sqrt(ω_2**2+(cβ*10**9)**2))/(2*np.pi*10**9)
f_3 = (np.sqrt(ω_3**2+(cβ*10**9)**2))/(2*np.pi*10**9)
# print (f_1)
# print (f_2)
# print (f_3)
```

Να χαραχθεί ο συντελεστής απόσβεσης και ο συντελεστής διάδοσης σε σχέση με το cβ για τους 2 πρώτους ρυθμούς αποκοπής.
$$ γ_m=α_m=\frac{\sqrt(ω_m^2-ω^2)}{c} \space για \space ω<ω_m \\
γ_m=iβ_m \Rightarrow β_m=\frac{\sqrt(ω^2-ω_m^2)}{c} \space για \space ω>ω_m $$

```python
ω_11 = np.linspace(0, 5232365464.746815, 10**5)
ω_21 = np.linspace(0, 10464730929.49363, 10**5)
a_1 = -(np.sqrt(ω_1**2-ω_11**2))/c
a_2 = -(np.sqrt(ω_2**2-ω_21**2))/c
# print (ω_11)
# print (ω_21)
# print (a_1)
# print (a_2)


ω_12 = np.linspace(5232365464.746815, 4*5232365464.746815, 10**5)
ω_22 = np.linspace(10464730929.49363, 2*10464730929.49363, 10**5)
b_1 = (np.sqrt(ω_12**2-ω_1**2))/c
b_2 = (np.sqrt(ω_22**2-ω_2**2))/c
# print (ω_12)
# print (ω_22)
# print (b_1)
# print (b_2)


plt.plot (ω_12, b_1, 'r')
plt.plot (ω_22, b_2, 'b')
plt.plot (ω_11, a_1, 'r')
plt.plot (ω_21, a_2, 'b')
plt.xlabel ('$cβ$')
plt.ylabel ('$α_m, β_m$')
```
plt.title ('Συντελεστές διάδοσης και απόσβεσης m=1, 2')
plt.axhline(y = 0, linestyle = 'dashed', color = 'black')
plt.show ()

