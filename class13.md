# The Past, Present, and Future of Local Storage for Web Applications

Native client applications used to have an advantage over web applications which is the larger size of data that can be stored, nowadays, with HTML5 storage the low storage capability can be overcomed even without the used of cookies and plugins that were someday necessary to store data for web applications.

First you have to make sure that HTML5 is compatible with your browser, here is a set of valid browsers:

1. Internet Explorer 8.0+
2. FIREFOX 3.5+
3. SAFARI 4.0+
4. CHROME 4.0+
5. OPERA 10.5+
6. IPHONE 2.0+
7. ANDROID 2.0+

## Using HTML5 Storage
Data is stored in HTML5 as key / value pairs, you can store any data type *but it will always be treated as a string* so consider using some conversion when needed, data can be accessed by using `getItem`, changed by using `setItem`, and removed by `reemoveItem`. When using `getItem` with a none existing key the return value will be null.

The changes a user does can be tracked in case of real changes i.e. not clearing a void variable or changing data back to its stored value.

While HTMl5 helps incresing the size of stored data, it is not limitless, the max available size is 5 MB.

Read more in [diveinto.html5doctor](http://diveinto.html5doctor.com/storage.html)

**Note: this is a summary for an article written on Febreuary 2011, a lot of innovations in tech industry might result in better practices.**
