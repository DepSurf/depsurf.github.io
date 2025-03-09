# Function: <code>__x2apic_send_IPI_shorthand</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which)
```

```json
{
  "name": "__x2apic_send_IPI_shorthand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579295285,
      "name": "__x2apic_send_IPI_shorthand",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:115",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579295440,
      "name": "__x2apic_send_IPI_shorthand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which)
```

```json
{
  "name": "__x2apic_send_IPI_shorthand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579325157,
      "name": "__x2apic_send_IPI_shorthand",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:115",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579325344,
      "name": "__x2apic_send_IPI_shorthand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void __x2apic_send_IPI_shorthand(int vector, u32 which)
```

```json
{
  "name": "__x2apic_send_IPI_shorthand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579326789,
      "name": "__x2apic_send_IPI_shorthand",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:126",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326976,
      "name": "__x2apic_send_IPI_shorthand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void __x2apic_send_IPI_shorthand(int vector, u32 which)
```

```json
{
  "name": "__x2apic_send_IPI_shorthand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579329509,
      "name": "__x2apic_send_IPI_shorthand",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:126",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329696,
      "name": "__x2apic_send_IPI_shorthand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void __x2apic_send_IPI_shorthand(int vector, u32 which)
```

```json
{
  "name": "__x2apic_send_IPI_shorthand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579384373,
      "name": "__x2apic_send_IPI_shorthand",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:126",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384560,
      "name": "__x2apic_send_IPI_shorthand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void __x2apic_send_IPI_shorthand(int vector, u32 which)
```

```json
{
  "name": "__x2apic_send_IPI_shorthand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579449877,
      "name": "__x2apic_send_IPI_shorthand",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:126",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450112,
      "name": "__x2apic_send_IPI_shorthand",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which)
```

```json
{
  "name": "__x2apic_send_IPI_shorthand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579537733,
      "name": "__x2apic_send_IPI_shorthand",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:126",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537920,
      "name": "__x2apic_send_IPI_shorthand",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which)
```

```json
{
  "name": "__x2apic_send_IPI_shorthand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579550469,
      "name": "__x2apic_send_IPI_shorthand",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:129",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550752,
      "name": "__x2apic_send_IPI_shorthand",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__x2apic_send_IPI_shorthand",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579578053,
      "name": "__x2apic_send_IPI_shorthand",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:86",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which)
```

```json
{
  "name": "__x2apic_send_IPI_shorthand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579291093,
      "name": "__x2apic_send_IPI_shorthand",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:115",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291248,
      "name": "__x2apic_send_IPI_shorthand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which)
```

```json
{
  "name": "__x2apic_send_IPI_shorthand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579226357,
      "name": "__x2apic_send_IPI_shorthand",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:115",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226720,
      "name": "__x2apic_send_IPI_shorthand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which)
```

```json
{
  "name": "__x2apic_send_IPI_shorthand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579292293,
      "name": "__x2apic_send_IPI_shorthand",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:115",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579292448,
      "name": "__x2apic_send_IPI_shorthand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which)
```

```json
{
  "name": "__x2apic_send_IPI_shorthand",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579301125,
      "name": "__x2apic_send_IPI_shorthand",
      "external": true,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:115",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301280,
      "name": "__x2apic_send_IPI_shorthand",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
void __x2apic_send_IPI_shorthand(int vector, u32 which)
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
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which)
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
void __x2apic_send_IPI_shorthand(int vector, u32 which)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __x2apic_send_IPI_shorthand(int vector, u32 which)
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
