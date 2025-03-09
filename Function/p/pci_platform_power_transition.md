# Function: <code>pci_platform_power_transition</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583261936,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:728",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/pci.c:pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583261936,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 133
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583572032,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:749",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583572032,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583708624,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:774",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708624,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583749568,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:769",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583749568,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008592,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:770",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008592,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584204144,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:782",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204144,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584292448,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:953",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292448,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584486624,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:979",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584486624,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584622224,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:966",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584622224,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585304544,
      "name": "pci_platform_power_transition",
      "external": true,
      "loc": "drivers/pci/pci.c:1019",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585304544,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585460784,
      "name": "pci_platform_power_transition",
      "external": true,
      "loc": "drivers/pci/pci.c:1159",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585460784,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585340672,
      "name": "pci_platform_power_transition",
      "external": true,
      "loc": "drivers/pci/pci.c:1189",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340672,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585797664,
      "name": "pci_platform_power_transition",
      "external": true,
      "loc": "drivers/pci/pci.c:1199",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585797664,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 151
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586985802,
      "name": "pci_platform_power_transition",
      "external": true,
      "loc": "drivers/pci/pci.c:1135",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586984896,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588152794,
      "name": "pci_platform_power_transition",
      "external": true,
      "loc": "drivers/pci/pci.c:1119",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588151728,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588428311,
      "name": "pci_platform_power_transition",
      "external": true,
      "loc": "drivers/pci/pci.c:1133",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588427280,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588724812,
      "name": "pci_platform_power_transition",
      "external": true,
      "loc": "drivers/pci/pci.c:1196",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:__pci_set_power_state",
        "drivers/pci/pci.c:__pci_set_power_state",
        "drivers/pci/pci.c:__pci_set_power_state"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588723760,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496865856,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:966",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496865856,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230143876,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:966",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230143876,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290946512,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:966",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290946512,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 304
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275565860,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:966",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275565860,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584574384,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:966",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584574384,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584502544,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:966",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584502544,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584572384,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:966",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584572384,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
int pci_platform_power_transition(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_platform_power_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584680128,
      "name": "pci_platform_power_transition",
      "external": false,
      "loc": "drivers/pci/pci.c:966",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584680128,
      "name": "pci_platform_power_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 151
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
