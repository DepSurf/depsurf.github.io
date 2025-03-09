# Function: <code>cpu_rmap_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583129584,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:88",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_release",
        "lib/cpu_rmap.c:free_irq_cpu_rmap",
        "lib/cpu_rmap.c:irq_cpu_rmap_add"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583129584,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583424358,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:88",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release",
        "lib/cpu_rmap.c:free_irq_cpu_rmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583424048,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583549846,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:88",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release",
        "lib/cpu_rmap.c:free_irq_cpu_rmap"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583549952,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 25
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583586752,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:88",
      "file": "lib/cpu_rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583586752,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583833573,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:88",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583833744,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584034069,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:88",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584034160,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584116805,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:88",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584116896,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584305756,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584305824,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584440428,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584440496,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585003211,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585002752,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585123947,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585123488,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585004507,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585004048,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585445611,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585445728,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586587021,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586587152,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587827373,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587827696,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588100527,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588098816,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588436670,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588434912,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496326192,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496326192,
      "name": "cpu_rmap_put",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229659880,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229659880,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290644512,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290644512,
      "name": "cpu_rmap_put",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275378296,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275378472,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584409164,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584409232,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584344364,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584344432,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584392076,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584392144,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
int cpu_rmap_put(struct cpu_rmap * rmap)
```

```json
{
  "name": "cpu_rmap_put",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584498140,
      "name": "cpu_rmap_put",
      "external": true,
      "loc": "lib/cpu_rmap.c:85",
      "file": "lib/cpu_rmap.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "lib/cpu_rmap.c:irq_cpu_rmap_add",
        "lib/cpu_rmap.c:irq_cpu_rmap_release"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498208,
      "name": "cpu_rmap_put",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 30
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
