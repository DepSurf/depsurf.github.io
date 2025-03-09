# Function: <code>__devm_clk_get</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct clk * __devm_clk_get(struct device * dev, const char * id, struct clk * (*)(struct device *, const char *) get, int (*)(struct clk *) init, void (*)(struct clk *) exit)
```

```json
{
  "name": "__devm_clk_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589278014,
      "name": "__devm_clk_get",
      "external": false,
      "loc": "drivers/clk/clk-devres.c:22",
      "file": "drivers/clk/clk-devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_prepared",
        "drivers/clk/clk-devres.c:devm_clk_get_optional",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get_prepared",
        "drivers/clk/clk-devres.c:devm_clk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589275952,
      "name": "__devm_clk_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
struct clk * __devm_clk_get(struct device * dev, const char * id, struct clk * (*)(struct device *, const char *) get, int (*)(struct clk *) init, void (*)(struct clk *) exit)
```

```json
{
  "name": "__devm_clk_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589574606,
      "name": "__devm_clk_get",
      "external": false,
      "loc": "drivers/clk/clk-devres.c:22",
      "file": "drivers/clk/clk-devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_prepared",
        "drivers/clk/clk-devres.c:devm_clk_get_optional",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get_prepared",
        "drivers/clk/clk-devres.c:devm_clk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589572544,
      "name": "__devm_clk_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
struct clk * __devm_clk_get(struct device * dev, const char * id, struct clk * (*)(struct device *, const char *) get, int (*)(struct clk *) init, void (*)(struct clk *) exit)
```

```json
{
  "name": "__devm_clk_get",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589884046,
      "name": "__devm_clk_get",
      "external": false,
      "loc": "drivers/clk/clk-devres.c:22",
      "file": "drivers/clk/clk-devres.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-devres.c:devm_clk_get_optional_enabled",
        "drivers/clk/clk-devres.c:devm_clk_get_optional_prepared",
        "drivers/clk/clk-devres.c:devm_clk_get_optional",
        "drivers/clk/clk-devres.c:devm_clk_get_enabled"
      ],
      "caller_func": [
        "drivers/clk/clk-devres.c:devm_clk_get_prepared",
        "drivers/clk/clk-devres.c:devm_clk_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589881984,
      "name": "__devm_clk_get",
      "section": ".text",
      "bind": "STB_LOCAL",
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
struct clk * __devm_clk_get(struct device * dev, const char * id, struct clk * (*)(struct device *, const char *) get, int (*)(struct clk *) init, void (*)(struct clk *) exit)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
