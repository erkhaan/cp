Read whole line of string w/ whitespaces and etc (regular cin will read only one word before space):
```C++
string s; // {a, b, c}
getline(cin, s);
cout << s << endl; // {a, b, c}
```

```C++
string s; // {a, b, c}
cin >> s;
cout << s << endl; // {a,
```
