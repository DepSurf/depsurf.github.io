# Function: <code>console_flush_all</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "console_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580275144,
      "name": "console_flush_all",
      "external": false,
      "loc": "kernel/printk/printk.c:2766",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:console_unlock"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
bool console_flush_all(bool do_cond_resched, u64 * next_seq, bool * handover)
```

```json
{
  "name": "console_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "console_flush_all",
      "external": false,
      "loc": "kernel/printk/printk.c:2859",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580483136,
      "name": "console_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
    },
    {
      "addr": 18446744071595985462,
      "name": "console_flush_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool console_flush_all(bool do_cond_resched, u64 * next_seq, bool * handover)
```

```json
{
  "name": "console_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "console_flush_all",
      "external": false,
      "loc": "kernel/printk/printk.c:2912",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580554864,
      "name": "console_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 417
    },
    {
      "addr": 18446744071596503732,
      "name": "console_flush_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
bool console_flush_all(bool do_cond_resched, u64 * next_seq, bool * handover)
```

```json
{
  "name": "console_flush_all",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "console_flush_all",
      "external": false,
      "loc": "kernel/printk/printk.c:2946",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:register_console",
        "kernel/printk/printk.c:console_flush_on_panic",
        "kernel/printk/printk.c:console_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580622224,
      "name": "console_flush_all",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    },
    {
      "addr": 18446744071597401630,
      "name": "console_flush_all.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 27
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
bool console_flush_all(bool do_cond_resched, u64 * next_seq, bool * handover)
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
