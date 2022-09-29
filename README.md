<!-- 
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages). 

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages). 
-->

DOB Input Field package helps you to take dob from user manually. This package validate user inputted DOB automatically.

## Features

 - Take DOB manually.
 - 3 different date Formats
 - Auto validation
 - Fixed character length
 - Date type input keyboard
 - User preferred Decoration

## Getting started

  Install the package :
```dart
dob_input_field: ^2.0.0
```

## Usage

Import the package first.

With DateFormat YYYYMMDD
``` 
 DOBInputField(
            firstDate: DateTime(1900),
            lastDate: DateTime.now(),
            showLabel: true,
            dateFormatType: DateFormatType.YYYYMMDD,
            autovalidateMode: AutovalidateMode.always,
            fieldLabelText: "With label",
          ),
```

With DateFormat DDMMYYYY
``` 
 DOBInputField(
            firstDate: DateTime(1900),
            lastDate: DateTime.now(),
            showLabel: true,
            dateFormatType: DateFormatType.DDMMYYYY,
            autovalidateMode: AutovalidateMode.always,
          ),
```

With Label and with validation
```dart
DOBInputField(
            firstDate: DateTime(1900),
            lastDate:DateTime.now() ,
            showLabel: true,
            autovalidateMode: AutovalidateMode.always,
            fieldLabelText: "With label",
          ),
```

Without Label and with validation
```dart
DOBInputField(
            firstDate: DateTime(1900),
            lastDate:DateTime.now() ,
          ),          
```
Without Label and without validation
```dart
DOBInputField(
            firstDate: DateTime(1900),
            lastDate:DateTime.now() ,
            autovalidateMode: AutovalidateMode.disabled,
          ),          
```

## Additional information
Stay in touch via [LinkedIN](https://www.linkedin.com/in/lakshydeep-14/)  | [Medium](https://lakshydeep-14.medium.com/) | [GitHub](https://github.com/lakshydeep-14)
