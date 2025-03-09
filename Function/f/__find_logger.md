# Function: <code>__find_logger</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586520432,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:25",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_bind_pf",
        "net/netfilter/nf_log.c:nf_log_proc_dostring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586520432,
      "name": "__find_logger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586962912,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:25",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586962912,
      "name": "__find_logger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587157792,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:24",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587157792,
      "name": "__find_logger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587288560,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:27",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587288560,
      "name": "__find_logger",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587810000,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:27",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587810000,
      "name": "__find_logger",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588155143,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:27",
      "file": "net/netfilter/nf_log.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588154512,
      "name": "__find_logger.part.4",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588338295,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:27",
      "file": "net/netfilter/nf_log.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588337664,
      "name": "__find_logger.part.5",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588736176,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588736176,
      "name": "__find_logger",
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588959968,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588959968,
      "name": "__find_logger",
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589915264,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589915264,
      "name": "__find_logger",
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589956336,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589956336,
      "name": "__find_logger",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589871136,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589871136,
      "name": "__find_logger",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590633040,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590633040,
      "name": "__find_logger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592256624,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592256624,
      "name": "__find_logger",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594090832,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594090832,
      "name": "__find_logger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594475888,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594475888,
      "name": "__find_logger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595278208,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595278208,
      "name": "__find_logger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 251
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336502562160,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336502562160,
      "name": "__find_logger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3235268848,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3235268848,
      "name": "__find_logger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055296142976,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055296142976,
      "name": "__find_logger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278721700,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278721700,
      "name": "__find_logger",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588566352,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588566352,
      "name": "__find_logger",
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588278336,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588278336,
      "name": "__find_logger",
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588898528,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588898528,
      "name": "__find_logger",
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
struct nf_logger * __find_logger(int pf, const char * str_logger)
```

```json
{
  "name": "__find_logger",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589040944,
      "name": "__find_logger",
      "external": false,
      "loc": "net/netfilter/nf_log.c:28",
      "file": "net/netfilter/nf_log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/netfilter/nf_log.c:nf_log_proc_dostring",
        "net/netfilter/nf_log.c:nf_log_bind_pf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589040944,
      "name": "__find_logger",
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
struct nf_logger * __find_logger(int pf, const char * str_logger)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
struct nf_logger * __find_logger(int pf, const char * str_logger)
```
</details>
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
