# Function: <code>pci_bus_resetable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583250432,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:3848",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bus_resetable",
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_try_reset_bus"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583250432,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583559840,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:4169",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_try_reset_bus",
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583559840,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583696768,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:4207",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_try_reset_bus",
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583696768,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583736896,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:4361",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_try_reset_bus",
        "drivers/pci/pci.c:pci_reset_bus",
        "drivers/pci/pci.c:pci_reset_bus",
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583736896,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584004827,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:4377",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_slot_reset"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_slot_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584004592,
      "name": "pci_bus_resetable.part.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584190032,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:4624",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_try_reset_bus",
        "drivers/pci/pci.c:pci_reset_bus",
        "drivers/pci/pci.c:pci_reset_bus",
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584190032,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584278720,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:4915",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584278720,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584473184,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5013",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584473184,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584608464,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5143",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584608464,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585285728,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5173",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585285728,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585440288,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5241",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585440288,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585320464,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5290",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585320464,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585775776,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5480",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585775776,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586961920,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5576",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586961920,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588125680,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5513",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588125680,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588400960,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5635",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588400960,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496847432,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5143",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496847432,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230127836,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5143",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230127836,
      "name": "pci_bus_resetable",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290924976,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5143",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290924976,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275551828,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5143",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275551828,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584560624,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5143",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584560624,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584488784,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5143",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584488784,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584558624,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5143",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584558624,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
bool pci_bus_resetable(struct pci_bus * bus)
```

```json
{
  "name": "pci_bus_resetable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584666368,
      "name": "pci_bus_resetable",
      "external": false,
      "loc": "drivers/pci/pci.c:5143",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_probe_reset_bus",
        "drivers/pci/pci.c:pci_bus_error_reset",
        "drivers/pci/pci.c:pci_slot_reset",
        "drivers/pci/pci.c:pci_bus_resetable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584666368,
      "name": "pci_bus_resetable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<details>
<summary>Removed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➖</summary>

```c
bool pci_bus_resetable(struct pci_bus * bus)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool pci_bus_resetable(struct pci_bus * bus)
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
bool pci_bus_resetable(struct pci_bus * bus)
```
</details>
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
