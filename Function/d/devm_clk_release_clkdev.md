# Function: <code>devm_clk_release_clkdev</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
```

```json
{
  "name": "devm_clk_release_clkdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585311654,
      "name": "devm_clk_release_clkdev",
      "external": true,
      "loc": "drivers/clk/clkdev.c:399",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585311635,
      "name": "devm_clk_release_clkdev.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071585311056,
      "name": "devm_clk_release_clkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
```

```json
{
  "name": "devm_clk_release_clkdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585448976,
      "name": "devm_clk_release_clkdev",
      "external": true,
      "loc": "drivers/clk/clkdev.c:399",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585448976,
      "name": "devm_clk_release_clkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
```

```json
{
  "name": "devm_clk_release_clkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586164848,
      "name": "devm_clk_release_clkdev",
      "external": true,
      "loc": "drivers/clk/clkdev.c:399",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586164848,
      "name": "devm_clk_release_clkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
```

```json
{
  "name": "devm_clk_release_clkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586281920,
      "name": "devm_clk_release_clkdev",
      "external": true,
      "loc": "drivers/clk/clkdev.c:399",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586281920,
      "name": "devm_clk_release_clkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
```

```json
{
  "name": "devm_clk_release_clkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586155696,
      "name": "devm_clk_release_clkdev",
      "external": true,
      "loc": "drivers/clk/clkdev.c:399",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586155696,
      "name": "devm_clk_release_clkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
```

```json
{
  "name": "devm_clk_release_clkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586657392,
      "name": "devm_clk_release_clkdev",
      "external": true,
      "loc": "drivers/clk/clkdev.c:371",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586657392,
      "name": "devm_clk_release_clkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
```

```json
{
  "name": "devm_clk_release_clkdev",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587925328,
      "name": "devm_clk_release_clkdev",
      "external": true,
      "loc": "drivers/clk/clkdev.c:371",
      "file": "drivers/clk/clkdev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587925328,
      "name": "devm_clk_release_clkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
```

```json
{
  "name": "devm_clk_release_clkdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497738072,
      "name": "devm_clk_release_clkdev",
      "external": true,
      "loc": "drivers/clk/clkdev.c:399",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497738072,
      "name": "devm_clk_release_clkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
```

```json
{
  "name": "devm_clk_release_clkdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230560300,
      "name": "devm_clk_release_clkdev",
      "external": true,
      "loc": "drivers/clk/clkdev.c:399",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230560300,
      "name": "devm_clk_release_clkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
```

```json
{
  "name": "devm_clk_release_clkdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275882012,
      "name": "devm_clk_release_clkdev",
      "external": true,
      "loc": "drivers/clk/clkdev.c:399",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275882012,
      "name": "devm_clk_release_clkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 170
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
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
```

```json
{
  "name": "devm_clk_release_clkdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585211504,
      "name": "devm_clk_release_clkdev",
      "external": true,
      "loc": "drivers/clk/clkdev.c:399",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585211504,
      "name": "devm_clk_release_clkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
```

```json
{
  "name": "devm_clk_release_clkdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585163712,
      "name": "devm_clk_release_clkdev",
      "external": true,
      "loc": "drivers/clk/clkdev.c:399",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585163712,
      "name": "devm_clk_release_clkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
```

```json
{
  "name": "devm_clk_release_clkdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585399376,
      "name": "devm_clk_release_clkdev",
      "external": true,
      "loc": "drivers/clk/clkdev.c:399",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585399376,
      "name": "devm_clk_release_clkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
```

```json
{
  "name": "devm_clk_release_clkdev",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585506720,
      "name": "devm_clk_release_clkdev",
      "external": true,
      "loc": "drivers/clk/clkdev.c:399",
      "file": "drivers/clk/clkdev.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585506720,
      "name": "devm_clk_release_clkdev",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void devm_clk_release_clkdev(struct device * dev, const char * con_id, const char * dev_id)
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
