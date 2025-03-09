# Function: <code>kfifo_copy_from_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583033072,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:188",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user",
        "lib/kfifo.c:__kfifo_from_user_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583033072,
      "name": "kfifo_copy_from_user.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583326496,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:188",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583326496,
      "name": "kfifo_copy_from_user.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583451408,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:188",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583451408,
      "name": "kfifo_copy_from_user.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583471952,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:188",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583471952,
      "name": "kfifo_copy_from_user.isra.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583652896,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:188",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583652896,
      "name": "kfifo_copy_from_user.isra.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583870736,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:188",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583870736,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583956528,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:188",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583956528,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584136016,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136016,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258416,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258416,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584666752,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584666752,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584784016,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584784016,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 275
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584827488,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584827488,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585245136,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585245136,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586086784,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586086784,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587069584,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587069584,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587328160,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587328160,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587611520,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587611520,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    }
  ]
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496137688,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496137688,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229461120,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229461120,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290395744,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290395744,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275194880,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275194880,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 302
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584227152,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584227152,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584162368,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584162368,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584210912,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584210912,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_from_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315472,
      "name": "kfifo_copy_from_user",
      "external": false,
      "loc": "lib/kfifo.c:175",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_from_user_r",
        "lib/kfifo.c:__kfifo_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315472,
      "name": "kfifo_copy_from_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
long unsigned int kfifo_copy_from_user(struct __kfifo * fifo, const void * from, unsigned int len, unsigned int off, unsigned int * copied)
```
</details>
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
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
