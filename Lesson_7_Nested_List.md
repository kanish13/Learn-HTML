Nested Lists:

A nested list in HTML is a list within a list. Nested lists in HTML are quite useful and are frequently used as the foundation for navigation menus since they determine the website's hierarchical structure. You can make a nested unordered list, a nested ordered list, or even an ordered list nested inside an unordered list.

CHALLENGE:

To achieve:
 ![image](https://user-images.githubusercontent.com/111358462/233427306-7b72cfbc-98e1-43bb-b4ac-abbb7642d99c.png)

 
Solution:

    <ul>
        <li>A</li>
        <li>B

        <ol>
            <li>B1</li>
            <li>B2
            <ul>
                <li>B2a</li>
                <li>
                    <ul>
                        <li>B2aa</li>
                        <li>B2ab</li>
                    </ul>
                </li>
                <li>B2b</li>
                <li>B2c</li>
            </ul></li>
            <li>B3
            <ol>
                <li>B31</li>
                <li>B32</li>
            </ol></li>
        </ol></li>

        <li>C</li>
    </ul>

