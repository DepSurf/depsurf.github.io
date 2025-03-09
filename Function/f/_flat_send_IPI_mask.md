# Function: <code>_flat_send_IPI_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579215313,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:56",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579215376,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:56",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579215376,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579227168,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:56",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579227168,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579224896,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:56",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579224896,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240576,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:56",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240576,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579253120,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:57",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253120,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276928,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:58",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276928,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291264,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:58",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291264,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579297248,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:51",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297248,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579327136,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:51",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579327136,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579328720,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:51",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579328720,
      "name": "_flat_send_IPI_mask",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579331424,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:51",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579331424,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386688,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:51",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386688,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452656,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:51",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452656,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579541056,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:51",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579541056,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579554304,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:51",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579554304,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579581824,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:31",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579581824,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579293056,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:51",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579293056,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579228608,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:51",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579228608,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579294256,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:51",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294256,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```

```json
{
  "name": "_flat_send_IPI_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579303088,
      "name": "_flat_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/apic_flat_64.c:51",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579303088,
      "name": "_flat_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void _flat_send_IPI_mask(long unsigned int mask, int vector)
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
