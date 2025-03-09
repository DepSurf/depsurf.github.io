# Function: <code>uv_apicid_to_pnode</code>

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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_apicid_to_pnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604785949,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:609",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579471636,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:609",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int uv_apicid_to_pnode(int apicid)
```

```json
{
  "name": "uv_apicid_to_pnode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579322527,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:555",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579493748,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:555",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321056,
      "name": "uv_apicid_to_pnode",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int uv_apicid_to_pnode(int apicid)
```

```json
{
  "name": "uv_apicid_to_pnode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579324926,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:545",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579476212,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:545",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579323872,
      "name": "uv_apicid_to_pnode",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int uv_apicid_to_pnode(int apicid)
```

```json
{
  "name": "uv_apicid_to_pnode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579327647,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:545",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579478212,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:545",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326608,
      "name": "uv_apicid_to_pnode",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int uv_apicid_to_pnode(int apicid)
```

```json
{
  "name": "uv_apicid_to_pnode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579382326,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:545",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579544077,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:545",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381632,
      "name": "uv_apicid_to_pnode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
    },
    {
      "addr": 18446744071592076229,
      "name": "uv_apicid_to_pnode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline, Transformation ❓</summary>

```c
int uv_apicid_to_pnode(int apicid)
```

```json
{
  "name": "uv_apicid_to_pnode",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579447525,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:545",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub"
      ]
    },
    {
      "addr": 18446744071579632733,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:545",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579446624,
      "name": "uv_apicid_to_pnode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 18446744071593842786,
      "name": "uv_apicid_to_pnode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_apicid_to_pnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627685161,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:545",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579747277,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:545",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_apicid_to_pnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619442799,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:551",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579793821,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:551",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_apicid_to_pnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621738916,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:551",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579827500,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:551",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_apicid_to_pnode",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604790090,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:609",
      "file": "arch/x86/kernel/apic/x2apic_uv_x.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_send_IPI_one",
        "arch/x86/kernel/apic/x2apic_uv_x.c:uv_wakeup_secondary"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579476964,
      "name": "uv_apicid_to_pnode",
      "external": false,
      "loc": "arch/x86/include/asm/uv/uv_hub.h:609",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
int uv_apicid_to_pnode(int apicid)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
int uv_apicid_to_pnode(int apicid)
```
</details>
</li>
</ul>
