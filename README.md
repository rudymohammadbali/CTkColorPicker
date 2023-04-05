# CTkColorPicker
**A modern color picker made for customtkinter!**

![Screenshot](https://user-images.githubusercontent.com/89206401/209182773-d76bf05c-610e-4297-aec5-7bb61a11d6d3.jpg)

## Download

```
pip install CTkColorPicker
```

### [<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/Akascape/CTkColorPicker?&color=white&label=Source%20Code&logo=Python&logoColor=yellow&style=for-the-badge"  width="300">](https://github.com/Akascape/CTkColorPicker/archive/refs/heads/main.zip)

## Requirements
- [customtkinter](https://github.com/TomSchimansky/CustomTkinter)
- [pillow](https://pypi.org/project/Pillow/)

### How to use?
```python
import customtkinter as ctk
from CTkColorPicker import AskColor

def ask_color():
    pick_color = AskColor(width=300) # Open the Color Picker, size of the window can be changed by adjusting width parameter
    color = pick_color.get() # Get the color
    button.configure(fg_color=color)
    
root = ctk.CTk()

button = ctk.CTkButton(master=root, text="CHOOSE COLOR", text_color="black", command=ask_color)
button.pack(padx=30, pady=20)
root.mainloop()
```

**Thats all, hope it will help!**
