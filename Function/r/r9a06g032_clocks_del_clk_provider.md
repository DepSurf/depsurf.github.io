# Function: <code>r9a06g032_clocks_del_clk_provider</code>

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
void r9a06g032_clocks_del_clk_provider(void * data)
```

```json
{
  "name": "r9a06g032_clocks_del_clk_provider",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511159312,
      "name": "r9a06g032_clocks_del_clk_provider",
      "external": false,
      "loc": "drivers/clk/renesas/r9a06g032-clocks.c:890",
      "file": "drivers/clk/renesas/r9a06g032-clocks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497931592,
      "name": "r9a06g032_clocks_del_clk_provider",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void r9a06g032_clocks_del_clk_provider(void * data)
```

```json
{
  "name": "r9a06g032_clocks_del_clk_provider",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243770180,
      "name": "r9a06g032_clocks_del_clk_provider",
      "external": false,
      "loc": "drivers/clk/renesas/r9a06g032-clocks.c:890",
      "file": "drivers/clk/renesas/r9a06g032-clocks.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/clk/renesas/r9a06g032-clocks.c:r9a06g032_clocks_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230678996,
      "name": "r9a06g032_clocks_del_clk_provider",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
void r9a06g032_clocks_del_clk_provider(void * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void r9a06g032_clocks_del_clk_provider(void * data)
```
</details>
</li>
</ul>
