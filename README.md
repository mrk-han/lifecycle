# lifecycle
A simple app with a mainActivity with logging attached to the Overrided LifeCycle Methods
- onCreate
- onStart
- onResume
- onPause
- onStop
- onDestroy


Example:
```
    @Override
    protected void onStart() {
        super.onStart();
        Log.v("MainActivity", "onStart");
    }
```
![onStart Example](https://github.com/mrk-han/lifecycle/blob/master/onStart_log_example.png)

