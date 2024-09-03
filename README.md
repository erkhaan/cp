# competitive programming tricks, tips (c++)

## String input

Read whole line of string w/ whitespaces and etc ):
```C++
string s; // {a, b, c}
getline(cin, s);
cout << s << endl; // {a, b, c}
```

Regular cin will read only one word before space:
```C++
string s; // {a, b, c}
cin >> s;
cout << s << endl; // {a,
```
