# Function: <code>apic_soft_disable</code>

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
void apic_soft_disable()
```

```json
{
  "name": "apic_soft_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579266000,
      "name": "apic_soft_disable",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1246",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266000,
      "name": "apic_soft_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void apic_soft_disable()
```

```json
{
  "name": "apic_soft_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579293648,
      "name": "apic_soft_disable",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1198",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293648,
      "name": "apic_soft_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void apic_soft_disable()
```

```json
{
  "name": "apic_soft_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579299664,
      "name": "apic_soft_disable",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1207",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579299664,
      "name": "apic_soft_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void apic_soft_disable()
```

```json
{
  "name": "apic_soft_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579302512,
      "name": "apic_soft_disable",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1207",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302512,
      "name": "apic_soft_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void apic_soft_disable()
```

```json
{
  "name": "apic_soft_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579350176,
      "name": "apic_soft_disable",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1204",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579350176,
      "name": "apic_soft_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void apic_soft_disable()
```

```json
{
  "name": "apic_soft_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411952,
      "name": "apic_soft_disable",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1213",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411952,
      "name": "apic_soft_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void apic_soft_disable()
```

```json
{
  "name": "apic_soft_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579493872,
      "name": "apic_soft_disable",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1209",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579493872,
      "name": "apic_soft_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void apic_soft_disable()
```

```json
{
  "name": "apic_soft_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579506128,
      "name": "apic_soft_disable",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1211",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579506128,
      "name": "apic_soft_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
void apic_soft_disable()
```

```json
{
  "name": "apic_soft_disable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579535225,
      "name": "apic_soft_disable",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1177",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic.c:disable_local_APIC"
      ],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579535104,
      "name": "apic_soft_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void apic_soft_disable()
```

```json
{
  "name": "apic_soft_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579264704,
      "name": "apic_soft_disable",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1246",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264704,
      "name": "apic_soft_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void apic_soft_disable()
```

```json
{
  "name": "apic_soft_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579200192,
      "name": "apic_soft_disable",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1246",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579200192,
      "name": "apic_soft_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void apic_soft_disable()
```

```json
{
  "name": "apic_soft_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579265904,
      "name": "apic_soft_disable",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1246",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579265904,
      "name": "apic_soft_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void apic_soft_disable()
```

```json
{
  "name": "apic_soft_disable",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579271504,
      "name": "apic_soft_disable",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:1246",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/smpboot.c:native_cpu_disable",
        "arch/x86/kernel/apic/apic.c:lapic_shutdown"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271504,
      "name": "apic_soft_disable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 63
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
void apic_soft_disable()
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
void apic_soft_disable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void apic_soft_disable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void apic_soft_disable()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void apic_soft_disable()
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
