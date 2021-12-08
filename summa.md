```
label1 -> Text = "Hello";
```
* Clicks a button and turns into the text hello

* label1 is the variable name. here, the variable name of the button


```
label1 -> Text = textbox1 -> Text;
```
* CHanges the text in the label1 to the text typed in the text box

## Button 
* Enabled -> True

```
Application::Exit() //To exit out of the app
```

## Convert textbox string to float
```
 String^ i1 = textBox1->Text;
 float rez = (float)(Convert::ToDouble(i1)*4.35);
 textBox2->Text = rez.ToString();
```
https://stackoverflow.com/questions/8718048/converting-textbox-string-to-float
## Message Box

```
MessageBox::Show("Incorrect pass", "Title of the window", MessageBoxButtons::OK, MessageBoxIcon::Error);
```
* Launches a message box

## New Window
* Insert a Panel
* Change dock


```
panel -> Hide(); #Hides the panel
panel -> Show(); #Shows the panel
```
---


```
```
