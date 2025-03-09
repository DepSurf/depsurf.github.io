# Function: <code>__irq_domain_deactivate_irq</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579812704,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1386",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_deactivate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579812704,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579811024,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1526",
      "file": "kernel/irq/irqdomain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_deactivate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579811024,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579846672,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1684",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579846672,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579880464,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1568",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579880464,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579927744,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1568",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579927744,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579966144,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1605",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579966144,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580015920,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1608",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580015920,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580065808,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1610",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580065808,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580047856,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1732",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047856,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580048608,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1695",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580048608,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580181632,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1740",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580181632,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580329808,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1744",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580329808,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580545808,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1812",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580545808,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580619248,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1793",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580619248,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580684192,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1793",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580684192,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491217792,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1608",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491217792,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225233000,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1608",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225233000,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271755062,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1608",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271755062,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579984656,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1608",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579984656,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579922432,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1608",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579922432,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579976192,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1608",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579976192,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```

```json
{
  "name": "__irq_domain_deactivate_irq",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580022832,
      "name": "__irq_domain_deactivate_irq",
      "external": false,
      "loc": "kernel/irq/irqdomain.c:1608",
      "file": "kernel/irq/irqdomain.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/irqdomain.c:irq_domain_deactivate_irq",
        "kernel/irq/irqdomain.c:__irq_domain_activate_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580022832,
      "name": "__irq_domain_deactivate_irq",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __irq_domain_deactivate_irq(struct irq_data * irq_data)
```
</details>
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
