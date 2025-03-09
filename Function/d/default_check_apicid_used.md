# Function: <code>default_check_apicid_used</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Duplicate ❓</summary>

```c
long unsigned int default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578999472,
      "name": "default_check_apicid_used",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:588",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579191696,
      "name": "default_check_apicid_used",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:588",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578999472,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071579191696,
      "name": "default_check_apicid_used",
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
long unsigned int default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578996400,
      "name": "default_check_apicid_used",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:595",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579192080,
      "name": "default_check_apicid_used",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:595",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578996400,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579192080,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
long unsigned int default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578998224,
      "name": "default_check_apicid_used",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:595",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579203824,
      "name": "default_check_apicid_used",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:595",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578998224,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579203824,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
long unsigned int default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Static Duplication",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578959744,
      "name": "default_check_apicid_used",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:575",
      "file": "arch/x86/xen/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071579201712,
      "name": "default_check_apicid_used",
      "external": false,
      "loc": "arch/x86/include/asm/apic.h:575",
      "file": "arch/x86/kernel/apic/apic_noop.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578959744,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579201712,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579217008,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217008,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229296,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229296,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579252992,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252992,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267008,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267008,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268656,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268656,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579296640,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579296640,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579301888,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579301888,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579304752,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579304752,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579352784,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579352784,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414864,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414864,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497344,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497344,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579509520,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509520,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
bool default_check_apicid_used(physid_mask_t * map, u32 apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579537536,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:21",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537536,
      "name": "default_check_apicid_used",
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267360,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267360,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202784,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202784,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268560,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268560,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```

```json
{
  "name": "default_check_apicid_used",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274160,
      "name": "default_check_apicid_used",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic_common.c:19",
      "file": "arch/x86/kernel/apic/apic_common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274160,
      "name": "default_check_apicid_used",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int apicid</code> ➡️ <code>u32 apicid</code>
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
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool default_check_apicid_used(physid_mask_t * map, int apicid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool default_check_apicid_used(physid_mask_t * map, int apicid)
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
