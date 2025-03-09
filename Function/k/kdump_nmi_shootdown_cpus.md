# Function: <code>kdump_nmi_shootdown_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579228079,
      "name": "kdump_nmi_shootdown_cpus",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:131",
      "file": "arch/x86/kernel/crash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
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
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579227913,
      "name": "kdump_nmi_shootdown_cpus",
      "external": false,
      "loc": "arch/x86/kernel/crash.c:136",
      "file": "arch/x86/kernel/crash.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/crash.c:native_machine_crash_shutdown"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240224,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:136",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240224,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579236256,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:137",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236256,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579252688,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:137",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252688,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579264128,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:106",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579264128,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579288720,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:107",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579288720,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305104,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:99",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305104,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579309200,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:99",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579309200,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579338064,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:114",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338064,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579338064,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:114",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579338064,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579341840,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:114",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579341840,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579399280,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:101",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579399280,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579465088,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:101",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579465088,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579556416,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:91",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579556416,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568704,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:91",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568704,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579597728,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:65",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579597728,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305104,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:99",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305104,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579239584,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:99",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579239584,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305104,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:99",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305104,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kdump_nmi_shootdown_cpus()
```

```json
{
  "name": "kdump_nmi_shootdown_cpus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579313312,
      "name": "kdump_nmi_shootdown_cpus",
      "external": true,
      "loc": "arch/x86/kernel/crash.c:99",
      "file": "arch/x86/kernel/crash.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579313312,
      "name": "kdump_nmi_shootdown_cpus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void kdump_nmi_shootdown_cpus()
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void kdump_nmi_shootdown_cpus()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void kdump_nmi_shootdown_cpus()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void kdump_nmi_shootdown_cpus()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void kdump_nmi_shootdown_cpus()
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
