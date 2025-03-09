# Function: <code>get_kmmio_fault_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579316551,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:101",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579321376,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:108",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579321376,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579336608,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:108",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579336608,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579330752,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:108",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579330752,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579356096,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:109",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579356096,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579368336,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:109",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579368336,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579395792,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:109",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579395792,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579411168,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:109",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579411168,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579414352,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:109",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579414352,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444080,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:109",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:add_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444080,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579441680,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:109",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:add_kmmio_fault_page",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579441680,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444560,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:109",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444560,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:109",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579509328,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071592091046,
      "name": "get_kmmio_fault_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:109",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579592672,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071593858055,
      "name": "get_kmmio_fault_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:115",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579703824,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071595970920,
      "name": "get_kmmio_fault_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:115",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579717312,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071596488503,
      "name": "get_kmmio_fault_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:115",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579752032,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 164
    },
    {
      "addr": 18446744071597385125,
      "name": "get_kmmio_fault_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579410192,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:109",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410192,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579339504,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:109",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579339504,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579410112,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:109",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579410112,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```

```json
{
  "name": "get_kmmio_fault_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579418976,
      "name": "get_kmmio_fault_page",
      "external": false,
      "loc": "arch/x86/mm/kmmio.c:109",
      "file": "arch/x86/mm/kmmio.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/kmmio.c:unregister_kmmio_probe",
        "arch/x86/mm/kmmio.c:register_kmmio_probe",
        "arch/x86/mm/kmmio.c:kmmio_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579418976,
      "name": "get_kmmio_fault_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
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
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct kmmio_fault_page * get_kmmio_fault_page(long unsigned int addr)
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
