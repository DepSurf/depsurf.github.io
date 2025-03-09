# Function: <code>default_apic_id_valid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
int default_apic_id_valid(int apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579191360,
      "name": "default_apic_id_valid",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:503",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579214448,
      "name": "default_apic_id_valid",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:503",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579191360,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579214448,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Duplicate ❓</summary>

```c
int default_apic_id_valid(int apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579191744,
      "name": "default_apic_id_valid",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:510",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579215040,
      "name": "default_apic_id_valid",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:510",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579191744,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579215040,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Duplicate ❓</summary>

```c
int default_apic_id_valid(int apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579203488,
      "name": "default_apic_id_valid",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:510",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579226832,
      "name": "default_apic_id_valid",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:510",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203488,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579226832,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate ❓</summary>

```c
int default_apic_id_valid(int apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579201408,
      "name": "default_apic_id_valid",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:506",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579224560,
      "name": "default_apic_id_valid",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:506",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579201408,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579224560,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
int default_apic_id_valid(int apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579217104,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217104,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int default_apic_id_valid(u32 apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229392,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229392,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int default_apic_id_valid(u32 apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579253088,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253088,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int default_apic_id_valid(u32 apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267104,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267104,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int default_apic_id_valid(u32 apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268752,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268752,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int default_apic_id_valid(u32 apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579296736,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296736,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int default_apic_id_valid(u32 apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579301984,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301984,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int default_apic_id_valid(u32 apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579304848,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304848,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int default_apic_id_valid(u32 apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579352880,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579352880,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int default_apic_id_valid(u32 apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414992,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414992,
      "name": "default_apic_id_valid",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497520,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497520,
      "name": "default_apic_id_valid",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int default_apic_id_valid(u32 apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509696,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509696,
      "name": "default_apic_id_valid",
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
int default_apic_id_valid(u32 apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267456,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267456,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int default_apic_id_valid(u32 apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202880,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202880,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int default_apic_id_valid(u32 apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268656,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268656,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int default_apic_id_valid(u32 apicid)
```

```json
{
  "name": "default_apic_id_valid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274256,
      "name": "default_apic_id_valid",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:43",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274256,
      "name": "default_apic_id_valid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int apicid</code> ➡️ <code>u32 apicid</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
int default_apic_id_valid(u32 apicid)
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
int default_apic_id_valid(u32 apicid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int default_apic_id_valid(u32 apicid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int default_apic_id_valid(u32 apicid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int default_apic_id_valid(u32 apicid)
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
