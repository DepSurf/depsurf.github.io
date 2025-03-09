# Function: <code>__sbitmap_get_word</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583572455,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:80",
      "file": "lib/sbitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_get"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583609840,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:82",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583609840,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583855888,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:82",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583855888,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584055792,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:82",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584055792,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584138928,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:120",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584138928,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584329152,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:107",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584329152,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584463840,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:107",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584463840,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585027936,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:107",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585027936,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585176384,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:97",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585176384,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585058176,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:146",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585058176,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585504416,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:146",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:__sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585504416,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586653168,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:136",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:__sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586653168,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587900544,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:136",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:__sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587900544,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588174985,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:136",
      "file": "lib/sbitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_find_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588465801,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:136",
      "file": "lib/sbitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/sbitmap.c:sbitmap_find_bit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496356064,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:107",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496356064,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229686212,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:107",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229686212,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290677296,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:107",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290677296,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275398954,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:107",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275398954,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584432592,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:107",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584432592,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584367696,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:107",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584367696,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584415504,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:107",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584415504,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```

```json
{
  "name": "__sbitmap_get_word",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584521552,
      "name": "__sbitmap_get_word",
      "external": false,
      "loc": "lib/sbitmap.c:107",
      "file": "lib/sbitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/sbitmap.c:sbitmap_get_shallow",
        "lib/sbitmap.c:sbitmap_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584521552,
      "name": "__sbitmap_get_word",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int __sbitmap_get_word(long unsigned int * word, long unsigned int depth, unsigned int hint, bool wrap)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
