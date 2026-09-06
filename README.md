# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```
 matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```
<img width="734" height="536" alt="435455013-f02b7eb9-5dee-43eb-a478-e942e9fb01fe" src="https://github.com/user-attachments/assets/d930cf6c-4141-4132-848e-3a9c6dff955b" />


```
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph')
plt.show()
```

<img width="746" height="566" alt="435455028-2d17f719-a298-4b32-87da-b2429f5a9a0a" src="https://github.com/user-attachments/assets/f1f4e289-5e85-403c-a00c-07fde2019f98" />


```
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph')
plt.legend()
plt.show()
```

<img width="752" height="594" alt="435455051-641d3bcb-e9a9-4adc-aaa0-a8446cbaec9c" src="https://github.com/user-attachments/assets/527e2d96-9a6c-4565-930b-fe2aeba55e52" />


```
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue') # Added closing quote and a color 'blue'
plt.ylim(1,8)
plt.xlim(1,8)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations')
plt.show()
```

<img width="711" height="568" alt="435455071-6d5a0892-a544-40f2-81bc-5a0e0e2cd1a4" src="https://github.com/user-attachments/assets/e3a43631-07cd-47a6-aeab-01898f2884f3" />


```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```

<img width="763" height="556" alt="435455085-77922832-01e6-4564-9442-192855289bf1" src="https://github.com/user-attachments/assets/1df6e4c2-6718-4a86-817e-b9b92707595b" />


```
years=range(2000,2012)
apples=[0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9375,0.895] 
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.895] 
plt.plot(years , apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)');
```

<img width="739" height="547" alt="435455120-f6e945a7-defa-4310-9ff4-56eda03b6c75" src="https://github.com/user-attachments/assets/7c38ec68-8c4d-4798-8cd7-e6137ca9a6fe" />


```
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)')
plt.title("Crop yield in Kanto")
plt.legend(['Apples','Oranges'])
```

<img width="794" height="598" alt="435455133-2b6d5c92-7ce1-4639-ba2e-13d2023ea312" src="https://github.com/user-attachments/assets/9797bdc8-b84f-4cde-ab88-f5a63673529c" />


```
years=[2010,2011,2012,2013,2014,2015]
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yield_apples)
plt.xlabel('Year')
plt.ylabel('Yield(tons per hectare)');
```

<img width="788" height="551" alt="435455146-353e554d-5349-47cb-b694-13e1fdc282b4" src="https://github.com/user-attachments/assets/6e2ab9c5-a294-4084-8c6c-89d971e84073" />

```
plt.figure(figsize=(12,6))
years=range(2000,2012)
plt.plot(years,oranges,marker='o')
plt.title("Yield of oranges (tons per hectare)");
```

<img width="814" height="457" alt="435455175-9ac67091-d7e5-40d0-9258-397a139b5d3c" src="https://github.com/user-attachments/assets/c4d50755-0c95-4923-86a4-7660e76cf83e" />


```
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title("Crop Yields in kanto")
plt.legend(['Apples','Oranges'])
```

<img width="786" height="594" alt="435455190-646bd07b-9efb-4052-abfd-a6f8c6a8afcb" src="https://github.com/user-attachments/assets/ca57dc1a-9401-4a62-b0c7-da7247bdff34" />


```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```
<img width="705" height="532" alt="435455204-8a5c23e0-2bc1-4c21-bbfe-6eb77dd5eabd" src="https://github.com/user-attachments/assets/1421b266-fc88-436f-b3b2-4ada23b6c31a" />


```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```

<img width="734" height="576" alt="435455217-54bf5c7b-cb8c-4d18-8e1b-0951c282f521" src="https://github.com/user-attachments/assets/8ae5e704-27b6-479d-9cc6-307bb6ede0a8" />


```
import numpy as np
x=np.arange(0,10)
y=np.arange(11,21)
x
```
<img width="421" height="48" alt="435455229-f6cb0bfa-e435-4384-9e22-dea384032cf1" src="https://github.com/user-attachments/assets/793395b7-4587-489b-902d-60d37529ee5e" />

```
y
```

<img width="466" height="47" alt="435455236-184443b3-a326-459f-8db9-cae10bc60ea8" src="https://github.com/user-attachments/assets/96a09150-bd0b-4028-82f4-ee712eb71621" />

```
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')

```

<img width="714" height="580" alt="435455253-24e184cb-7440-4b22-8e0f-01562fd4c5e1" src="https://github.com/user-attachments/assets/3447d307-f08a-4c95-b45a-d06a0228ae08" />

```
y=x*x
y
```

<img width="467" height="36" alt="435455264-b9596a81-1900-415b-afc2-d11d7ce83c40" src="https://github.com/user-attachments/assets/dfced98d-0303-450a-a18f-98266fb6a361" />


```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('x axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
<img width="734" height="597" alt="435455277-4b2ab289-8ee1-480f-ae4b-4ba54273e020" src="https://github.com/user-attachments/assets/196a4b91-bb21-4f19-91ac-3933cb47837f" />


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
<img width="694" height="544" alt="435455292-9eef89c6-a996-434d-bbbb-0ab7f893cf57" src="https://github.com/user-attachments/assets/882a8f82-bbf0-4f26-9f5c-c4104aa5b80a" />


```
np.pi
```

<img width="241" height="39" alt="435455304-bba420a0-cb56-42bf-9648-0a4d3fedc857" src="https://github.com/user-attachments/assets/1949263d-20f0-4f27-9411-2d1c4ca4d038" />


```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```

<img width="750" height="553" alt="435455316-a9026c9b-69a7-417f-8e99-3693859e37b7" src="https://github.com/user-attachments/assets/8df680f9-cd01-47ba-9eeb-b76534b1d45d" />


```
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```

<img width="715" height="520" alt="435455330-fae028f4-dd38-43c1-a491-77970cf91b28" src="https://github.com/user-attachments/assets/0da14d70-ec44-45d7-ab29-522771a82548" />


```
plt.stackplot(x,y1,y2,y3,labels=['Line 1','Line 2','Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X-axis')
plt.ylabel('Y-axis')
plt.show()
```

<img width="724" height="570" alt="435455350-607bfd3d-98e6-49d0-bb0a-b81107c1ab9f" src="https://github.com/user-attachments/assets/4d529909-4750-4e96-8b00-218ca2ebd766" />


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
plt.plot(x_smooth,y_smooth,'-',label='Spline')
plt.legend()
plt.show()
```

<img width="710" height="542" alt="435455362-904d2d92-d78c-4b2a-aa56-786ea118eec0" src="https://github.com/user-attachments/assets/3fa9734e-da86-4832-9da8-d83f8e06264f" />


```
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.bar(names,values,color="green")
plt.show()
```
<img width="712" height="537" alt="435455377-2711c38f-3a15-4152-9fa3-f85be76a3e2c" src="https://github.com/user-attachments/assets/228a5669-b27a-48b6-a83b-e9aca1073c02" />

```
values=[5,6,3,7,2]
names=["A","B","C","D","E"]
plt.barh(names,values,color="yellowgreen")
plt.show()
```
<img width="714" height="532" alt="435455394-2dc9fe43-edbe-4564-bb39-04d31d935fba" src="https://github.com/user-attachments/assets/874fea9c-e7e7-4be6-863e-b98335fe2248" />


```
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My Bar Chart!')
plt.show()

```

<img width="706" height="570" alt="435455405-c783d857-5a2f-4651-a2ef-1584650c200a" src="https://github.com/user-attachments/assets/118f327c-4336-434c-8966-a1c8286f27d1" />


```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
<img width="702" height="583" alt="435455551-10362787-3690-4ec9-841e-e5b395a6b970" src="https://github.com/user-attachments/assets/58fedd66-a9d2-415d-ad15-c07b197a10c4" />
```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```

<img width="798" height="619" alt="435455570-d562442f-d3ce-4341-bdd3-c4da27698536" src="https://github.com/user-attachments/assets/6482e878-ff8e-47fd-9f60-e8bd35656dd8" />

```
x=[2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()

```

<img width="761" height="524" alt="435455584-a279dee9-33db-44e5-9484-f8a50522db4c" src="https://github.com/user-attachments/assets/c000ab90-b7e3-4776-ad83-be8fe88623ff" />
```

# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
