# BITS NVDA Course, Week 3

## Agenda

| Item | Topic | Instructor | Length|
|------|-------|------------|-------|
| A. | Introduction | Debee Armstrong | 5 minutes |
| B. | Student questions| All instructors | 15 minutes |
| C. | Optional homework presentations | Various Students| TBD |
| D. | Basic Text Review Commands| Joel Dodson | 20 minutes |
| e. | Object Navigation| Joel Dodson| 30 Minutes |
| F. | Student questions | All instructors | remainder of class time |

## Terminology

### **Text Review

Refers to commands for reviewing text without changing the position of the focus or cursor.

### **Review Cursor**

An imaginary cursor or pointer that points to a particular character onscreen. By "imaginary" we mean that it is not visible, but it is a way for NVDA to locate a particular point onscreen. Text review moves this pointer without changing where Windows knows the focus is located.

### **Object**

Everything in Windows is an object. A window, a control, a running program or a single character, all are objects. Windows itself is a giant database of objects and what appears onscreen is just the tip of that iceberg! 

### ***Navigator Object***

Yet another "imaginary" pointer built in to NVDA. This marks a particular objectin Windows and it can move from one object to another.

### **Object hierarchy **

Objects are arranged with some containing other objects. This branching "tree-structure" is called a hierarchy. For example a dialog box is an object, it is inside a window, which itself is an object. Inside the dialog box you might find a list. That list is of course an object. And inside that list you would find items, Each item is an object. When voiceover users on the mac "interact" with a control, they are also moving down the branch of an object hierarchy.

### **Parent-Child Objects **

This refers to where an object is positioned in the hierarchy. For example a list item is a child object and its parent object is the actual list. The list too is a child object; its parent object is the dialog box containing the list. The dialog box is a child object to the window containing that box. The window is the parent object to the dialog box.

## What is text review good for?

Sometimes when you hear speech you don't know how a word is spelled; a good example is a person't email address, or a code you must write down. Using your arrow keys you can move line by line, word by word, or character by character.

That's all good if you have what many programmers call the caret or cursor, and some books call the insertion point. This is your editing cursor, that lets you read and alter text.

But sometimes the text you are reading has no cursor. Maybe it's information about the progress of an update, or you're trying to pair a device and need to read text onscreen. In this case, you use text review commands to navigate by line, word or character to explore text without need for a cursor to be available. As long as something has focus, you can use text review to examine it. This is similar to the JAWS invisible cursor.

But text review can only see the current control. If that control for example is the OK button in a dalog box, the only thing you'll be able to review is the letters O and K. But if the control is an informational message, such as the percentage of a Windows update download, you will be able to easily read it with text review.updat

Another use for text review is also great even when you do have a cursor. Suppose you are doing a search and replace. You type in your search phrase, tab to replace and now you want to verify your search entry was currect. You can tab back there of course, but you can also use text review to examine the text without loosing your position.

Or suppose you are filling out a form or taking a quiz. You are typing your answer, but need to review the entire question again. Text review comes in handy, because you can stay positioned in the edit field typing your answer while using text review to re-examine the question to which you are responding.

### Summary

Sighted users can type in one place while looking at another place onscreen. This makes them more efficient than screen reader users, who often need to arrow or tab to an item simply to read it. Text review gives us back some of that power, the ability to read text without moving our focus.

## Why learn object navigation

It seem really unnecessarily complex. But it allows you to use applications that won't accept the focus. It allows you to read all the available text on and off the screen that is currently in the giant Windows database regardless of where your focus or cursor is located.

For example, if you receive an error message but cannot understand it, object navigation will allow you to poke around Windows until you find it. Once the navigator object lands on that message, you can use text review commands to inspect it.

Remember, we said text review can only review the focused object, such as the OK button in a dialog box. But object review can navigate to other controls in that box, and then, you can use text review to explore them.

### Summary

Object navigation enables you to explore the Windows hierarchy and see what's there. It is a way to position a mouse to somewhere you need to click because an object cannot accept keyboard focus. A mastery of object navigation gives you the power to work with less accessible applications.

## Combining Object Navigation and Text Review

Once you navigate to an object, you will want to use text review to see what's there. For example if you navigate from a window down to its dialog box, down to a list box, and further down to a list item, you will now want to read that list item word by word or character by character if you didn't understand speech fully when you landed the navigator object on the list item. That's another great use for text review.

## Keystrokes and yet more keystrokes

To move the navigator object, a plethora of keystrokes exists. To use text review, whether you are examining something that has the Windows focus or the navigator object focus, there are yet more keystrokes.

Master a handful at a time. For example, focus simply on text review and use it on a familiar document so you get the hang of how it works. 

(You have also received a current copy of the NVDA keystroke list)

One good place to try object navigation is the Windows Settings application. Explore different settings first with your tab and arrow keys. Then try object navigation. Once you can comfortably move around the hierarchy, use text review to explore what the navigator object lands on.

To explore reading dialog boxes try these ideas:

- Hit the Windows key to get the search box, type Winver and press Enter. You will encounter the "About Windows" dialog box. Use object navigation and text review to explore this box. Note that you cannot tab around it to rread everything with your arrow keys.
- Hold the Windows key while pressing R to get a Run command. In the edit box that appers, type some nonsense, a gibberish bunch of letters is good. Press Enter. An error message appers. Explore it with object navigation and text review.
- Do you have a favorite program with controls you cannot readily access? Try your newly-found object navigation skills to explore it
  






