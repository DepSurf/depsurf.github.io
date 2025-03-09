# Function: <code>uv_phys_pkg_id</code>

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
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```

```json
{
  "name": "uv_phys_pkg_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579292304,
      "name": "uv_phys_pkg_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:627",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292304,
      "name": "uv_phys_pkg_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```

```json
{
  "name": "uv_phys_pkg_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579321360,
      "name": "uv_phys_pkg_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:661",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321360,
      "name": "uv_phys_pkg_id",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```

```json
{
  "name": "uv_phys_pkg_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579324304,
      "name": "uv_phys_pkg_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:812",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579324304,
      "name": "uv_phys_pkg_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
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
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```

```json
{
  "name": "uv_phys_pkg_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579327024,
      "name": "uv_phys_pkg_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:808",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327024,
      "name": "uv_phys_pkg_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```

```json
{
  "name": "uv_phys_pkg_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_phys_pkg_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:808",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381744,
      "name": "uv_phys_pkg_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071592076655,
      "name": "uv_phys_pkg_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```

```json
{
  "name": "uv_phys_pkg_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_phys_pkg_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:814",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446736,
      "name": "uv_phys_pkg_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071593843140,
      "name": "uv_phys_pkg_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```

```json
{
  "name": "uv_phys_pkg_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_phys_pkg_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:814",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579533296,
      "name": "uv_phys_pkg_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071595966036,
      "name": "uv_phys_pkg_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```

```json
{
  "name": "uv_phys_pkg_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_phys_pkg_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:815",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579546208,
      "name": "uv_phys_pkg_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
    },
    {
      "addr": 18446744071596483702,
      "name": "uv_phys_pkg_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
u32 uv_phys_pkg_id(u32 initial_apicid, int index_msb)
```

```json
{
  "name": "uv_phys_pkg_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_phys_pkg_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:792",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579574544,
      "name": "uv_phys_pkg_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071597380007,
      "name": "uv_phys_pkg_id.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```

```json
{
  "name": "uv_phys_pkg_id",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579298240,
      "name": "uv_phys_pkg_id",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:627",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579298240,
      "name": "uv_phys_pkg_id",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
int uv_phys_pkg_id(int initial_apicid, int index_msb)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int initial_apicid</code> ➡️ <code>u32 initial_apicid</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u32</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
int uv_phys_pkg_id(int initial_apicid, int index_msb)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
