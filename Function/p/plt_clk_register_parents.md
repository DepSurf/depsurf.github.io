# Function: <code>plt_clk_register_parents</code>

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
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584398040,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:271",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
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
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584804968,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:271",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
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
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585034868,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:271",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
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
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585142436,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:265",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
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
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585349607,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:266",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
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
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585488151,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:266",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
const char * * plt_clk_register_parents(struct platform_device * pdev, struct clk_plt_data * data, const struct pmc_clk * clks)
```

```json
{
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586208896,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:266",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586208896,
      "name": "plt_clk_register_parents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
const char * * plt_clk_register_parents(struct platform_device * pdev, struct clk_plt_data * data, const struct pmc_clk * clks)
```

```json
{
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586328352,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:266",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586328352,
      "name": "plt_clk_register_parents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
const char * * plt_clk_register_parents(struct platform_device * pdev, struct clk_plt_data * data, const struct pmc_clk * clks)
```

```json
{
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586201984,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:266",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586201984,
      "name": "plt_clk_register_parents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
const char * * plt_clk_register_parents(struct platform_device * pdev, struct clk_plt_data * data, const struct pmc_clk * clks)
```

```json
{
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586707328,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:266",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586707328,
      "name": "plt_clk_register_parents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
const char * * plt_clk_register_parents(struct platform_device * pdev, struct clk_plt_data * data, const struct pmc_clk * clks)
```

```json
{
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587978960,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:266",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587978960,
      "name": "plt_clk_register_parents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 609
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
const char * * plt_clk_register_parents(struct platform_device * pdev, struct clk_plt_data * data, const struct pmc_clk * clks)
```

```json
{
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589344128,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:266",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589344128,
      "name": "plt_clk_register_parents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
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
const char * * plt_clk_register_parents(struct platform_device * pdev, struct clk_plt_data * data, const struct pmc_clk * clks)
```

```json
{
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589642704,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:266",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589642704,
      "name": "plt_clk_register_parents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
const char * * plt_clk_register_parents(struct platform_device * pdev, struct clk_plt_data * data, const struct pmc_clk * clks)
```

```json
{
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589953056,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:266",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589953056,
      "name": "plt_clk_register_parents",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 616
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585250679,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:266",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
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
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585202855,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:266",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
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
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585438551,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:266",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
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
  "name": "plt_clk_register_parents",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585546471,
      "name": "plt_clk_register_parents",
      "external": false,
      "loc": "drivers/clk/x86/clk-pmc-atom.c:266",
      "file": "drivers/clk/x86/clk-pmc-atom.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe"
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
const char * * plt_clk_register_parents(struct platform_device * pdev, struct clk_plt_data * data, const struct pmc_clk * clks)
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
