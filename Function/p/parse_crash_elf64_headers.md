# Function: <code>parse_crash_elf64_headers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595169374,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:999",
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
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595343832,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1002",
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
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595592178,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1002",
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
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596522141,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1002",
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
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602849586,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1002",
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
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603023194,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1161",
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
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604821705,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1183",
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604923990,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1188",
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
      "addr": 18446744071604923990,
      "name": "parse_crash_elf64_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1147
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604959278,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1188",
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
      "addr": 18446744071604959278,
      "name": "parse_crash_elf64_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1153
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609262830,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1188",
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
      "addr": 18446744071609262830,
      "name": "parse_crash_elf64_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 570
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612331485,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1188",
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
      "addr": 18446744071612331485,
      "name": "parse_crash_elf64_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 580
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614471822,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1188",
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
      "addr": 18446744071614471822,
      "name": "parse_crash_elf64_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 581
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615417783,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1192",
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
      "addr": 18446744071615417783,
      "name": "parse_crash_elf64_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 588
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617212001,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1210",
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
      "addr": 18446744071617212001,
      "name": "parse_crash_elf64_headers",
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627915696,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1209",
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
      "addr": 18446744071627915696,
      "name": "parse_crash_elf64_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 720
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619678768,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1208",
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
      "addr": 18446744071619678768,
      "name": "parse_crash_elf64_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 714
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621984976,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1208",
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
      "addr": 18446744071621984976,
      "name": "parse_crash_elf64_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 770
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511001576,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1188",
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
      "addr": 18446603336511001576,
      "name": "parse_crash_elf64_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1164
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
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243481440,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1188",
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055302663792,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1188",
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
      "addr": 13835058055302663792,
      "name": "parse_crash_elf64_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1412
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604864738,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1188",
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
      "addr": 18446744071604864738,
      "name": "parse_crash_elf64_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1153
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604833790,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1188",
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
      "addr": 18446744071604833790,
      "name": "parse_crash_elf64_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1153
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604941922,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1188",
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
      "addr": 18446744071604941922,
      "name": "parse_crash_elf64_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1153
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
int parse_crash_elf64_headers()
```

```json
{
  "name": "parse_crash_elf64_headers",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071604963448,
      "name": "parse_crash_elf64_headers",
      "external": false,
      "loc": "fs/proc/vmcore.c:1188",
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
      "addr": 18446744071604963448,
      "name": "parse_crash_elf64_headers",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 1153
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
int parse_crash_elf64_headers()
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
int parse_crash_elf64_headers()
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
int parse_crash_elf64_headers()
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
