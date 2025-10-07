# ASSIGMENT6

from tkinter import*
window = Tk()
window.geometry('500x500')
# button = Button(window,text="hello",width=12)
# button.place(x-=200,-y-=300)
# inp = Label(window , text = "hello")
inp = Entry(window , width=56,borderwidth=5)
inp.place( x = 0 ,y = 0)
def click(num):
    result =inp.get()
    inp.delete(0,END)
    inp.insert(0 , str(result) + str(num))
button = Button(window,text='1',width= 12 , command = lambda:click(1))
button.place( x = 10, y = 60 )
button = Button(window,text='2',width=12 , command = lambda:click(2))
button.place( x = 80, y = 60 )
button = Button(window,text='3',width=12 , command = lambda:click(3))
button.place( x = 170, y = 60 )
button = Button(window,text='4',width=12, command = lambda:click(4))
button.place( x = 10, y = 120 )
button = Button(window,text='5',width=12,command = lambda:click(5))
button.place( x = 80, y = 120 )
button = Button(window,text='6',width=12 ,command = lambda:click(6))
button.place( x = 170, y = 120 )
button = Button(window,text='7',width=12 ,command = lambda:click(7))
button.place( x = 10, y = 180 )
button = Button(window,text='8',width=12,command = lambda:click(8))
button.place( x = 80, y = 180 )
button = Button(window,text='9',width=12 ,command = lambda:click(9))
button.place( x = 170, y = 180 )
button = Button(window,text='0',width=12 , command = lambda:click(0))
button.place( x = 10, y = 240 )
def add():
    ni = inp.get()
    global math
    math ="addition"
    global i
    i = int(ni)
    inp.delete(0,END)
button = Button(window,text='+',width=12 , command = add)
button.place( x = 80, y = 240 )

def sub():
        ni = inp.get()
        global math
        math ="substraction"
        global i
        i = int(ni)
        inp.delete(0,END)
button = Button(window,text='-',width=12 ,command = sub)
button.place( x = 170, y = 240 )

def multiplication():
        ni = inp.get()
        global math
        math ="multiplication"
        global i
        i = int(ni)
        inp.delete(0,END)
button = Button(window,text='*',width=12,command = multiplication)
button.place( x = 10, y = 300 )

def div():
        ni = inp.get()
        global math
        math ="divide"
        global i
        i = int(ni)
        inp.delete(0,END)
button = Button(window,text='/',width=12 , command = div)
button.place( x = 80, y = 300 )

def equl():
    n1 = inp.get()
    global math
    inp.delete(0,END)
    if math == "addition":
        inp. insert(0,i + int(n1))
    elif math  == "substraction":
        inp.insert(0 ,i - int(n1))
    elif math == "multiplication":
        inp.insert(0,i *int(n1))
    elif math == "divide":
            inp.insert(0 , i / int(n1)) 
                
button = Button(window,text='=',width=12,command =  equl)
button.place( x = 170, y = 300 )
def clear():
        inp.delete(0,END)
button = Button(window,text='clear',width=12,command = clear)
button.place( x = 10, y = 350 )
mainloop()
