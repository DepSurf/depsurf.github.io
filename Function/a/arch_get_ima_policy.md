# Function: <code>arch_get_ima_policy</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
const const char * * arch_get_ima_policy()
```

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579339984,
      "name": "arch_get_ima_policy",
      "external": true,
      "loc": "arch/x86/kernel/ima_arch.c:70",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_arch_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579339984,
      "name": "arch_get_ima_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
const const char * * arch_get_ima_policy()
```

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579355296,
      "name": "arch_get_ima_policy",
      "external": true,
      "loc": "arch/x86/kernel/ima_arch.c:88",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_arch_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355296,
      "name": "arch_get_ima_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
const const char * * arch_get_ima_policy()
```

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579359568,
      "name": "arch_get_ima_policy",
      "external": true,
      "loc": "arch/x86/kernel/ima_arch.c:86",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_arch_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579359568,
      "name": "arch_get_ima_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_get_ima_policy",
      "external": false,
      "loc": "include/linux/ima.h:43",
      "file": "security/integrity/ima/ima_policy.c",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_get_ima_policy",
      "external": false,
      "loc": "include/linux/ima.h:54",
      "file": "security/integrity/ima/ima_policy.c",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_get_ima_policy",
      "external": false,
      "loc": "include/linux/ima.h:60",
      "file": "security/integrity/ima/ima_policy.c",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_get_ima_policy",
      "external": false,
      "loc": "include/linux/ima.h:62",
      "file": "security/integrity/ima/ima_policy.c",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
const const char * * arch_get_ima_policy()
```

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_get_ima_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_efi.c:65",
      "file": "security/integrity/ima/ima_efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_arch_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594092438,
      "name": "arch_get_ima_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071585434000,
      "name": "arch_get_ima_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
const const char * * arch_get_ima_policy()
```

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_get_ima_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_efi.c:65",
      "file": "security/integrity/ima/ima_efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_arch_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596103228,
      "name": "arch_get_ima_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586191200,
      "name": "arch_get_ima_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
const const char * * arch_get_ima_policy()
```

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_get_ima_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_efi.c:65",
      "file": "security/integrity/ima/ima_efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_arch_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596626334,
      "name": "arch_get_ima_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586428928,
      "name": "arch_get_ima_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
const const char * * arch_get_ima_policy()
```

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_get_ima_policy",
      "external": true,
      "loc": "security/integrity/ima/ima_efi.c:68",
      "file": "security/integrity/ima/ima_efi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_arch_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597531976,
      "name": "arch_get_ima_policy.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586694080,
      "name": "arch_get_ima_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_get_ima_policy",
      "external": false,
      "loc": "include/linux/ima.h:42",
      "file": "security/integrity/ima/ima_policy.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_get_ima_policy",
      "external": false,
      "loc": "include/linux/ima.h:42",
      "file": "security/integrity/ima/ima_policy.c",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
const const char * * arch_get_ima_policy()
```

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282709968,
      "name": "arch_get_ima_policy",
      "external": true,
      "loc": "arch/powerpc/kernel/ima_arch.c:63",
      "file": "arch/powerpc/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_arch_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282709968,
      "name": "arch_get_ima_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "arch_get_ima_policy",
      "external": false,
      "loc": "include/linux/ima.h:42",
      "file": "security/integrity/ima/ima_policy.c",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
const const char * * arch_get_ima_policy()
```

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579355472,
      "name": "arch_get_ima_policy",
      "external": true,
      "loc": "arch/x86/kernel/ima_arch.c:86",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_arch_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355472,
      "name": "arch_get_ima_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
const const char * * arch_get_ima_policy()
```

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579287744,
      "name": "arch_get_ima_policy",
      "external": true,
      "loc": "arch/x86/kernel/ima_arch.c:86",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_arch_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579287744,
      "name": "arch_get_ima_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
const const char * * arch_get_ima_policy()
```

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579355392,
      "name": "arch_get_ima_policy",
      "external": true,
      "loc": "arch/x86/kernel/ima_arch.c:86",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_arch_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579355392,
      "name": "arch_get_ima_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
const const char * * arch_get_ima_policy()
```

```json
{
  "name": "arch_get_ima_policy",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579363840,
      "name": "arch_get_ima_policy",
      "external": true,
      "loc": "arch/x86/kernel/ima_arch.c:86",
      "file": "arch/x86/kernel/ima_arch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_policy.c:ima_init_arch_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579363840,
      "name": "arch_get_ima_policy",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
const const char * * arch_get_ima_policy()
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
const const char * * arch_get_ima_policy()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
const const char * * arch_get_ima_policy()
```
</details>
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
const const char * * arch_get_ima_policy()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
const const char * * arch_get_ima_policy()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
const const char * * arch_get_ima_policy()
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
