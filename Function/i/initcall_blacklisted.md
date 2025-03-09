# Function: <code>initcall_blacklisted</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071578853494,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:728",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "init/main.c:do_one_initcall"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578853488,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:707",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578853488,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578853488,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:718",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578853488,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578853488,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:746",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578853488,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578853520,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:761",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578853520,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578854208,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:780",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578854208,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578854208,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:783",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578854208,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578854384,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:835",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578854384,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578854384,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:835",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578854384,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578858752,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:1098",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578858752,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578858944,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:1119",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578858944,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578858912,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:1141",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578858912,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 202
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578858976,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:1202",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578858976,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578850128,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:1196",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578850128,
      "name": "initcall_blacklisted",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578851696,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:1206",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578851696,
      "name": "initcall_blacklisted",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578851120,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:1132",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578851120,
      "name": "initcall_blacklisted",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578851136,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:1136",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578851136,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490174536,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:835",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490174536,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 232
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224384108,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:835",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224384108,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282227424,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:835",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282227424,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 764
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271335728,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:835",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271335728,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578854384,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:835",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578854384,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578847456,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:835",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578847456,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578854384,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:835",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578854384,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
bool initcall_blacklisted(initcall_t fn)
```

```json
{
  "name": "initcall_blacklisted",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578854384,
      "name": "initcall_blacklisted",
      "external": false,
      "loc": "init/main.c:835",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:do_one_initcall"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578854384,
      "name": "initcall_blacklisted",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
bool initcall_blacklisted(initcall_t fn)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
