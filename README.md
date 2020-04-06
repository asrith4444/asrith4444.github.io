## Welcome to Asrith's Blog

You can see the [Keepy](https://asrith4444.github.io/keepy) to preview the content Keepy.

### Markdown

A simple Python file finder code

```markdown
import os
i=os.listdir("C:/Users/DELL/Desktop/Python")
#for j in i:
#    print(j)
print('--------------------------------')
# List all files in a directory using scandir()
basepath = "C:/Users/DELL/Desktop/Python"
#with os.scandir(basepath) as entries:
#    for entry in entries:
#       if entry.is_file():
#            print(entry.name)
for f_name in os.listdir('C:/Users/DELL/Desktop/Python'):
     if f_name.endswith('.py'):
         print(f_name)
```
###AKC
//For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
