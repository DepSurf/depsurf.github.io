# Function: <code>verify_dirent_name</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581941072,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:110",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581941072,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582171856,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:110",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582171856,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582218448,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:110",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582218448,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582244656,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:110",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:compat_fillonedir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir",
        "fs/readdir.c:fillonedir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582244656,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582562480,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:110",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:compat_fillonedir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir",
        "fs/readdir.c:fillonedir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582562480,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583091760,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:110",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:compat_fillonedir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir",
        "fs/readdir.c:fillonedir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583091760,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583659760,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:110",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:compat_fillonedir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir",
        "fs/readdir.c:fillonedir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583659760,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583877136,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:146",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:compat_fillonedir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir",
        "fs/readdir.c:fillonedir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583877136,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584084176,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:150",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:compat_filldir",
        "fs/readdir.c:compat_fillonedir",
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir",
        "fs/readdir.c:fillonedir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584084176,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493429568,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:110",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493429568,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227009424,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:110",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227009424,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286987504,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:110",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286987504,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273130242,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:110",
      "file": "fs/readdir.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581909808,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:110",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581909808,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581847392,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:110",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581847392,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581901120,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:110",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581901120,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
int verify_dirent_name(const char * name, int len)
```

```json
{
  "name": "verify_dirent_name",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581970736,
      "name": "verify_dirent_name",
      "external": false,
      "loc": "fs/readdir.c:110",
      "file": "fs/readdir.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/readdir.c:filldir64",
        "fs/readdir.c:filldir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581970736,
      "name": "verify_dirent_name",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
int verify_dirent_name(const char * name, int len)
```
</details>
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
int verify_dirent_name(const char * name, int len)
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
