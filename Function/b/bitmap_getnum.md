# Function: <code>bitmap_getnum</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
const char * bitmap_getnum(const char * str, unsigned int * num)
```

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584103040,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:516",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584103040,
      "name": "bitmap_getnum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
const char * bitmap_getnum(const char * str, unsigned int * num)
```

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225824,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:536",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225824,
      "name": "bitmap_getnum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584632649,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:524",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parse_region",
        "lib/bitmap.c:bitmap_parse_region",
        "lib/bitmap.c:bitmap_parse_region",
        "lib/bitmap.c:bitmap_parse_region"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584751689,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:524",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parse_region",
        "lib/bitmap.c:bitmap_parse_region",
        "lib/bitmap.c:bitmap_parse_region",
        "lib/bitmap.c:bitmap_parse_region"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584780259,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:524",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585210528,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:645",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parse_region",
        "lib/bitmap.c:bitmap_parse_region",
        "lib/bitmap.c:bitmap_parse_region",
        "lib/bitmap.c:bitmap_parse_region",
        "lib/bitmap.c:bitmap_parse_region",
        "lib/bitmap.c:bitmap_parse_region",
        "lib/bitmap.c:bitmap_parse_region",
        "lib/bitmap.c:bitmap_parse_region"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586047312,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:661",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587031121,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:672",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587286378,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:672",
      "file": "lib/bitmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist"
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
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587633594,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap-str.c:239",
      "file": "lib/bitmap-str.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/bitmap-str.c:bitmap_parselist",
        "lib/bitmap-str.c:bitmap_parselist",
        "lib/bitmap-str.c:bitmap_parselist",
        "lib/bitmap-str.c:bitmap_parselist"
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
const char * bitmap_getnum(const char * str, unsigned int * num)
```

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496099648,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:536",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496099648,
      "name": "bitmap_getnum",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
const char * bitmap_getnum(const char * str, unsigned int * num)
```

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229426804,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:536",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229426804,
      "name": "bitmap_getnum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
const char * bitmap_getnum(const char * str, unsigned int * num)
```

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290345296,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:536",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290345296,
      "name": "bitmap_getnum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
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
const char * bitmap_getnum(const char * str, unsigned int * num)
```

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275168470,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:536",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275168470,
      "name": "bitmap_getnum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
const char * bitmap_getnum(const char * str, unsigned int * num)
```

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194560,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:536",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194560,
      "name": "bitmap_getnum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
const char * bitmap_getnum(const char * str, unsigned int * num)
```

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584129776,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:536",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584129776,
      "name": "bitmap_getnum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
const char * bitmap_getnum(const char * str, unsigned int * num)
```

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584178320,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:536",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584178320,
      "name": "bitmap_getnum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
const char * bitmap_getnum(const char * str, unsigned int * num)
```

```json
{
  "name": "bitmap_getnum",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584282656,
      "name": "bitmap_getnum",
      "external": false,
      "loc": "lib/bitmap.c:536",
      "file": "lib/bitmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist",
        "lib/bitmap.c:bitmap_parselist"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584282656,
      "name": "bitmap_getnum",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
const char * bitmap_getnum(const char * str, unsigned int * num)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
const char * bitmap_getnum(const char * str, unsigned int * num)
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
