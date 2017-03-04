# NumPswView
android 数字密码输入框，仿支付宝、微信等6位数字支付密码。
### 效果图
![](numpass.gif)
### 使用方式
添加依赖
```
compile 'com.dongqing.numpsw:numpswview:1.0.0'
```
布局文件
```
<com.dongqing.numpsw.NumPswView
    xmlns:app="http://schemas.android.com/apk/res-auto"
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:inputType="number"
    android:maxLength="6"
    app:borderColor="#CCCCCC"
    app:borderMargin="10dp"
    app:borderRadius="3dp"
    app:borderWidth="5dp"
    app:passwordColor="#CCCCCC"
    app:passwordLength="6"
    app:passwordWidth="10dp"
    app:solidColor="#FFFFFF" />
```
### 属性说明
|       属性      |        说明      |
|      :-----:    |       :-----:     |
|  borderColor    | 分割线的颜色       |
|  borderMargin    | 边框的距离       |
|  borderRadius    | 边框圆角       |
|  borderWidth    | 边框的宽度       |
|  passwordColor    | 密码的颜色       |
|  passwordLength    | 密码长度       |
|  passwordWidth    | 密码的半径       |
|  solidColor    | 边框填充颜色       |
### 最后
[我的博客](http://dongqing.website)
