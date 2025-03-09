# Function: <code>dump_common_audit_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582409845,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:211",
      "file": "security/lsm_audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lsm_audit.c:common_lsm_audit"
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
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582631253,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:211",
      "file": "security/lsm_audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lsm_audit.c:common_lsm_audit"
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
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582724357,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:211",
      "file": "security/lsm_audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lsm_audit.c:common_lsm_audit"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582816975,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:211",
      "file": "security/lsm_audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lsm_audit.c:common_lsm_audit"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582973793,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:211",
      "file": "security/lsm_audit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/lsm_audit.c:common_lsm_audit"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583173360,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:211",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583173360,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1903
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583289664,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:211",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583289664,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1981
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583477040,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:208",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583477040,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1932
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583582992,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:208",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583582992,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1932
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583935584,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:209",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583935584,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2005
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584055520,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:209",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584055520,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2025
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584083488,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:209",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584083488,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2071
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584456304,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:208",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584456304,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2104
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585090368,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:208",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585090368,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2232
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585814032,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:197",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585814032,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2232
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586045936,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:197",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586045936,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2238
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586294704,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:197",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586294704,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2242
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495362008,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:208",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495362008,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1908
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228736888,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:208",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228736888,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2072
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289373824,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:208",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289373824,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2392
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274568496,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:208",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274568496,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1904
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583551728,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:208",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583551728,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1932
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583488784,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:208",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583488784,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1932
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583535504,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:208",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583535504,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1932
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
```

```json
{
  "name": "dump_common_audit_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583632448,
      "name": "dump_common_audit_data",
      "external": false,
      "loc": "security/lsm_audit.c:208",
      "file": "security/lsm_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/lsm_audit.c:common_lsm_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583632448,
      "name": "dump_common_audit_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1932
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
void dump_common_audit_data(struct audit_buffer * ab, struct common_audit_data * a)
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
