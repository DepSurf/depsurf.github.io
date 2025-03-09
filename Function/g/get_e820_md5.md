# Function: <code>get_e820_md5</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int get_e820_md5(struct e820map * map, void * buf)
```

```json
{
  "name": "get_e820_md5",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586764192,
      "name": "get_e820_md5",
      "external": false,
      "loc": "arch/x86/power/hibernate_64.c:203",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:arch_hibernation_header_restore",
        "arch/x86/power/hibernate_64.c:arch_hibernation_header_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764192,
      "name": "get_e820_md5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int get_e820_md5(struct e820_table * table, void * buf)
```

```json
{
  "name": "get_e820_md5",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586887472,
      "name": "get_e820_md5",
      "external": false,
      "loc": "arch/x86/power/hibernate_64.c:224",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:arch_hibernation_header_restore",
        "arch/x86/power/hibernate_64.c:arch_hibernation_header_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586887472,
      "name": "get_e820_md5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int get_e820_md5(struct e820_table * table, void * buf)
```

```json
{
  "name": "get_e820_md5",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587376288,
      "name": "get_e820_md5",
      "external": false,
      "loc": "arch/x86/power/hibernate_64.c:224",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:arch_hibernation_header_restore",
        "arch/x86/power/hibernate_64.c:arch_hibernation_header_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587376288,
      "name": "get_e820_md5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
int get_e820_md5(struct e820_table * table, void * buf)
```

```json
{
  "name": "get_e820_md5",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587680144,
      "name": "get_e820_md5",
      "external": false,
      "loc": "arch/x86/power/hibernate_64.c:234",
      "file": "arch/x86/power/hibernate_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate_64.c:arch_hibernation_header_restore",
        "arch/x86/power/hibernate_64.c:arch_hibernation_header_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587680144,
      "name": "get_e820_md5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 338
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
int get_e820_md5(struct e820_table * table, void * buf)
```

```json
{
  "name": "get_e820_md5",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587819648,
      "name": "get_e820_md5",
      "external": false,
      "loc": "arch/x86/power/hibernate.c:74",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate.c:arch_hibernation_header_restore",
        "arch/x86/power/hibernate.c:arch_hibernation_header_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587819648,
      "name": "get_e820_md5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 174
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
int get_e820_md5(struct e820_table * table, void * buf)
```

```json
{
  "name": "get_e820_md5",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588122752,
      "name": "get_e820_md5",
      "external": false,
      "loc": "arch/x86/power/hibernate.c:75",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate.c:arch_hibernation_header_restore",
        "arch/x86/power/hibernate.c:arch_hibernation_header_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588122752,
      "name": "get_e820_md5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int get_e820_md5(struct e820_table * table, void * buf)
```

```json
{
  "name": "get_e820_md5",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588327552,
      "name": "get_e820_md5",
      "external": false,
      "loc": "arch/x86/power/hibernate.c:75",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate.c:arch_hibernation_header_restore",
        "arch/x86/power/hibernate.c:arch_hibernation_header_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588327552,
      "name": "get_e820_md5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int get_e820_md5(struct e820_table * table, void * buf)
```

```json
{
  "name": "get_e820_md5",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591149728,
      "name": "get_e820_md5",
      "external": false,
      "loc": "arch/x86/power/hibernate.c:75",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate.c:arch_hibernation_header_restore",
        "arch/x86/power/hibernate.c:arch_hibernation_header_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591149728,
      "name": "get_e820_md5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int get_e820_md5(struct e820_table * table, void * buf)
```

```json
{
  "name": "get_e820_md5",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591235712,
      "name": "get_e820_md5",
      "external": false,
      "loc": "arch/x86/power/hibernate.c:75",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate.c:arch_hibernation_header_restore",
        "arch/x86/power/hibernate.c:arch_hibernation_header_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591235712,
      "name": "get_e820_md5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
int get_e820_md5(struct e820_table * table, void * buf)
```

```json
{
  "name": "get_e820_md5",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587934336,
      "name": "get_e820_md5",
      "external": false,
      "loc": "arch/x86/power/hibernate.c:75",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate.c:arch_hibernation_header_restore",
        "arch/x86/power/hibernate.c:arch_hibernation_header_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587934336,
      "name": "get_e820_md5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int get_e820_md5(struct e820_table * table, void * buf)
```

```json
{
  "name": "get_e820_md5",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587647616,
      "name": "get_e820_md5",
      "external": false,
      "loc": "arch/x86/power/hibernate.c:75",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate.c:arch_hibernation_header_restore",
        "arch/x86/power/hibernate.c:arch_hibernation_header_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587647616,
      "name": "get_e820_md5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int get_e820_md5(struct e820_table * table, void * buf)
```

```json
{
  "name": "get_e820_md5",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588266112,
      "name": "get_e820_md5",
      "external": false,
      "loc": "arch/x86/power/hibernate.c:75",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate.c:arch_hibernation_header_restore",
        "arch/x86/power/hibernate.c:arch_hibernation_header_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588266112,
      "name": "get_e820_md5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
int get_e820_md5(struct e820_table * table, void * buf)
```

```json
{
  "name": "get_e820_md5",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588401280,
      "name": "get_e820_md5",
      "external": false,
      "loc": "arch/x86/power/hibernate.c:75",
      "file": "arch/x86/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/power/hibernate.c:arch_hibernation_header_restore",
        "arch/x86/power/hibernate.c:arch_hibernation_header_save"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588401280,
      "name": "get_e820_md5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
int get_e820_md5(struct e820map * map, void * buf)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct e820_table * table</code>
</li>
<li>
<b>Param removed. </b>
<code>struct e820map * map</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int get_e820_md5(struct e820_table * table, void * buf)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int get_e820_md5(struct e820_table * table, void * buf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int get_e820_md5(struct e820_table * table, void * buf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int get_e820_md5(struct e820_table * table, void * buf)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int get_e820_md5(struct e820_table * table, void * buf)
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
