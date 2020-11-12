---
  title: Myanmar Python Programming  
  output:
    html_document:
      css: html-md-01.css
      fig_caption: yes
      highlight: haddock
      number_sections: yes
      theme: spacelab
      toc: yes
      toc_float: true
      collapsed: no
---

# PYTHON PROGRAMMING BY YELINAUNG





## What is Python?



### နာမည်ကြီး programming languageဖြစ်ပီးတော့<mark> Guido van Rossum </mark>ကနေ တီထွင်ခဲ့ပီး ၁၉၉၁ ခုနှစ်မှာ ထုတ်ပေးခဲ့ပါတယ်

### ဘာကြောင့် Python?



- Python ဟာ (Windows, Mac, Linux, Raspberry Pi, Termux etc) မှာ run နိုင်.  

- Python code အရေးသားဟာ eng စာလို ရီုးရှင်း. နားလည်းရလွယ်တယ်  

- Python ဟာ တစ်ခြား programming languageတေထက် ရေးရတာတဲ့ စာကြောင်းရေပိုနည်း.  

- Python ဟာ interpreted languageဖြ့စ်တဲ့တွက်ကြောင့် compileလုပ်စရာမလိုပဲ အချိန်နက်တစ်းပြေးညီrunနိုင်  

- Python ဟာ system automation script တေလည်းရေးနိုင်  

### သိထားရန်

-     လက်ရှီမာ python2 (EOL) |python3 ဆိုပီး versions နှစ်မျိုးကိုအသုံးနေလျက်ရှိပါတယ် 

-  ဒီtutorial မှာတော့ vim (code editor)ကို အသုံးပြုပီး ရေး ပြသွားမှာဖြစ်ပါတယ်

## INSTALL နည်း

### window

### linux

### termux



## syntax(သတ်ပုံ) code ရေးသားပုံ

- pythonတွင် tab space (quote ကွင်းစကွင်းပိတ်)များသည် အရေးပါပီး tabမေ့ခဲံလျင်errorများကြုံတွေ့နိုင်သည်

### syntax အမှန်

```python
def say_hello():
    print("Hello") #tab
say_hello()
```



### syntax အမှား

```python
def say_hello():
print("Hello") #no tab
say_hello()
```

```python
def say_hello():#space
    print("Hello" #ကွင်းပိတ်ကျန်ခဲံ
say_hello()
```

```python
def say_hello():#space
print("Hello) #double quoteကျန်ခဲံ
say_hello()
```





# Comments

- commentsဆို တာ code တေကိုမှတ်ချက်ပေးတာဖြစ်ပီး python ကထို comments များကိုမဖတ်ပါ*  

- comments မှာ 1.single line comment(တစ်ကြောင်းတည်း comments ပေးခြင်း) 2.multi line comment (စာကြောင်းအများမပြားကိူ comments ပေးခြင်း) ဆိုပီးနှစ်မျိုးရှိပါတယ်  

- single line comment(တစ်ကြောင်းတည်း comments ပေးခြင်း) ကိူ # (hash)နဲ့ရေးရပီး စာတစ်ကြောင်းရဲ့ရှေ့မှာဖြစ်စေ နောက်မှဖြစ်စေ ရေးပီး comments ပေးနိုင်  

- multi line comment (စာကြောင်းအများမပြားကိူ comments ပေးခြင်း) ကိူ " (double quote)သုံးခု အစနဲ့ " သုံးခုအပိတ် သို့မဟုတ် '(single quote) နဲ့ရေးပီး comments ပေးနိုင်  
  eg.single line comment  

```py
#this will print Hello  
def say_hello():#space  
 print("Hello") #tab  
say_hello() #call say_hello() function
```

**eg.single line comment  **

```py
def say_hello():  
 print("Hello")   
#say_hello() #say_hello() function will not be call becouse commented
```



**eg.multi-line comment  **

```py
#double quote  
"""  
def say_hello():  
 print("Hello")   
say_hello()  
"""
```



```py
#singel quote  
'''  
def say_hello():  
 print("Hello")   
say_hello()  
'''  
#this will print nothing cos commented all
```



# Variables

### variables ဟာ data တေ သိပ်းပေးဖို့အသုံးပြုပါတယ်

- 

- variables တေရဲ့တန်းတေကို ကိုယ် က assign (သတ်မှတ်ပေး) လုပ်ပေးရပါတယ်  
  
  ```py
  age = 26 # age is variable
  
  name = "YeLinAung" # name is variable
  
  print(age)  
  print(name)
  ```
  
  

### အပေါ်က Exampleမှာ

- *age* *ဆိုတဲ့ variable ထဲကို* *26* ဆို တဲ့ value or data or တန်ဖိုးကို သတ်မှတ်ပေးလိုက်ပြီး name ဆိုတဲ့ variable ထဲကိုYeLinAung *ဆို တဲ့ value or data or တန်ဖိုးကို သတ်မှတ်ပေးလိုက်ပါတယ်*  

```py
age = 26 # age is variable

name = "YeLinAung" # name is variable  
name = 'MgMg' # string ကို ' or " နဲ့သတ်မှတ်ပေးနိူင်  
"""

"""  
print(age)  
print(name)
```



### အပေါ်က Exampleမှာ

- name ဆိုတဲ့နေရာမှာ ပထမ “yelinaung ”လို့သတ်မှတ်ပေးပီး  

-  နောက်ထပ် name ကို MgMg လို့သတ်မှတ်ပေးလိုက်တဲ့အခါမှာ variable name ရဲ့တန်ဖိုးဟာ Mg Mg ဖြစ်သွားပါတယ်  

-  string data တန်ဖိုးတေကို " or ' နဲ့ သတ်မှတ်ပေးနိုင်ပါတယ်  

### Variable ရေးတဲ့အခါမှာ သတိထားစရာများ

အမှန်  

```py
#အခု variable names ပုံစဲအတိုင်းရေးနိုင်:

name = "YeLinAung"  
my_name = "YeLinAung"  
_my_name = "YeLinAung"  
myNameIs = "YeLinAung"  
MYNAMEIS = "YeLinAung"  
mynameis = "YeLinAung"
```

 

အမှား  

```py
# variable names:အမှား  
2ndname = "YeLinAung"  
i-am = "YeLinAung"  
i am = "YeLinAung"
```










































































































