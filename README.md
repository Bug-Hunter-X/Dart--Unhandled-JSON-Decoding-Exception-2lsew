# Dart Unhandled JSON Decoding Exception

This repository demonstrates a common error in Dart applications: failing to gracefully handle exceptions that may arise during JSON decoding. The `bug.dart` file contains code that directly accesses the JSON data without checking for the existence of the key, which might lead to a runtime error if the JSON structure is unexpected. The `bugSolution.dart` file provides a robust solution that handles these scenarios effectively.