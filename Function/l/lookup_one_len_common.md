# Function: <code>lookup_one_len_common</code>

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
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_len_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581629200,
      "name": "lookup_one_len_common",
      "external": false,
      "loc": "fs/namei.c:2434",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581629200,
      "name": "lookup_one_len_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_len_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581715376,
      "name": "lookup_one_len_common",
      "external": false,
      "loc": "fs/namei.c:2458",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581715376,
      "name": "lookup_one_len_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_len_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581832896,
      "name": "lookup_one_len_common",
      "external": false,
      "loc": "fs/namei.c:2456",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581832896,
      "name": "lookup_one_len_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_len_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581905360,
      "name": "lookup_one_len_common",
      "external": false,
      "loc": "fs/namei.c:2449",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581905360,
      "name": "lookup_one_len_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_len_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582137936,
      "name": "lookup_one_len_common",
      "external": false,
      "loc": "fs/namei.c:2477",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582137936,
      "name": "lookup_one_len_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_len_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582184528,
      "name": "lookup_one_len_common",
      "external": false,
      "loc": "fs/namei.c:2475",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582184528,
      "name": "lookup_one_len_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 185
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
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_len_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582206736,
      "name": "lookup_one_len_common",
      "external": false,
      "loc": "fs/namei.c:2565",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582206736,
      "name": "lookup_one_len_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_len_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493385968,
      "name": "lookup_one_len_common",
      "external": false,
      "loc": "fs/namei.c:2449",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493385968,
      "name": "lookup_one_len_common",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_len_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226967996,
      "name": "lookup_one_len_common",
      "external": false,
      "loc": "fs/namei.c:2449",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226967996,
      "name": "lookup_one_len_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 220
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
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_len_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286928640,
      "name": "lookup_one_len_common",
      "external": false,
      "loc": "fs/namei.c:2449",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286928640,
      "name": "lookup_one_len_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_len_common",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273101708,
      "name": "lookup_one_len_common",
      "external": false,
      "loc": "fs/namei.c:2449",
      "file": "fs/namei.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273101708,
      "name": "lookup_one_len_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_len_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581874096,
      "name": "lookup_one_len_common",
      "external": false,
      "loc": "fs/namei.c:2449",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581874096,
      "name": "lookup_one_len_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_len_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581811696,
      "name": "lookup_one_len_common",
      "external": false,
      "loc": "fs/namei.c:2449",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581811696,
      "name": "lookup_one_len_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_len_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581865408,
      "name": "lookup_one_len_common",
      "external": false,
      "loc": "fs/namei.c:2449",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581865408,
      "name": "lookup_one_len_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
```

```json
{
  "name": "lookup_one_len_common",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581931424,
      "name": "lookup_one_len_common",
      "external": false,
      "loc": "fs/namei.c:2449",
      "file": "fs/namei.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/namei.c:lookup_one_len_unlocked",
        "fs/namei.c:lookup_one_len",
        "fs/namei.c:try_lookup_one_len"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581931424,
      "name": "lookup_one_len_common",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 182
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
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
int lookup_one_len_common(const char * name, struct dentry * base, int len, struct qstr * this)
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
