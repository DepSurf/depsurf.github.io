# Function: <code>do_readlinkat</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581598640,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:382",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581598640,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581684624,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:385",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581684624,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581802816,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:387",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581802816,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581875408,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:387",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581875408,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582098864,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:407",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582098864,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582145600,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:395",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145600,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582170480,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:413",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582170480,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582487776,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:431",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582487776,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583009184,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:444",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583009184,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583571744,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:459",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583571744,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583787824,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:465",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583787824,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583993440,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:487",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583993440,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493344600,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:387",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__arm64_sys_readlink",
        "fs/stat.c:__arm64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493344600,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226938596,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:387",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__se_sys_readlink",
        "fs/stat.c:__se_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226938596,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 308
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286893280,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:387",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__se_sys_readlink",
        "fs/stat.c:__se_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286893280,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273074846,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:387",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__se_sys_readlink",
        "fs/stat.c:__se_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273074846,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 258
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581844144,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:387",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581844144,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581781808,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:387",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581781808,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581835456,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:387",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581835456,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
```

```json
{
  "name": "do_readlinkat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581904848,
      "name": "do_readlinkat",
      "external": false,
      "loc": "fs/stat.c:387",
      "file": "fs/stat.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/stat.c:__ia32_sys_readlink",
        "fs/stat.c:__x64_sys_readlink",
        "fs/stat.c:__ia32_sys_readlinkat",
        "fs/stat.c:__x64_sys_readlinkat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581904848,
      "name": "do_readlinkat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 286
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
int do_readlinkat(int dfd, const char * pathname, char * buf, int bufsiz)
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
