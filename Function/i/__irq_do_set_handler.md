# Function: <code>__irq_do_set_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579755888,
      "name": "__irq_do_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:734",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:__irq_set_handler",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579755888,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 363
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579778736,
      "name": "__irq_do_set_handler",
      "external": true,
      "loc": "kernel/irq/chip.c:777",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579778736,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804688,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:786",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804688,
      "name": "__irq_do_set_handler",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802384,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:891",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579802384,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 413
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579836512,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:914",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836512,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579870384,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:912",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870384,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579917424,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:912",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579917424,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:984",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579955504,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071579957977,
      "name": "__irq_do_set_handler.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580005360,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:984",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580005360,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580054928,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:984",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580054928,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580037520,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:973",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037520,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580038384,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:976",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580038384,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580170944,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:976",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580170944,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580319520,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:971",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580319520,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580533728,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:973",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580533728,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 531
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580607024,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:988",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580607024,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580671536,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:985",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chip_and_handler_name",
        "kernel/irq/chip.c:irq_set_chained_handler_and_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580671536,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 592
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491201504,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:984",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491201504,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225220624,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:984",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225220624,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284104560,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:984",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284104560,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 652
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271743278,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:984",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271743278,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
    }
  ]
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579974096,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:984",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974096,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579911904,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:984",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579911904,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579965632,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:984",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579965632,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
void __irq_do_set_handler(struct irq_desc * desc, irq_flow_handler_t handle, int is_chained, const char * name)
```

```json
{
  "name": "__irq_do_set_handler",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580012160,
      "name": "__irq_do_set_handler",
      "external": false,
      "loc": "kernel/irq/chip.c:984",
      "file": "kernel/irq/chip.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/chip.c:irq_set_chained_handler_and_data",
        "kernel/irq/chip.c:__irq_set_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580012160,
      "name": "__irq_do_set_handler",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 376
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
