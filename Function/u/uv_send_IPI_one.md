# Function: <code>uv_send_IPI_one</code>

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
void uv_send_IPI_one(int cpu, int vector)
```

```json
{
  "name": "uv_send_IPI_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579292000,
      "name": "uv_send_IPI_one",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:542",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292000,
      "name": "uv_send_IPI_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void uv_send_IPI_one(int cpu, int vector)
```

```json
{
  "name": "uv_send_IPI_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579322480,
      "name": "uv_send_IPI_one",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:567",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322480,
      "name": "uv_send_IPI_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 209
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
void uv_send_IPI_one(int cpu, int vector)
```

```json
{
  "name": "uv_send_IPI_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579324880,
      "name": "uv_send_IPI_one",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:724",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579324880,
      "name": "uv_send_IPI_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void uv_send_IPI_one(int cpu, int vector)
```

```json
{
  "name": "uv_send_IPI_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579327600,
      "name": "uv_send_IPI_one",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:720",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327600,
      "name": "uv_send_IPI_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
void uv_send_IPI_one(int cpu, int vector)
```

```json
{
  "name": "uv_send_IPI_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_send_IPI_one",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:720",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382256,
      "name": "uv_send_IPI_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071592076938,
      "name": "uv_send_IPI_one.cold",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void uv_send_IPI_one(int cpu, int vector)
```

```json
{
  "name": "uv_send_IPI_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_send_IPI_one",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:726",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447440,
      "name": "uv_send_IPI_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071593843410,
      "name": "uv_send_IPI_one.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void uv_send_IPI_one(int cpu, int vector)
```

```json
{
  "name": "uv_send_IPI_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_send_IPI_one",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:726",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579534352,
      "name": "uv_send_IPI_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071595966130,
      "name": "uv_send_IPI_one.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void uv_send_IPI_one(int cpu, int vector)
```

```json
{
  "name": "uv_send_IPI_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_send_IPI_one",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:727",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579547264,
      "name": "uv_send_IPI_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071596483796,
      "name": "uv_send_IPI_one.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void uv_send_IPI_one(int cpu, int vector)
```

```json
{
  "name": "uv_send_IPI_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "uv_send_IPI_one",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:728",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579575536,
      "name": "uv_send_IPI_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
    },
    {
      "addr": 18446744071597380101,
      "name": "uv_send_IPI_one.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void uv_send_IPI_one(int cpu, int vector)
```

```json
{
  "name": "uv_send_IPI_one",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579297824,
      "name": "uv_send_IPI_one",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_uv_x.c:542",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297824,
      "name": "uv_send_IPI_one",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void uv_send_IPI_one(int cpu, int vector)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void uv_send_IPI_one(int cpu, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void uv_send_IPI_one(int cpu, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void uv_send_IPI_one(int cpu, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void uv_send_IPI_one(int cpu, int vector)
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
void uv_send_IPI_one(int cpu, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void uv_send_IPI_one(int cpu, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
void uv_send_IPI_one(int cpu, int vector)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
