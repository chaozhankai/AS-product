# Read ME

#### 一.实验名称

​	验证Activity的生命周期

#### 二.实验要求与目的

​	参看上述文档，完成其中生命周期的例子，并设法验证 

#### 三.实验步骤

##### 1.验证生命周期

```
private static final String TAG = MainActivity.class.getSimpleName();

@Override
protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);
    setContentView(R.layout.activity_main);
    Log.e(TAG,"onCreate is invoke!!!");

}

@Override
protected void onRestart() {
    super.onRestart();
    Log.e(TAG,"onRestart is invoke!!!");
}

@Override
protected void onStart() {
    super.onStart();
    Log.e(TAG,"onStart is invoke!!!");
}

@Override
protected void onResume() {
    super.onResume();
    Log.e(TAG,"onResume is invoke!!!");
}

@Override
protected void onStop() {
    super.onStop();
    Log.e(TAG,"onStop is invoke!!!");
}

protected void onDestroy() {
    super.onDestroy();
    Log.e(TAG,"onDestroy is invoke!!!");
}
```

实验截图 ：

<img src="https://github.com/chaozhankai/AS-product/blob/master/text2/text2/app/11.png" height="400" alt="Screenshot"/>

 

