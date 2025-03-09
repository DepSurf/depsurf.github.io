# Function: <code>hibernation_available</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579692965,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:68",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579693968,
      "name": "hibernation_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579712069,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:69",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579713056,
      "name": "hibernation_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579739605,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:69",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579740592,
      "name": "hibernation_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579735989,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:71",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579736720,
      "name": "hibernation_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579769296,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:71",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579769296,
      "name": "hibernation_available",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803568,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:71",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803568,
      "name": "hibernation_available",
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
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579850192,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:71",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579850192,
      "name": "hibernation_available",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579884256,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:69",
      "file": "kernel/power/hibernate.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579884256,
      "name": "hibernation_available",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579934325,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:70",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934976,
      "name": "hibernation_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579978629,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:82",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:is_hibernate_resume_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579979024,
      "name": "hibernation_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579967240,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:82",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:is_hibernate_resume_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965136,
      "name": "hibernation_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579969832,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:82",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:is_hibernate_resume_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579967776,
      "name": "hibernation_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580100956,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:83",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:is_hibernate_resume_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098880,
      "name": "hibernation_available",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580240036,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:82",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:is_hibernate_resume_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580237376,
      "name": "hibernation_available",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580435330,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:82",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:is_hibernate_resume_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580431312,
      "name": "hibernation_available",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580503951,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:83",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume_initcall",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:is_hibernate_resume_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580500544,
      "name": "hibernation_available",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580563823,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:83",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:resume_store",
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume_initcall",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open",
        "kernel/power/user.c:is_hibernate_resume_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580560432,
      "name": "hibernation_available",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernation_available",
      "external": false,
      "loc": "include/linux/suspend.h:464",
      "file": "kernel/power/main.c",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225141840,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:70",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225142640,
      "name": "hibernation_available",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernation_available",
      "external": false,
      "loc": "include/linux/suspend.h:464",
      "file": "kernel/power/main.c",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "hibernation_available",
      "external": false,
      "loc": "include/linux/suspend.h:464",
      "file": "kernel/power/main.c",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579902165,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:70",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579902816,
      "name": "hibernation_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579841381,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:70",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842032,
      "name": "hibernation_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579894597,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:70",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579895248,
      "name": "hibernation_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool hibernation_available()
```

```json
{
  "name": "hibernation_available",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579940581,
      "name": "hibernation_available",
      "external": true,
      "loc": "kernel/power/hibernate.c:70",
      "file": "kernel/power/hibernate.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/hibernate.c:disk_store",
        "kernel/power/hibernate.c:software_resume",
        "kernel/power/hibernate.c:hibernate"
      ],
      "caller_func": [
        "kernel/power/main.c:state_show",
        "kernel/power/user.c:snapshot_open"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941232,
      "name": "hibernation_available",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
bool hibernation_available()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool hibernation_available()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool hibernation_available()
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
