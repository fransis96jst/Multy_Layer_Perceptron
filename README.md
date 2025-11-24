# Multyb Layer Perceptron

**Berdasarkan modul yang berikan, rumus update bobot ADALINE adalah sebagai berikut:**    
$\Delta w_i = \alpha (t - y) x_i$

**Keterangan yang ada di modul:**   
$\alpha$ = learning rate (laju pembelajaran)  atau simbol classic $\eta$   
$t$ = target keluaran (nilai yang diinginkan)  
$y$ = keluaran aktual jaringan  
$x_i$ = masukan ke-i (vektor input)  
$w_i$ = bobot ke-i (vektor bobot)  
$b$ = bias  
$\Delta w_i$ = perubahan bobot ke-i   
$\Delta b$ = delta bias   

**Rumus pembaruan bobot lengkapnya:**  
wᵢ(baru) = wᵢ(lama) + Δwᵢ  
$w_i(baru) = w_i(lama) + \Delta w_i$  
atau ditulis:   

$$
w_i(baru) = w_i(lama) + \alpha . (t - y) . x_i
$$  


``wᵢ(baru) = wᵢ(lama) + α × (t − y) × xᵢ``

$net$ = $\sum(x_i.w_i)+b$   

$$
net = \sum_{i=1} ^{n} w_i x_i + b
$$

