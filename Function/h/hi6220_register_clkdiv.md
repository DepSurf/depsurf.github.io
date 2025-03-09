# Function: <code>hi6220_register_clkdiv</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct clk * hi6220_register_clkdiv(struct device * dev, const char * name, const char * parent_name, long unsigned int flags, void * reg, u8 shift, u8 width, u32 mask_bit, spinlock_t * lock)
```

```json
{
  "name": "hi6220_register_clkdiv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497825560,
      "name": "hi6220_register_clkdiv",
      "external": true,
      "loc": "drivers/clk/hisilicon/clkdivider-hi6220.c:100",
      "file": "drivers/clk/hisilicon/clkdivider-hi6220.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/hisilicon/clk.c:hi6220_clk_register_divider"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497825560,
      "name": "hi6220_register_clkdiv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
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
struct clk * hi6220_register_clkdiv(struct device * dev, const char * name, const char * parent_name, long unsigned int flags, void * reg, u8 shift, u8 width, u32 mask_bit, spinlock_t * lock)
```

```json
{
  "name": "hi6220_register_clkdiv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230629740,
      "name": "hi6220_register_clkdiv",
      "external": true,
      "loc": "drivers/clk/hisilicon/clkdivider-hi6220.c:100",
      "file": "drivers/clk/hisilicon/clkdivider-hi6220.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/hisilicon/clk.c:hi6220_clk_register_divider"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230629740,
      "name": "hi6220_register_clkdiv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
struct clk * hi6220_register_clkdiv(struct device * dev, const char * name, const char * parent_name, long unsigned int flags, void * reg, u8 shift, u8 width, u32 mask_bit, spinlock_t * lock)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct clk * hi6220_register_clkdiv(struct device * dev, const char * name, const char * parent_name, long unsigned int flags, void * reg, u8 shift, u8 width, u32 mask_bit, spinlock_t * lock)
```
</details>
</li>
</ul>
