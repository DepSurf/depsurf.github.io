# Function: <code>printk_get_next_message</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
bool printk_get_next_message(struct printk_message * pmsg, u64 seq, bool is_extended, bool may_suppress)
```

```json
{
  "name": "printk_get_next_message",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "printk_get_next_message",
      "external": false,
      "loc": "kernel/printk/printk.c:2757",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_emit_next_record",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580553024,
      "name": "printk_get_next_message",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 792
    },
    {
      "addr": 18446744071596503637,
      "name": "printk_get_next_message.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
bool printk_get_next_message(struct printk_message * pmsg, u64 seq, bool is_extended, bool may_suppress)
```

```json
{
  "name": "printk_get_next_message",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "printk_get_next_message",
      "external": true,
      "loc": "kernel/printk/printk.c:2776",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:console_emit_next_record",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read",
        "kernel/printk/printk.c:devkmsg_read"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597401535,
      "name": "printk_get_next_message.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071580620384,
      "name": "printk_get_next_message",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 792
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
bool printk_get_next_message(struct printk_message * pmsg, u64 seq, bool is_extended, bool may_suppress)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
