# Function: <code>fuse_drop_waiting</code>

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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582778032,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:130",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:__fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582778032,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582882048,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:166",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:__fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582882048,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583061184,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:166",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:__fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583061184,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583167712,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:89",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583167712,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583490160,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:89",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583490160,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583598592,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:90",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_put_request",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583598592,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583621680,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:90",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_put_request",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583621680,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583980704,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:90",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_put_request",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583980704,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584563344,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:90",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_put_request",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584563344,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585241152,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:90",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_put_request",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585241152,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585470960,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:90",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_put_request",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585470960,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585705984,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:90",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_put_request",
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585705984,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494880768,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:89",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494880768,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228296840,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:89",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228296840,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055288743216,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:89",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288743216,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274199852,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:89",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/fuse/dev.c:fuse_get_req",
        "fs/fuse/dev.c:fuse_get_req"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583136448,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:89",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583136448,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583073600,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:89",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583073600,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583120480,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:89",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583120480,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```

```json
{
  "name": "fuse_drop_waiting",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583214320,
      "name": "fuse_drop_waiting",
      "external": false,
      "loc": "fs/fuse/dev.c:89",
      "file": "fs/fuse/dev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/fuse/dev.c:fuse_get_req"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583214320,
      "name": "fuse_drop_waiting",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void fuse_drop_waiting(struct fuse_conn * fc)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void fuse_drop_waiting(struct fuse_conn * fc)
```
</details>
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
