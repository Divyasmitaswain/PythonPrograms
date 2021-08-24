#!/usr/bin/env python
# coding: utf-8

# # Loops Program

# In[1]:


x,y=12,10
if(x<y):
    st="x is less than y"
elif(x==y):
    st="x is same as y"
else:
    st="x is greater than y"
print(st)    


# In[2]:


lst=[1,2,3,4,5]
for i in lst:
    print(i)


# In[3]:


while(i<10):
    print(i)
    i=i+1


# In[4]:


i=18
if(i>12):
    print("18 is not less than 12")
print("i'm not in if")    


# In[5]:


i=149
if(i<=150):
    print("149 is less than 150")
    print("i is in if block")
else:
    print("149 is greater than 150")
    print("i in else block")


# In[7]:


for i in range(3,17,2):
    print(i)


# In[8]:


for i in range(10):
    print(i)
    i=i+1
    print(i)


# In[9]:


li=[1,2,3,4,5,6,7]
j=0
for i in li:
    for i in li:
        i=i+1
        j=j+1
    print(j)
print(j)    

