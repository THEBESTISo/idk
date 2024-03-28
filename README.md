# idk
import 'package:flutter/material.dart';

void main() {
  runApp(HelloWorldApp());
}

class HelloWorldApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    var buildAppBar2 = buildAppBar();
    return MaterialApp(
      home: Scaffold(
        appBar: buildAppBar2,
        body: Center(
          child: Text('Hello World'),
        ),
      ),
    );
  }

  AppBar buildAppBar() {
    return AppBar(
      title: const Text('Hello World App'),
    );
  }
}
