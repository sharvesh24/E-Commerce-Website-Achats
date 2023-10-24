import tkinter
import tkinter as Achats
import tkinter.ttk as ttk
from tkinter import *
from tkinter.ttk import *
from tkinter.ttk import Label, Style
from PIL import ImageTk, Image
from tkinter import scrolledtext
from tkinter import messagebox
window_main=Tk()
window_main.title("Achats")
window_main.resizable(False,False)
Achats.Label()
ttk.Label()
Label()
Text()

window_main.configure(bg='gray22', height=1028, width=2056)
window_main.geometry("2056x1028")
Label_middle = Achats.Label(window_main,
                        text='ACHATS', foreground="skyblue", background="gray22", font="Algerian 100", borderwidth=25, relief='groove')
Label_middle.place(relx=0.5,
                   rely=0.3,
                   anchor='center')
txt_1=Achats.Label(window_main,
               text="An e-commerce platform", foreground='salmon', bg='gray22', font='calibiri 25')
txt_1.place(relx=0.5,
            rely=0.4,
            anchor='center')
Top_text=Achats.Label(window_main,
                  text="IF YOU CAN'T STOP THINKING ABOUT IT...", foreground='floralwhite', bg='gray22', font="forte 22")
Top_text.place(relx=0.2,
               rely=0.05,
               anchor='center')
Top_txt=Achats.Label(window_main,
                 text="BUY IT", foreground='lightgoldenrod', bg='gray22', font='ravie 50')
Top_txt.place(relx=0.12,
              rely=0.13,
              anchor='center')
Top_left=Achats.Label(window_main,
                  text="BECAUSE IT IS SHOP O'CLOCK", fg='burlywood3', bg='gray22', font='stencil 22')
Top_left.place(relx=0.83,
               rely=0.05,
               anchor='center')
Top_left1=Achats.Label(window_main,
                   text="EVERYDAY", fg='thistle1', bg='gray22', font='gigi 48')
Top_left1.place(relx=0.83,
                rely=0.13,
                anchor='center')
Check_Variable_TC = IntVar()
c1 = Checkbutton(window_main, text="Click here to accept our terms and conditions", cursor="plus", variable=Check_Variable_TC)
c1.place(relx=0.0,
         rely=0.99,
         anchor='w')

frame_1 = Frame(window_main, relief='groove')
frame_1.pack()
frame_1.place(anchor='center', relx=0.5, rely=0.75)
img_1 = ImageTk.PhotoImage(Image.open("Imgs//achats_logo.png").resize((300,300)))
label_1 = Label(frame_1, image = img_1)
label_1.pack()

frame_2 = Frame(window_main, relief='groove')
frame_2.pack()
frame_2.place(anchor='center', relx=0.15, rely=0.65)
img_2 = ImageTk.PhotoImage(Image.open("Imgs//Shopping_Bag.png").resize((400,400)))
label_2 = Label(frame_2, image = img_2)
label_2.pack()

frame_3 = Frame(window_main, relief='groove')
frame_3.pack()
frame_3.place(anchor='center', relx=0.85, rely=0.65)
img_3 = ImageTk.PhotoImage(Image.open("Imgs//HOT_SALE.png").resize((400,400)))
label_3 = Label(frame_3, image = img_3)
label_3.pack()


def openNewWindow():
    if Check_Variable_TC.get():

        window = Toplevel(window_main)
        window.title("Categories")
        window.state("zoomed")
        window.resizable(False,False)
        window.configure(bg='gray22', height=1028, width=2056)
        window.geometry("2056x1028")


        Categories_text = Achats.Label(window,
                                       text="Categories", foreground='floralwhite', bg='gray22', font="calibiri 25")
        Categories_text.place(relx=0.2,
                              rely=0.05,
                              anchor='center')

        frame_1 = Frame(window, relief='groove')
        frame_1.pack()
        frame_1.place(anchor='center', relx=0.8, rely=0.45)
        img_1 = ImageTk.PhotoImage(Image.open("Imgs//All_Products_1.png").resize((400, 400)))
        label_1 = Label(frame_1, image=img_1)
        label_1.pack()

        frame_2 = Frame(window, relief='groove')
        frame_2.pack()
        frame_2.place(anchor='center', relx=0.5, rely=0.45)
        img_2 = ImageTk.PhotoImage(Image.open("Imgs//All_Products_2.png").resize((400, 400)))
        label_2 = Label(frame_2, image=img_2)
        label_2.pack()

        def openNewWindow():
            newWindow = Toplevel(window)
            newWindow.title("Electronics")
            newWindow.geometry("2056x1028")
            newWindow.resizable(False,False)
            newWindow.configure(bg ='gray22', height=1028, width=2056)
            newWindow.state("zoomed")
            Electronics_text1 = Achats.Label(newWindow, text="Headphones:", foreground='salmon', background='gray22', font='calibiri 25')
            Electronics_text2 = Achats.Label(newWindow, text="Speakers:", foreground='salmon', background='gray22', font='calibiri 25')
            Electronics_text3 = Achats.Label(newWindow, text="Television:", foreground='salmon', background='gray22',font='calibiri 25')
            Electronics_text1.place(relx=0.1,rely=0.05,anchor='center')
            Electronics_text2.place(relx=0.1, rely=0.36, anchor='center')
            Electronics_text3.place(relx=0.1, rely=0.68, anchor='center')
            frame_1 = Frame(newWindow, relief='groove')
            frame_1.pack()
            frame_1.place(anchor='center', relx=0.3, rely=0.20)
            img_1 = ImageTk.PhotoImage(Image.open("Imgs//headphones_1.png").resize((200,200)))
            label_1 = Label(frame_1, image=img_1)
            label_1.pack()

            frame_2 = Frame(newWindow, relief='groove')
            frame_2.pack()
            frame_2.place(anchor='center', relx=0.7, rely=0.20)
            img_2 = ImageTk.PhotoImage(Image.open("Imgs//headphones_2.jpg").resize((200, 200)))
            label_2 = Label(frame_2, image=img_2)
            label_2.pack()

            frame_3 = Frame(newWindow, relief='groove')
            frame_3.pack()
            frame_3.place(anchor='center', relx=0.3, rely=0.51)
            img_3 = ImageTk.PhotoImage(Image.open("Imgs//speakers_1.jpg").resize((200, 200)))
            label_3 = Label(frame_3, image=img_3)
            label_3.pack()

            frame_4 = Frame(newWindow, relief='groove')
            frame_4.pack()
            frame_4.place(anchor='center', relx=0.7, rely=0.51)
            img_4 = ImageTk.PhotoImage(Image.open("Imgs//speakers_2.jpg").resize((200, 200)))
            label_4 = Label(frame_4, image=img_4)
            label_4.pack()

            frame_5 = Frame(newWindow, relief='groove')
            frame_5.pack()
            frame_5.place(anchor='center', relx=0.3, rely=0.82)
            img_5 = ImageTk.PhotoImage(Image.open("Imgs//Televisions_1.png").resize((200, 200)))
            label_5 = Label(frame_5, image=img_5)
            label_5.pack()

            frame_6 = Frame(newWindow, relief='groove')
            frame_6.pack()
            frame_6.place(anchor='center', relx=0.7, rely=0.82)
            img_6 = ImageTk.PhotoImage(Image.open("Imgs//Televisions_2.jpg").resize((200, 200)))
            label_6 = Label(frame_6, image=img_6)
            label_6.pack()

            Headphones_text1 = Achats.Label(newWindow, text="Name: Bass HD Gaming HeadSet\nPrice: 9.99$\nProductID: 27689242", foreground='yellow', background='gray22', font='Times 15 bold italic')
            Headphones_text2 = Achats.Label(newWindow, text="Name: Regazon Wire Headphones\nPrice: 14.99$\nProductID: 94514941", foreground='yellow', background='gray22', font='Times 15 bold italic')
            Headphones_text1.place(relx=0.375, rely=0.10)
            Headphones_text2.place(relx=0.775, rely=0.10)

            Speakers_text1 = Achats.Label(newWindow, text="Name: Audioengine Stereo Speakers\nPrice: 649.99$\nProductID: 61439522",foreground='yellow', background='gray22', font='Times 15 bold italic')
            Speakers_text2 = Achats.Label(newWindow,text="Name: JSB Bluetooth Speakers\nPrice: 74.99$\nProductID: 22552987", foreground='yellow', background='gray22', font='Times 15 bold italic')
            Speakers_text1.place(relx=0.375, rely=0.40)
            Speakers_text2.place(relx=0.775, rely=0.40)

            Televisions_text1 = Achats.Label(newWindow, text="Name: iFFALCON 55in Android TV\nPrice: 69.99$\nProductID: 85361988",foreground='yellow', background='gray22', font='Times 15 bold italic')
            Televisions_text2 = Achats.Label(newWindow,text="Name: Croma 32in LED TV\nPrice: 159.99$\nProductID: 70712086", foreground='yellow', background='gray22', font='Times 15 bold italic')
            Televisions_text1.place(relx=0.375, rely=0.70)
            Televisions_text2.place(relx=0.775, rely=0.70)

            CheckVar1 = tkinter.IntVar()
            CheckVar2 = tkinter.IntVar()
            CheckVar3 = tkinter.IntVar()
            CheckVar4 = tkinter.IntVar()
            CheckVar5 = tkinter.IntVar()
            CheckVar6 = tkinter.IntVar()
            checkbox_1 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar1, onvalue=1, offvalue=0)
            checkbox_1.place(relx=0.375,rely=0.30)
            checkbox_2 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar2, onvalue=1, offvalue=0)
            checkbox_2.place(relx=0.775,rely=0.30)
            checkbox_3 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus",variable=CheckVar3, onvalue=1, offvalue=0)
            checkbox_3.place(relx=0.375,rely=0.60)
            checkbox_4 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus",variable=CheckVar4, onvalue=1, offvalue=0)
            checkbox_4.place(relx=0.775,rely=0.60)
            checkbox_5 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus",variable=CheckVar5, onvalue=1, offvalue=0)
            checkbox_5.place(relx=0.375,rely=0.90)
            checkbox_6 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus",variable=CheckVar6, onvalue=1, offvalue=0)
            checkbox_6.place(relx=0.775,rely=0.90)

            def Total_cost():
                total_cost = 0
                L= []
                if CheckVar1.get():
                    total_cost += 10
                    L.extend([("Bass HD Gaming Headset","10","24689242")])
                if CheckVar2.get():
                    total_cost += 15
                    L.extend([("Regazon Wire Headphones","15","94514941")])
                if CheckVar3.get():
                    total_cost += 650
                    L.extend([("Audio Engine Stereo Speakers","650","61439522")])
                if CheckVar4.get():
                    total_cost += 75
                    L.extend([("JSB Bluetooth Speakers","75","22552987")])
                if CheckVar5.get():
                    L.extend([("iFFALCON 55in Android TV","70","85361988")])
                    total_cost += 70
                if CheckVar6.get():
                    L.extend(([("Croma 32in LED TV","160","70712086")]))
                    total_cost += 160
                answer = messagebox.askyesno("Check out",f"total cost is {total_cost}$, Do you want to proceed?")
                if answer:
                    transaction_win = Toplevel(window_main)
                    transaction_win.title("Details")
                    tkinter.Label(transaction_win,text = "First Name:").grid(row=0)
                    tkinter.Label(transaction_win,text="").grid(row=1)
                    tkinter.Label(transaction_win,text= "Card Number:").grid(row=2)
                    tkinter.Label(transaction_win,text="").grid(row=3)
                    tkinter.Label(transaction_win,text="CVV:").grid(row=4)
                    tkinter.Label(transaction_win, text="").grid(row=5)

                    def continue_btn():
                        try:
                            if type(int(e2.get())) == int:
                                if  len(e2.get()) == 16:
                                    if type(int(e3.get()) == int):
                                        if  len(e3.get()) == 3:
                                            messagebox.showinfo("Transaction Successful!", "Thank you!")
                                            transaction_win.destroy()
                                            newWindow.destroy()
                                            window.destroy()
                                            bill_win = Toplevel(window_main)
                                            bill_win.title("Receipt")
                                            tkinter.Label(bill_win,text="     ").grid(row=0)
                                            tkinter.Label(bill_win, text='Receipt', font=('Helvetica', 18, 'bold')).grid(row=0, column=1)
                                            tkinter.Label(bill_win, text="Name:").grid(row=1)
                                            tkinter.Label(bill_win,text="Price($):").grid(row=1, column=1)
                                            tkinter.Label(bill_win,text="ProductID:").grid(row=1,column=2)
                                            tkinter.Label(bill_win, text="").grid(row=2)
                                            for i in range(len(L)):
                                                tkinter.Label(bill_win,text=L[i][0]).grid(row=2+i,column=0)
                                                tkinter.Label(bill_win, text=L[i][1]).grid(row=2 + i, column=1)
                                                tkinter.Label(bill_win, text=L[i][2]).grid(row=2 + i, column=2)
                                            tkinter.Label(bill_win,text="Total:", font=('Helvetica', 18, 'bold')).grid(row=3+len(L), column=0)
                                            tkinter.Label(bill_win, text=f"{total_cost}$", font=('Helvetica', 18, 'bold')).grid(row=3 + len(L), column=1)
                                            bill_win.mainloop()

                                        else:
                                            messagebox.showwarning("Error!", "Invalid CVV")
                                            transaction_win.destroy()
                                            newWindow.destroy()
                                            window.destroy()
                                    else:
                                        messagebox.showwarning("Error!", "Invalid CVV")
                                        transaction_win.destroy()
                                        newWindow.destroy()
                                        window.destroy()
                                else:
                                    messagebox.showwarning("Error!", "Invalid Number")
                                    transaction_win.destroy()
                                    newWindow.destroy()
                                    window.destroy()

                            else:
                                messagebox.showwarning("Error!", "Invalid Number")
                                transaction_win.destroy()
                                newWindow.destroy()
                                window.destroy()

                        except Exception as e:
                            messagebox.showwarning("CRITICAL ERROR!", "INVALID")
                            transaction_win.destroy()
                            newWindow.destroy()
                            window.destroy()

                    def cancel_btn():
                        messagebox.showinfo("Transaction cancelled", "Cancelled!")
                        transaction_win.destroy()
                        newWindow.destroy()
                        window.destroy()

                    tkinter.Button(transaction_win, text="Continue", command=continue_btn).grid(row=6, column=0)
                    tkinter.Button(transaction_win, text="Cancel", command=cancel_btn).grid(row=6, column=1)

                    e1 = tkinter.Entry(transaction_win)
                    e2 = tkinter.Entry(transaction_win)
                    e3 = tkinter.Entry(transaction_win)
                    e1.grid(row=0, column=1)
                    e2.grid(row=2, column=1)
                    e3.grid(row=4, column=1)
                    transaction_win.mainloop()

                else:
                    messagebox.showinfo("Transaction Cancelled","Oops")
                    newWindow.destroy()
                    window.destroy()

            btn_electronics = Achats.Button(newWindow, text="Check Out", command=Total_cost,foreground="floralwhite", bg="blue", font= "Times 20")
            btn_electronics.place(relx=0.90,rely=0.95,anchor='w')

            newWindow.mainloop()


        btn = Achats.Button(window, text="1.Electronics", command=openNewWindow, foreground='salmon', bg='gray22',
                            font='calibiri 25')
        btn.place(relx=0.12,
                  rely=0.13,
                  anchor='center')
        btn.place(x=0, y=20)

        def openNewWindow():
            newWindow = Toplevel(window)
            newWindow.title("Mobiles and Computers")
            newWindow.geometry("2056x1028")
            newWindow.resizable(False, False)
            newWindow.configure(bg='gray22', height=1028, width=2056)
            newWindow.state("zoomed")
            MAC_text1 = Achats.Label(newWindow, text="Laptops:", foreground='salmon', background='gray22',
                                     font='calibiri 25')
            MAC_text2 = Achats.Label(newWindow, text="Smartphones:", foreground='salmon', background='gray22',
                                     font='calibiri 25')
            MAC_text3 = Achats.Label(newWindow, text="Computers:", foreground='salmon', background='gray22',
                                     font='calibiri 25')
            MAC_text1.place(relx=0.1, rely=0.05, anchor='center')
            MAC_text2.place(relx=0.1, rely=0.36, anchor='center')
            MAC_text3.place(relx=0.1, rely=0.68, anchor='center')
            frame_1 = Frame(newWindow, relief='groove')
            frame_1.pack()
            frame_1.place(anchor='center', relx=0.3, rely=0.20)
            img_1 = ImageTk.PhotoImage(Image.open("Imgs//Laptops_1.png").resize((200, 200)))
            label_1 = Label(frame_1, image=img_1)
            label_1.pack()

            frame_2 = Frame(newWindow, relief='groove')
            frame_2.pack()
            frame_2.place(anchor='center', relx=0.7, rely=0.20)
            img_2 = ImageTk.PhotoImage(Image.open("Imgs//Laptops_2.png").resize((200, 200)))
            label_2 = Label(frame_2, image=img_2)
            label_2.pack()

            frame_3 = Frame(newWindow, relief='groove')
            frame_3.pack()
            frame_3.place(anchor='center', relx=0.3, rely=0.51)
            img_3 = ImageTk.PhotoImage(Image.open("Imgs//SmartPhones_1.png").resize((200, 200)))
            label_3 = Label(frame_3, image=img_3)
            label_3.pack()

            frame_4 = Frame(newWindow, relief='groove')
            frame_4.pack()
            frame_4.place(anchor='center', relx=0.7, rely=0.51)
            img_4 = ImageTk.PhotoImage(Image.open("Imgs//SmartPhones_2.png").resize((200, 200)))
            label_4 = Label(frame_4, image=img_4)
            label_4.pack()

            frame_5 = Frame(newWindow, relief='groove')
            frame_5.pack()
            frame_5.place(anchor='center', relx=0.3, rely=0.82)
            img_5 = ImageTk.PhotoImage(Image.open("Imgs//Computers_1.png").resize((200, 200)))
            label_5 = Label(frame_5, image=img_5)
            label_5.pack()

            frame_6 = Frame(newWindow, relief='groove')
            frame_6.pack()
            frame_6.place(anchor='center', relx=0.7, rely=0.82)
            img_6 = ImageTk.PhotoImage(Image.open("Imgs//Computers_2.png").resize((200, 200)))
            label_6 = Label(frame_6, image=img_6)
            label_6.pack()

            Laptop_text1 = Achats.Label(newWindow,
                                        text="Name: Ptron Laptop(12GB RAM)\nPrice: 1299.99$\nProductID: 31589620",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text2 = Achats.Label(newWindow, text="Name: Zigya (4GB,256GB)\nPrice: 799.99$\nProductID: 21536987",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text1.place(relx=0.375, rely=0.10)
            Laptop_text2.place(relx=0.775, rely=0.10)

            Phone_text1 = Achats.Label(newWindow,
                                       text="Name: Opera 12GB,256GB \nPrice: 679.99$\nProductID: 61439522",
                                       foreground='yellow', background='gray22', font='Times 15 bold italic')
            Phone_text2 = Achats.Label(newWindow, text="Name: Zero 8GB,64GB\nPrice: 299.99$\nProductID: 58153649",
                                       foreground='yellow', background='gray22', font='Times 15 bold italic')
            Phone_text1.place(relx=0.375, rely=0.40)
            Phone_text2.place(relx=0.775, rely=0.40)

            Comp_text1 = Achats.Label(newWindow,
                                      text="Name: Laser Desktop(16GB)\nPrice: 1199.99$\nProductID: 87423691",
                                      foreground='yellow', background='gray22', font='Times 15 bold italic')
            Comp_text2 = Achats.Label(newWindow, text="Name: Index Desktop(4GB)\nPrice: 359.99$\nProductID: 651935860",
                                      foreground='yellow', background='gray22', font='Times 15 bold italic')
            Comp_text1.place(relx=0.375, rely=0.70)
            Comp_text2.place(relx=0.775, rely=0.70)

            CheckVar1 = tkinter.IntVar()
            CheckVar2 = tkinter.IntVar()
            CheckVar3 = tkinter.IntVar()
            CheckVar4 = tkinter.IntVar()
            CheckVar5 = tkinter.IntVar()
            CheckVar6 = tkinter.IntVar()
            checkbox_1 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar1, onvalue=1,
                                     offvalue=0)
            checkbox_1.place(relx=0.375, rely=0.30)
            checkbox_2 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar2, onvalue=1,
                                     offvalue=0)
            checkbox_2.place(relx=0.775, rely=0.30)
            checkbox_3 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar3, onvalue=1,
                                     offvalue=0)
            checkbox_3.place(relx=0.375, rely=0.60)
            checkbox_4 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar4, onvalue=1,
                                     offvalue=0)
            checkbox_4.place(relx=0.775, rely=0.60)
            checkbox_5 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar5, onvalue=1,
                                     offvalue=0)
            checkbox_5.place(relx=0.375, rely=0.90)
            checkbox_6 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar6, onvalue=1,
                                     offvalue=0)
            checkbox_6.place(relx=0.775, rely=0.90)

            def Total_cost():
                total_cost = 0
                L= []
                if CheckVar1.get():
                    total_cost += 1300
                    L.extend([("Ptron Laptop(12GB)","1300","31589620")])
                if CheckVar2.get():
                    total_cost += 800
                    L.extend([("Zigya (4GB,256GB)","800","21536987")])
                if CheckVar3.get():
                    total_cost += 680
                    L.extend([("Opera (12GB,256GB)","680","61439522")])
                if CheckVar4.get():
                    total_cost += 300
                    L.extend([("Zero(8GB,64GB)","300","58153649")])
                if CheckVar5.get():
                    L.extend([("Laser Desktop(16GB)","1200","87423691")])
                    total_cost += 1200
                if CheckVar6.get():
                    L.extend(([("Index Desktop(4GB)","360","651935860")]))
                    total_cost += 360
                answer = messagebox.askyesno("Check out",f"total cost is {total_cost}$, Do you want to proceed?")
                if answer:
                    transaction_win = Toplevel(window_main)
                    transaction_win.title("Details")
                    tkinter.Label(transaction_win, text="First Name:", width=15).grid(row=0)
                    tkinter.Label(transaction_win, text="").grid(row=1)
                    tkinter.Label(transaction_win, text="Card Number:").grid(row=2)
                    tkinter.Label(transaction_win, text="").grid(row=3)
                    tkinter.Label(transaction_win, text="CVV:").grid(row=4)
                    tkinter.Label(transaction_win, text="").grid(row=5)

                    def continue_btn():
                        try:
                            if type(int(e2.get())) == int:
                                if len(e2.get()) == 16:
                                    if type(int(e3.get()) == int):
                                        if len(e3.get()) == 3:
                                            messagebox.showinfo("Transaction Successful!", "Thank you!")
                                            transaction_win.destroy()
                                            newWindow.destroy()
                                            window.destroy()
                                            bill_win = Toplevel(window_main)
                                            bill_win.title("Receipt")
                                            tkinter.Label(bill_win, text="     ").grid(row=0)
                                            tkinter.Label(bill_win, text='Receipt',
                                                          font=('Helvetica', 18, 'bold')).grid(row=0, column=1)
                                            tkinter.Label(bill_win, text="Name:").grid(row=1)
                                            tkinter.Label(bill_win, text="Price($):").grid(row=1, column=1)
                                            tkinter.Label(bill_win, text="ProductID:").grid(row=1, column=2)
                                            tkinter.Label(bill_win, text="").grid(row=2)
                                            for i in range(len(L)):
                                                tkinter.Label(bill_win, text=L[i][0]).grid(row=2 + i, column=0)
                                                tkinter.Label(bill_win, text=L[i][1]).grid(row=2 + i, column=1)
                                                tkinter.Label(bill_win, text=L[i][2]).grid(row=2 + i, column=2)
                                            tkinter.Label(bill_win, text="Total:", font=('Helvetica', 18, 'bold')).grid(
                                                row=3 + len(L), column=0)
                                            tkinter.Label(bill_win, text=f"{total_cost}$",
                                                          font=('Helvetica', 18, 'bold')).grid(row=3 + len(L), column=1)
                                            bill_win.mainloop()

                                        else:
                                            messagebox.showwarning("Error!", "Invalid CVV")
                                            transaction_win.destroy()
                                            newWindow.destroy()
                                            window.destroy()
                                    else:
                                        messagebox.showwarning("Error!", "Invalid CVV")
                                        transaction_win.destroy()
                                        newWindow.destroy()
                                        window.destroy()
                                else:
                                    messagebox.showwarning("Error!", "Invalid Number")
                                    transaction_win.destroy()
                                    newWindow.destroy()
                                    window.destroy()

                            else:
                                messagebox.showwarning("Error!", "Invalid Number")
                                transaction_win.destroy()
                                newWindow.destroy()
                                window.destroy()

                        except:
                            messagebox.showwarning("CRITICAL ERROR!", "INVALID")
                            transaction_win.destroy()
                            newWindow.destroy()
                            window.destroy()

                    def cancel_btn():
                        messagebox.showinfo("Transaction cancelled", "Cancelled!")
                        transaction_win.destroy()
                        newWindow.destroy()
                        window.destroy()

                    tkinter.Button(transaction_win, text="Continue", command=continue_btn).grid(row=6, column=0)
                    tkinter.Button(transaction_win, text="Cancel", command=cancel_btn).grid(row=6, column=1)

                    e1 = tkinter.Entry(transaction_win)
                    e2 = tkinter.Entry(transaction_win)
                    e3 = tkinter.Entry(transaction_win)
                    e1.grid(row=0, column=1)
                    e2.grid(row=2, column=1)
                    e3.grid(row=4, column=1)
                    transaction_win.mainloop()

                else:
                    messagebox.showinfo("Transaction Cancelled", "Oops")
                    newWindow.destroy()
                    window.destroy()

            btn_electronics = Achats.Button(newWindow, text="Check Out", command=Total_cost, foreground="floralwhite",
                                            bg="blue", font="Times 20")
            btn_electronics.place(relx=0.90,rely=0.95,anchor='w')

            newWindow.mainloop()

        btn = Achats.Button(window, text="2.Mobile And Computers", command=openNewWindow, foreground='salmon',
                            bg='gray22', font='calibiri 25')
        btn.place(relx=0.175,
                  rely=0.23,
                  anchor='center')
        btn.place(x=0, y=20)

        def openNewWindow():
            newWindow = Toplevel(window)
            newWindow.title("Men's Fashion")
            newWindow.geometry("2056x1028")
            newWindow.resizable(False, False)
            newWindow.configure(bg='gray22', height=1028, width=2056)
            newWindow.state("zoomed")
            MF_text1 = Achats.Label(newWindow, text="Formals:", foreground='salmon', background='gray22',
                                    font='calibiri 25')
            MF_text2 = Achats.Label(newWindow, text="Casuals:", foreground='salmon', background='gray22',
                                    font='calibiri 25')
            MF_text3 = Achats.Label(newWindow, text="Winter Wear:", foreground='salmon', background='gray22',
                                    font='calibiri 25')
            MF_text1.place(relx=0.1, rely=0.05, anchor='center')
            MF_text2.place(relx=0.1, rely=0.36, anchor='center')
            MF_text3.place(relx=0.1, rely=0.68, anchor='center')
            frame_1 = Frame(newWindow, relief='groove')
            frame_1.pack()
            frame_1.place(anchor='center', relx=0.3, rely=0.20)
            img_1 = ImageTk.PhotoImage(Image.open("Imgs//Formals_1.png").resize((200, 200)))
            label_1 = Label(frame_1, image=img_1)
            label_1.pack()

            frame_2 = Frame(newWindow, relief='groove')
            frame_2.pack()
            frame_2.place(anchor='center', relx=0.7, rely=0.20)
            img_2 = ImageTk.PhotoImage(Image.open("Imgs//Formals_2.png").resize((200, 200)))
            label_2 = Label(frame_2, image=img_2)
            label_2.pack()

            frame_3 = Frame(newWindow, relief='groove')
            frame_3.pack()
            frame_3.place(anchor='center', relx=0.3, rely=0.51)
            img_3 = ImageTk.PhotoImage(Image.open("Imgs//Casuals_1.png").resize((200, 200)))
            label_3 = Label(frame_3, image=img_3)
            label_3.pack()

            frame_4 = Frame(newWindow, relief='groove')
            frame_4.pack()
            frame_4.place(anchor='center', relx=0.7, rely=0.51)
            img_4 = ImageTk.PhotoImage(Image.open("Imgs//Casuals_2.png").resize((200, 200)))
            label_4 = Label(frame_4, image=img_4)
            label_4.pack()

            frame_5 = Frame(newWindow, relief='groove')
            frame_5.pack()
            frame_5.place(anchor='center', relx=0.3, rely=0.82)
            img_5 = ImageTk.PhotoImage(Image.open("Imgs//Winterwears_1.png").resize((200, 200)))
            label_5 = Label(frame_5, image=img_5)
            label_5.pack()

            frame_6 = Frame(newWindow, relief='groove')
            frame_6.pack()
            frame_6.place(anchor='center', relx=0.7, rely=0.82)
            img_6 = ImageTk.PhotoImage(Image.open("Imgs//Winterwears_2.png").resize((200, 200)))
            label_6 = Label(frame_6, image=img_6)
            label_6.pack()

            Laptop_text1 = Achats.Label(newWindow, text="Name: Coat Suit\nPrice: 119.99$\nProductID: 15984632",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text2 = Achats.Label(newWindow, text="Name: Formal Shirt&Tie\nPrice: 59.99$\nProductID: 45961254",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text1.place(relx=0.375, rely=0.10)
            Laptop_text2.place(relx=0.775, rely=0.10)

            Phone_text1 = Achats.Label(newWindow,
                                       text="Name: Tshirt\nPrice: 24.99$\nProductID: 52369841",
                                       foreground='yellow', background='gray22', font='Times 15 bold italic')
            Phone_text2 = Achats.Label(newWindow, text="Name: Track Pant\nPrice: 34.99$\nProductID: 85612475",
                                       foreground='yellow', background='gray22', font='Times 15 bold italic')
            Phone_text1.place(relx=0.375, rely=0.40)
            Phone_text2.place(relx=0.775, rely=0.40)

            Comp_text1 = Achats.Label(newWindow,
                                      text="Name: Sweaters\nPrice: 29.99$\nProductID: 74865921",
                                      foreground='yellow', background='gray22', font='Times 15 bold italic')
            Comp_text2 = Achats.Label(newWindow, text="Raincoat\nPrice: 19.99$\nProductID: 96325964",
                                      foreground='yellow', background='gray22', font='Times 15 bold italic')
            Comp_text1.place(relx=0.375, rely=0.70)
            Comp_text2.place(relx=0.775, rely=0.70)

            CheckVar1 = tkinter.IntVar()
            CheckVar2 = tkinter.IntVar()
            CheckVar3 = tkinter.IntVar()
            CheckVar4 = tkinter.IntVar()
            CheckVar5 = tkinter.IntVar()
            CheckVar6 = tkinter.IntVar()
            checkbox_1 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar1, onvalue=1,
                                     offvalue=0)
            checkbox_1.place(relx=0.375, rely=0.30)
            checkbox_2 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar2, onvalue=1,
                                     offvalue=0)
            checkbox_2.place(relx=0.775, rely=0.30)
            checkbox_3 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar3, onvalue=1,
                                     offvalue=0)
            checkbox_3.place(relx=0.375, rely=0.60)
            checkbox_4 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar4, onvalue=1,
                                     offvalue=0)
            checkbox_4.place(relx=0.775, rely=0.60)
            checkbox_5 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar5, onvalue=1,
                                     offvalue=0)
            checkbox_5.place(relx=0.375, rely=0.90)
            checkbox_6 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar6, onvalue=1,
                                     offvalue=0)
            checkbox_6.place(relx=0.775, rely=0.90)

            def Total_cost():
                total_cost = 0
                L = []
                if CheckVar1.get():
                    total_cost += 120
                    L.extend([("Coat Suit", "120", "15984632")])
                if CheckVar2.get():
                    total_cost += 60
                    L.extend([("Formal Shirt&Tie", "60", "45961254")])
                if CheckVar3.get():
                    total_cost += 25
                    L.extend([("Tshirt", "25", "52369841")])
                if CheckVar4.get():
                    total_cost += 35
                    L.extend([("Track Pant", "35", "85612475")])
                if CheckVar5.get():
                    L.extend([("Sweaters", "30", "74865921")])
                    total_cost += 30
                if CheckVar6.get():
                    L.extend(([("RainCoat", "20", "96325964")]))
                    total_cost += 20
                answer = messagebox.askyesno("Check out", f"total cost is {total_cost}$, Do you want to proceed?")
                if answer:
                    transaction_win = Toplevel(window_main)
                    transaction_win.title("Details")
                    tkinter.Label(transaction_win, text="First Name:", width=15).grid(row=0)
                    tkinter.Label(transaction_win, text="").grid(row=1)
                    tkinter.Label(transaction_win, text="Card Number:").grid(row=2)
                    tkinter.Label(transaction_win, text="").grid(row=3)
                    tkinter.Label(transaction_win, text="CVV:").grid(row=4)
                    tkinter.Label(transaction_win, text="").grid(row=5)

                    def continue_btn():
                        try:
                            if type(int(e2.get())) == int:
                                if len(e2.get()) == 16:
                                    if type(int(e3.get()) == int):
                                        if len(e3.get()) == 3:
                                            messagebox.showinfo("Transaction Successful!", "Thank you!")
                                            transaction_win.destroy()
                                            newWindow.destroy()
                                            window.destroy()
                                            bill_win = Toplevel(window_main)
                                            bill_win.title("Receipt")
                                            tkinter.Label(bill_win, text="     ").grid(row=0)
                                            tkinter.Label(bill_win, text='Receipt',
                                                          font=('Helvetica', 18, 'bold')).grid(row=0, column=1)
                                            tkinter.Label(bill_win, text="Name:").grid(row=1)
                                            tkinter.Label(bill_win, text="Price($):").grid(row=1, column=1)
                                            tkinter.Label(bill_win, text="ProductID:").grid(row=1, column=2)
                                            tkinter.Label(bill_win, text="").grid(row=2)
                                            for i in range(len(L)):
                                                tkinter.Label(bill_win, text=L[i][0]).grid(row=2 + i, column=0)
                                                tkinter.Label(bill_win, text=L[i][1]).grid(row=2 + i, column=1)
                                                tkinter.Label(bill_win, text=L[i][2]).grid(row=2 + i, column=2)
                                            tkinter.Label(bill_win, text="Total:", font=('Helvetica', 18, 'bold')).grid(
                                                row=3 + len(L), column=0)
                                            tkinter.Label(bill_win, text=f"{total_cost}$",
                                                          font=('Helvetica', 18, 'bold')).grid(row=3 + len(L), column=1)
                                            bill_win.mainloop()

                                        else:
                                            messagebox.showwarning("Error!", "Invalid CVV")
                                            transaction_win.destroy()
                                            newWindow.destroy()
                                            window.destroy()
                                    else:
                                        messagebox.showwarning("Error!", "Invalid CVV")
                                        transaction_win.destroy()
                                        newWindow.destroy()
                                        window.destroy()
                                else:
                                    messagebox.showwarning("Error!", "Invalid Number")
                                    transaction_win.destroy()
                                    newWindow.destroy()
                                    window.destroy()

                            else:
                                messagebox.showwarning("Error!", "Invalid Number")
                                transaction_win.destroy()
                                newWindow.destroy()
                                window.destroy()

                        except:
                            messagebox.showwarning("CRITICAL ERROR!", "INVALID")
                            transaction_win.destroy()
                            newWindow.destroy()
                            window.destroy()

                    def cancel_btn():
                        messagebox.showinfo("Transaction cancelled", "Cancelled!")
                        transaction_win.destroy()
                        newWindow.destroy()
                        window.destroy()

                    tkinter.Button(transaction_win, text="Continue", command=continue_btn).grid(row=6, column=0)
                    tkinter.Button(transaction_win, text="Cancel", command=cancel_btn).grid(row=6, column=1)

                    e1 = tkinter.Entry(transaction_win)
                    e2 = tkinter.Entry(transaction_win)
                    e3 = tkinter.Entry(transaction_win)
                    e1.grid(row=0, column=1)
                    e2.grid(row=2, column=1)
                    e3.grid(row=4, column=1)
                    transaction_win.mainloop()

                else:
                    messagebox.showinfo("Transaction Cancelled", "Oops")
                    newWindow.destroy()
                    window.destroy()

            btn_electronics = Achats.Button(newWindow, text="Check Out", command=Total_cost, foreground="floralwhite",
                                            bg="blue", font="Times 20")
            btn_electronics.place(relx=0.90,rely=0.95,anchor='w')

            newWindow.mainloop()

        btn = Achats.Button(window, text="3.Men's Fashion", command=openNewWindow, foreground='salmon',
                            bg='gray22', font='calibiri 25')
        btn.place(relx=0.135,
                  rely=0.33,
                  anchor='center')
        btn.place(x=0, y=20)

        def openNewWindow():
            newWindow = Toplevel(window)
            newWindow.title("Women's Fashion")
            newWindow.geometry("2056x1028")
            newWindow.resizable(False, False)
            newWindow.configure(bg='gray22', height=1028, width=2056)
            newWindow.state("zoomed")
            MF_text1 = Achats.Label(newWindow, text="Women's Tops:", foreground='salmon', background='gray22',
                                    font='calibiri 25')
            MF_text2 = Achats.Label(newWindow, text="Women's Shirts/Pants:", foreground='salmon', background='gray22',
                                    font='calibiri 25')
            MF_text3 = Achats.Label(newWindow, text="Pants:", foreground='salmon', background='gray22',
                                    font='calibiri 25')

            MF_text1.place(relx=0.1, rely=0.05, anchor='center')
            MF_text2.place(relx=0.1, rely=0.36, anchor='center')
            MF_text3.place(relx=0.1, rely=0.68, anchor='center')
            frame_1 = Frame(newWindow, relief='groove')
            frame_1.pack()
            frame_1.place(anchor='center', relx=0.3, rely=0.20)
            img_1 = ImageTk.PhotoImage(Image.open("Imgs//Women_Tops_1.png").resize((200, 200)))
            label_1 = Label(frame_1, image=img_1)
            label_1.pack()

            frame_2 = Frame(newWindow, relief='groove')
            frame_2.pack()
            frame_2.place(anchor='center', relx=0.7, rely=0.20)
            img_2 = ImageTk.PhotoImage(Image.open("Imgs//Women_Tops_2.png").resize((200, 200)))
            label_2 = Label(frame_2, image=img_2)
            label_2.pack()

            frame_3 = Frame(newWindow, relief='groove')
            frame_3.pack()
            frame_3.place(anchor='center', relx=0.3, rely=0.51)
            img_3 = ImageTk.PhotoImage(Image.open("Imgs//Women_Shirt_1.png").resize((200, 200)))
            label_3 = Label(frame_3, image=img_3)
            label_3.pack()

            frame_4 = Frame(newWindow, relief='groove')
            frame_4.pack()
            frame_4.place(anchor='center', relx=0.7, rely=0.51)
            img_4 = ImageTk.PhotoImage(Image.open("Imgs//Women_Shirt_2.png").resize((200, 200)))
            label_4 = Label(frame_4, image=img_4)
            label_4.pack()

            frame_5 = Frame(newWindow, relief='groove')
            frame_5.pack()
            frame_5.place(anchor='center', relx=0.3, rely=0.82)
            img_5 = ImageTk.PhotoImage(Image.open("Imgs//Women_Pant_1.png").resize((200, 200)))
            label_5 = Label(frame_5, image=img_5)
            label_5.pack()

            frame_6 = Frame(newWindow, relief='groove')
            frame_6.pack()
            frame_6.place(anchor='center', relx=0.7, rely=0.82)
            img_6 = ImageTk.PhotoImage(Image.open("Imgs//Women_Pant_2.png").resize((200, 200)))
            label_6 = Label(frame_6, image=img_6)
            label_6.pack()

            Laptop_text1 = Achats.Label(newWindow, text="Name: Moyabo Cuffed Sleeve\nPrice: 21.99$\nProductID: 56432897",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text2 = Achats.Label(newWindow, text="Name: FSHEWIN Womens Tops\nPrice: 59.99$\nProductID: 45637123",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text3 = Achats.Label(newWindow,
                                        text="Name: Legendary Whitetails Shirt Tops\nPrice: 34.99$\nProductID: 56473823",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text4 = Achats.Label(newWindow, text="Name: WDIRARA Women's pant\nPrice: 42.99$\nProductID: 54637221",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text5 = Achats.Label(newWindow, text="Name: Corduroy High pant\nPrice: 26.99$\nProductID: 45673342",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text6 = Achats.Label(newWindow, text="Name: ALLUMK Black Sequin\nPrice: 45.99$\nProductID: 56463432",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text1.place(relx=0.375, rely=0.10)
            Laptop_text2.place(relx=0.775, rely=0.10)

            Phone_text1 = Achats.Label(newWindow,
                                       text="Name: Legendary Whitetails Shirt\nPrice: 24.99$\nProductID: 52369841",
                                       foreground='yellow', background='gray22', font='Times 15 bold italic')
            Phone_text2 = Achats.Label(newWindow, text="WDIRARA Women's pant\nPrice: 34.99$\nProductID: 85612475",
                                       foreground='yellow', background='gray22', font='Times 15 bold italic')
            Phone_text1.place(relx=0.375, rely=0.40)
            Phone_text2.place(relx=0.775, rely=0.40)

            Comp_text1 = Achats.Label(newWindow,
                                      text="Name: Corduroy High pant\nPrice: 29.99$\nProductID: 74865921",
                                      foreground='yellow', background='gray22', font='Times 15 bold italic')
            Comp_text2 = Achats.Label(newWindow, text="ALLUMK Black Sequin\nPrice: 19.99$\nProductID: 96325964",
                                      foreground='yellow', background='gray22', font='Times 15 bold italic')
            Comp_text1.place(relx=0.375, rely=0.70)
            Comp_text2.place(relx=0.775, rely=0.70)

            CheckVar1 = tkinter.IntVar()
            CheckVar2 = tkinter.IntVar()
            CheckVar3 = tkinter.IntVar()
            CheckVar4 = tkinter.IntVar()
            CheckVar5 = tkinter.IntVar()
            CheckVar6 = tkinter.IntVar()
            checkbox_1 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar1, onvalue=1,
                                     offvalue=0)
            checkbox_1.place(relx=0.375, rely=0.30)
            checkbox_2 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar2, onvalue=1,
                                     offvalue=0)
            checkbox_2.place(relx=0.775, rely=0.30)
            checkbox_3 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar3, onvalue=1,
                                     offvalue=0)
            checkbox_3.place(relx=0.375, rely=0.60)
            checkbox_4 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar4, onvalue=1,
                                     offvalue=0)
            checkbox_4.place(relx=0.775, rely=0.60)
            checkbox_5 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar5, onvalue=1,
                                     offvalue=0)
            checkbox_5.place(relx=0.375, rely=0.90)
            checkbox_6 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar6, onvalue=1,
                                     offvalue=0)
            checkbox_6.place(relx=0.775, rely=0.90)

            def Total_cost():
                total_cost = 0
                L= []
                if CheckVar1.get():
                    total_cost += 22
                    L.extend([("Moyabo Cuffed Sleeve","22","56432897")])
                if CheckVar2.get():
                    total_cost += 60
                    L.extend([("FSHEWIN Women's Top","60","45637123")])
                if CheckVar3.get():
                    total_cost += 25
                    L.extend([("Legendary Whitetails Shirt","25","52369841")])
                if CheckVar4.get():
                    total_cost += 35
                    L.extend([("WDIRARA Women's Pant","35","85612475")])
                if CheckVar5.get():
                    L.extend([("Corduroy High Pant","30","74865921")])
                    total_cost += 30
                if CheckVar6.get():
                    L.extend(([("ALLUMK Black Sequin","20","96325964")]))
                    total_cost += 20
                answer = messagebox.askyesno("Check out",f"total cost is {total_cost}$, Do you want to proceed?")
                if answer:
                    transaction_win = Toplevel(window_main)
                    transaction_win.title("Details")
                    tkinter.Label(transaction_win,text = "First Name:",width=15).grid(row=0)
                    tkinter.Label(transaction_win,text="").grid(row=1)
                    tkinter.Label(transaction_win,text= "Card Number:").grid(row=2)
                    tkinter.Label(transaction_win,text="").grid(row=3)
                    tkinter.Label(transaction_win,text="CVV:").grid(row=4)
                    tkinter.Label(transaction_win, text="").grid(row=5)

                    def continue_btn():
                        try:
                            if type(int(e2.get())) == int:
                                if len(e2.get()) == 16:
                                    if type(int(e3.get()) == int):
                                        if len(e3.get()) == 3:
                                            messagebox.showinfo("Transaction Successful!", "Thank you!")
                                            transaction_win.destroy()
                                            newWindow.destroy()
                                            window.destroy()
                                            bill_win = Toplevel(window_main)
                                            bill_win.title("Receipt")
                                            tkinter.Label(bill_win, text="     ").grid(row=0)
                                            tkinter.Label(bill_win, text='Receipt',
                                                          font=('Helvetica', 18, 'bold')).grid(row=0, column=1)
                                            tkinter.Label(bill_win, text="Name:").grid(row=1)
                                            tkinter.Label(bill_win, text="Price($):").grid(row=1, column=1)
                                            tkinter.Label(bill_win, text="ProductID:").grid(row=1, column=2)
                                            tkinter.Label(bill_win, text="").grid(row=2)
                                            for i in range(len(L)):
                                                tkinter.Label(bill_win, text=L[i][0]).grid(row=2 + i, column=0)
                                                tkinter.Label(bill_win, text=L[i][1]).grid(row=2 + i, column=1)
                                                tkinter.Label(bill_win, text=L[i][2]).grid(row=2 + i, column=2)
                                            tkinter.Label(bill_win, text="Total:", font=('Helvetica', 18, 'bold')).grid(
                                                row=3 + len(L), column=0)
                                            tkinter.Label(bill_win, text=f"{total_cost}$",
                                                          font=('Helvetica', 18, 'bold')).grid(row=3 + len(L), column=1)
                                            bill_win.mainloop()

                                        else:
                                            messagebox.showwarning("Error!", "Invalid CVV")
                                            transaction_win.destroy()
                                            newWindow.destroy()
                                            window.destroy()
                                    else:
                                        messagebox.showwarning("Error!", "Invalid CVV")
                                        transaction_win.destroy()
                                        newWindow.destroy()
                                        window.destroy()
                                else:
                                    messagebox.showwarning("Error!", "Invalid Number")
                                    transaction_win.destroy()
                                    newWindow.destroy()
                                    window.destroy()

                            else:
                                messagebox.showwarning("Error!", "Invalid Number")
                                transaction_win.destroy()
                                newWindow.destroy()
                                window.destroy()

                        except:
                            messagebox.showwarning("CRITICAL ERROR!", "INVALID")
                            transaction_win.destroy()
                            newWindow.destroy()
                            window.destroy()

                    def cancel_btn():
                        messagebox.showinfo("Transaction cancelled", "Cancelled!")
                        transaction_win.destroy()
                        newWindow.destroy()
                        window.destroy()

                    tkinter.Button(transaction_win, text="Continue", command=continue_btn).grid(row=6, column=0)
                    tkinter.Button(transaction_win, text="Cancel", command=cancel_btn).grid(row=6, column=1)

                    e1 = tkinter.Entry(transaction_win)
                    e2 = tkinter.Entry(transaction_win)
                    e3 = tkinter.Entry(transaction_win)
                    e1.grid(row=0, column=1)
                    e2.grid(row=2, column=1)
                    e3.grid(row=4, column=1)
                    transaction_win.mainloop()

                else:
                    messagebox.showinfo("Transaction Cancelled","Oops")
                    newWindow.destroy()
                    window.destroy()
            btn_electronics = Achats.Button(newWindow, text="Check Out", command=Total_cost, foreground="floralwhite",
                                            bg="blue", font="Times 20")
            btn_electronics.place(relx=0.90,rely=0.95,anchor='w')

            newWindow.mainloop()

        btn = Achats.Button(window, text="4.Women's Fashion", command=openNewWindow, foreground='salmon', bg='gray22',
                            font='calibiri 25')
        btn.place(relx=0.15,
                  rely=0.43,
                  anchor='center')
        btn.place(x=0, y=20)

        def openNewWindow():
            newWindow = Toplevel(window)
            newWindow.title("Books")
            newWindow.geometry("2056x1028")
            newWindow.resizable(False, False)
            newWindow.configure(bg='gray22', height=1028, width=2056)
            newWindow.state("zoomed")
            Book_text1 = Achats.Label(newWindow, text="Novels:", foreground='salmon', background='gray22',
                                      font='calibiri 25')
            Book_text2 = Achats.Label(newWindow, text="Sci-Fi", foreground='salmon', background='gray22',
                                      font='calibiri 25')
            Book_text3 = Achats.Label(newWindow, text="Educational:", foreground='salmon', background='gray22',
                                      font='calibiri 25')
            Book_text1.place(relx=0.1, rely=0.05, anchor='center')
            Book_text2.place(relx=0.1, rely=0.36, anchor='center')
            Book_text3.place(relx=0.1, rely=0.68, anchor='center')
            frame_1 = Frame(newWindow, relief='groove')
            frame_1.pack()
            frame_1.place(anchor='center', relx=0.3, rely=0.20)
            img_1 = ImageTk.PhotoImage(Image.open("Imgs//Novels_1.png").resize((200, 200)))
            label_1 = Label(frame_1, image=img_1)
            label_1.pack()

            frame_2 = Frame(newWindow, relief='groove')
            frame_2.pack()
            frame_2.place(anchor='center', relx=0.7, rely=0.20)
            img_2 = ImageTk.PhotoImage(Image.open("Imgs//Novels_2.png").resize((200, 200)))
            label_2 = Label(frame_2, image=img_2)
            label_2.pack()

            frame_3 = Frame(newWindow, relief='groove')
            frame_3.pack()
            frame_3.place(anchor='center', relx=0.3, rely=0.51)
            img_3 = ImageTk.PhotoImage(Image.open("Imgs//Sci_1.png").resize((200, 200)))
            label_3 = Label(frame_3, image=img_3)
            label_3.pack()

            frame_4 = Frame(newWindow, relief='groove')
            frame_4.pack()
            frame_4.place(anchor='center', relx=0.7, rely=0.51)
            img_4 = ImageTk.PhotoImage(Image.open("Imgs//Sci_2.png").resize((200, 200)))
            label_4 = Label(frame_4, image=img_4)
            label_4.pack()

            frame_5 = Frame(newWindow, relief='groove')
            frame_5.pack()
            frame_5.place(anchor='center', relx=0.3, rely=0.82)
            img_5 = ImageTk.PhotoImage(Image.open("Imgs//Educational_1.png").resize((200, 200)))
            label_5 = Label(frame_5, image=img_5)
            label_5.pack()

            frame_6 = Frame(newWindow, relief='groove')
            frame_6.pack()
            frame_6.place(anchor='center', relx=0.7, rely=0.82)
            img_6 = ImageTk.PhotoImage(Image.open("Imgs//Educational_2.png").resize((200, 200)))
            label_6 = Label(frame_6, image=img_6)
            label_6.pack()

            Laptop_text1 = Achats.Label(newWindow, text="Name: The Lord of the Rings\nPrice: 12.99$\nProductID: 45982367",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text2 = Achats.Label(newWindow, text="Name: Harry Potter\nPrice: 14.99$\nProductID: 4129385",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text1.place(relx=0.375, rely=0.10)
            Laptop_text2.place(relx=0.775, rely=0.10)

            Phone_text1 = Achats.Label(newWindow,
                                       text="Name: Dune \nPrice: 24.99$\nProductID: 15869753",
                                       foreground='yellow', background='gray22', font='Times 15 bold italic')
            Phone_text2 = Achats.Label(newWindow, text="Name: Weaponized\nPrice: 7.99$\nProductID: 58153649",
                                       foreground='yellow', background='gray22', font='Times 15 bold italic')
            Phone_text1.place(relx=0.375, rely=0.40)
            Phone_text2.place(relx=0.775, rely=0.40)

            Comp_text1 = Achats.Label(newWindow,
                                      text="Name: Math Guide Class10\nPrice: 6.99$\nProductID: 87423691",
                                      foreground='yellow', background='gray22', font='Times 15 bold italic')
            Comp_text2 = Achats.Label(newWindow, text="PCM Books for Class 12 \nPrice: 14.99$\nProductID: 651935860",
                                      foreground='yellow', background='gray22', font='Times 15 bold italic')
            Comp_text1.place(relx=0.375, rely=0.70)
            Comp_text2.place(relx=0.775, rely=0.70)

            CheckVar1 = tkinter.IntVar()
            CheckVar2 = tkinter.IntVar()
            CheckVar3 = tkinter.IntVar()
            CheckVar4 = tkinter.IntVar()
            CheckVar5 = tkinter.IntVar()
            CheckVar6 = tkinter.IntVar()
            checkbox_1 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar1, onvalue=1,
                                     offvalue=0)
            checkbox_1.place(relx=0.375, rely=0.30)
            checkbox_2 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar2, onvalue=1,
                                     offvalue=0)
            checkbox_2.place(relx=0.775, rely=0.30)
            checkbox_3 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar3, onvalue=1,
                                     offvalue=0)
            checkbox_3.place(relx=0.375, rely=0.60)
            checkbox_4 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar4, onvalue=1,
                                     offvalue=0)
            checkbox_4.place(relx=0.775, rely=0.60)
            checkbox_5 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar5, onvalue=1,
                                     offvalue=0)
            checkbox_5.place(relx=0.375, rely=0.90)
            checkbox_6 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar6, onvalue=1,
                                     offvalue=0)
            checkbox_6.place(relx=0.775, rely=0.90)

            def Total_cost():
                total_cost = 0
                L= []
                if CheckVar1.get():
                    total_cost += 13
                    L.extend([("The Lord of the Rings","13","45982367")])
                if CheckVar2.get():
                    total_cost += 15
                    L.extend([("Harry Potter","15","4129385")])
                if CheckVar3.get():
                    total_cost += 25
                    L.extend([("Dune","25","15869753")])
                if CheckVar4.get():
                    total_cost += 8
                    L.extend([("Weaponized","8","58153649")])
                if CheckVar5.get():
                    L.extend([("Maths Guide class 10","7","87423691")])
                    total_cost += 7
                if CheckVar6.get():
                    L.extend(([("PCM books for class 12","15","651935860")]))
                    total_cost += 15
                answer = messagebox.askyesno("Check out",f"total cost is {total_cost}$, Do you want to proceed?")
                if answer:
                    transaction_win = Toplevel(window_main)
                    transaction_win.title("Details")
                    tkinter.Label(transaction_win,text = "First Name:",width=15).grid(row=0)
                    tkinter.Label(transaction_win,text="").grid(row=1)
                    tkinter.Label(transaction_win,text= "Card Number:").grid(row=2)
                    tkinter.Label(transaction_win,text="").grid(row=3)
                    tkinter.Label(transaction_win,text="CVV:").grid(row=4)
                    tkinter.Label(transaction_win, text="").grid(row=5)

                    def continue_btn():
                        try:
                            if type(int(e2.get())) == int:
                                if len(e2.get()) == 16:
                                    if type(int(e3.get()) == int):
                                        if len(e3.get()) == 3:
                                            messagebox.showinfo("Transaction Successful!", "Thank you!")
                                            transaction_win.destroy()
                                            newWindow.destroy()
                                            window.destroy()
                                            bill_win = Toplevel(window_main)
                                            bill_win.title("Receipt")
                                            tkinter.Label(bill_win, text="     ").grid(row=0)
                                            tkinter.Label(bill_win, text='Receipt',
                                                          font=('Helvetica', 18, 'bold')).grid(row=0, column=1)
                                            tkinter.Label(bill_win, text="Name:").grid(row=1)
                                            tkinter.Label(bill_win, text="Price($):").grid(row=1, column=1)
                                            tkinter.Label(bill_win, text="ProductID:").grid(row=1, column=2)
                                            tkinter.Label(bill_win, text="").grid(row=2)
                                            for i in range(len(L)):
                                                tkinter.Label(bill_win, text=L[i][0]).grid(row=2 + i, column=0)
                                                tkinter.Label(bill_win, text=L[i][1]).grid(row=2 + i, column=1)
                                                tkinter.Label(bill_win, text=L[i][2]).grid(row=2 + i, column=2)
                                            tkinter.Label(bill_win, text="Total:", font=('Helvetica', 18, 'bold')).grid(
                                                row=3 + len(L), column=0)
                                            tkinter.Label(bill_win, text=f"{total_cost}$",
                                                          font=('Helvetica', 18, 'bold')).grid(row=3 + len(L), column=1)
                                            bill_win.mainloop()

                                        else:
                                            messagebox.showwarning("Error!", "Invalid CVV")
                                            transaction_win.destroy()
                                            newWindow.destroy()
                                            window.destroy()
                                    else:
                                        messagebox.showwarning("Error!", "Invalid CVV")
                                        transaction_win.destroy()
                                        newWindow.destroy()
                                        window.destroy()
                                else:
                                    messagebox.showwarning("Error!", "Invalid Number")
                                    transaction_win.destroy()
                                    newWindow.destroy()
                                    window.destroy()

                            else:
                                messagebox.showwarning("Error!", "Invalid Number")
                                transaction_win.destroy()
                                newWindow.destroy()
                                window.destroy()

                        except:
                            messagebox.showwarning("CRITICAL ERROR!", "INVALID")
                            transaction_win.destroy()
                            newWindow.destroy()
                            window.destroy()

                    def cancel_btn():
                        messagebox.showinfo("Transaction cancelled", "Cancelled!")
                        transaction_win.destroy()
                        newWindow.destroy()
                        window.destroy()

                    tkinter.Button(transaction_win, text="Continue", command=continue_btn).grid(row=6, column=0)
                    tkinter.Button(transaction_win, text="Cancel", command=cancel_btn).grid(row=6, column=1)

                    e1 = tkinter.Entry(transaction_win)
                    e2 = tkinter.Entry(transaction_win)
                    e3 = tkinter.Entry(transaction_win)
                    e1.grid(row=0, column=1)
                    e2.grid(row=2, column=1)
                    e3.grid(row=4, column=1)
                    transaction_win.mainloop()

                else:
                    messagebox.showinfo("Transaction Cancelled","Oops")
                    newWindow.destroy()
                    window.destroy()

            btn_electronics = Achats.Button(newWindow, text="Check Out", command=Total_cost, foreground="floralwhite",
                                            bg="blue", font="Times 20")
            btn_electronics.place(relx=0.90,rely=0.95,anchor='w')

            newWindow.mainloop()

        btn = Achats.Button(window, text="5.Books", command=openNewWindow, foreground='salmon', bg='gray22',
                            font='calibiri 25')
        btn.place(relx=0.095,
                  rely=0.53,
                  anchor='center')
        btn.place(x=0, y=20)

        def openNewWindow():
            newWindow = Toplevel(window)
            newWindow.title("Video Games")
            newWindow.geometry("2056x1028")
            newWindow.resizable(False, False)
            newWindow.configure(bg='gray22', height=1028, width=2056)
            newWindow.state("zoomed")
            VG_text1 = Achats.Label(newWindow, text="Simulator:", foreground='salmon', background='gray22',
                                    font='calibiri 25')
            VG_text2 = Achats.Label(newWindow, text="Action:", foreground='salmon', background='gray22',
                                    font='calibiri 25')
            VG_text3 = Achats.Label(newWindow, text="Adventure:", foreground='salmon', background='gray22',
                                    font='calibiri 25')
            VG_text1.place(relx=0.1, rely=0.05, anchor='center')
            VG_text2.place(relx=0.1, rely=0.36, anchor='center')
            VG_text3.place(relx=0.1, rely=0.68, anchor='center')
            frame_1 = Frame(newWindow, relief='groove')
            frame_1.pack()
            frame_1.place(anchor='center', relx=0.3, rely=0.20)
            img_1 = ImageTk.PhotoImage(Image.open("Imgs//Simulation_1.png").resize((200, 200)))
            label_1 = Label(frame_1, image=img_1)
            label_1.pack()

            frame_2 = Frame(newWindow, relief='groove')
            frame_2.pack()
            frame_2.place(anchor='center', relx=0.7, rely=0.20)
            img_2 = ImageTk.PhotoImage(Image.open("Imgs//Simulation_2.png").resize((200, 200)))
            label_2 = Label(frame_2, image=img_2)
            label_2.pack()

            frame_3 = Frame(newWindow, relief='groove')
            frame_3.pack()
            frame_3.place(anchor='center', relx=0.3, rely=0.51)
            img_3 = ImageTk.PhotoImage(Image.open("Imgs//Action_1.png").resize((200, 200)))
            label_3 = Label(frame_3, image=img_3)
            label_3.pack()

            frame_4 = Frame(newWindow, relief='groove')
            frame_4.pack()
            frame_4.place(anchor='center', relx=0.7, rely=0.51)
            img_4 = ImageTk.PhotoImage(Image.open("Imgs//Action_2.png").resize((200, 200)))
            label_4 = Label(frame_4, image=img_4)
            label_4.pack()

            frame_5 = Frame(newWindow, relief='groove')
            frame_5.pack()
            frame_5.place(anchor='center', relx=0.3, rely=0.82)
            img_5 = ImageTk.PhotoImage(Image.open("Imgs//Adventure_1.png").resize((200, 200)))
            label_5 = Label(frame_5, image=img_5)
            label_5.pack()

            frame_6 = Frame(newWindow, relief='groove')
            frame_6.pack()
            frame_6.place(anchor='center', relx=0.7, rely=0.82)
            img_6 = ImageTk.PhotoImage(Image.open("Imgs//Adventure_2.png").resize((200, 200)))
            label_6 = Label(frame_6, image=img_6)
            label_6.pack()

            Laptop_text1 = Achats.Label(newWindow, text="Name: Mud Runner\nPrice: 4.99$\nProductID: 15963287",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text2 = Achats.Label(newWindow, text="Name: Flight Simulation\nPrice: 6.99$\nProductID: 15987463",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text1.place(relx=0.375, rely=0.10)
            Laptop_text2.place(relx=0.775, rely=0.10)

            Phone_text1 = Achats.Label(newWindow,
                                       text="Name: Hitman\nPrice: 4.99$\nProductID: 45932815",
                                       foreground='yellow', background='gray22', font='Times 15 bold italic')
            Phone_text2 = Achats.Label(newWindow, text="Name: GTA\nPrice: 12.99$\nProductID: 75963282",
                                       foreground='yellow', background='gray22', font='Times 15 bold italic')
            Phone_text1.place(relx=0.375, rely=0.40)
            Phone_text2.place(relx=0.775, rely=0.40)

            Comp_text1 = Achats.Label(newWindow,
                                      text="Name: Genshin Impact\nPrice: 9.99$\nProductID: 74865921",
                                      foreground='yellow', background='gray22', font='Times 15 bold italic')
            Comp_text2 = Achats.Label(newWindow, text="God of War\nPrice: 11.99$\nProductID: 96325964",
                                      foreground='yellow', background='gray22', font='Times 15 bold italic')
            Comp_text1.place(relx=0.375, rely=0.70)
            Comp_text2.place(relx=0.775, rely=0.70)

            CheckVar1 = tkinter.IntVar()
            CheckVar2 = tkinter.IntVar()
            CheckVar3 = tkinter.IntVar()
            CheckVar4 = tkinter.IntVar()
            CheckVar5 = tkinter.IntVar()
            CheckVar6 = tkinter.IntVar()
            checkbox_1 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar1, onvalue=1,
                                     offvalue=0)
            checkbox_1.place(relx=0.375, rely=0.30)
            checkbox_2 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar2, onvalue=1,
                                     offvalue=0)
            checkbox_2.place(relx=0.775, rely=0.30)
            checkbox_3 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar3, onvalue=1,
                                     offvalue=0)
            checkbox_3.place(relx=0.375, rely=0.60)
            checkbox_4 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar4, onvalue=1,
                                     offvalue=0)
            checkbox_4.place(relx=0.775, rely=0.60)
            checkbox_5 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar5, onvalue=1,
                                     offvalue=0)
            checkbox_5.place(relx=0.375, rely=0.90)
            checkbox_6 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar6, onvalue=1,
                                     offvalue=0)
            checkbox_6.place(relx=0.775, rely=0.90)

            def Total_cost():
                total_cost = 0
                L= []
                if CheckVar1.get():
                    total_cost += 5
                    L.extend([("Mud Runner","5","15963287")])
                if CheckVar2.get():
                    total_cost += 7
                    L.extend([("Flight Simulator","7","15987463")])
                if CheckVar3.get():
                    total_cost += 5
                    L.extend([("HitMan","5","45932815")])
                if CheckVar4.get():
                    total_cost += 13
                    L.extend([("GTA","13","75963282")])
                if CheckVar5.get():
                    L.extend([("Genshin Impact","10","74865921")])
                    total_cost += 10
                if CheckVar6.get():
                    L.extend(([("God of War ","12","96325964")]))
                    total_cost += 12
                answer = messagebox.askyesno("Check out",f"total cost is {total_cost}$, Do you want to proceed?")
                if answer:
                    transaction_win = Toplevel(window_main)
                    transaction_win.title("Details")
                    tkinter.Label(transaction_win,text = "First Name:",width=15).grid(row=0)
                    tkinter.Label(transaction_win,text="").grid(row=1)
                    tkinter.Label(transaction_win,text= "Card Number:").grid(row=2)
                    tkinter.Label(transaction_win,text="").grid(row=3)
                    tkinter.Label(transaction_win,text="CVV:").grid(row=4)
                    tkinter.Label(transaction_win, text="").grid(row=5)

                    def continue_btn():
                        try:
                            if type(int(e2.get())) == int:
                                if len(e2.get()) == 16:
                                    if type(int(e3.get()) == int):
                                        if len(e3.get()) == 3:
                                            messagebox.showinfo("Transaction Successful!", "Thank you!")
                                            transaction_win.destroy()
                                            newWindow.destroy()
                                            window.destroy()
                                            bill_win = Toplevel(window_main)
                                            bill_win.title("Receipt")
                                            tkinter.Label(bill_win, text="     ").grid(row=0)
                                            tkinter.Label(bill_win, text='Receipt',
                                                          font=('Helvetica', 18, 'bold')).grid(row=0, column=1)
                                            tkinter.Label(bill_win, text="Name:").grid(row=1)
                                            tkinter.Label(bill_win, text="Price($):").grid(row=1, column=1)
                                            tkinter.Label(bill_win, text="ProductID:").grid(row=1, column=2)
                                            tkinter.Label(bill_win, text="").grid(row=2)
                                            for i in range(len(L)):
                                                tkinter.Label(bill_win, text=L[i][0]).grid(row=2 + i, column=0)
                                                tkinter.Label(bill_win, text=L[i][1]).grid(row=2 + i, column=1)
                                                tkinter.Label(bill_win, text=L[i][2]).grid(row=2 + i, column=2)
                                            tkinter.Label(bill_win, text="Total:", font=('Helvetica', 18, 'bold')).grid(
                                                row=3 + len(L), column=0)
                                            tkinter.Label(bill_win, text=f"{total_cost}$",
                                                          font=('Helvetica', 18, 'bold')).grid(row=3 + len(L), column=1)
                                            bill_win.mainloop()

                                        else:
                                            messagebox.showwarning("Error!", "Invalid CVV")
                                            transaction_win.destroy()
                                            newWindow.destroy()
                                            window.destroy()
                                    else:
                                        messagebox.showwarning("Error!", "Invalid CVV")
                                        transaction_win.destroy()
                                        newWindow.destroy()
                                        window.destroy()
                                else:
                                    messagebox.showwarning("Error!", "Invalid Number")
                                    transaction_win.destroy()
                                    newWindow.destroy()
                                    window.destroy()

                            else:
                                messagebox.showwarning("Error!", "Invalid Number")
                                transaction_win.destroy()
                                newWindow.destroy()
                                window.destroy()

                        except:
                            messagebox.showwarning("CRITICAL ERROR!", "INVALID")
                            transaction_win.destroy()
                            newWindow.destroy()
                            window.destroy()

                    def cancel_btn():
                        messagebox.showinfo("Transaction cancelled", "Cancelled!")
                        transaction_win.destroy()
                        newWindow.destroy()
                        window.destroy()

                    tkinter.Button(transaction_win, text="Continue", command=continue_btn).grid(row=6, column=0)
                    tkinter.Button(transaction_win, text="Cancel", command=cancel_btn).grid(row=6, column=1)

                    e1 = tkinter.Entry(transaction_win)
                    e2 = tkinter.Entry(transaction_win)
                    e3 = tkinter.Entry(transaction_win)
                    e1.grid(row=0, column=1)
                    e2.grid(row=2, column=1)
                    e3.grid(row=4, column=1)
                    transaction_win.mainloop()

                else:
                    messagebox.showinfo("Transaction Cancelled","Oops")
                    newWindow.destroy()
                    window.destroy()

            btn_electronics = Achats.Button(newWindow, text="Check Out", command=Total_cost, foreground="floralwhite",
                                            bg="blue", font="Times 20")
            btn_electronics.place(relx=0.90,rely=0.95,anchor='w')

            newWindow.mainloop()

        btn = Achats.Button(window, text="6.Video games", command=openNewWindow, foreground='salmon', bg='gray22',
                            font='calibiri 25')

        btn.place(relx=0.13,
                  rely=0.63,
                  anchor='center')
        btn.place(x=0, y=20)

        def openNewWindow():
            newWindow = Toplevel(window)
            newWindow.title("Sports")
            newWindow.geometry("2056x1028")
            newWindow.resizable(False, False)
            newWindow.configure(bg='gray22', height=1028, width=2056)
            newWindow.state("zoomed")
            Sports_text1 = Achats.Label(newWindow, text="Equipments:", foreground='salmon', background='gray22',
                                        font='calibiri 25')
            Sports_text2 = Achats.Label(newWindow, text="Rackets:", foreground='salmon', background='gray22',
                                        font='calibiri 25')
            Sports_text3 = Achats.Label(newWindow, text="Shoes:", foreground='salmon', background='gray22',
                                        font='calibiri 25')
            Sports_text1.place(relx=0.1, rely=0.05, anchor='center')
            Sports_text2.place(relx=0.1, rely=0.36, anchor='center')
            Sports_text3.place(relx=0.1, rely=0.68, anchor='center')
            frame_1 = Frame(newWindow, relief='groove')
            frame_1.pack()
            frame_1.place(anchor='center', relx=0.3, rely=0.20)
            img_1 = ImageTk.PhotoImage(Image.open("Imgs//Equipments_1.png").resize((200, 200)))
            label_1 = Label(frame_1, image=img_1)
            label_1.pack()

            frame_2 = Frame(newWindow, relief='groove')
            frame_2.pack()
            frame_2.place(anchor='center', relx=0.7, rely=0.20)
            img_2 = ImageTk.PhotoImage(Image.open("Imgs//Equipments_2.png").resize((200, 200)))
            label_2 = Label(frame_2, image=img_2)
            label_2.pack()

            frame_3 = Frame(newWindow, relief='groove')
            frame_3.pack()
            frame_3.place(anchor='center', relx=0.3, rely=0.51)
            img_3 = ImageTk.PhotoImage(Image.open("Imgs//Rackets_1.png").resize((200, 200)))
            label_3 = Label(frame_3, image=img_3)
            label_3.pack()

            frame_4 = Frame(newWindow, relief='groove')
            frame_4.pack()
            frame_4.place(anchor='center', relx=0.7, rely=0.51)
            img_4 = ImageTk.PhotoImage(Image.open("Imgs//Rackets_2.png").resize((200, 200)))
            label_4 = Label(frame_4, image=img_4)
            label_4.pack()

            frame_5 = Frame(newWindow, relief='groove')
            frame_5.pack()
            frame_5.place(anchor='center', relx=0.3, rely=0.82)
            img_5 = ImageTk.PhotoImage(Image.open("Imgs//Shoes_1.png").resize((200, 200)))
            label_5 = Label(frame_5, image=img_5)
            label_5.pack()

            frame_6 = Frame(newWindow, relief='groove')
            frame_6.pack()
            frame_6.place(anchor='center', relx=0.7, rely=0.82)
            img_6 = ImageTk.PhotoImage(Image.open("Imgs//Shoes_2.png").resize((200, 200)))
            label_6 = Label(frame_6, image=img_6)
            label_6.pack()

            Laptop_text1 = Achats.Label(newWindow, text="Name: Hockey Stick\nPrice: 15.99$\nProductID: 45982367",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text2 = Achats.Label(newWindow, text="Name: Plastic cones\nPrice: 9.99$\nProductID: 4129385",
                                        foreground='yellow', background='gray22', font='Times 15 bold italic')
            Laptop_text1.place(relx=0.375, rely=0.10)
            Laptop_text2.place(relx=0.775, rely=0.10)

            Phone_text1 = Achats.Label(newWindow,
                                       text="Name: Badminton \nPrice: 39.99$\nProductID: 15869753",
                                       foreground='yellow', background='gray22', font='Times 15 bold italic')
            Phone_text2 = Achats.Label(newWindow, text="Name: Tennis\nPrice: 74.99$\nProductID: 58153649",
                                       foreground='yellow', background='gray22', font='Times 15 bold italic')
            Phone_text1.place(relx=0.375, rely=0.40)
            Phone_text2.place(relx=0.775, rely=0.40)

            Comp_text1 = Achats.Label(newWindow,
                                      text="Name: Non marking shoes\nPrice: 49.99$\nProductID: 87423691",
                                      foreground='yellow', background='gray22', font='Times 15 bold italic')
            Comp_text2 = Achats.Label(newWindow, text="Running Shoes \nPrice: 94.99$\nProductID: 651935860",
                                      foreground='yellow', background='gray22', font='Times 15 bold italic')
            Comp_text1.place(relx=0.375, rely=0.70)
            Comp_text2.place(relx=0.775, rely=0.70)

            CheckVar1 = tkinter.IntVar()
            CheckVar2 = tkinter.IntVar()
            CheckVar3 = tkinter.IntVar()
            CheckVar4 = tkinter.IntVar()
            CheckVar5 = tkinter.IntVar()
            CheckVar6 = tkinter.IntVar()
            checkbox_1 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar1, onvalue=1,
                                     offvalue=0)
            checkbox_1.place(relx=0.375, rely=0.30)
            checkbox_2 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar2, onvalue=1,
                                     offvalue=0)
            checkbox_2.place(relx=0.775, rely=0.30)
            checkbox_3 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar3, onvalue=1,
                                     offvalue=0)
            checkbox_3.place(relx=0.375, rely=0.60)
            checkbox_4 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar4, onvalue=1,
                                     offvalue=0)
            checkbox_4.place(relx=0.775, rely=0.60)
            checkbox_5 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar5, onvalue=1,
                                     offvalue=0)
            checkbox_5.place(relx=0.375, rely=0.90)
            checkbox_6 = Checkbutton(newWindow, text="ADD TO CART🛒", cursor="plus", variable=CheckVar6, onvalue=1,
                                     offvalue=0)
            checkbox_6.place(relx=0.775, rely=0.90)

            def Total_cost():
                total_cost = 0
                L= []
                if CheckVar1.get():
                    total_cost += 16
                    L.extend([("Hockey Stick","16","45982367")])
                if CheckVar2.get():
                    total_cost += 10
                    L.extend([("Plastic Cones","10","4129385")])
                if CheckVar3.get():
                    total_cost += 40
                    L.extend([("Badminton Racquet","40","15869753")])
                if CheckVar4.get():
                    total_cost += 75
                    L.extend([("Tennis Racquet","75","58153649")])
                if CheckVar5.get():
                    L.extend([("Non-marking Shoes","50","87423691")])
                    total_cost += 50
                if CheckVar6.get():
                    L.extend(([("Running Shoes","95","651935860")]))
                    total_cost += 95
                answer = messagebox.askyesno("Check out",f"total cost is {total_cost}$, Do you want to proceed?")
                if answer:
                    transaction_win = Toplevel(window_main)
                    transaction_win.title("Details")
                    tkinter.Label(transaction_win,text = "First Name:",width=15).grid(row=0)
                    tkinter.Label(transaction_win,text="").grid(row=1)
                    tkinter.Label(transaction_win,text= "Card Number:").grid(row=2)
                    tkinter.Label(transaction_win,text="").grid(row=3)
                    tkinter.Label(transaction_win,text="CVV:").grid(row=4)
                    tkinter.Label(transaction_win, text="").grid(row=5)

                    def continue_btn():
                        try:
                            if type(int(e2.get())) == int:
                                if len(e2.get()) == 16:
                                    if type(int(e3.get()) == int):
                                        if len(e3.get()) == 3:
                                            messagebox.showinfo("Transaction Successful!", "Thank you!")
                                            transaction_win.destroy()
                                            newWindow.destroy()
                                            window.destroy()
                                            bill_win = Toplevel(window_main)
                                            bill_win.title("Receipt")
                                            tkinter.Label(bill_win, text="     ").grid(row=0)
                                            tkinter.Label(bill_win, text='Receipt',
                                                          font=('Helvetica', 18, 'bold')).grid(row=0, column=1)
                                            tkinter.Label(bill_win, text="Name:").grid(row=1)
                                            tkinter.Label(bill_win, text="Price($):").grid(row=1, column=1)
                                            tkinter.Label(bill_win, text="ProductID:").grid(row=1, column=2)
                                            tkinter.Label(bill_win, text="").grid(row=2)
                                            for i in range(len(L)):
                                                tkinter.Label(bill_win, text=L[i][0]).grid(row=2 + i, column=0)
                                                tkinter.Label(bill_win, text=L[i][1]).grid(row=2 + i, column=1)
                                                tkinter.Label(bill_win, text=L[i][2]).grid(row=2 + i, column=2)
                                            tkinter.Label(bill_win, text="Total:", font=('Helvetica', 18, 'bold')).grid(
                                                row=3 + len(L), column=0)
                                            tkinter.Label(bill_win, text=f"{total_cost}$",
                                                          font=('Helvetica', 18, 'bold')).grid(row=3 + len(L), column=1)
                                            bill_win.mainloop()

                                        else:
                                            messagebox.showwarning("Error!", "Invalid CVV")
                                            transaction_win.destroy()
                                            newWindow.destroy()
                                            window.destroy()
                                    else:
                                        messagebox.showwarning("Error!", "Invalid CVV")
                                        transaction_win.destroy()
                                        newWindow.destroy()
                                        window.destroy()
                                else:
                                    messagebox.showwarning("Error!", "Invalid Number")
                                    transaction_win.destroy()
                                    newWindow.destroy()
                                    window.destroy()

                            else:
                                messagebox.showwarning("Error!", "Invalid Number")
                                transaction_win.destroy()
                                newWindow.destroy()
                                window.destroy()

                        except:
                            messagebox.showwarning("CRITICAL ERROR!", "INVALID")
                            transaction_win.destroy()
                            newWindow.destroy()
                            window.destroy()

                    def cancel_btn():
                        messagebox.showinfo("Transaction cancelled", "Cancelled!")
                        transaction_win.destroy()
                        newWindow.destroy()
                        window.destroy()

                    tkinter.Button(transaction_win, text="Continue", command=continue_btn).grid(row=6, column=0)
                    tkinter.Button(transaction_win, text="Cancel", command=cancel_btn).grid(row=6, column=1)

                    e1 = tkinter.Entry(transaction_win)
                    e2 = tkinter.Entry(transaction_win)
                    e3 = tkinter.Entry(transaction_win)
                    e1.grid(row=0, column=1)
                    e2.grid(row=2, column=1)
                    e3.grid(row=4, column=1)
                    transaction_win.mainloop()

                else:
                    messagebox.showinfo("Transaction Cancelled","Oops")
                    newWindow.destroy()
                    window.destroy()

            btn_electronics = Achats.Button(newWindow, text="Check Out", command=Total_cost, foreground="floralwhite",
                                            bg="blue", font="Times 20")
            btn_electronics.place(relx=0.90,rely=0.95,anchor='w')

            newWindow.mainloop()

        btn = Achats.Button(window, text="7.Sports", command=openNewWindow, foreground='salmon', bg='gray22',
                            font='calibiri 25')
        btn.place(relx=0.10,
                  rely=0.73,
                  anchor='center')
        btn.place(x=0, y=20)
        window.mainloop()


    else:
        Achats.messagebox.showwarning("Warning","Please Accept our terms and conditions to proceed!")


btn = Achats.Button(window_main, text =">>> 🛒🛒!!!Click here to shop!!!🛒🛒 <<", command =openNewWindow, bg='pink', font='kristenitc')
btn.place(relx=0.5,
          rely=0.5,
          anchor='center')
btn.place(x=0, y=20)



window_main.state('zoomed')
window_main.mainloop()
