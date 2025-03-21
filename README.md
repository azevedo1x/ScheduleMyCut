
  curl -sL https://firebase.tools | bash
  firebase login
  dart pub global activate flutterfire_cli
  flutterfire configure

Also, keep the build_runner on while developing:

  dart run build_runner watch
