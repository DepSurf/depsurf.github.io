# Function: <code>enabled_monitors_next</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * enabled_monitors_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "enabled_monitors_next",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581712941,
      "name": "enabled_monitors_next",
      "external": false,
      "loc": "kernel/trace/rv/rv.c:412",
      "file": "kernel/trace/rv/rv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/rv/rv.c:enabled_monitors_start"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581711008,
      "name": "enabled_monitors_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071596012443,
      "name": "enabled_monitors_next.cold",
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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * enabled_monitors_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "enabled_monitors_next",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581871821,
      "name": "enabled_monitors_next",
      "external": false,
      "loc": "kernel/trace/rv/rv.c:410",
      "file": "kernel/trace/rv/rv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/rv/rv.c:enabled_monitors_start"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581869712,
      "name": "enabled_monitors_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071596532449,
      "name": "enabled_monitors_next.cold",
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * enabled_monitors_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "enabled_monitors_next",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581994781,
      "name": "enabled_monitors_next",
      "external": false,
      "loc": "kernel/trace/rv/rv.c:410",
      "file": "kernel/trace/rv/rv.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/rv/rv.c:enabled_monitors_start"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581992672,
      "name": "enabled_monitors_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 111
    },
    {
      "addr": 18446744071597433183,
      "name": "enabled_monitors_next.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void * enabled_monitors_next(struct seq_file * m, void * p, loff_t * pos)
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
