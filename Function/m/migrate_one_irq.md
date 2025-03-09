# Function: <code>migrate_one_irq</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579821892,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:25",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579857276,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:51",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579890852,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:52",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579937924,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:52",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579976516,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:52",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580026020,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:52",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
bool migrate_one_irq(struct irq_desc * desc)
```

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:53",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580076448,
      "name": "migrate_one_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
    },
    {
      "addr": 18446744071580077505,
      "name": "migrate_one_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
bool migrate_one_irq(struct irq_desc * desc)
```

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:53",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580058576,
      "name": "migrate_one_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 543
    },
    {
      "addr": 18446744071591304302,
      "name": "migrate_one_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
bool migrate_one_irq(struct irq_desc * desc)
```

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:53",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580059280,
      "name": "migrate_one_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
    },
    {
      "addr": 18446744071591247141,
      "name": "migrate_one_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
bool migrate_one_irq(struct irq_desc * desc)
```

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:53",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580191840,
      "name": "migrate_one_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 547
    },
    {
      "addr": 18446744071592140085,
      "name": "migrate_one_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
bool migrate_one_irq(struct irq_desc * desc)
```

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:53",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580342352,
      "name": "migrate_one_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    },
    {
      "addr": 18446744071593910901,
      "name": "migrate_one_irq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
bool migrate_one_irq(struct irq_desc * desc)
```

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580559952,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:53",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580559952,
      "name": "migrate_one_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
bool migrate_one_irq(struct irq_desc * desc)
```

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580633424,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:53",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580633424,
      "name": "migrate_one_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
bool migrate_one_irq(struct irq_desc * desc)
```

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580698576,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:53",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698576,
      "name": "migrate_one_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 445
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
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491229832,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:52",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225243828,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:52",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284132572,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:52",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579994756,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:52",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579933428,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:52",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579986292,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:52",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "migrate_one_irq",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580032948,
      "name": "migrate_one_irq",
      "external": false,
      "loc": "kernel/irq/cpuhotplug.c:52",
      "file": "kernel/irq/cpuhotplug.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/irq/cpuhotplug.c:irq_migrate_all_off_this_cpu"
      ],
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
bool migrate_one_irq(struct irq_desc * desc)
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
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
