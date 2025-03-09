# Function: <code>show_opcodes</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579049507,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:95",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_ip",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049507,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 225
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:93",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_ip",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054483,
      "name": "show_opcodes.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071579054192,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:93",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_ip",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062261,
      "name": "show_opcodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071579061888,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:93",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_ip",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064357,
      "name": "show_opcodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071579063984,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:109",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_ip",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579072722,
      "name": "show_opcodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    },
    {
      "addr": 18446744071579071936,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:119",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_ip",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591244974,
      "name": "show_opcodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579076064,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:119",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_ip",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591188769,
      "name": "show_opcodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579083040,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:119",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_ip",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592052331,
      "name": "show_opcodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579106000,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:113",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_ip",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593819034,
      "name": "show_opcodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071579136592,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
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
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579178176,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:113",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579178176,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579181600,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:113",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181600,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579210816,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:113",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579210816,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:93",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_ip",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064709,
      "name": "show_opcodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071579064336,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:93",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_ip",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578997461,
      "name": "show_opcodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071578997088,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:93",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_ip",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579064293,
      "name": "show_opcodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071579063920,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```

```json
{
  "name": "show_opcodes",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "show_opcodes",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:93",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:show_ip",
        "arch/x86/mm/fault.c:__bad_area_nosemaphore"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068357,
      "name": "show_opcodes.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071579067984,
      "name": "show_opcodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void show_opcodes(struct pt_regs * regs, const char * loglvl)
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
