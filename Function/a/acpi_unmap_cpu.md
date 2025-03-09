# Function: <code>acpi_unmap_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579170064,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:732",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579170064,
      "name": "acpi_unmap_cpu",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579171584,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:739",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579171584,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579181680,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:744",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181680,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579180608,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:760",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180608,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579196080,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:778",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196080,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579207968,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:784",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579207968,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579231552,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:785",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579231552,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579244880,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:768",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244880,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579247072,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:768",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579247072,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579271568,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:769",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579271568,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579278992,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:769",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579278992,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579281760,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:769",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579281760,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579324928,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:767",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579324928,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579384752,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:835",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384752,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579462000,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:848",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579462000,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579474576,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:857",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579474576,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579505344,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:866",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579505344,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497426792,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "drivers/acpi/acpi_processor.c:171",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497426792,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_WEAK",
      "size": 28
    }
  ]
}
```
</details>
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
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579245920,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:768",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579245920,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579181360,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:768",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579181360,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579246976,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:768",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579246976,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
int acpi_unmap_cpu(int cpu)
```

```json
{
  "name": "acpi_unmap_cpu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579252544,
      "name": "acpi_unmap_cpu",
      "external": true,
      "loc": "arch/x86/kernel/acpi/boot.c:768",
      "file": "arch/x86/kernel/acpi/boot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579252544,
      "name": "acpi_unmap_cpu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_unmap_cpu(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_unmap_cpu(int cpu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_unmap_cpu(int cpu)
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
