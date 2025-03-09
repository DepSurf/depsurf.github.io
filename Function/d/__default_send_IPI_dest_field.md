# Function: <code>__default_send_IPI_dest_field</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579192181,
      "name": "__default_send_IPI_dest_field",
      "external": false,
      "loc": "arch/x86/include/asm/ipi.h:93",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579210693,
      "name": "__default_send_IPI_dest_field",
      "external": false,
      "loc": "arch/x86/include/asm/ipi.h:93",
      "file": "arch/x86/kernel/apic/apic_numachip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071579215340,
      "name": "__default_send_IPI_dest_field",
      "external": false,
      "loc": "arch/x86/include/asm/ipi.h:93",
      "file": "arch/x86/kernel/apic/apic_flat_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_mask_allbutself",
        "arch/x86/kernel/apic/apic_flat_64.c:flat_send_IPI_allbutself"
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579192592,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:51",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579192592,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579204304,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:51",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579204304,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579202128,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:51",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202128,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579217632,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:52",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579217632,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579229920,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:52",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579229920,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579253616,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:52",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579253616,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579267632,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:52",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579267632,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579269760,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:145",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269760,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579297744,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:145",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297744,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579302992,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:146",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579302992,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579305856,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:146",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579305856,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579353936,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:146",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579353936,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 103
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579416320,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:146",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579416320,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579499264,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:146",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499264,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579511440,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:146",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579511440,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
void __default_send_IPI_dest_field(unsigned int dest_mask, int vector, unsigned int dest_mode)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579540332,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:173",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys"
      ],
      "caller_func": [
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579539408,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579268464,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:145",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268464,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579203888,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:145",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579203888,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579269664,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:145",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579269664,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```

```json
{
  "name": "__default_send_IPI_dest_field",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579275264,
      "name": "__default_send_IPI_dest_field",
      "external": true,
      "loc": "arch/x86/kernel/apic/ipi.c:145",
      "file": "arch/x86/kernel/apic/ipi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_allbutself_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_mask_sequence_phys",
        "arch/x86/kernel/apic/ipi.c:default_send_IPI_single_phys",
        "arch/x86/kernel/apic/apic_numachip.c:numachip_send_IPI_one",
        "arch/x86/kernel/apic/apic_flat_64.c:_flat_send_IPI_mask"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579275264,
      "name": "__default_send_IPI_dest_field",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int dest_mask</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int dest_mode</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int mask</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int dest</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __default_send_IPI_dest_field(unsigned int mask, int vector, unsigned int dest)
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
