# Function: <code>__clocksource_suspend_select</code>

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
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __clocksource_suspend_select(struct clocksource * cs)
```

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580049801,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:461",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580049760,
      "name": "__clocksource_suspend_select",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446744071580053464,
      "name": "__clocksource_suspend_select.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580094333,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:461",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580093328,
      "name": "__clocksource_suspend_select.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071580096935,
      "name": "__clocksource_suspend_select.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580143293,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:468",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580142288,
      "name": "__clocksource_suspend_select.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071580145911,
      "name": "__clocksource_suspend_select.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580206256,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:468",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select",
        "kernel/time/clocksource.c:clocksource_suspend_select"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580190992,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:468",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select",
        "kernel/time/clocksource.c:clocksource_suspend_select"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580196363,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:569",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select",
        "kernel/time/clocksource.c:clocksource_suspend_select"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580341979,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:681",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select",
        "kernel/time/clocksource.c:clocksource_suspend_select"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580555179,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:687",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select",
        "kernel/time/clocksource.c:clocksource_suspend_select"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580812491,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:706",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select",
        "kernel/time/clocksource.c:clocksource_suspend_select"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580895691,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:717",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select",
        "kernel/time/clocksource.c:clocksource_suspend_select"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580986123,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:740",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select",
        "kernel/time/clocksource.c:clocksource_suspend_select"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491364188,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:468",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491363280,
      "name": "__clocksource_suspend_select.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225363952,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:468",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225361432,
      "name": "__clocksource_suspend_select.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284299912,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:468",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284298624,
      "name": "__clocksource_suspend_select.part.0",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936271855590,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:468",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271854842,
      "name": "__clocksource_suspend_select.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580112493,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:468",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580111488,
      "name": "__clocksource_suspend_select.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071580115111,
      "name": "__clocksource_suspend_select.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580057805,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:468",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056800,
      "name": "__clocksource_suspend_select.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071580060407,
      "name": "__clocksource_suspend_select.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580103565,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:468",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580102560,
      "name": "__clocksource_suspend_select.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071580106183,
      "name": "__clocksource_suspend_select.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__clocksource_suspend_select",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580155309,
      "name": "__clocksource_suspend_select",
      "external": false,
      "loc": "kernel/time/clocksource.c:468",
      "file": "kernel/time/clocksource.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ],
      "caller_func": [
        "kernel/time/clocksource.c:__clocksource_register_scale",
        "kernel/time/clocksource.c:clocksource_suspend_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580154304,
      "name": "__clocksource_suspend_select.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    },
    {
      "addr": 18446744071580157927,
      "name": "__clocksource_suspend_select.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void __clocksource_suspend_select(struct clocksource * cs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void __clocksource_suspend_select(struct clocksource * cs)
```
</details>
</li>
</ul>
