# Function: <code>parse_crash_elf32_headers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595169857,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1055",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595344342,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1058",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595592688,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1058",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596522621,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1058",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602850066,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1058",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603023634,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1217",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_init"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604822166,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1239",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_init"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604925137,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1244",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604925137,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1151
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
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604960431,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1244",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604960431,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1144
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
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609264161,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1244",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:parse_crash_elf_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609264161,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 552
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
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612332826,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1244",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:parse_crash_elf_headers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612332826,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 562
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
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614473164,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1244",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614473164,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 579
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
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615419132,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1248",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615419132,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 592
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
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617213435,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1266",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617213435,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 618
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
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627917504,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1265",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627917504,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 717
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
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619680576,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1264",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619680576,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 717
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
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621986848,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1264",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621986848,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 761
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
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511002740,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1244",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511002740,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1160
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
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243481484,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1244",
      "file": "fs/proc/vmcore.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/vmcore.c:vmcore_init"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302665204,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1244",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055302665204,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1396
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604865891,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1244",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604865891,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1144
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
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604834943,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1244",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604834943,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1144
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
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604943075,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1244",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604943075,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1144
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
int parse_crash_elf32_headers()
```

```json
{
  "name": "parse_crash_elf32_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604964601,
      "name": "parse_crash_elf32_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1244",
      "file": "fs/proc/vmcore.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/vmcore.c:vmcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071604964601,
      "name": "parse_crash_elf32_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1144
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
int parse_crash_elf32_headers()
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int parse_crash_elf32_headers()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int parse_crash_elf32_headers()
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
