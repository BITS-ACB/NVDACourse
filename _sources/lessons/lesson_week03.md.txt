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

### **Text Review**

Refers to commands for reviewing text without changing the position of the focus or cursor. These are NVDA commands that enable you to read by character, word or line.

### **Review Cursor**

An imaginary cursor or pointer that points to a particular character. By "imaginary" we mean that it is not part of Windows , but it is a way for NVDA to locate a particular point onscreen. Text review moves this pointer without changing where Windows knows the focus is located.

### **Object**

Everything in Windows is an object. A window, a control, a running program or a single character, all are objects. Windows itself is a giant database of objects and what appears onscreen is just the tip of that iceberg!

### ***Navigator Object***

Yet another "imaginary" pointer built in to NVDA. This marks a particular objectin Windows and it can move from one object to another.

### **Object hierarchy**

Objects are arranged with some containing other objects. This branching "tree-structure" is called a hierarchy. For example a dialog box is an object, it is inside a window, which itself is an object. Inside the dialog box you might find a list. That list is of course an object. And inside that list you would find items, Each item is an object. When voiceover users on the mac "interact" with a control, they are also moving down the branch of an object hierarchy.

### **Parent-Child Objects**

This refers to where an object is positioned in the hierarchy. For example a list item is a child object and its parent object is the actual list. The list too is a child object; its parent object is the dialog box containing the list. The dialog box is a child object to the window containing that box. The window is the parent object to the dialog box. NVDA calls the parent object the "containing object" but most Windows developers use the parent-child terminology.

### **Review Modes**

NVDA has three separate review modes; that is three different modes where text review is available. You are always using one of these modes, and the review cursor is tethered to what is appropriate in that mode. The three modes are:

- Screen Review
- Object Review
- Document review

Screen review is just like it sounds. It lets you examine all text that NVDA can see on your visible screen. Often, text is there that NVDA cannot see.

Object review is also just like it sounds. It lets you move the "navigator object" around the hierarchy so you can navigate even outside the visible screen.

As you move from one Windows object to another, your text review commands operate only on the object the navigator object is pointing to. For example, if you navigate to a dialog box, navigate inside it to a list, navigate inside the list to a single item in that list, then use text review, you are only able to read the text of that single list item.

Document review works only when you are in what NVDA calls a "browse mode" object, what JAWS calls a virtual cursor. You normally can only use the document review mode in a word processor, usually Word, or HTML pages such as a message in Outlook or a web page in your browser. There are exceptions, however. Many applications that use HTML will put you in a web-like interface that NVDA can navigate with document review.

NVDA has keystrokes to go to the "next" or previous mode and that next and previous depend on what review mode is currently available. For example, if you aren't on a web page you only have screen review and object review available.

### **tethering**

Refers to the concept of keeping one pointer or cursor at the same position as another cursor. For eexample, the navigator object can be tethered to the focus and usually is, but when you use object navigation, you are moving away from the focus. The review cursor is also usually tether to the focus, but when you use screen review, it also moves around. The same is true for text review.

## What is text review good for?

Sometimes when you hear speech you don't know how a word is spelled; a good example is a person's email address, or a code you must write down. Using your arrow keys you can move line by line, word by word, or character by character.

That's all good if you have what many programmers call the caret or cursor, and some books call the insertion point. This is your editing cursor, that lets you read and alter text.

But sometimes the text you are reading has no cursor. Maybe it's information about the progress of an update, or you're trying to pair a device and need to read text onscreen. In this case, you use text review commands to navigate by line, word or character to explore text without need for a cursor to be available. As long as something has focus, you can use text review to examine it. This is similar to the JAWS keystrokes that let you read by line, word or character.

But text review can only see the current control. If that control for example is the OK button in a dialog box, the only thing you'll be able to review is the letters O and K. But if the control is an informational message, such as the information from Windows update, you will be able to easily read it with text review. and if you are in the screen review mode, text review can often navigate more text.

Another use for text review is also great even when you do have a cursor. Suppose you are doing a search and replace. You type in your search phrase, tab to replace and now you want to verify your search entry was currect. You can tab back there of course, but you can also use text review to examine the text without loosing your position.

Or suppose you are filling out a form or taking a quiz. You are typing your answer, but need to review the entire question again. Text review comes in handy, because you can stay positioned in the edit field typing your answer while using text review to re-examine the question to which you are responding.

## What is object review good for?

Object review, though complex is very powerful. It lets you navigate the entire database of what NVDA can see, not just what's at your current focus or what's currently onscreen. Not only can you move the navigator object outside your currently focused application, you can also take it somewhere, move the mouse there and issue a click. This gives you the ability to click on something NVDA can see but that you cannot reach with the keyboard.

### Summary

Sighted users can type in one place while looking at another place onscreen. This makes them more efficient than screen reader users, who often need to arrow or tab to an item simply to read it. Text review gives us back some of that power, the ability to read text without moving our focus.

## Concept Summary

A cursor is a visual pointer that often blinks that points to a single character, for example in a word processor or edit box on a web page. The cursor can be called a caret or an insertion point; those terms are synonyms.

The "focus" or "system focus" is where Windows thinks you are located. If there's a cursor, then that's also where the system focus is. But if you are tabbing or arrowing around where no cursor exists, there is still a "system focus" where you are located. If a mouse user clicks something, they have moved the system focus to that something. If you hear the term "keyboard focus" it indicates that you arrived there with a keystroke and not the click of a mouse.

Text review is usually tethered to the system focus unless you move it away with NVDA commands.

The term "navigator object" is specific to NVDA. It is an NVDA concept only. It is where NVDA is pointing to in the object hierarchy. The navigator object is usually tethered with the system focus, unless you use object navigation to move it elsewhere.

## Compare with JAWS

If you use JAWS, you may know it has five cursors labeled PC, JAWS, Invisible, Virtual and Touch.  NVDA is not really any different except because it was developed by geeks, its concepts can appear more complicated.

The JAWS PC cursor is the same thing as what NVDA calls the focus or the caret or the cursor or the insertion point. When you edit text, there's actually a cursor onscreen, and because it can look like a circumflex, it is often called the caret. But books on Microsoft Office also call the same thing the insertion point. JAWS calls it the PC cursor and NVDA the focus.

If you are not editing text, but you can navigate to a control using either the keyboard or the mouse, that control is considered to have "gained focus" and visually a dotted outline surrounds the control.  JAWS also refers to this as the PC cursor, and NVDA the focus.

When you use the JAWS keystrokes to move to the next or previous line, word or character, you are using the equivalent of the NVDA text review. That is, the focus or editing cursor is not moving, JAWS is pointing to somewhere else to allow you to read the previous or next line, word or character without needing to change your actual cursor position or focus.

When you are in NVDA's browse mode, it is the same as the JAWS virtual cursor. When you are in NVDA's focus mode, it's the same as
the JAWS forms mode.

NVDA's review mode cursor is like the JAWS invisible cursor,  and if you use either you will notice they oftenn cannot find everything on screen. This is because proper Windows techniques are not always used when building a Windows application. But usually what the invisible cursor can see is also what the NVDA review mode can see. Both of these only see what is written to the screen.

NVDA's navigator object actually goes beyond this, enabling you to explore the entire database of Windows objects, often called an off-screen model. You only use object navigation if you need to; many users function quite fine without knowing how it works.

JAWS actually also has object navigation, but it's considered an advanced topic. Read more about it under the JAWS help in the section titled Using the Touch Cursor, under the last heading "Advanced navigation".

## Why learn object navigation

It seem really unnecessarily complex. But it allows you to use applications that won't accept the focus. It allows you to read all the available text on and off the screen that is currently in the giant Windows database regardless of where your focus or cursor is located.

For example, if you receive an error message but cannot understand it, object navigation will allow you to poke around Windows until you find it. Once the navigator object lands on that message, you can use text review commands to inspect it.

Remember, we said text review can only review the focused object, such as the OK button in a dialog box. But object review can navigate to other controls in that box, and then, you can use text review to explore them.

Object navigation can be extremely helpful when working with the ribbon in File explorer and Office products. It's also great for working with Windows settings. Try using it also with Windows store apps; those that were designed with accessibility in mind  can be even more accessible with object navigation.

## In Summary

Object navigation enables you to explore the Windows hierarchy and see what's there. It is a way to position a mouse to somewhere you need to click when an object cannot accept keyboard focus. A mastery of object navigation gives you the power to work with less accessible applications.

## Combining Object Navigation and Text Review

Once you navigate to an object, you will want to use text review to see what's there. For example if you navigate from a window down to its dialog box, down to a list box, and further down to a list item, you will now want to read that list item word by word or character by character if you didn't understand speech fully when you landed the navigator object on the list item. That's another great use for text review.

## Keystrokes and yet more keystrokes

To move the navigator object, a plethora of keystrokes exists. To use text review, whether you are examining something that has the Windows focus or the navigator object focus, there are yet more keystrokes.

Master a handful at a time. For example, focus simply on text review and use it on a familiar document so you get the hang of how it works. A list of most common keystrokes both for text review and object navigation is given below with explanations of how they work.

(You have also received a current copy of the NVDA keystroke list)

One good place to try object navigation is the Windows Settings application. Explore different settings first with your tab and arrow keys. Then try object navigation. Once you can comfortably move around the hierarchy, use text review to explore what the navigator object lands on.

To explore reading dialog boxes try these ideas:

- Hit the Windows key to get the search box, type Winver and press Enter. You will encounter the "About Windows" dialog box. Use object navigation and text review to explore this box. Note that you cannot tab around it to rread everything with your arrow keys.
- Hold the Windows key while pressing R to get a Run command. In the edit box that appears, type some nonsense, a gibberish bunch of letters is good. Press Enter. An error message appears. Explore it with object navigation and text review.
- Do you have a favorite program with controls you cannot readily access? Try your newly-found object navigation skills to explore it.

## Putting It All together

Don't worry if you are completely confused. This is one feature set you use when you need it. For example, your boss is requiring you use an application that doesn't seen to be very keyboard accessible. Or you need to carefully review some messages a program is sending. In general, you would:

1. Toggle to the appropriate review mode.
2. If in object review, first use object navigation to get to the object with the text you need to read. If you are in an HTML document, this isn't necessary and it's also not necessary if you are trying to just review the screen.
3. Use text review to go to the "top of the text that the review cursor can navigate.
4. Review line by line or word by word, depending on how much text is there.
5. Review by character if you get to a word whose spelling you need or that you didn't understand.

## Most useful keystrokes

You can find all keystrokes in the NVDA Key commands document.

### Text Review with a Desktop keyboard

Note: all these use the numeric keypad. Notice the pattern that helps you master these keystrokes.

- Go to previous line of text. -- Seven
- Go to next line of text. -- Nine
- Go to previous word. -- Four
- Go to next word. -- Six
- Go to previous character. -- One
- Go to next character. -- Three.
- Read current line. -- Eight
- Read current word. -- Five
- Read Current character. -- Two

Notice that 9 8 and 7 handle lines, 4 5 and 6 handle words and 1 2 and 3 handle characters, with everything going from left to right, previous, current and next.

Now,  notice what happens when you add the shift keys with the numbers on your numeric keypad.

- Go to top line. -- Shift with seven
- Go to bottom line. -- Shift with nine
- Go to beginning of line. -- Shift and One
- Go to end of line. -- Shift and Three.

So for example if you wanted to read the next line, you'd press the 9. For the next word, it's the 6. But if you wanted to go to the end of that line,you'd hold the shift and press the Three. If you wanted to move to a previous line, you'd use the seven key. For the previous word, it's the 4. But if you wanted to return back to the start of the line, you'd hole the shift and the 1 key.  To return to the beginning of text, it's the shift and the 7 key and to the end of the text, it's the shift and the 9 key.

Note too that the shift with the numeric keypad 4 and 6 are not defined. You can use the input gestures feature to assign them to a regularly used navigation command.

This pattern makes more sense when you practice it, so load up a document in Word or notepad and fool around with text review.

If you will frequently use text review on a laptop you can always purchase a small numeric keypad that connects via USB or a full-sized desktop keyboard.

The advantage of the desktop mode is that the pattern is easier to remember.

But the laptop mode is not too far off: it also has a pattern. However since you don't have a separate numeric keypad, you have to use the NVDA key together with familiar keys.

- Go to previous line. -- NVDA+Up Arrow
- Go to next line. -- NVDA+Down arrow
- Go to previous word. -- NVDA+Control+Left arrow
- Go to next word. -- NVDA+Control+Right arrow

Note that if you are moving the system cursor up and down you are using the up and down arrow keys to read by lines. But if you are reviewing text without moving the system cursor, you use the NVDA key with up and down arrow to review by lines.

And if you are moving the system cursor by words, it's the control with the left and right arrows that you are using. But if you are reviewing by words without moving the system cursor, then you are holding the NVDA key together with the control and a left or right arrow key.

The same patternn continues for moving the review cursor to the start or end of a line.

- Go to start of line. -- NVDA+Home
- Go to end of line. -- NVDA+End.

You use Home and end to move the system cursor to the start or end of a line. You hold the NVDA key with home or end to move the review cursor to the start or end of a line.

Moving by characters in laptop mode continues with this pattern.

- Go to previous character. -- NVDA+Left arrow
- Go to next character. -- NVDA+right arrow

The left and right arrows by themselves move the system cursor whereas these arrow keys when pressed while holding the NVDA key move the review cursor to the next or previous character.

Remember, in laptop mode, the NVDA key is the caps lock key.

To read the current item in laptop mode the pattern breaks a bit. it uses the period key with the NVDA key.

- Read the current line under the review cursor. -- NVDA+Shift+Period
- Read the current word under the review cursor. -- NVDA+Control+Period
- Read the current character under the review cursor. -- NVDA+Period

Remember too we are dealing with the review cursor here. If you are reading the current line that the system cursor is positioned on, the keystroke is NVDA+L. If text review is tethered to the system focus, then you will hear the same thing with NVDA+Shift+Period.

### Object Navigation with a Desktop Keyboard

This is a very easy pattern to follow:

- Previous object. --NVDA+Four
- Next object. -- NVDA+Six
- Parent object. -- NVDA+Eight
- First child object -- NVDA+2

Think of this as a three-dimensional structure. If you hold the NvDA key and keep ressing the numeric keypad 8 you are going up in the hierarchy to the object containing all objects. If you hold the NVDA key and press the numeric keypad 2, you are moving down to the first child object, then down to its first child object, etc. "Turtles all the way down!"

If you press the NVDA key with the numberic keypad 4, you are moving in the same level of the hierarchy to the first object, and you are likely already there if you got there with the 2 key previously. But if you hold the NVDA key with the numeric keypad 6, you are also moving on the same level, right to the next object on that level.

A good place to explore this is by loading up an application with dialog boxes, such as settings in an app or preferences or configuration. The office ribbon also is good for object navigation. Notice its usefulness within a ribbon or menu structure.

Moving from right to left on most desktop keyboards you have the minus key, the star or multiply key and the slash or divide key. The fourth key from the right is the numeric lock. If that is on then the number pad reverts to its normal usage, but when it is off, the NVDA navigation keys are active.

If you press the Divide key, the third one from the right, it will click the left mouse button. If you hold the NVDA key and press the divide key, you can move the mouse pointer to the location of the navigator object. This is useful if you need to click on a control where you cannot get keyboard focus to work. So you'd first navigate there with object navigation. Then you'd hold the insert key which is the NVDA key and press the numeric keypad divide. Next you'd press the numeric keypad divide by itself to actually click on that control.

### Laptop Mode Object Navigation

- Previous Object. -- NVDA+Shift+Left arrow
- Next object. -- NVDA+Shift+Right arrow
- Parent Object -- NVDA+Shift+Up arrow
- First Child Object. -- NVDA+Shift+Down
-
- This is the same pattern as screen review except that objects can contain objects; A parent object may itself have a parent. A child object always has a parent object but it can also have siblings, that is multiple child objects you navigate left and right with the NVDA- Shift and right or left arrow keys. Remember in laptop mode the NVDA key is the caps lock key.

If you want to toggle between the three review modes, load up a web page. Then explore using document review, object review, and screen review.

## Homework Ideas

Prepare a presentation on something that interest you or try one of these ideas:

- How do you use the review cursor to copy text to the clipboard to paste in to another application. How for example would you email your Windows version to tech support?
- Demonstrate how you can use object navigation to click the mouse on a control you cannot access from the keyboard.
- Describe the patterns inherent in text review and object navigation keystrokes. How do these patterns help you memorize the keystrokes you need?  - Show how to read information in Windows update under settings.
- Use text and object review to explore what wi-fi networks are available.
- Use object navigation to explore the ribbon in any Microsoft Office product or in File explorer.
- Explain how to route the review cursor or navigator object to the focus so you can return to your starting point.

