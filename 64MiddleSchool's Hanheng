from tkinter import *
from tkinter import messagebox
from PIL import ImageTk, Image

def change():
    label.config(text="我一勒子我拍死你我")
    messagebox.showinfo("我说了啊", "你考虑考虑，你好好考虑考虑")
    label.config(text="欢迎来到韩红的程序")

window = Tk()
window.title("六十四中韩勇")
label = Label(window, text="欢迎来到韩红的程序")
label.pack()
b = Button(window, text="点击我", command=change)
b.pack()
image = Image.open("蚕蛹 - 副本.PNG")
pyt = ImageTk.PhotoImage(image)
hanheng = Label(window, image=pyt)
hanheng.pack()
window.mainloop()
