# Function: <code>__clk_hw_register_mux</code>

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
struct clk_hw * __clk_hw_register_mux(struct device * dev, struct device_node * np, const char * name, u8 num_parents, const const char * * parent_names, const struct clk_hw * * parent_hws, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_hw_register_mux",
      "external": true,
      "loc": "drivers/clk/clk-mux.c:148",
      "file": "drivers/clk/clk-mux.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-mux.c:clk_register_mux_table",
        "drivers/clk/x86/clk-st.c:st_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586203708,
      "name": "__clk_hw_register_mux.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586202832,
      "name": "__clk_hw_register_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
struct clk_hw * __clk_hw_register_mux(struct device * dev, struct device_node * np, const char * name, u8 num_parents, const const char * * parent_names, const struct clk_hw * * parent_hws, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_hw_register_mux",
      "external": true,
      "loc": "drivers/clk/clk-mux.c:148",
      "file": "drivers/clk/clk-mux.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-mux.c:clk_register_mux_table",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591445252,
      "name": "__clk_hw_register_mux.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586322192,
      "name": "__clk_hw_register_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
struct clk_hw * __clk_hw_register_mux(struct device * dev, struct device_node * np, const char * name, u8 num_parents, const const char * * parent_names, const struct clk_hw * * parent_hws, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_hw_register_mux",
      "external": true,
      "loc": "drivers/clk/clk-mux.c:149",
      "file": "drivers/clk/clk-mux.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-mux.c:clk_register_mux_table",
        "drivers/clk/clk-mux.c:__devm_clk_hw_register_mux",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591386463,
      "name": "__clk_hw_register_mux.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586196032,
      "name": "__clk_hw_register_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
struct clk_hw * __clk_hw_register_mux(struct device * dev, struct device_node * np, const char * name, u8 num_parents, const const char * * parent_names, const struct clk_hw * * parent_hws, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_hw_register_mux",
      "external": true,
      "loc": "drivers/clk/clk-mux.c:149",
      "file": "drivers/clk/clk-mux.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-mux.c:clk_register_mux_table",
        "drivers/clk/clk-mux.c:__devm_clk_hw_register_mux",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592425823,
      "name": "__clk_hw_register_mux.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071586698960,
      "name": "__clk_hw_register_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
struct clk_hw * __clk_hw_register_mux(struct device * dev, struct device_node * np, const char * name, u8 num_parents, const const char * * parent_names, const struct clk_hw * * parent_hws, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u32 mask, u8 clk_mux_flags, const u32 * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__clk_hw_register_mux",
      "external": true,
      "loc": "drivers/clk/clk-mux.c:149",
      "file": "drivers/clk/clk-mux.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-mux.c:clk_register_mux_table",
        "drivers/clk/clk-mux.c:__devm_clk_hw_register_mux",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594294245,
      "name": "__clk_hw_register_mux.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071587971856,
      "name": "__clk_hw_register_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
struct clk_hw * __clk_hw_register_mux(struct device * dev, struct device_node * np, const char * name, u8 num_parents, const const char * * parent_names, const struct clk_hw * * parent_hws, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u32 mask, u8 clk_mux_flags, const u32 * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589334688,
      "name": "__clk_hw_register_mux",
      "external": true,
      "loc": "drivers/clk/clk-mux.c:149",
      "file": "drivers/clk/clk-mux.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-mux.c:clk_register_mux_table",
        "drivers/clk/clk-mux.c:__devm_clk_hw_register_mux",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589334688,
      "name": "__clk_hw_register_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
struct clk_hw * __clk_hw_register_mux(struct device * dev, struct device_node * np, const char * name, u8 num_parents, const const char * * parent_names, const struct clk_hw * * parent_hws, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u32 mask, u8 clk_mux_flags, const u32 * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589632928,
      "name": "__clk_hw_register_mux",
      "external": true,
      "loc": "drivers/clk/clk-mux.c:149",
      "file": "drivers/clk/clk-mux.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-mux.c:clk_register_mux_table",
        "drivers/clk/clk-mux.c:__devm_clk_hw_register_mux",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589632928,
      "name": "__clk_hw_register_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 506
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
struct clk_hw * __clk_hw_register_mux(struct device * dev, struct device_node * np, const char * name, u8 num_parents, const const char * * parent_names, const struct clk_hw * * parent_hws, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u32 mask, u8 clk_mux_flags, const u32 * table, spinlock_t * lock)
```

```json
{
  "name": "__clk_hw_register_mux",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589942976,
      "name": "__clk_hw_register_mux",
      "external": true,
      "loc": "drivers/clk/clk-mux.c:149",
      "file": "drivers/clk/clk-mux.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk-mux.c:clk_register_mux_table",
        "drivers/clk/clk-mux.c:__devm_clk_hw_register_mux",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589942976,
      "name": "__clk_hw_register_mux",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 553
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
struct clk_hw * __clk_hw_register_mux(struct device * dev, struct device_node * np, const char * name, u8 num_parents, const const char * * parent_names, const struct clk_hw * * parent_hws, const struct clk_parent_data * parent_data, long unsigned int flags, void * reg, u8 shift, u32 mask, u8 clk_mux_flags, u32 * table, spinlock_t * lock)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 * table</code> ➡️ <code>const u32 * table</code>
</li>
</ul>
</details>
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
