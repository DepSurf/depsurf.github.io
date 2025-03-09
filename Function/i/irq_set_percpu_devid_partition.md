# Function: <code>irq_set_percpu_devid_partition</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579760896,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:629",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579760896,
      "name": "irq_set_percpu_devid_partition",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579787744,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:817",
      "file": "kernel/irq/irqdesc.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579787744,
      "name": "irq_set_percpu_devid_partition",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579785264,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:834",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579785264,
      "name": "irq_set_percpu_devid_partition",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579818752,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:823",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579818752,
      "name": "irq_set_percpu_devid_partition",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579852608,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:840",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579852608,
      "name": "irq_set_percpu_devid_partition",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579899600,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:845",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579899600,
      "name": "irq_set_percpu_devid_partition",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579934416,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:900",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579934416,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579984544,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:900",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984544,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580032848,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:907",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580032848,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580016592,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:858",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016592,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580017264,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:858",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580017264,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580149488,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:870",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580149488,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580294304,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:847",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580294304,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580505232,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:874",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580505232,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580577376,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:893",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580577376,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 155
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580641664,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:893",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580641664,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491171552,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:900",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid",
        "drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491171552,
      "name": "irq_set_percpu_devid_partition",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225196576,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:900",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid",
        "drivers/irqchip/irq-partition-percpu.c:partition_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225196576,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284070736,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:900",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284070736,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271723190,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:900",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271723190,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579953280,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:900",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579953280,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579891152,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:900",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891152,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579944816,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:900",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579944816,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
```

```json
{
  "name": "irq_set_percpu_devid_partition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579991168,
      "name": "irq_set_percpu_devid_partition",
      "external": true,
      "loc": "kernel/irq/irqdesc.c:900",
      "file": "kernel/irq/irqdesc.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdesc.c:irq_set_percpu_devid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579991168,
      "name": "irq_set_percpu_devid_partition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int irq_set_percpu_devid_partition(unsigned int irq, const struct cpumask * affinity)
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
