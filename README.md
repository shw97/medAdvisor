# medAdvisor
CSS Changes for the exercise
## Task 1:
Change the style such that when user scrolls down to view more content (rows), the header row is still visible.
<br><br>
## Solution:
- Add a vertical scrollbar (overflow-y).
- Set the position attribute of header of table to sticky (Sticks to the position).
## Snapshot:
-  Add vertical scrollbar:
![Image of table](https://github.com/shw97/medAdvisor/blob/master/Table%20with%20vertical%20scroll.png)
- Snapshot after scrolling vertically (Header remains fixed(sticks))
![Image of table](https://github.com/shw97/medAdvisor/blob/master/Table%20after%20vertical%20scroll.png)
## Task 2:
Change the style such that when user scrolls to view more content to the right, the first two columns remain fixed in their position.
## Solution:
- Set the position attribute of first and second column (nth-child: n=1,2) of table to sticky (Sticks to the position).
- Set the z-index for smooth user experience (Optional).
## Snapshot:
- After scrolling horizontally

![Image of table](https://github.com/shw97/medAdvisor/blob/master/Table%20after%20horizontal%20scroll.png)
- Snapshot after scrolling horizontally (First two columns stick)

![Image of table](https://github.com/shw97/medAdvisor/blob/master/Table%20after%20horizontal%20scroll%202.png)

## Snapshot:
- Complete Result 
![Image of table](https://github.com/shw97/medAdvisor/blob/master/Table%20with%20vertical%20and%20horizontal%20scroll.png)
