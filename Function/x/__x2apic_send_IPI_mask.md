# Function: <code>__x2apic_send_IPI_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211760,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:40",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579212832,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:27",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211760,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071579212832,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579212400,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:48",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579213552,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:35",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212400,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 175
    },
    {
      "addr": 18446744071579213552,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 325
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579224096,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:48",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579225264,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:35",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579224096,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071579225264,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 330
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579221808,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:48",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579223584,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:36",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579221808,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
    },
    {
      "addr": 18446744071579223584,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579238400,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:50",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579239248,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:39",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579238400,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
    },
    {
      "addr": 18446744071579239248,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579250656,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:50",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579251776,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:39",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250656,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071579251776,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579274688,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:50",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579275584,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:39",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579274688,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071579275584,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 303
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579289072,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:50",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579290000,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:39",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_all",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579289072,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071579290000,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579294960,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:45",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579296048,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:37",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579294960,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071579296048,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579324784,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:45",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579326384,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:37",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579324784,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071579326384,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579326368,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:52",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579327984,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:38",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579326368,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    },
    {
      "addr": 18446744071579327984,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 289
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579329136,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:52",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579330672,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:38",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579329136,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
    },
    {
      "addr": 18446744071579330672,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383920,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:52",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579385824,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:38",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383920,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 241
    },
    {
      "addr": 18446744071579385824,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579449392,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:52",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579451616,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:44",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579449392,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    },
    {
      "addr": 18446744071579451616,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 354
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579537248,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:52",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579539216,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:44",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579537248,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071579539216,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550080,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:52",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 0,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:39",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550080,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
    },
    {
      "addr": 18446744071579552032,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071596484034,
      "name": "__x2apic_send_IPI_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision, Transformation ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578144,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:54",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 0,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:39",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578144,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 267
    },
    {
      "addr": 18446744071579579808,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 451
    },
    {
      "addr": 18446744071597380338,
      "name": "__x2apic_send_IPI_mask.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579290768,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:45",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579291856,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:37",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579290768,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071579291856,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579226080,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:45",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579227344,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:37",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579226080,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
    },
    {
      "addr": 18446744071579227344,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579291968,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:45",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579293056,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:37",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579291968,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071579293056,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```

```json
{
  "name": "__x2apic_send_IPI_mask",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579300800,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_phys.c:45",
      "file": "arch/x86/kernel/apic/x2apic_phys.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_phys.c:x2apic_send_IPI_mask"
      ]
    },
    {
      "addr": 18446744071579301888,
      "name": "__x2apic_send_IPI_mask",
      "external": false,
      "loc": "arch/x86/kernel/apic/x2apic_cluster.c:37",
      "file": "arch/x86/kernel/apic/x2apic_cluster.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/x2apic_cluster.c:x2apic_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579300800,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 193
    },
    {
      "addr": 18446744071579301888,
      "name": "__x2apic_send_IPI_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __x2apic_send_IPI_mask(const struct cpumask * mask, int vector, int apic_dest)
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
