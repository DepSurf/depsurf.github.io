# Function: <code>common_mmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int common_mmap(const char * op, struct file * file, long unsigned int prot, long unsigned int flags)
```

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582534976,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:500",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582534976,
      "name": "common_mmap",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int common_mmap(const char * op, struct file * file, long unsigned int prot, long unsigned int flags)
```

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582774048,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:473",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582774048,
      "name": "common_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int common_mmap(const char * op, struct file * file, long unsigned int prot, long unsigned int flags)
```

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582872880,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:476",
      "file": "security/apparmor/lsm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582872880,
      "name": "common_mmap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582942149,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:459",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582942064,
      "name": "common_mmap.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583102949,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:459",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583102864,
      "name": "common_mmap.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583309150,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:488",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583309072,
      "name": "common_mmap.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583426382,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:483",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583426304,
      "name": "common_mmap.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583611982,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:479",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583611904,
      "name": "common_mmap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583718158,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:479",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718080,
      "name": "common_mmap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584098079,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:494",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_mmap_file"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584215255,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:494",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_mmap_file"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584241851,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:503",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_mmap_file"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584627531,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:503",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_mmap_file"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585286173,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:696",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_mmap_file"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586019209,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:738",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_mmap_file"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586260317,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:736",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_mmap_file"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586513453,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:734",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_file_mprotect",
        "security/apparmor/lsm.c:apparmor_mmap_file",
        "security/apparmor/lsm.c:apparmor_mmap_file"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495513376,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:479",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495513224,
      "name": "common_mmap.part.0",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228882148,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:479",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228882040,
      "name": "common_mmap.part.0",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289585340,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:479",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289585216,
      "name": "common_mmap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274693078,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:479",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274692944,
      "name": "common_mmap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583686894,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:479",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583686816,
      "name": "common_mmap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583623950,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:479",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583623872,
      "name": "common_mmap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583670670,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:479",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583670592,
      "name": "common_mmap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "common_mmap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583769278,
      "name": "common_mmap",
      "external": false,
      "loc": "security/apparmor/lsm.c:479",
      "file": "security/apparmor/lsm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ],
      "caller_func": [
        "security/apparmor/lsm.c:apparmor_file_mprotect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583769200,
      "name": "common_mmap.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int common_mmap(const char * op, struct file * file, long unsigned int prot, long unsigned int flags)
```
</details>
</li>
</ul>
