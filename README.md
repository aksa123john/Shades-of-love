# Shades-of-love
import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  // This widget is the root of your application.
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Flutter Demo',
      theme: ThemeData(

        primarySwatch: Colors.blue,
      ),
      home: MyHomePage(title: 'Flutter Demo Home Page'),
    );
  }
}

class MyHomePage extends StatefulWidget {
  MyHomePage({Key? key, required this.title}) : super(key: key);

  // This widget is the home page of your application. It is stateful, meaning
  // that it has a State object (defined below) that contains fields that affect
  // how it looks.

  // This class is the configuration for the state. It holds the values (in this
  // case the title) provided by the parent (in this case the App widget) and
  // used by the build method of the State. Fields in a Widget subclass are
  // always marked "final".

  final String title;

  @override
  _MyHomePageState createState() => _MyHomePageState();
}

class _MyHomePageState extends State<MyHomePage> {
  int _counter = 0;

  void _incrementCounter() {
    setState(() {
      // This call to setState tells the Flutter framework that something has
      // changed in this State, which causes it to rerun the build method below
      // so that the display can reflect the updated values. If we changed
      // _counter without calling setState(), then the build method would not be
      // called again, and so nothing would appear to happen.
      _counter++;
    });
  }

  @override
  Widget build(BuildContext context) {
    // This method is rerun every time setState is called, for instance as done
    // by the _incrementCounter method above.
    //
    // The Flutter framework has been optimized to make rerunning build methods
    // fast, so that you can just rebuild anything that needs updating rather
    // than having to individually change instances of widgets.
    return Scaffold(
      appBar: AppBar(
        // Here we take the value from the MyHomePage object that was created by
        // the App.build method, and use it to set our appbar title.
        title: Text(widget.title),
      ),
      body: Center(
        // Center is a layout widget. It takes a single child and positions i
          // Figma Flutter Generator SignupandsigninWidget - FRAME
            child: Column(
              children: [
                Container(
                    width: 414,
                    height: 896,
                    decoration: BoxDecoration(
                      color : Color.fromRGBO(255, 255, 255, 1),
                    ),
                    child: Stack(
                        children: <Widget>[
                          Positioned(
                              top: 1.7496507167816162,
                              left: 415.7372741699219,
                              child: Transform.rotate(
                                angle: -90.22365153959882 * (math.pi / 180),
                                child: Container(
                                    width: 894.4439086914062,
                                    height: 415.1769104003906,
                                    decoration: BoxDecoration(
                                      image : DecorationImage(
                                          image: AssetImage('assets/images/Pridemonth1024x6821.png'),
                                          fit: BoxFit.fitWidth
                                      ),
                                    )
                                ),
                              )
                          ),Positioned(
                              top: 882,
                              left: 136,
                              child: Divider(
                                  color: Color.fromRGBO(230, 230, 230, 1),
                                  thickness: 5
                              )

                          ),Positioned(
                              top: 308,
                              left: 22.5,
                              child: Container(
                                width: 374,
                                height: 63,
                                decoration: BoxDecoration(
                                  color : Color.fromRGBO(255, 255, 255, 1),
                                ),
                                child: Stack(
                                    children: <Widget>[
                                    Positioned(
                                    top: 0,
                                    left: 0,
                                    child: SvgPicture.asset(
                                        'assets/images/vector.svg',
                                        semanticsLabel: 'vector'
                                    );
                                ),Positioned(
                                  top: 25,
                                  left: 11,
                                  child: Text('Username
                                  ', textAlign: TextAlign.left, style: TextStyle(
                                      color: Color.fromRGBO(0, 0, 0, 1),
                                  fontFamily: 'Roboto',
                                  fontSize: 16,
                                  letterSpacing: 0 /*percentages not used in flutter. defaulting to zero*/,
                                  fontWeight: FontWeight.normal,
                                  height: 1.5 /*PERCENT not supported*/
                              ),)
                          ),
                        ]
                    )
                )
        ),Positioned(
          top: 432,
          left: 22.5,
          child: Container(
                  width: 374,
                  height: 63,
                  decoration: BoxDecoration(
                    color : Color.fromRGBO(255, 255, 255, 1),
                  ),
                  child: Stack(
                      children: <Widget>[
                        Positioned(
                            top: 0,
                            left: 0,
                            child: SvgPicture.asset(
                                'assets/images/vector.svg',
                                semanticsLabel: 'vector'
                            );
                        ),Positioned(
                            top: 16,
                            left: 22,
                            child: Text('Password', textAlign: TextAlign.left, style: TextStyle(
                                color: Color.fromRGBO(0, 0, 0, 1),
                                fontFamily: 'Roboto',
                                fontSize: 16,
                                letterSpacing: 0 /*percentages not used in flutter. defaulting to zero*/,
                                fontWeight: FontWeight.normal,
                                height: 1.5 /*PERCENT not supported*/
                            ),)
                        ),
                      ]
                  )
          )
      ),Positioned(
          top: 557,
          left: 19.5,
          child: Container(
                  width: 374,
                  height: 63,

                  child: Stack(
                      children: <Widget>[
                        Positioned(
                            top: 0,
                            left: 0,
                            child: Container(
                                width: 374,
                                height: 63,
                                decoration: BoxDecoration(
                                  borderRadius : BorderRadius.only(
                                    topLeft: Radius.circular(38),
                                    topRight: Radius.circular(38),
                                    bottomLeft: Radius.circular(38),
                                    bottomRight: Radius.circular(38),
                                  ),
                                  color : Color.fromRGBO(225, 238, 221, 1),
                                )
                            )
                        ),Positioned(
                            top: 24.499988555908203,
                            left: 161.09896850585938,
                            child: Text('LOG IN', textAlign: TextAlign.left, style: TextStyle(
                                color: Color.fromRGBO(63, 69, 83, 1),
                                fontFamily: 'HelveticaNeue',
                                fontSize: 14,
                                letterSpacing: 0 /*percentages not used in flutter. defaulting to zero*/,
                                fontWeight: FontWeight.normal,
                                height: 1.5 /*PERCENT not supported*/
                            ),)
                        ),
                      ]
                  )
          )
      ),Positioned(
          top: 695,
          left: 19.5,
          child: Container(
                  width: 374,
                  height: 63,

                  child: Stack(
                      children: <Widget>[
                        Positioned(
                            top: 0,
                            left: 0,
                            child: Container(
                                width: 374,
                                height: 63,
                                decoration: BoxDecoration(
                                  borderRadius : BorderRadius.only(
                                    topLeft: Radius.circular(38),
                                    topRight: Radius.circular(38),
                                    bottomLeft: Radius.circular(38),
                                    bottomRight: Radius.circular(38),
                                  ),
                                  color : Color.fromRGBO(225, 238, 221, 1),
                                )
                            )
                        ),
                      ]
                  )
          )
      ),Positioned(
          top: 668,
          left: 135.5,
          child: Text('Forgot Password?', textAlign: TextAlign.left, style: TextStyle(
                  color: Color.fromRGBO(63, 65, 78, 1),
                  fontFamily: 'HelveticaNeue',
                  fontSize: 14,
                  letterSpacing: 0 /*percentages not used in flutter. defaulting to zero*/,
                  fontWeight: FontWeight.normal,
                  height: 1.5 /*PERCENT not supported*/
          ),)
      ),Positioned(
          top: 709,
          left: 151.5,
          child: Container(
                  width: 180,
                  height: 49,
                  decoration: BoxDecoration(

                  ),
                  child: Stack(
                      children: <Widget>[
                        Positioned(
                            top: 0,
                            left: 6,
                            child: Text('Sign up', textAlign: TextAlign.left, style: TextStyle(
                                color: Color.fromRGBO(0, 0, 0, 1),
                                fontFamily: 'Roboto',
                                fontSize: 25,
                                letterSpacing: 0 /*percentages not used in flutter. defaulting to zero*/,
                                fontWeight: FontWeight.normal,
                                height: 1.5 /*PERCENT not supported*/
                            ),)
                        ),
                      ]
                  )
          )
      ),Positioned(
          top: 717,
          left: 117.5,

      ),
          ]
      )
    ),
              ],
    // Figma Flutter Generator Group6871Widget - GROUP
    Column(
      children: [
        Padding(
          padding: const EdgeInsets.all(8.0),
          child: Container(
          width: 414,
          height: 896,

          child: Stack(
          children: <Widget>[
          Positioned(
          top: 0,
          left: 0,
          child: Container(
          width: 414,
          height: 896,
          decoration: BoxDecoration(
          color : Color.fromRGBO(255, 255, 255, 1),
          ),
          child: Stack(
          children: <Widget>[
          Positioned(
          top: -23.562314987182617,
          left: -16.16431427001953,
          child: Transform.rotate(
          angle: 0.3311600926641291 * (math.pi / 180),
          child: Container(
          width: 450.1144714355469,
          height: 920.8018798828125,
          decoration: BoxDecoration(
          image : DecorationImage(
          image: AssetImage('assets/images/Images11.png'),
          fit: BoxFit.fitWidth
          ),
          )
          ),
          )
          ),Positioned(
          top: 161,
          left: 16,
          child: Container(
          width: 384,
          height: 287,
          decoration: BoxDecoration(
          color : Color.fromRGBO(35, 31, 32, 1),
          )
          )
          ),Positioned(
          top: 882,
          left: 136,
          child: Divider(
          color: Color.fromRGBO(230, 230, 230, 1),
          thickness: 5
          )

          ),Positioned(
          top: 841,
          left: 344.2388916015625,
          child: Container(
          width: 55.000003814697266,
          height: 55.000003814697266,

          child: Stack(
          children: <Widget>[
          Positioned(
          top: 55.000003814697266,
          left: 55,
          child: Container(
          width: 55,
          height: 55,

          child: Stack(
          children: <Widget>[
          Positioned(
          top: 0,
          left: 0,
          child: Container(
          width: 55,
          height: 55,

          child: Stack(
          children: <Widget>[
          Positioned(
          top: 0,
          left: 0,
          child: Transform.rotate(
          angle: 179.99999491025392 * (math.pi / 180),
          child: Container(
          width: 55,
          height: 55,
          decoration: BoxDecoration(
          borderRadius : BorderRadius.only(
          topLeft: Radius.circular(38),
          topRight: Radius.circular(38),
          bottomLeft: Radius.circular(38),
          bottomRight: Radius.circular(38),
          ),
          color : Color.fromRGBO(35, 31, 32, 1),
          border : Border.all(
          color: Color.fromRGBO(35, 31, 32, 1),
          width: 1,
          ),
          )
          ),
          )
          ),
          ]
          )
          )
          ),
          ]
          )
          )
          ),Positioned(
          top: 36.500003814697266,
          left: 36.84906768798828,
          child: Transform.rotate(
          angle: 179.99999491025392 * (math.pi / 180),
          child: SvgPicture.asset(
          'assets/images/vector.svg',
          semanticsLabel: 'vector'
          );,
          )
          ),
          ]
          )
          )
          ),Positioned(
          top: 0,
          left: 4,
          child: Container(
          width: 410,
          height: 83,
          decoration: BoxDecoration(
          color : Color.fromRGBO(16, 17, 16, 1),
          )
          )
          ),Positioned(
          top: 16,
          left: 4,
          child: Container(
          width: 123,
          height: 20,

          child: Stack(
          children: <Widget>[
          Positioned(
          top: 0,
          left: 0,
          child: Container(
          width: 123,
          height: 20,
          decoration: BoxDecoration(
          borderRadius : BorderRadius.only(
          topLeft: Radius.circular(38),
          topRight: Radius.circular(38),
          bottomLeft: Radius.circular(38),
          bottomRight: Radius.circular(38),
          ),
          color : Color.fromRGBO(244, 18, 31, 1),
          )
          )
          ),
          ]
          )
          )
          ),Positioned(
          top: 16,
          left: 291,
          child: Container(
          width: 105,
          height: 20,

          child: Stack(
          children: <Widget>[
          Positioned(
          top: 0,
          left: 0,
          child: Container(
          width: 105,
          height: 20,
          decoration: BoxDecoration(
          borderRadius : BorderRadius.only(
          topLeft: Radius.circular(38),
          topRight: Radius.circular(38),
          bottomLeft: Radius.circular(38),
          bottomRight: Radius.circular(38),
          ),
          color : Color.fromRGBO(78, 36, 245, 1),
          )
          )
          ),
          ]
          )
          )
          ),Positioned(
          top: 15,
          left: 150,
          child: Container(
          width: 124,
          height: 20,

          child: Stack(
          children: <Widget>[
          Positioned(
          top: 0,
          left: 0,
          child: Container(
          width: 124,
          height: 20,
          decoration: BoxDecoration(
          borderRadius : BorderRadius.only(
          topLeft: Radius.circular(38),
          topRight: Radius.circular(38),
          bottomLeft: Radius.circular(38),
          bottomRight: Radius.circular(38),
          ),
          color : Color.fromRGBO(100, 224, 42, 1),
          )
          )
          ),
          ]
          )
          )
          ),Positioned(
          top: 19,
          left: 177,
          child: Text('Community', textAlign: TextAlign.left, style: TextStyle(
          color: Color.fromRGBO(0, 0, 0, 1),
          fontFamily: 'Roboto',
          fontSize: 14,
          letterSpacing: 0 /*percentages not used in flutter. defaulting to zero*/,
          fontWeight: FontWeight.normal,
          height: 1.5 /*PERCENT not supported*/
          ),)
          ),Positioned(
          top: 20,
          left: 313,
          child: Text('Patron', textAlign: TextAlign.left, style: TextStyle(
          color: Color.fromRGBO(0, 0, 0, 1),
          fontFamily: 'Roboto',
          fontSize: 14,
          letterSpacing: 0 /*percentages not used in flutter. defaulting to zero*/,
          fontWeight: FontWeight.normal,
          height: 1.5 /*PERCENT not supported*/
          ),)
          ),Positioned(
          top: 21,
          left: 46,
          child: Text('shop', textAlign: TextAlign.left, style: TextStyle(
          color: Color.fromRGBO(37, 34, 34, 1),
          fontFamily: 'Roboto',
          fontSize: 14,
          letterSpacing: 0 /*percentages not used in flutter. defaulting to zero*/,
          fontWeight: FontWeight.normal,
          height: 1.5 /*PERCENT not supported*/
          ),)
          ),Positioned(
          top: 835,
          left: 380,
          child: Container(
          width: 25,
          height: 42,

          child: Stack(
          children: <Widget>[
          Positioned(
          top: 0,
          left: 0,
          child: Container(
          width: 25,
          height: 23,
          decoration: BoxDecoration(
          color : Color.fromRGBO(238, 32, 81, 1),
          borderRadius : BorderRadius.all(Radius.elliptical(25, 23)),
          )
          )
          ),Positioned(
          top: 4,
          left: 9,
          child: Text('7
          ', textAlign: TextAlign.left, style: TextStyle(
          color: Color.fromRGBO(35, 31, 32, 1),
          fontFamily: 'Roboto',
          fontSize: 18,
          letterSpacing: 0 /*percentages not used in flutter. defaulting to zero*/,
          fontWeight: FontWeight.normal,
          height: 1.5 /*PERCENT not supported*/
          ),)
          ),
          ]
          )
          )
          ),Positioned(
          top: 887.2012939453125,
          left: 352.2388916015625,
          child: Transform.rotate(
          angle: 86.57762884931707 * (math.pi / 180),
          child: SvgPicture.asset(
          'assets/images/vector16.svg',
          semanticsLabel: 'vector16'
          );,
          )
          ),Positioned(
          top: 84,
          left: 18,
          child: null
          ),Positioned(
          top: 458,
          left: 16,
          child: null
          ),Positioned(
          top: 459,
          left: 32,
          child: Container(
          width: 61,
          height: 68,
          decoration: BoxDecoration(
          image : DecorationImage(
          image: AssetImage('assets/images/Download51.png'),
          fit: BoxFit.fitWidth
          ),
          )
          )
          ),Positioned(
          top: 537,
          left: 18,
          child: Container(
          width: 387,
          height: 298,
          decoration: BoxDecoration(
          color : Color.fromRGBO(35, 31, 32, 1),
          )
          )
          ),Positioned(
          top: 554,
          left: 32,
          child: Container(
          width: 357,
          height: 160,
          decoration: BoxDecoration(
          image : DecorationImage(
          image: AssetImage('assets/images/Download61.png'),
          fit: BoxFit.fitWidth
          ),
          )
          )
          ),Positioned(
          top: 180,
          left: 29,
          child: Container(
          width: 360,
          height: 162,
          decoration: BoxDecoration(
          image : DecorationImage(
          image: AssetImage('assets/images/Download21.png'),
          fit: BoxFit.fitWidth
          ),
          )
          )
          ),Positioned(
          top: 84,
          left: 31,
          child: Container(
          width: 62,
          height: 69,
          decoration: BoxDecoration(
          image : DecorationImage(
          image: AssetImage('assets/images/Download31.png'),
          fit: BoxFit.fitWidth
          ),
          )
          )
          ),Positioned(
          top: 97,
          left: 117,
          child: Text('Little bake house', textAlign: TextAlign.left, style: TextStyle(
          color: Color.fromRGBO(255, 255, 255, 1),
          fontFamily: 'Rhodium Libre',
          fontSize: 16,
          letterSpacing: 0 /*percentages not used in flutter. defaulting to zero*/,
          fontWeight: FontWeight.normal,
          height: 1.5 /*PERCENT not supported*/
          ),)
          ),Positioned(
          top: 407,
          left: 210,
          child: Container(
          width: 192,
          height: 37,

          child: Stack(
          children: <Widget>[
          Positioned(
          top: 0,
          left: 0,
          child: null
          ),Positioned(
          top: 5.0454559326171875,
          left: 82.60464477539062,
          child: Container(
          width: 40.930233001708984,
          height: 26.909090042114258,
          decoration: BoxDecoration(
          image : DecorationImage(
          image: AssetImage('assets/images/Shoppingcarticoninflatstyleshoppingsymbolvector206160551.png'),
          fit: BoxFit.fitWidth
          ),
          )
          )
          ),Positioned(
          top: 5.0454559326171875,
          left: 136.93020629882812,
          child: Container(
          width: 37.953487396240234,
          height: 26.909090042114258,
          decoration: BoxDecoration(
          image : DecorationImage(
          image: AssetImage('assets/images/Questionmarkiconbubblevector260nw17148749711.png'),
          fit: BoxFit.fitWidth
          ),
          )
          )
          ),Positioned(
          top: 10.93182373046875,
          left: 8.186060905456543,
          child: Text('Price:\$12', textAlign: TextAlign.left, style: TextStyle(
          color: Color.fromRGBO(0, 0, 0, 1),
          fontFamily: 'Roboto',
          fontSize: 16,
          letterSpacing: 0 /*percentages not used in flutter. defaulting to zero*/,
          fontWeight: FontWeight.normal,
          height: 1.5 /*PERCENT not supported*/
          ),)
          ),
          ]
          )
          )
          ),Positioned(
          top: 789,
          left: 177,
          child: Container(
          width: 224,
          height: 41,

          child: Stack(
          children: <Widget>[
          Positioned(
          top: 0,
          left: 0,
          child: null
          ),Positioned(
          top: 5.590909004211426,
          left: 96.3720932006836,
          child: Container(
          width: 47.75193786621094,
          height: 29.81818199157715,
          decoration: BoxDecoration(
          image : DecorationImage(
          image: AssetImage('assets/images/Shoppingcarticoninflatstyleshoppingsymbolvector206160551.png'),
          fit: BoxFit.fitWidth
          ),
          )
          )
          ),Positioned(
          top: 6,
          left: 163,
          child: Container(
          width: 44.27906799316406,
          height: 29.81818199157715,
          decoration: BoxDecoration(
          image : DecorationImage(
          image: AssetImage('assets/images/Questionmarkiconbubblevector260nw17148749711.png'),
          fit: BoxFit.fitWidth
          ),
          )
          )
          ),Positioned(
          top: 12.113636016845703,
          left: 9.550387382507324,
          child: Text('Price:\$15', textAlign: TextAlign.left, style: TextStyle(
          color: Color.fromRGBO(0, 0, 0, 1),
          fontFamily: 'Roboto',
          fontSize: 16,
          letterSpacing: 0 /*percentages not used in flutter. defaulting to zero*/,
          fontWeight: FontWeight.normal,
          height: 1.5 /*PERCENT not supported*/
          ),)
          ),
          ]
          )
          )
          ),Positioned(
          top: 370,
          left: 29,
          child: Text(' Scrumptious cupcakes anytime ! Delivered all over Bangalore......', textAlign: TextAlign.left, style: TextStyle(
          color: Color.fromRGBO(255, 255, 255, 1),
          fontFamily: 'Red Rose',
          fontSize: 16,
          letterSpacing: 0 /*percentages not used in flutter. defaulting to zero*/,
          fontWeight: FontWeight.normal,
          height: 1.5 /*PERCENT not supported*/
          ),)
          ),Positioned(
          top: 474,
          left: 118,
          child: Text('Jwell', textAlign: TextAlign.left, style: TextStyle(
          color: Color.fromRGBO(255, 255, 255, 1),
          fontFamily: 'Rhodium Libre',
          fontSize: 16,
          letterSpacing: 0 /*percentages not used in flutter. defaulting to zero*/,
          fontWeight: FontWeight.normal,
          height: 1.5 /*PERCENT not supported*/
          ),)
          ),Positioned(
          top: 739,
          left: 25,
          child: Text('Gender neutral, handmade jewellery. Customized precisely for you taste ! Shippings all over India', textAlign: TextAlign.left, style: TextStyle(
          color: Color.fromRGBO(255, 255, 255, 1),
          fontFamily: 'Roboto',
          fontSize: 16,
          letterSpacing: 0 /*percentages not used in flutter. defaulting to zero*/,
          fontWeight: FontWeight.normal,
          height: 1.5 /*PERCENT not supported*/
          ),)
          ),Positioned(
          top: 269,
          left: 296,
          child: Container(
          width: 100,
          height: 100,
          decoration: BoxDecoration(

          ),
          child: Stack(
          children: <Widget>[

          ]
          )
          )
          ),Positioned(
          top: 840,
          left: 177,
          child: Container(
          width: 55,
          height: 57,
          decoration: BoxDecoration(
          image : DecorationImage(
          image: AssetImage('assets/images/Images21.png'),
          fit: BoxFit.fitWidth
          ),
          )
          )
          ),Positioned(
          top: 837,
          left: 39,
          child: Container(
          width: 71,
          height: 57,
          decoration: BoxDecoration(
          image : DecorationImage(
          image: AssetImage('assets/images/Download11.png'),
          fit: BoxFit.fitWidth
          ),
          )
          )
          ),
          ]
          )
          )
          ),
          ]
          )
          ),
        ),
      ],
    )
    );

