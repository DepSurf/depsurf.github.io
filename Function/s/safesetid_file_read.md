# Function: <code>safesetid_file_read</code>

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
ssize_t safesetid_file_read(struct file * file, char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583667216,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:209",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583667216,
      "name": "safesetid_file_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
ssize_t safesetid_file_read(struct file * file, char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583773488,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:209",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583773488,
      "name": "safesetid_file_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
ssize_t safesetid_file_read(struct file * file, char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584164752,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:209",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584164752,
      "name": "safesetid_file_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584284064,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:263",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_gid_file_read",
        "security/safesetid/securityfs.c:safesetid_uid_file_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584284064,
      "name": "safesetid_file_read.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584309152,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:263",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_gid_file_read",
        "security/safesetid/securityfs.c:safesetid_uid_file_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584309152,
      "name": "safesetid_file_read.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584695744,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:263",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_gid_file_read",
        "security/safesetid/securityfs.c:safesetid_uid_file_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584695744,
      "name": "safesetid_file_read.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585359456,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:263",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_gid_file_read",
        "security/safesetid/securityfs.c:safesetid_uid_file_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585359456,
      "name": "safesetid_file_read.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586109232,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:263",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_gid_file_read",
        "security/safesetid/securityfs.c:safesetid_uid_file_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586109232,
      "name": "safesetid_file_read.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586347840,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:263",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_gid_file_read",
        "security/safesetid/securityfs.c:safesetid_uid_file_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586347840,
      "name": "safesetid_file_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586614896,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:263",
      "file": "security/safesetid/securityfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/safesetid/securityfs.c:safesetid_gid_file_read",
        "security/safesetid/securityfs.c:safesetid_uid_file_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586614896,
      "name": "safesetid_file_read.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
ssize_t safesetid_file_read(struct file * file, char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495575040,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:209",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495575040,
      "name": "safesetid_file_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
ssize_t safesetid_file_read(struct file * file, char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228937132,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:209",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3228937132,
      "name": "safesetid_file_read",
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
ssize_t safesetid_file_read(struct file * file, char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289670720,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:209",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289670720,
      "name": "safesetid_file_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
ssize_t safesetid_file_read(struct file * file, char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274742320,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:209",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274742320,
      "name": "safesetid_file_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
ssize_t safesetid_file_read(struct file * file, char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583742224,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:209",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583742224,
      "name": "safesetid_file_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
ssize_t safesetid_file_read(struct file * file, char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583679280,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:209",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583679280,
      "name": "safesetid_file_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
ssize_t safesetid_file_read(struct file * file, char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583726000,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:209",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583726000,
      "name": "safesetid_file_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
ssize_t safesetid_file_read(struct file * file, char * buf, size_t len, loff_t * ppos)
```

```json
{
  "name": "safesetid_file_read",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583826752,
      "name": "safesetid_file_read",
      "external": false,
      "loc": "security/safesetid/securityfs.c:209",
      "file": "security/safesetid/securityfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583826752,
      "name": "safesetid_file_read",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
ssize_t safesetid_file_read(struct file * file, char * buf, size_t len, loff_t * ppos)
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
ssize_t safesetid_file_read(struct file * file, char * buf, size_t len, loff_t * ppos)
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
