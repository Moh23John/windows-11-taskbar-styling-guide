# Bubbles theme (White Accents, Minimalistic) for Windows 11 Taskbar Styler

This is a modified version of the original Bubbles theme, originally made by [m417z](https://github.com/m417z). Modified by [Moh23John](https://github.com/Moh23John).
I have made a few changes, with the main focus of changing the accents to white. The theme is meant for certain taskbar settings. The code for these parts that aren't meant to be used with this theme, have been excluded. I have given a screenshot of taskbar settings to copy down below. I have also included a JSONC file, which has comments which tell you what (almost) each line of code does. This helps you customize the taskbar if you like, and you can also use the information from the JSONC here to customize the original Bubbles theme. 

## Installation

* Open the Windows 11 Taskbar Styler mod in Windhawk.
* Go to the "Advanced" tab.
* Copy the content below to the text box under "Mod settings" and click "Save".

## Screenshots (Taskbar Settings)

![Screenshot](Screenshot1.png)
![Screenshot](Screenshot2.png)
## Screenshots (Preview)
![Screenshot](Screenshot3.png)
![Screenshot](Screenshot4.png)
![Screenshot](Screenshot5.png)
![Screenshot](Screenshot6.png)
<details>
<summary>Content to import (click to expand)</summary>

```json
{
  "controlStyles[0].target": "Rectangle#BackgroundFill",
  "controlStyles[0].styles[0]": "Fill=#1b1b19",
  "controlStyles[1].target": "Taskbar.TaskListLabeledButtonPanel@RunningIndicatorStates > Border#BackgroundElement",
  "controlStyles[1].styles[0]": "Background=#303030",
  "controlStyles[1].styles[1]": "CornerRadius=20",
  "controlStyles[1].styles[2]": "Background@NoRunningIndicator=#40303030",
  "controlStyles[2].target": "Taskbar.TaskListButtonPanel@CommonStates > Border#BackgroundElement",
  "controlStyles[2].styles[0]": "Background=#303030",
  "controlStyles[2].styles[1]": "CornerRadius=20",
  "controlStyles[2].styles[2]": "Background@ActivePointerOver=#242424",
  "controlStyles[2].styles[3]": "Background@InactivePointerOver=#242424",
  "controlStyles[2].styles[4]": "Background@ActivePressed=#181818",
  "controlStyles[2].styles[5]": "Background@InactivePressed=#181818",
  "controlStyles[3].target": "Grid#SystemTrayFrameGrid",
  "controlStyles[3].styles[0]": "Background=#303030",
  "controlStyles[3].styles[1]": "CornerRadius=20",
  "controlStyles[3].styles[2]": "Margin=0,5,4,5",
  "controlStyles[3].styles[3]": "Padding=10,0,0,0",
  "controlStyles[4].target": "Taskbar.TaskListLabeledButtonPanel@CommonStates > Rectangle#RunningIndicator",
  "controlStyles[4].styles[0]": "Width=40",
  "controlStyles[4].styles[1]": "Height=40",
  "controlStyles[4].styles[2]": "Stroke@InactivePointerOver=#CCCCCC",
  "controlStyles[4].styles[3]": "Stroke@InactivePressed=#F0F0F0",
  "controlStyles[4].styles[4]": "Stroke@ActiveNormal=#B0B0B0",
  "controlStyles[4].styles[5]": "Stroke@ActivePointerOver=#D0D0D0",
  "controlStyles[4].styles[6]": "Stroke@ActivePressed=#F0F0F0",
  "controlStyles[4].styles[7]": "Fill=Transparent",
  "controlStyles[4].styles[8]": "RadiusX=20",
  "controlStyles[4].styles[9]": "RadiusY=20",
  "controlStyles[4].styles[10]": "StrokeThickness=3.5",
  "controlStyles[4].styles[11]": "Margin=0",
  "controlStyles[4].styles[12]": "Stroke@MultiWindowPointerOver=#CCCCCC",
  "controlStyles[4].styles[13]": "Stroke@MultiWindowPressed=#F0F0F0",
  "controlStyles[4].styles[14]": "Stroke@MultiWindowActive=#B0B0B0",
  "controlStyles[4].styles[15]": "Fill@MultiWindowNormal=#88AAAAAA",
  "controlStyles[4].styles[16]": "Fill@MultiWindowPointerOver=#88AAAAAA",
  "controlStyles[4].styles[17]": "Fill@MultiWindowActive=#88AAAAAA",
  "controlStyles[4].styles[18]": "Fill@MultiWindowPressed=#88AAAAAA",
  "controlStyles[5].target": "TextBlock#TimeInnerTextBlock",
  "controlStyles[5].styles[0]": "Foreground=White",
  "controlStyles[6].target": "TextBlock#DateInnerTextBlock",
  "controlStyles[6].styles[0]": "Foreground=White",
  "controlStyles[7].target": "SystemTray.TextIconContent > Grid > SystemTray.AdaptiveTextBlock#Base > TextBlock",
  "controlStyles[7].styles[0]": "Foreground=White",
  "controlStyles[12].target": "Grid#OverflowRootGrid > Border",
  "controlStyles[12].styles[0]": "Background=#E6E6E6CC",
  "controlStyles[12].styles[1]": "BorderBrush=#ee0808",
  "controlStyles[12].styles[2]": "BorderThickness=2.5",
  "controlStyles[13].target": "Taskbar.ExperienceToggleButton#LaunchListButton[AutomationProperties.AutomationId=StartButton] > Taskbar.TaskListButtonPanel > Microsoft.UI.Xaml.Controls.AnimatedVisualPlayer#Icon",
  "controlStyles[13].styles[0]": "Margin=1,0,0,0",
  "controlStyles[14].target": "SystemTray.Stack#ShowDesktopStack",
  "controlStyles[14].styles[0]": "Padding=5,0,5,0",
  "controlStyles[14].styles[1]": "Margin=2,0,10,0",
  "controlStyles[15].target": "Windows.UI.Xaml.Shapes.Rectangle#ShowDesktopPipe",
  "controlStyles[15].styles[0]": "MinWidth=4",
  "controlStyles[15].styles[1]": "RadiusX=2",
  "controlStyles[15].styles[2]": "RadiusY=2",
  "controlStyles[16].target": "SystemTray.Stack#NotifyIconStack > Windows.UI.Xaml.Controls.Grid > SystemTray.StackListView > Windows.UI.Xaml.Controls.ItemsPresenter > Windows.UI.Xaml.Controls.StackPanel > Windows.UI.Xaml.Controls.ContentPresenter > SystemTray.ChevronIconView > Windows.UI.Xaml.Controls.Grid > Windows.UI.Xaml.Controls.Border#BackgroundBorder",
  "controlStyles[16].styles[0]": "CornerRadius=16,5,5,16",
  "controlStyles[16].styles[1]": "Margin=-3,4,0,4"
}
```
</details>

<details>
<summary>JSONC File with helpful comments to edit the theme to your liking (Click to expand) </summary>
``` json
{
  "controlStyles[0].target": "Rectangle#BackgroundFill", // Taskbar background
  "controlStyles[0].styles[0]": "Fill=#1b1b19", // Color of the whole taskbar background
  "controlStyles[1].target": "Taskbar.TaskListLabeledButtonPanel@RunningIndicatorStates > Border#BackgroundElement", // These affect how the background of the icons look while they are running and not running
  "controlStyles[1].styles[0]": "Background=#303030", // Color that appears in the background of the icon when the program is running
  "controlStyles[1].styles[1]": "CornerRadius=20", // How rounded the corners of the icon's borders are. The lower, the more straight the edges are, resembling a rectangle.
  "controlStyles[1].styles[2]": "Background@NoRunningIndicator=#40303030", // Color that appears in the background of the icon when the program is not running
  "controlStyles[2].target": "Taskbar.TaskListButtonPanel@CommonStates > Border#BackgroundElement", //These effect icon's backgrounds when they are hovored over and also the windows icon's background
  "controlStyles[2].styles[0]": "Background=#303030", // Windows icon background color when not hovored over. "Background@...." dictates the background color of it when it is hovored over.
  "controlStyles[2].styles[1]": "CornerRadius=20", //  How rounded the corners of the icon's borders are. The lower, the more straight the edges are, resembling a rectangle.
  "controlStyles[2].styles[2]": "Background@ActivePointerOver=#242424", // Color of the icon when the mouse is hovering over it for a program currently on screen
  "controlStyles[2].styles[3]": "Background@InactivePointerOver=#242424", // Color of the icon when the mouse is hovering over it for a program running in the background
  "controlStyles[2].styles[4]": "Background@ActivePressed=#181818", // Color of the icon when the mouse is pressed for a program currently on screen
  "controlStyles[2].styles[5]": "Background@InactivePressed=#181818", // Color of the icon when the mouse is pressed for a program running in the background
  "controlStyles[3].target": "Grid#SystemTrayFrameGrid", // Changes how the right "System Tray" seperate layer on top of the taskbar looks.
  "controlStyles[3].styles[0]": "Background=#303030", // Background color for the layer.
  "controlStyles[3].styles[1]": "CornerRadius=20", // Roundness of the edges for the layer.
  "controlStyles[3].styles[2]": "Margin=0,5,4,5", // How many pixels away from the each direction the layer of the taskbar is located. The format is Left, Top, Right, Bottom. The left parameter does not matter. For example, The top parameter dictates how many pixels away from the taskbar's top the system tray layer is.
  "controlStyles[3].styles[3]": "Padding=10,0,0,0", // This dictates how many pixels away from the margin, or border the content inside of the system tray is. It also follows the format of Left, Top, Right, Bottom. 
  "controlStyles[4].target": "Taskbar.TaskListLabeledButtonPanel@CommonStates > Rectangle#RunningIndicator",
  "controlStyles[4].styles[0]": "Width=40",
  "controlStyles[4].styles[1]": "Height=40",
  "controlStyles[4].styles[2]": "Stroke@InactivePointerOver=#CCCCCC", // Color of the icon border when the mouse is hovering over it for a program running in the background
  "controlStyles[4].styles[3]": "Stroke@InactivePressed=#F0F0F0", // Color of the icon border when the mouse is pressed for a program running in the background
  "controlStyles[4].styles[4]": "Stroke@ActiveNormal=#B0B0B0", // Color of the icon border for a program currently on screen
  "controlStyles[4].styles[5]": "Stroke@ActivePointerOver=#D0D0D0", // Color of the icon border when the mouse is hovering over it for a program currently on screen
  "controlStyles[4].styles[6]": "Stroke@ActivePressed=#F0F0F0", // Color of the icon border when the mouse is pressed for a program currently on screen
  "controlStyles[4].styles[7]": "Fill=Transparent", // Fill color of the icon background when it is running.
  "controlStyles[4].styles[8]": "RadiusX=20", 
  "controlStyles[4].styles[9]": "RadiusY=20",
  "controlStyles[4].styles[10]": "StrokeThickness=3", // The width of the line along the border of the icon.
  "controlStyles[4].styles[11]": "Margin=0,0,0,0", // The distance between the border along the icon and all of the directions. Refer to line 18.
  "controlStyles[4].styles[12]": "Stroke@MultiWindowPointerOver=#CCCCCC", // Color of the icon border when the mouse is hovering over it for a program with multiple windows open
  "controlStyles[4].styles[13]": "Stroke@MultiWindowPressed=#F0F0F0", // Color of the icon border when the icon is clicked on for a program with multiple windows open
  "controlStyles[4].styles[14]": "Stroke@MultiWindowActive=#B0B0B0", // Color of the icon border for a program with multiple windows currently on screen
  "controlStyles[4].styles[15]": "Fill@MultiWindowNormal=#88AAAAAA", // Fill color of the icon background when multiple windows are open
  "controlStyles[4].styles[16]": "Fill@MultiWindowPointerOver=#88AAAAAA", // Fill color of the icon background when the mouse is hovering over it when multiple windows are open
  "controlStyles[4].styles[17]": "Fill@MultiWindowActive=#88AAAAAA", // Fill color of the icon background when the program is running and multiple windows are open
  "controlStyles[4].styles[18]": "Fill@MultiWindowPressed=#88AAAAAA", // Fill color of the icon background when the mouse is pressed on it when multiple windows are open
  "controlStyles[5].target": "TextBlock#TimeInnerTextBlock", // Color of the text for the time
  "controlStyles[5].styles[0]": "Foreground=White",
  "controlStyles[6].target": "TextBlock#DateInnerTextBlock", // Color of the text for the date
  "controlStyles[6].styles[0]": "Foreground=White",
  "controlStyles[7].target": "SystemTray.TextIconContent > Grid > SystemTray.AdaptiveTextBlock#Base > TextBlock", // Color for the system tray icons
  "controlStyles[7].styles[0]": "Foreground=White",
  "controlStyles[12].target": "Grid#OverflowRootGrid > Border",
  "controlStyles[12].styles[0]": "Background=#EE080810",
  "controlStyles[12].styles[1]": "BorderBrush=#303030",
  "controlStyles[12].styles[2]": "BorderThickness=2.5",
  "controlStyles[13].target": "Taskbar.ExperienceToggleButton#LaunchListButton[AutomationProperties.AutomationId=StartButton] > Taskbar.TaskListButtonPanel > Microsoft.UI.Xaml.Controls.AnimatedVisualPlayer#Icon",
  "controlStyles[13].styles[0]": "Margin=1,0,0,0",
  "controlStyles[14].target": "SystemTray.Stack#ShowDesktopStack",
  "controlStyles[14].styles[0]": "Padding=5,0,5,0",
  "controlStyles[14].styles[1]": "Margin=2,0,10,0",
  "controlStyles[15].target": "Windows.UI.Xaml.Shapes.Rectangle#ShowDesktopPipe",
  "controlStyles[15].styles[0]": "MinWidth=4",
  "controlStyles[15].styles[1]": "RadiusX=2",
  "controlStyles[15].styles[2]": "RadiusY=2",
  "controlStyles[16].target": "SystemTray.Stack#NotifyIconStack > Windows.UI.Xaml.Controls.Grid > SystemTray.StackListView > Windows.UI.Xaml.Controls.ItemsPresenter > Windows.UI.Xaml.Controls.StackPanel > Windows.UI.Xaml.Controls.ContentPresenter > SystemTray.ChevronIconView > Windows.UI.Xaml.Controls.Grid > Windows.UI.Xaml.Controls.Border#BackgroundBorder",
  "controlStyles[16].styles[0]": "CornerRadius=16,5,5,16",
  "controlStyles[16].styles[1]": "Margin=-3,4,0,4"
}
``` 
</details>