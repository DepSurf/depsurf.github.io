# Function: <code>next_arg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_arg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579499139,
      "name": "next_arg",
      "external": false,
      "loc": "kernel/params.c:165",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:parse_args"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_arg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579513137,
      "name": "next_arg",
      "external": false,
      "loc": "kernel/params.c:165",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:parse_args"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "next_arg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579533809,
      "name": "next_arg",
      "external": false,
      "loc": "kernel/params.c:165",
      "file": "kernel/params.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/params.c:parse_args"
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588199008,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:199",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588199008,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588747808,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:199",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588747808,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589125616,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:199",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589125616,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589360304,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:199",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589360304,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 261
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589817376,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:201",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589817376,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590043696,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:201",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590043696,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585037552,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:201",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585037552,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585189456,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:214",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585189456,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585072320,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:227",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585072320,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585519008,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:227",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585519008,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 250
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586671248,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:227",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586671248,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 298
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595750704,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:227",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595750704,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596275008,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:227",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596275008,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597159744,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:227",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597159744,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503804704,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:201",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503804704,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 352
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236427824,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:201",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236427824,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 384
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297643648,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:201",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297643648,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 420
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279701692,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:201",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279701692,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589645952,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:201",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589645952,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589371824,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:201",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589371824,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590089328,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:201",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590089328,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
char * next_arg(char * args, char * * param, char * * val)
```

```json
{
  "name": "next_arg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590139584,
      "name": "next_arg",
      "external": true,
      "loc": "lib/cmdline.c:201",
      "file": "lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/params.c:parse_args"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590139584,
      "name": "next_arg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 263
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
char * next_arg(char * args, char * * param, char * * val)
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
