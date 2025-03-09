# Function: <code>__pr_flush</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool __pr_flush(struct console * con, int timeout_ms, bool reset_on_progress)
```

```json
{
  "name": "__pr_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580275568,
      "name": "__pr_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:3366",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:suspend_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580275568,
      "name": "__pr_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pr_flush",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580484240,
      "name": "__pr_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:3622",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:suspend_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580484240,
      "name": "__pr_flush.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pr_flush",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580555904,
      "name": "__pr_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:3663",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:suspend_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580555904,
      "name": "__pr_flush.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 380
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__pr_flush",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580624512,
      "name": "__pr_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:3750",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_start",
        "kernel/printk/printk.c:console_stop",
        "kernel/printk/printk.c:console_unblank",
        "kernel/printk/printk.c:resume_console",
        "kernel/printk/printk.c:suspend_console"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624512,
      "name": "__pr_flush.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 664
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool __pr_flush(struct console * con, int timeout_ms, bool reset_on_progress)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
bool __pr_flush(struct console * con, int timeout_ms, bool reset_on_progress)
```
</details>
</li>
</ul>
