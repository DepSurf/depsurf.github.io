# Function: <code>namecmp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581484272,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:86",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:insert_header"
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
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581673242,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:86",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:insert_header"
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
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581761386,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:86",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:insert_header"
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
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581809648,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:87",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581809648,
      "name": "namecmp",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581959200,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:88",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581959200,
      "name": "namecmp",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582144208,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:88",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582144208,
      "name": "namecmp",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582238832,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:88",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582238832,
      "name": "namecmp",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582403248,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:93",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582403248,
      "name": "namecmp",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582502208,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:93",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582502208,
      "name": "namecmp",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582804000,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:94",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582804000,
      "name": "namecmp",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582877632,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:95",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582877632,
      "name": "namecmp",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582906000,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:95",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582906000,
      "name": "namecmp",
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
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583240256,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:95",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583240256,
      "name": "namecmp",
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
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583739360,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:116",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583739360,
      "name": "namecmp",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584353344,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:109",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584353344,
      "name": "namecmp",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584583664,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:101",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584583664,
      "name": "namecmp",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584815040,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:101",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584815040,
      "name": "namecmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494126808,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:93",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494126808,
      "name": "namecmp",
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
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227576292,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:93",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_header",
        "fs/proc/proc_sysctl.c:find_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227576292,
      "name": "namecmp",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287800784,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:93",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287800784,
      "name": "namecmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273613000,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:93",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:insert_header"
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
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582470944,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:93",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582470944,
      "name": "namecmp",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582408176,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:93",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582408176,
      "name": "namecmp",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582461424,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:93",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582461424,
      "name": "namecmp",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
```

```json
{
  "name": "namecmp",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582541760,
      "name": "namecmp",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:93",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:insert_header"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582541760,
      "name": "namecmp",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
int namecmp(const char * name1, int len1, const char * name2, int len2)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int namecmp(const char * name1, int len1, const char * name2, int len2)
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
