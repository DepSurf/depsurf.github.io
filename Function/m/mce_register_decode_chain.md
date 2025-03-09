# Function: <code>mce_register_decode_chain</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579122256,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:212",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579122256,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595176809,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:209",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579122560,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579129328,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:216",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579129328,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579129584,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:159",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:dev_mcelog_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579129584,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579144160,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:168",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:dev_mcelog_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579144160,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579154704,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mcheck/mce.c:163",
      "file": "arch/x86/kernel/cpu/mcheck/mce.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init",
        "arch/x86/kernel/cpu/mcheck/mce.c:mcheck_init",
        "arch/x86/kernel/cpu/mcheck/dev-mcelog.c:dev_mcelog_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579154704,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579144144,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:161",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579144144,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:178",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579167591,
      "name": "mce_register_decode_chain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071579156656,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579159104,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:178",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579159104,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609079929,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:163",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579177664,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579174288,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:163",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579174288,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579181232,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:163",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181232,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579215168,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:163",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579215168,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579266352,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:149",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266352,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627601957,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:149",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579328672,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619356021,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:143",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579337248,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071621650037,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:145",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init"
      ],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579367120,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579159472,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:178",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579159472,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579090784,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:178",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device",
        "drivers/acpi/nfit/mce.c:nfit_mce_register",
        "drivers/edac/mce_amd.c:mce_amd_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579090784,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579159024,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:178",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579159024,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void mce_register_decode_chain(struct notifier_block * nb)
```

```json
{
  "name": "mce_register_decode_chain",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579164160,
      "name": "mce_register_decode_chain",
      "external": true,
      "loc": "arch/x86/kernel/cpu/mce/core.c:178",
      "file": "arch/x86/kernel/cpu/mce/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/core.c:mcheck_init",
        "arch/x86/kernel/cpu/mce/dev-mcelog.c:dev_mcelog_init_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579164160,
      "name": "mce_register_decode_chain",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void mce_register_decode_chain(struct notifier_block * nb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void mce_register_decode_chain(struct notifier_block * nb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void mce_register_decode_chain(struct notifier_block * nb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void mce_register_decode_chain(struct notifier_block * nb)
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
