## 1.an H2 sized header

#### 2.an H4 sized header

3.a link to an external web site:[吉林大学在线学堂](http://jlu.fy.chaoxing.com/portal)

4.a link between markdown pages. Link from README.md to the second markdown file and from the second markdown file back to the README.md:[LinkToAnotherMarkdown](AnotherMarkdown.md)

5.an image that is a file in the directory:
![ImageofHuangMountain](https://github.com/RosieChurchill/Homework1/blob/main/ImageOfHuangMountain.jpg)

6.an image that is located on the web (not a file in the directory). If you right-click on an image in a web browser there is an option in the pop up to get the address/URL to the image:
![ImageOfPicture](https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fup.enterdesk.com%2Fedpic_source%2F9e%2F73%2F69%2F9e7369d71ba4baf4b43e9aeda82e9bf3.jpg&refer=http%3A%2F%2Fup.enterdesk.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1651210517&t=bb07f880b4f1a5097f96754c667276f7)

7.a code block with syntax highlighting for the programming language being used. Put some example code in the code block. I don't care what code. Note that those three ticks that define a code block are backticks not apostrophes:
```javascript
public void display(){
        ListNode node = head;
        while (node!=null){
            if (node.next==null){
                System.out.print(node.data );
                node = node.next;
            }else{
                System.out.print(node.data + "->");
                node = node.next;
            }
        }
    }
```
> 8.a block quote

9.a bulleted list:
* first
* second
* third

10.a numbered list:
- first
- second
- third

11.a table:
| Number | Item   |
| ------ | ------ |
| 1      | pencil |
| 2      | eraser |

12.**bolded text**

13.*italicized text*

14.~~strikethrough text~~

15.horizontal rule:
***	
