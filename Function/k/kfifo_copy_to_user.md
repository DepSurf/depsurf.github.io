# Function: <code>kfifo_copy_to_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583033616,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:249",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user",
        "lib/kfifo.c:__kfifo_to_user_r"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583033616,
      "name": "kfifo_copy_to_user.isra.10",
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
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583327088,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:249",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583327088,
      "name": "kfifo_copy_to_user.isra.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583452000,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:249",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583452000,
      "name": "kfifo_copy_to_user.isra.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583472544,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:249",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583472544,
      "name": "kfifo_copy_to_user.isra.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583653488,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:249",
      "file": "lib/kfifo.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583653488,
      "name": "kfifo_copy_to_user.isra.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583871280,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:249",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583871280,
      "name": "kfifo_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583956032,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:249",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583956032,
      "name": "kfifo_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584136576,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584136576,
      "name": "kfifo_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 252
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
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584258992,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584258992,
      "name": "kfifo_copy_to_user",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584666176,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584666176,
      "name": "kfifo_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584783440,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584783440,
      "name": "kfifo_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584828064,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584828064,
      "name": "kfifo_copy_to_user",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585245520,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585245520,
      "name": "kfifo_copy_to_user",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586086176,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586086176,
      "name": "kfifo_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587068928,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587068928,
      "name": "kfifo_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587327504,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587327504,
      "name": "kfifo_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587610864,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587610864,
      "name": "kfifo_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496138368,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496138368,
      "name": "kfifo_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 928
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
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229460336,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229460336,
      "name": "kfifo_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 516
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
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290396816,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290396816,
      "name": "kfifo_copy_to_user",
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
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275195510,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275195510,
      "name": "kfifo_copy_to_user",
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
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584227728,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584227728,
      "name": "kfifo_copy_to_user",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584162944,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584162944,
      "name": "kfifo_copy_to_user",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584211488,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584211488,
      "name": "kfifo_copy_to_user",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
```

```json
{
  "name": "kfifo_copy_to_user",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584316048,
      "name": "kfifo_copy_to_user",
      "external": false,
      "loc": "lib/kfifo.c:236",
      "file": "lib/kfifo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/kfifo.c:__kfifo_to_user_r",
        "lib/kfifo.c:__kfifo_to_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584316048,
      "name": "kfifo_copy_to_user",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
long unsigned int kfifo_copy_to_user(struct __kfifo * fifo, void * to, unsigned int len, unsigned int off, unsigned int * copied)
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
