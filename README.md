# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
Start the program.

Step 2:
Import numpy and enter the matrix values.

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
End the program

## Program:#Program to find the eigen values and eigen vectors.
#Developed by: Naveen M
#RegisterNumber:25017603
import numpy as np
A = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigenvalues, eigenvectors = np.linalg.eig(A)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")

## Output:|
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c9040aa6-d8b4-4b1e-863c-f1b169cda7d3" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6719682a-fa44-4184-9669-513da3d57411" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
