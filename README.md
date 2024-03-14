import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text('Row with Centered Buttons'),
        ),
        body: Center(
          child: Row(
            mainAxisAlignment: MainAxisAlignment.center,
            children: <Widget>[
              ElevatedButton(
                onPressed: () {
                },
                child: Text('Button 1'),
              ),
              ElevatedButton(
                onPressed: () {   
                },
                child: Text('Button 2'),
              ),
              ElevatedButton(
                onPressed: () {
                },
                child: Text('Button 3'),
              ),
            ],
          ),
        ),
      ),
    );
  }
}
