# Research and Development / AI Assignment

##  Objective
Estimate the unknown parameters **θ**, **M**, and **X** from the given curve equations:

x = (t*cos(θ) - e^{M|t|}*sin(0.3t)sin(θ) + X)  
y = (42 + t*sin(θ) + e^{M|t|}*sin(0.3t)*cos(θ))

##  Final Results
- **θ** = 31.037521219°  
- **M** = 0.031198679  
- **X** = 55.081089378  

### Error Metrics
- Mean L1 error: 0.755887  
- Mean L2 error: 0.550766  
- Max L2 error: 1.075429  

##  Tools Used
- Python, NumPy, Pandas, SciPy, Matplotlib (Google Colab)
- Desmos for final visual validation

##  Desmos Submission Equation

\left(t*\cos(31.037521219)-e^{0.031198679\left|t\right|}\cdot\sin(0.3t)\sin(31.037521219)+55.081089378,\ 42+t*\sin(31.037521219)+e^{0.031198679\left|t\right|}\cdot\sin(0.3t)\cos(31.037521219)\right)

##  Author
**Ananya M S**  
(Submitted as part of Research & Development / AI Assignment)
