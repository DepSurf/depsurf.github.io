# Function: <code>pm_clk_list_unlock</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void pm_clk_list_unlock(struct pm_subsys_data * psd)
```

```json
{
  "name": "pm_clk_list_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587023456,
      "name": "pm_clk_list_unlock",
      "external": false,
      "loc": "drivers/base/power/clock_ops.c:64",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/clock_ops.c:pm_clk_destroy",
        "drivers/base/power/clock_ops.c:pm_clk_remove_clk",
        "drivers/base/power/clock_ops.c:pm_clk_remove_clk",
        "drivers/base/power/clock_ops.c:pm_clk_remove",
        "drivers/base/power/clock_ops.c:pm_clk_remove",
        "drivers/base/power/clock_ops.c:__pm_clk_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587023456,
      "name": "pm_clk_list_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void pm_clk_list_unlock(struct pm_subsys_data * psd)
```

```json
{
  "name": "pm_clk_list_unlock",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587590608,
      "name": "pm_clk_list_unlock",
      "external": false,
      "loc": "drivers/base/power/clock_ops.c:64",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/clock_ops.c:pm_clk_destroy",
        "drivers/base/power/clock_ops.c:pm_clk_remove_clk",
        "drivers/base/power/clock_ops.c:pm_clk_remove_clk",
        "drivers/base/power/clock_ops.c:pm_clk_remove",
        "drivers/base/power/clock_ops.c:pm_clk_remove",
        "drivers/base/power/clock_ops.c:__pm_clk_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587590608,
      "name": "pm_clk_list_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pm_clk_list_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588927516,
      "name": "pm_clk_list_unlock",
      "external": false,
      "loc": "drivers/base/power/clock_ops.c:64",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_destroy",
        "drivers/base/power/clock_ops.c:pm_clk_remove_clk",
        "drivers/base/power/clock_ops.c:pm_clk_remove_clk",
        "drivers/base/power/clock_ops.c:pm_clk_remove",
        "drivers/base/power/clock_ops.c:pm_clk_remove",
        "drivers/base/power/clock_ops.c:__pm_clk_add"
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
  "name": "pm_clk_list_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590440780,
      "name": "pm_clk_list_unlock",
      "external": false,
      "loc": "drivers/base/power/clock_ops.c:64",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_destroy",
        "drivers/base/power/clock_ops.c:pm_clk_remove_clk",
        "drivers/base/power/clock_ops.c:pm_clk_remove_clk",
        "drivers/base/power/clock_ops.c:pm_clk_remove",
        "drivers/base/power/clock_ops.c:pm_clk_remove",
        "drivers/base/power/clock_ops.c:__pm_clk_add"
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
  "name": "pm_clk_list_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590760444,
      "name": "pm_clk_list_unlock",
      "external": false,
      "loc": "drivers/base/power/clock_ops.c:64",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_destroy",
        "drivers/base/power/clock_ops.c:pm_clk_remove_clk",
        "drivers/base/power/clock_ops.c:pm_clk_remove_clk",
        "drivers/base/power/clock_ops.c:pm_clk_remove",
        "drivers/base/power/clock_ops.c:pm_clk_remove",
        "drivers/base/power/clock_ops.c:__pm_clk_add"
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
  "name": "pm_clk_list_unlock",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591102636,
      "name": "pm_clk_list_unlock",
      "external": false,
      "loc": "drivers/base/power/clock_ops.c:64",
      "file": "drivers/base/power/clock_ops.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/clock_ops.c:pm_clk_destroy",
        "drivers/base/power/clock_ops.c:pm_clk_remove_clk",
        "drivers/base/power/clock_ops.c:pm_clk_remove_clk",
        "drivers/base/power/clock_ops.c:pm_clk_remove",
        "drivers/base/power/clock_ops.c:pm_clk_remove",
        "drivers/base/power/clock_ops.c:__pm_clk_add"
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void pm_clk_list_unlock(struct pm_subsys_data * psd)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void pm_clk_list_unlock(struct pm_subsys_data * psd)
```
</details>
</li>
</ul>
