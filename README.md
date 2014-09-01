JSharedPreferences
==================

It can store simple strings on Android SharedPreferences.

## How To Use
Read Google's resources about how to **bind JavaScript to Android code** [here.](http://developer.android.com/guide/webapps/webview.html#BindingJavaScript)
 
## JavaScript API
#### Save a new string:
```
setItem(key, value)

```
#### Get a string:
```
getItem(key)

```
#### Delete a string:
```
removeItem(key)

```

N.B. Both key and value are Strings.

## Examples
- You can integrate a WebView on Android and use JSharedPrefernces instead of LocalStorage to save little data.
- If you want a working example [Croma](https://github.com/numixproject/croma) is actually using JSharedPreferences.

Developed by [Rotolo Paolo](https://github.com/PaoloRotolo) and [Satyajit Sahoo](https://github.com/satya164)
