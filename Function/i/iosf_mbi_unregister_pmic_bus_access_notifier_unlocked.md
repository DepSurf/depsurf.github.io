# Function: <code>iosf_mbi_unregister_pmic_bus_access_notifier_unlocked</code>

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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402864,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:221",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402864,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579433680,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:400",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579433680,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:391",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579450348,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 18
    },
    {
      "addr": 18446744071579449184,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579452784,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:415",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579452784,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579474804,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:415",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474048,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579470948,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:415",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579470192,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579473060,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:415",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579472304,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579538548,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:415",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537984,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579626740,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:415",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579626048,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579740436,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:415",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579739600,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579786916,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:415",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579786096,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579820692,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:415",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579819872,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579448624,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:415",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448624,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579377600,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:415",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579377600,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579448544,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:415",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579448544,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```

```json
{
  "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579458096,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "external": true,
      "loc": "arch/x86/platform/intel/iosf_mbi.c:415",
      "file": "arch/x86/platform/intel/iosf_mbi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_unregister_pmic_bus_access_notifier"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579458096,
      "name": "iosf_mbi_unregister_pmic_bus_access_notifier_unlocked",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
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
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int iosf_mbi_unregister_pmic_bus_access_notifier_unlocked(struct notifier_block * nb)
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
