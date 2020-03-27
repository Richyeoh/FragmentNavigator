# FragmentNavigator

## 如何使用？
您只需要在使用``androidx.navigation.fragment.NaHostFragment`` 地方，替换成 ``com.richyeoh.android.navigator.NavHostFragment``，就是那么简单，不是么？

## 请不要吐槽FragmentNavigator里的代码！！！
虽然很丑，但是他在一定程度上帮助你解决了一定的问题不是么？
好吧，我承认前面只是甩锅，因为我尝试了一下午的时间准备自定义完美的Navigator，最终还是失败了。
具体原因是，结合BottomNavigationView使用时问题，假入我们有3个底部Menu，当App打开时默认选择了第一个，接着我们点击第二个按钮，看似Fragment正常显示的情况加，你再次点击第二个Menu，就会照成界面错乱问题，接着就一发不可收拾。

## 接下来干点啥？
Emmmm，我可能是继续上面实验，直到做出我认为很完美的Navigator为止。

## 瞎剧透！！！
接下来的Navigation应该会支持Fragment生命周期。
