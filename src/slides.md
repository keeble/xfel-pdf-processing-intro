---
marp: true
theme: rose-pine
size: 16:9
backgroundImage: url('../assets/dls_blue.png')
style: |
  h1 {
    font-size: 3.2rem;
  }
  h2 {
     font-size: 2.2rem; 
  }
  h3 {
    font-size: 1.8rem;
  }
  p {
    font-size: 1.5rem;
    }
  li {
    font-size: 1.5rem;
    color: var(--text);
  }
---
# uf-TS/PDF EuXFEL Processing/Analysis Meeting
![bg opacity](../assets/gradient.jpeg)

---
## Agenda
1. uf-TS/PDF processing requirements (Dean)
2. EuXFEL processing capabilities (Luca)
3. Discussion of best processing route
4. Downstream analysis
5. AOB

---
# uf-TS/PDF Processing Requirements
![bg opacity](../assets/gradient.jpeg)
Dean Keeble
12 April 2023

---
## Contents
- What is TS/PDF
- What is different to "normal" scattering experiments
- Processing vs Analysis
- What is required to process the data
- One possible solution
---
![bg right width:634](../assets/scattering.jpg)
## What is TS/PDF?
TS = Total Scattering
i.e. we want to get to $F(Q)$, the total scattering structure factor
$$ 
F(Q) = \sum _{i,j=1}^{n} c_ic_jf_i(Q)f_j(Q)[A_{ij}(Q)-1]
$$

---
## What is the PDF?
If you've successfully extracted your $F(Q)$, it's straightforward$^{\mathsf{TM}}$ to convert it to the pair distribution function
$$
G(r)=\frac{1}{8\pi^3\rho_0}\int_0^{\infty}4\pi Q^2F(Q)\frac{\sin Qr}{Qr} \,\text{d}r
$$

---
## What is  different to "normal" scattering experiments
So a total scattering experiment is just a scattering experiment 

---
## Processing vs Analysis

---
## What is required to process the data

---
## One possible solution

---

## List of things
Normal markdown rules apply:

It helps us keep track of: 
- things
- other things
- those things over there
- and more! :o: :smiley: :white_check_mark:

---
<!--- make pictures wide --->
![bg w:1268](../assets/wide_picture.jpg)

---
![bg opacity](../assets/gradient.jpeg)
# fitting long lines to page width
#### <!--fit--> https://www.diamond.ac.uk/Instruments/Crystallography/I19/Manual/EH1.html

---
