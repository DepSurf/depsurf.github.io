# Function: <code>mmap_violation_check</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583678282,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:76",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583784995,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:76",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int mmap_violation_check(enum ima_hooks func, struct file * file, char * * pathbuf, const char * * pathname, char * filename)
```

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584174864,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:74",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174864,
      "name": "mmap_violation_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int mmap_violation_check(enum ima_hooks func, struct file * file, char * * pathbuf, const char * * pathname, char * filename)
```

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584293728,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:80",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584293728,
      "name": "mmap_violation_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int mmap_violation_check(enum ima_hooks func, struct file * file, char * * pathbuf, const char * * pathname, char * filename)
```

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584327648,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:80",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584327648,
      "name": "mmap_violation_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int mmap_violation_check(enum ima_hooks func, struct file * file, char * * pathbuf, const char * * pathname, char * filename)
```

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584715136,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:85",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584715136,
      "name": "mmap_violation_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int mmap_violation_check(enum ima_hooks func, struct file * file, char * * pathbuf, const char * * pathname, char * filename)
```

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585389920,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:85",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585389920,
      "name": "mmap_violation_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int mmap_violation_check(enum ima_hooks func, struct file * file, char * * pathbuf, const char * * pathname, char * filename)
```

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586142560,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:85",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586142560,
      "name": "mmap_violation_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
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
int mmap_violation_check(enum ima_hooks func, struct file * file, char * * pathbuf, const char * * pathname, char * filename)
```

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586380672,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:84",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586380672,
      "name": "mmap_violation_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
int mmap_violation_check(enum ima_hooks func, struct file * file, char * * pathbuf, const char * * pathname, char * filename)
```

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586645264,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:85",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586645264,
      "name": "mmap_violation_check",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495588176,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:76",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228949180,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:76",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289688232,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:76",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274752956,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:76",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583753731,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:76",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583690787,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:76",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583737507,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:76",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mmap_violation_check",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583838435,
      "name": "mmap_violation_check",
      "external": false,
      "loc": "security/integrity/ima/ima_main.c:76",
      "file": "security/integrity/ima/ima_main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int mmap_violation_check(enum ima_hooks func, struct file * file, char * * pathbuf, const char * * pathname, char * filename)
```
</details>
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
