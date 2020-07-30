# Code blocks

In order to show some code, you can have to grap you code into three backticks ( ` ) and specify the language you are using like this examples.

## Hello world in some languages

```C++
#include stdio.h

int main(void)
{
    puts("Hello, world!");
}
```

```java
import javax.swing.JFrame;  //Importing class JFrame
import javax.swing.JLabel;  //Importing class JLabel
public class HelloWorld {
    public static void main(String[] args) {
        JFrame frame = new JFrame();           //Creating frame
        frame.setTitle("Hi!");                 //Setting title frame
        frame.add(new JLabel("Hello, world!"));//Adding text to frame
        frame.pack();                          //Setting size to smallest
        frame.setLocationRelativeTo(null);     //Centering frame
        frame.setVisible(true);                //Showing frame
    }
}
```

```js
document.write('Hello, world!');
```

```python
print "Hello, world!"
```

## Differences in code

You can use code blocks to show the differences in a commit or what have changed in function.

```diff
const myName = 'Alex';
- const myNickName = 'alexu';
+ const myNickName = 'sweetraare';
```

## Inline code

If you need to add inline code. You have to grap it in backticks. Like this.

I thing that you have to use `const myNickName = 'yesBoy'`
