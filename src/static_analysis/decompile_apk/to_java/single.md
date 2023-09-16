# 单个反编译

* 背景：JEB默认情况下去反编译apk的话，显示的是Bytecode字节码：
  * ![jeb_decompiled_show_bytecode](../../../assets/img/jeb_decompiled_show_bytecode.png)
  * 而不是我们要的`Java`代码
* 需求：对于单个类去反编译出java代码

从左下角窗口中，展开找到自己要反编译的java的类->右键->`Decompile`：

![jeb_choose_class_right_decompile](../../../assets/img/jeb_choose_class_right_decompile.png)

会弹框开始反编译：

![jeb_decompiling_to_java](../../../assets/img/jeb_decompiling_to_java.jpg)

首次会有（勾选不再提示后，之后就不会再显示）额外的弹框提示，新的反编译的内容要显示在新的视图，但要替代当前视图：

![jeb_tip_view_replaced](../../../assets/img/jeb_tip_view_replaced.jpg)

以及还会提示，显示窗口要分左右两个子窗口，右边用于显示刚反编译出来的java源代码：

![jeb_tip_workspace_panel_split](../../../assets/img/jeb_tip_workspace_panel_split.png)

然后就可以正常显示反编译后的java源代码了：

![jeb_show_decompiled_java_code](../../../assets/img/jeb_show_decompiled_java_code.jpg)
