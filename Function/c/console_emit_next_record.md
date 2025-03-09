# Function: <code>console_emit_next_record</code>

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
  "name": "console_emit_next_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "console_emit_next_record",
      "external": false,
      "loc": "kernel/printk/printk.c:2676",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_unlock",
        "kernel/printk/printk.c:console_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580274288,
      "name": "console_emit_next_record.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
    },
    {
      "addr": 18446744071593903855,
      "name": "console_emit_next_record.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
  "name": "console_emit_next_record",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "console_emit_next_record",
      "external": false,
      "loc": "kernel/printk/printk.c:2769",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_all",
        "kernel/printk/printk.c:console_flush_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580481968,
      "name": "console_emit_next_record.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 841
    },
    {
      "addr": 18446744071595985303,
      "name": "console_emit_next_record.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
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
bool console_emit_next_record(struct console * con, bool * handover, int cookie)
```

```json
{
  "name": "console_emit_next_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "console_emit_next_record",
      "external": false,
      "loc": "kernel/printk/printk.c:2831",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580554384,
      "name": "console_emit_next_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
    },
    {
      "addr": 18446744071596503712,
      "name": "console_emit_next_record.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
bool console_emit_next_record(struct console * con, bool * handover, int cookie)
```

```json
{
  "name": "console_emit_next_record",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "console_emit_next_record",
      "external": false,
      "loc": "kernel/printk/printk.c:2857",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_flush_all"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580621744,
      "name": "console_emit_next_record",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 459
    },
    {
      "addr": 18446744071597401610,
      "name": "console_emit_next_record.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
bool console_emit_next_record(struct console * con, bool * handover, int cookie)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
