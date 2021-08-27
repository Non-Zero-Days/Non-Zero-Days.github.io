## Python

### Prerequisites:

Install [Python](https://www.python.org/downloads/)

### Loose Agenda:

Gain familiarity with basic commands in Python

### Step by Step

#### Setup playground

Create a directory for this exercise

Open Visual Studio Code

Select File > Open Folder and select the directory that was created in the first step

On the left side nav menu select the topmost icon to open the Explorer window (Alternatively, use the hot-key Ctrl+Shift+E)

Right click in the Explorer window, select "New File" then enter the name app.py

#### Printing Output

Write the following code into your app.py file

```
print("Non-Zero Days!")
```

Open the Terminal window with Ctrl+Shift+`

Run the following command

```
py app.py
```

#### User Input

Replace your python code with the following code

```
message = input("Please write a message\n")
print("You wrote the following message:\n" + message)
```

Open the Terminal window with Ctrl+`

Run the following command

```
py app.py
```

Enter a test message then press enter.

#### Conditional If

Replace your python code with the following code

```
message = input("Please write a message\n")

if(message != ''):
    print("You wrote the following message:\n" + message)
```

Open the Terminal window with Ctrl+`

Run the following command

```
py app.py
```

Enter an empty message and see the result. Try again with a non-empty message.

#### For Loop

Replace your python code with the following code

```
message = input("Please write a message\n")

if(message != ''):
    for character in message:
        print(character)
```

Open the Terminal window with Ctrl+`

Run the following command

```
py app.py
```

Enter an empty message and see the result. Try again with a non-empty message.

#### File Input and Output

In the Explorer Window, create a new file named test.txt and enter the following text

```
Have you considered liking and subscribing?
This text is really subtle.
But actually though.
```

Replace your python code in app.py with the following code

```
file = open('test.txt', 'r')
for line in file:
    print(line)
```

Open the Terminal window with Ctrl+`

Run the following command

```
py app.py
```

Replace your python code in app.py with the following code

```
message = input("Please write a message\n")
file = open('test.txt', 'w')
file.write(message)
file.close()
```

Open the Terminal window with Ctrl+`

Run the following command

```
py app.py
```

Enter a message then press enter. Open your test.txt and see the result.

Congratulations on a non-zero day!
