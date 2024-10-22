# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY
# NAME: INFANTINA MARIA L (212223100013)
# DEP: CSE(CYBER SECURITY)
# AIM:
  To Perform Data Visualization using matplot python library for the given data.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# ALGORITHM:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# CODING AND OUTPUT:
```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```
![image](https://github.com/user-attachments/assets/514a9951-0ff7-4086-b8c6-94d0f624b02d)
```
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/7c9d2a55-2990-4436-ad8c-48fb12a2a6ea)
```
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='red',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('some cool customizations')
plt.show()
```
![image](https://github.com/user-attachments/assets/9f0b03f7-4a69-43f9-b678-1a941dc7d625)
```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![image](https://github.com/user-attachments/assets/27787e84-e7c5-4981-95d0-f8720ed5bac8)
```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
```
![image](https://github.com/user-attachments/assets/f4d5e846-585a-4b42-9639-969fcaa31b6c)
```
import matplotlib.pyplot as plt
years= range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('years')
plt.ylabel('yield (tons per hectare)')
```
![image](https://github.com/user-attachments/assets/516144a8-ff0f-4871-b6d2-92d5cd01317c)
```
import matplotlib.pyplot as plt
years= range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('years')
plt.ylabel('yield (tons per hectare)')
plt.title("corp yields in kanto")
plt.legend(['apples','oranges'])
```
![image](https://github.com/user-attachments/assets/396a9559-9867-4c89-bf60-9dfcca9e1955)
```
yields_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
years=[2010,2011,2012,2013,2014,2015] 
plt.plot(years,yields_apples)
plt.xlabel('year')

plt.ylabel('Yield (tons per hectare)');
```
![image](https://github.com/user-attachments/assets/f92ecdbe-1d5e-45c4-ad03-d437bafe5f53)
```
import matplotlib.pyplot as plt
years= range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("yield of oranges (tons per hectare)");
```
![image](https://github.com/user-attachments/assets/9b10384a-59a5-4ea5-ae17-218ff4ec9aaf)
```
import matplotlib.pyplot as plt
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('years')
plt.ylabel('yield (tons per hectare)')
plt.title("crop yields in kanto")
plt.legend(['apples','oranges'])
```
![image](https://github.com/user-attachments/assets/260a5ee0-9583-4836-b560-c31313f5c681)
```
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```
![image](https://github.com/user-attachments/assets/3cd11413-d5d4-4e3e-96d6-a6db23c10eea)
```
x=[1,2,3,4,5,6,7,8,9,10]
y=[2,4,5,7,6,8,9,11,12,12]
plt.scatter(x,y,label="stars",color="purple",marker="*",s=40)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('my scatter plot!')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/52f81215-0c6b-445f-b560-37ee93e9f15c)
```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,12)
x
```
![image](https://github.com/user-attachments/assets/ab33fcc0-d384-48b5-9970-28ed41ebe96f)
```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
y
```
![image](https://github.com/user-attachments/assets/9bd75ce2-bab7-4e40-8d0d-58346e03a22e)
```
plt.scatter(x,y,c='r')
plt.xlabel('x axis')
plt.ylabel('y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![image](https://github.com/user-attachments/assets/e20f171a-4bdb-415c-9ea2-698b79689ff5)
```
y=x*x
y
```
![image](https://github.com/user-attachments/assets/6e61333d-6ccb-41d8-8141-d337bfd8c11b)
```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('x axis')
plt.ylabel('y axis')
plt.title('2D Diagram')
```
![image](https://github.com/user-attachments/assets/46125a34-d63f-43e1-b543-094879a91077)
```
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
```
![image](https://github.com/user-attachments/assets/e76bee4a-02e6-4990-8b8a-947ba5be41f5)
```
x=np.arange(0,4 * np.pi,0.1)
y=np.sin(x)
plt.title("Sine wave form")
plt.plot(x,y)
plt.show()
```
![image](https://github.com/user-attachments/assets/4ac84bf4-909e-4128-98d0-6ce8b27ef644)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color="blue")
plt.fill_between(x,y2,color="purple")
plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```
![image](https://github.com/user-attachments/assets/cd1266e2-4967-49b8-9731-ec5cade808f9)
```
plt.stackplot(x,y1,y2,y3,labels=['Line1','Line2','Line3'])
plt.legend(loc='upper left')
plt.title("Stacked Line chart")
plt.xlabel('x axis')
plt.ylabel('y axis')
plt.show()
```
![image](https://github.com/user-attachments/assets/b786091c-7697-49b9-af21-eaf2f8b2fd06)
```
import numpy as np
import matplotlib.pyplot as plt
from scipy.interpolate import make_interp_spline
x=np.array([1,2,3,4,5,6,7,8,9,10])
y=np.array([2,4,5,7,8,8,9,10,11,12])
spl=make_interp_spline(x,y)
x_smooth=np.linspace(x.min(),x.max(),100)
y_smooth=spl(x_smooth)
plt.plot(x,y,'o',label='data')
plt.plot(x_smooth,y_smooth,'-',label='spline')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/6b84489f-ca64-47e0-a5ca-5ca69cc513a7)
```
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.bar(names,values,color="blue")
plt.show()
```
![image](https://github.com/user-attachments/assets/a7d67101-6aee-4eda-9316-d24604377794)
```
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.barh(names,values,color="orange")
plt.show()
```
![image](https://github.com/user-attachments/assets/86886a9f-ed35-4de6-986e-884099efef61)
```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['blue','orange']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x axis')
plt.ylabel('y axis')
plt.title("Bar chart!")
plt.show()
```
![image](https://github.com/user-attachments/assets/b1c71dab-fdc9-4afc-83e7-4c96b3494e1b)
```
x=[2,8,10]
y=[11,16,9]
x1=[3,9,11]
y1=[6,15,7]
plt.bar(x,y,color='g')
plt.bar(x1,y1,color='blue')
plt.title('bar graph')
plt.xlabel('x axis')
plt.ylabel('y axis')
plt.show()
```
![image](https://github.com/user-attachments/assets/3858bafd-e711-4412-8986-37092a7274c9)
```
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('no.of people')
plt.title('Histogram')
plt.show()
```
![image](https://github.com/user-attachments/assets/b44763b1-4ab6-44f3-9e2f-bcd188449dcf)
```
import matplotlib.pyplot as plt
x=[2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()
```
![image](https://github.com/user-attachments/assets/04524d27-5fad-4ebe-9358-b26a27dbfff7)
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![image](https://github.com/user-attachments/assets/82a5777f-f533-4592-a7e5-be04395e0c8f)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box plot')
```

![image](https://github.com/user-attachments/assets/a11f5c04-8f6a-4a3c-8cfe-774d06aa8872)
```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/c5bf3f9c-0c9d-4ab1-98ff-b9d7c2a75ad6)
```
labels='python','c++','ruby','java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
```
![image](https://github.com/user-attachments/assets/dd9ea43c-915b-4f43-a7f6-e59472202cd3)

# RESULT:
 Data Visualization using matplot python library for the given data have executed successfully.

