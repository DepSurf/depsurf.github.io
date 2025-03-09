# Function: <code>berlin2_div_register</code>

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
struct clk_hw * berlin2_div_register(const struct berlin2_div_map * map, void * base, const char * name, u8 div_flags, const char * * parent_names, int num_parents, long unsigned int flags, spinlock_t * lock)
```

```json
{
  "name": "berlin2_div_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336511148800,
      "name": "berlin2_div_register",
      "external": true,
      "loc": "drivers/clk/berlin/berlin2-div.c:228",
      "file": "drivers/clk/berlin/berlin2-div.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336511148800,
      "name": "berlin2_div_register",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 224
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
struct clk_hw * berlin2_div_register(const struct berlin2_div_map * map, void * base, const char * name, u8 div_flags, const char * * parent_names, int num_parents, long unsigned int flags, spinlock_t * lock)
```

```json
{
  "name": "berlin2_div_register",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3243600420,
      "name": "berlin2_div_register",
      "external": true,
      "loc": "drivers/clk/berlin/berlin2-div.c:228",
      "file": "drivers/clk/berlin/berlin2-div.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/berlin/bg2.c:berlin2_clock_setup",
        "drivers/clk/berlin/bg2q.c:berlin2q_clock_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3243600420,
      "name": "berlin2_div_register",
      "section": ".init.text",
      "bind": "STB_GLOBAL",
      "size": 216
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
struct clk_hw * berlin2_div_register(const struct berlin2_div_map * map, void * base, const char * name, u8 div_flags, const char * * parent_names, int num_parents, long unsigned int flags, spinlock_t * lock)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct clk_hw * berlin2_div_register(const struct berlin2_div_map * map, void * base, const char * name, u8 div_flags, const char * * parent_names, int num_parents, long unsigned int flags, spinlock_t * lock)
```
</details>
</li>
</ul>
