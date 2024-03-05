[<<Back](../README.md)

### Exception Handling

```dart
try {
 // Code that might throw an exception
 int result = 10 ~/ 0; // This will throw a 'DivisionByZero' exception
} catch (e) {
 // Handle the exception
 print('An error occurred: $e');
}
```

### Error Widgets

```dart
//Flutter offers error widgets like `ErrorWidget`, `ErrorCatcher`, and `ErrorListener` to catch and display errors
ErrorWidget(builder: (BuildContext context, Object error) {
 return Text('An error occurred: $error');
}),
```
