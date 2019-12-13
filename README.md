# fab_menu_items

This is Fluter Fab Menu Items........




![Pub](https://img.shields.io/pub/v/fab_menu_items?style=flat-square)



# fab_menu_items


----

This is Fluter Fab Menu Items........

## Example code

```dart

import 'package:fab_menu_items/fab_menu_items.dart';
import 'package:flutter/material.dart';


class Mainapp extends StatefulWidget {
  @override
  _MainappState createState() => _MainappState();
}

class _MainappState extends State<Mainapp> {
  @override
  Widget build(BuildContext context) {
    return Stack(
      children: <Widget>[
        Scaffold(
          body: Container(
            child: Center(
              child: Text('Fab Menu Items'),
            ),
          ),
        ),
        Fabmenuitems(
          height: 310,
          weith: 150,
          animatedIcons: AnimatedIcons.menu_close,
          fabcolor: Colors.black,
          containercolor: Colors.white,
          childrens: <Widget>[
            Container(
              padding: EdgeInsets.only(left: 10,right: 10,top: 10,bottom: 2),
              alignment: Alignment.centerLeft,
              child: Row(
                children: <Widget>[
                  Icon(Icons.bubble_chart,size: 24,color: Colors.indigo,),
                  SizedBox(width: 10,),
                  Expanded(child: Text("Dummy two",style: TextStyle(
                      color: Colors.black54,fontSize: 14,fontWeight: FontWeight.w500
                  ),))
                ],
              ),
            ),
            Divider(),

            Container(
              padding: EdgeInsets.only(left: 10,right: 10,top: 2,bottom: 2),
              alignment: Alignment.centerLeft,
              child: Row(
                children: <Widget>[
                  Icon(Icons.bubble_chart,size: 24,color: Colors.indigo,),
                  SizedBox(width: 10,),
                  Expanded(child: Text("Dummy two",style: TextStyle(
                      color: Colors.black54,fontSize: 14,fontWeight: FontWeight.w500
                  ),))
                ],
              ),
            ),
            Divider(),

            Container(
              padding: EdgeInsets.only(left: 10,right: 10,top: 2,bottom: 2),
              alignment: Alignment.centerLeft,
              child: Row(
                children: <Widget>[
                  Icon(Icons.bubble_chart,size: 24,color: Colors.indigo,),
                  SizedBox(width: 10,),
                  Expanded(child: Text("Dummy two",style: TextStyle(
                      color: Colors.black54,fontSize: 14,fontWeight: FontWeight.w500
                  ),))
                ],
              ),
            ),
            Divider(),

            Container(
              padding: EdgeInsets.only(left: 10,right: 10,top: 2,bottom: 2),
              alignment: Alignment.centerLeft,
              child: Row(
                children: <Widget>[
                  Icon(Icons.bubble_chart,size: 24,color: Colors.indigo,),
                  SizedBox(width: 10,),
                  Expanded(child: Text("Dummy two",style: TextStyle(
                      color: Colors.black54,fontSize: 14,fontWeight: FontWeight.w500
                  ),))
                ],
              ),
            ),
            Divider(),

            Container(
              padding: EdgeInsets.only(left: 10,right: 10,top: 2,bottom: 2),
              alignment: Alignment.centerLeft,
              child: Row(
                children: <Widget>[
                  Icon(Icons.bubble_chart,size: 24,color: Colors.indigo,),
                  SizedBox(width: 10,),
                  Expanded(child: Text("Dummy two",style: TextStyle(
                      color: Colors.black54,fontSize: 14,fontWeight: FontWeight.w500
                  ),))
                ],
              ),
            ),
            Divider(),

            Container(
              padding: EdgeInsets.only(left: 10,right: 10,top: 2,bottom: 2),
              alignment: Alignment.centerLeft,
              child: Row(
                children: <Widget>[
                  Icon(Icons.bubble_chart,size: 24,color: Colors.indigo,),
                  SizedBox(width: 10,),
                  Expanded(child: Text("Dummy two",style: TextStyle(
                      color: Colors.black54,fontSize: 14,fontWeight: FontWeight.w500
                  ),))
                ],
              ),
            ),
            Divider(),

            Container(
              padding: EdgeInsets.only(left: 10,right: 10,top: 2,bottom: 2),
              alignment: Alignment.centerLeft,
              child: Row(
                children: <Widget>[
                  Icon(Icons.bubble_chart,size: 24,color: Colors.indigo,),
                  SizedBox(width: 10,),
                  Expanded(child: Text("Dummy two",style: TextStyle(
                      color: Colors.black54,fontSize: 14,fontWeight: FontWeight.w500
                  ),))
                ],
              ),
            ),
            Divider(),

            Container(
              padding: EdgeInsets.only(left: 10,right: 10,top: 2,bottom: 2),
              alignment: Alignment.centerLeft,
              child: Row(
                children: <Widget>[
                  Icon(Icons.bubble_chart,size: 24,color: Colors.indigo,),
                  SizedBox(width: 10,),
                  Expanded(child: Text("Dummy two",style: TextStyle(
                      color: Colors.black54,fontSize: 14,fontWeight: FontWeight.w500
                  ),))
                ],
              ),
            ),
            Divider(),




          ],
        )

      ],
    );
  }
}


```






#Demo

![](https://raw.githubusercontent.com/asif4483/fab_menu_items/master/fabmenuitems.gif)
