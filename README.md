ZSearcher
=========

<p>
Window Searcher and organizer. This application allows users to filter windows with a specified title or process name and bring it to the foreground. It cannot search against title and process name, only one. This filter supports regex and is not case sensitive.
<br>
At launch time, the application automatically hides itself to avoid messing up the ALT+TAB workflow.
</p>

<p>
Example:<br>
  Windows open (text within parenthesis is the process name is not part of the window title) :<br>
    GitHub (chrome.exe)<br>
    GitHub - Firefox (firefox.exe)<br>
  <br>
  Filter: chrome<br>
  Resulting filtered windows: GitHub (chrome.exe)<br>
  <br>
  Filter: github<br>
  Resulting filtered windows: GitHub (chrome.exe)<br>
                              GitHub - Firefox (firefox.exe)<br>
  <br>
  Filter: github.*firefox<br>
  Resulting filtered windows: GitHub - Firefox (firefox.exe)
</p> 

<table>
  <tr>
    <th colspan="2">Shortcut keys:</th>
  </tr>
  <tr>
    <td>ALT + `</td>
    <td>Displays application and brings it to the foreground.</td>
  </tr>
  <tr>
    <td>ALT + ~</td>
    <td>Displays application and brings it to the foreground, but with the filter cleared and current window selected in the application.</td>
  </tr>
  <tr>
    <td>ALT + ~</td>
    <td>Displays application and brings it to the foreground,</td>
  </tr>
  <tr>
    <td colspan="2">The following require the application to be open and in the foreground:</td>
  </tr>
  <tr>
    <td>ENTER</td>
    <td>Bring selected window to the foreground and activate it</td>
  </tr>
  <tr>
    <td>[SHIFT] + TAB</td>
    <td>Cycle through and select previous/next window in the list</td>
  </tr>
  <tr>
    <td>CTRL + Q</td>
    <td>Resize window to fill top left quarter of the screen</td>
  </tr>
  <tr>
    <td>CTRL + W</td>
    <td>Resize window to fill top half of the screen</td>
  </tr>
  <tr>
    <td>CTRL + E</td>
    <td>Resize window to fill top right quarter of the screen</td>
  </tr>
  <tr>
    <td>CTRL + A</td>
    <td>Resize window to fill left half of the screen</td>
  </tr>
  <tr>
    <td>CTRL + S</td>
    <td>Resize window to fill the whole screen</td>
  </tr>
  <tr>
    <td>CTRL + D</td>
    <td>Resize window to fill right half of the screen</td>
  </tr>
  <tr>
    <td>CTRL + Z</td>
    <td>Resize window to fill bottom left quarter of the screen</td>
  </tr>
  <tr>
    <td>CTRL + X</td>
    <td>Resize window to fill bottom half of the screen</td>
  </tr>
  <tr>
    <td>CTRL + C</td>
    <td>Resize window to fill bottom right quarter of the screen</td>
  </tr>
  <tr>
    <td>CTRL + 1</td>
    <td>Move window to monitor 1</td>
  </tr>
  <tr>
    <td>CTRL + 2</td>
    <td>Move window to monitor 2</td>
  </tr>
  <tr>
    <td>CTRL + 3</td>
    <td>Move window to monitor 3</td>
  </tr>
</table>
