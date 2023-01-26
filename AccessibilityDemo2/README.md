### Android UI自动化测试
#### 通过 AccessibilityService获取控件信息
- Android studio 中 运行该项目，在设备 的 设置-无障碍 中打开  AccessibilityDemo
- getRootInActiveWindow()方法，只有在窗口发生改变的时候，获取子节点才不会为null；MyAccessibility.java中使用的是该方法。
- getwindows()返回的是一个AccessibilityWindowInfo的List集合，包括界面上所有的东西；ExampleAccessibilityService.java使用的是该方法。