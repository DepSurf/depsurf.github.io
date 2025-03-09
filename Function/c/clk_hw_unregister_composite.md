# Function: <code>clk_hw_unregister_composite</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void clk_hw_unregister_composite(struct clk_hw * hw)
```

```json
{
  "name": "clk_hw_unregister_composite",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586205024,
      "name": "clk_hw_unregister_composite",
      "external": true,
      "loc": "drivers/clk/clk-composite.c:397",
      "file": "drivers/clk/clk-composite.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586205024,
      "name": "clk_hw_unregister_composite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void clk_hw_unregister_composite(struct clk_hw * hw)
```

```json
{
  "name": "clk_hw_unregister_composite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586324398,
      "name": "clk_hw_unregister_composite",
      "external": true,
      "loc": "drivers/clk/clk-composite.c:399",
      "file": "drivers/clk/clk-composite.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-composite.c:devm_clk_hw_release_composite"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586324336,
      "name": "clk_hw_unregister_composite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void clk_hw_unregister_composite(struct clk_hw * hw)
```

```json
{
  "name": "clk_hw_unregister_composite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586198462,
      "name": "clk_hw_unregister_composite",
      "external": true,
      "loc": "drivers/clk/clk-composite.c:399",
      "file": "drivers/clk/clk-composite.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-composite.c:devm_clk_hw_release_composite"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586198400,
      "name": "clk_hw_unregister_composite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void clk_hw_unregister_composite(struct clk_hw * hw)
```

```json
{
  "name": "clk_hw_unregister_composite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586701502,
      "name": "clk_hw_unregister_composite",
      "external": true,
      "loc": "drivers/clk/clk-composite.c:399",
      "file": "drivers/clk/clk-composite.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-composite.c:devm_clk_hw_release_composite"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586701440,
      "name": "clk_hw_unregister_composite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void clk_hw_unregister_composite(struct clk_hw * hw)
```

```json
{
  "name": "clk_hw_unregister_composite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587973917,
      "name": "clk_hw_unregister_composite",
      "external": true,
      "loc": "drivers/clk/clk-composite.c:429",
      "file": "drivers/clk/clk-composite.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-composite.c:devm_clk_hw_release_composite"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587973856,
      "name": "clk_hw_unregister_composite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void clk_hw_unregister_composite(struct clk_hw * hw)
```

```json
{
  "name": "clk_hw_unregister_composite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589337021,
      "name": "clk_hw_unregister_composite",
      "external": true,
      "loc": "drivers/clk/clk-composite.c:431",
      "file": "drivers/clk/clk-composite.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-composite.c:devm_clk_hw_release_composite"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589336944,
      "name": "clk_hw_unregister_composite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void clk_hw_unregister_composite(struct clk_hw * hw)
```

```json
{
  "name": "clk_hw_unregister_composite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589635277,
      "name": "clk_hw_unregister_composite",
      "external": true,
      "loc": "drivers/clk/clk-composite.c:434",
      "file": "drivers/clk/clk-composite.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-composite.c:devm_clk_hw_release_composite"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589635200,
      "name": "clk_hw_unregister_composite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void clk_hw_unregister_composite(struct clk_hw * hw)
```

```json
{
  "name": "clk_hw_unregister_composite",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589945373,
      "name": "clk_hw_unregister_composite",
      "external": true,
      "loc": "drivers/clk/clk-composite.c:434",
      "file": "drivers/clk/clk-composite.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-composite.c:devm_clk_hw_release_composite"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589945296,
      "name": "clk_hw_unregister_composite",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void clk_hw_unregister_composite(struct clk_hw * hw)
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
