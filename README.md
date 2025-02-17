# flutter_impeller_view_flicker

If you have a stack with any sort of view ([webview_flutter](https://pub.dev/packages/webview_flutter), [flutter_unity_widget](https://pub.dev/packages/flutter_unity_widget), etc) and then a flutter widget above it with a running animation and go from backgrounded to foregrounded you will occasionally see a glimpse of the view and the flutter UI will flicker. 
