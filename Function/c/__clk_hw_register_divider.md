# Function: <code>__clk_hw_register_divider</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct clk_hw * __clk_hw_register_divider(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_divider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_hw_register_divider",
      "external": true,
      "loc": "drivers/clk/clk-divider.c:466",
      "file": "drivers/clk/clk-divider.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-divider.c:clk_register_divider_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586199463,
      "name": "__clk_hw_register_divider.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586196720,
      "name": "__clk_hw_register_divider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
struct clk_hw * __clk_hw_register_divider(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_divider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_hw_register_divider",
      "external": true,
      "loc": "drivers/clk/clk-divider.c:467",
      "file": "drivers/clk/clk-divider.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-divider.c:__devm_clk_hw_register_divider",
        "drivers/clk/clk-divider.c:clk_register_divider_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591445204,
      "name": "__clk_hw_register_divider.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586315840,
      "name": "__clk_hw_register_divider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
struct clk_hw * __clk_hw_register_divider(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_divider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_hw_register_divider",
      "external": true,
      "loc": "drivers/clk/clk-divider.c:467",
      "file": "drivers/clk/clk-divider.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-divider.c:__devm_clk_hw_register_divider",
        "drivers/clk/clk-divider.c:clk_register_divider_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591386415,
      "name": "__clk_hw_register_divider.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586189456,
      "name": "__clk_hw_register_divider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct clk_hw * __clk_hw_register_divider(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_divider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_hw_register_divider",
      "external": true,
      "loc": "drivers/clk/clk-divider.c:537",
      "file": "drivers/clk/clk-divider.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-divider.c:__devm_clk_hw_register_divider",
        "drivers/clk/clk-divider.c:clk_register_divider_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592424697,
      "name": "__clk_hw_register_divider.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586691536,
      "name": "__clk_hw_register_divider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct clk_hw * __clk_hw_register_divider(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_divider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_hw_register_divider",
      "external": true,
      "loc": "drivers/clk/clk-divider.c:537",
      "file": "drivers/clk/clk-divider.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-divider.c:__devm_clk_hw_register_divider",
        "drivers/clk/clk-divider.c:clk_register_divider_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594293089,
      "name": "__clk_hw_register_divider.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587963616,
      "name": "__clk_hw_register_divider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
struct clk_hw * __clk_hw_register_divider(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_divider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589325248,
      "name": "__clk_hw_register_divider",
      "external": true,
      "loc": "drivers/clk/clk-divider.c:537",
      "file": "drivers/clk/clk-divider.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-divider.c:__devm_clk_hw_register_divider",
        "drivers/clk/clk-divider.c:clk_register_divider_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589325248,
      "name": "__clk_hw_register_divider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
struct clk_hw * __clk_hw_register_divider(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_divider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589623424,
      "name": "__clk_hw_register_divider",
      "external": true,
      "loc": "drivers/clk/clk-divider.c:537",
      "file": "drivers/clk/clk-divider.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-divider.c:__devm_clk_hw_register_divider",
        "drivers/clk/clk-divider.c:clk_register_divider_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589623424,
      "name": "__clk_hw_register_divider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
struct clk_hw * __clk_hw_register_divider(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_divider",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589933344,
      "name": "__clk_hw_register_divider",
      "external": true,
      "loc": "drivers/clk/clk-divider.c:537",
      "file": "drivers/clk/clk-divider.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-divider.c:__devm_clk_hw_register_divider",
        "drivers/clk/clk-divider.c:clk_register_divider_table"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589933344,
      "name": "__clk_hw_register_divider",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 502
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
struct clk_hw * __clk_hw_register_divider(struct device * dev, struct device_node * np, const char * name, const char * parent_name, const struct clk_hw * parent_hw, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u8 width, u8 clk_divider_flags, const struct clk_div_table * table, spinlock_t * lock)
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
