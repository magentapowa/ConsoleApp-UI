ConsoleApp UI

Example images from the [SofaSoup](https://github.com/magentapowa/SofaSoup) project.

```
public bool AreYouSure( string message = "Are you sure you want to proceed?",string breadcrumb="",int defaultOpption=1)
```
![](https://github.com/magentapowa/ConsoleApp-UI/blob/master/imgs/Screen%20Shot%202018-06-10%20at%2015.15.05.png)

```
public int Menu<T>(List<T> menu, int menuIndex, bool isHorizontal, bool hasEscape, string breadcrumb = "", string text = "")
```
![](https://github.com/magentapowa/ConsoleApp-UI/blob/master/imgs/Screen%20Shot%202018-06-10%20at%2015.14.20.png)
![](https://github.com/magentapowa/ConsoleApp-UI/blob/master/imgs/Screen%20Shot%202018-06-10%20at%2015.14.30.png)

```
public int SubMenu<T>(List<string> submenu, int subIndex, List<T> basemenu, int baseIndex, string breadcrumb = "", string text="") //
```
![](https://github.com/magentapowa/ConsoleApp-UI/blob/master/imgs/Screen%20Shot%202018-06-10%20at%2015.14.34.png)

```
public int SubList<T>(List<T> list, int listIndex,bool hasHeaders,  List<string> basemenu, int baseIndex, bool isNavigable,string breadcrumb = "",string message= "")
```
![](https://github.com/magentapowa/ConsoleApp-UI/blob/master/imgs/Screen%20Shot%202018-06-10%20at%2015.31.44.png)
![](https://github.com/magentapowa/ConsoleApp-UI/blob/master/imgs/Screen%20Shot%202018-06-1)

```
public int SubMenuFromSubList<T>(List<string> submenu, int subIndex, List<T> list, int listIndex, List<string> basemenu, int baseIndex, string breadcrumb="",string text="")
```
![](https://github.com/magentapowa/ConsoleApp-UI/blob/master/imgs/Screen%20Shot%202018-06-10%20at%2015.14.48.png)