# Function: <code>read_wb_reg</code>

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
u64 read_wb_reg(int reg, int n)
```

```json
{
  "name": "read_wb_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490308000,
      "name": "read_wb_reg",
      "external": false,
      "loc": "arch/arm64/kernel/hw_breakpoint.c:105",
      "file": "arch/arm64/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/hw_breakpoint.c:watchpoint_handler",
        "arch/arm64/kernel/hw_breakpoint.c:watchpoint_handler",
        "arch/arm64/kernel/hw_breakpoint.c:breakpoint_handler",
        "arch/arm64/kernel/hw_breakpoint.c:breakpoint_handler",
        "arch/arm64/kernel/hw_breakpoint.c:toggle_bp_registers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490308000,
      "name": "read_wb_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 608
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
u32 read_wb_reg(int n)
```

```json
{
  "name": "read_wb_reg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224462168,
      "name": "read_wb_reg",
      "external": false,
      "loc": "arch/arm/kernel/hw_breakpoint.c:94",
      "file": "arch/arm/kernel/hw_breakpoint.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm/kernel/hw_breakpoint.c:arch_hw_breakpoint_init",
        "arch/arm/kernel/hw_breakpoint.c:hw_breakpoint_pending",
        "arch/arm/kernel/hw_breakpoint.c:hw_breakpoint_pending",
        "arch/arm/kernel/hw_breakpoint.c:hw_breakpoint_pending",
        "arch/arm/kernel/hw_breakpoint.c:hw_breakpoint_pending"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224462168,
      "name": "read_wb_reg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 828
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
u64 read_wb_reg(int reg, int n)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
u32 read_wb_reg(int n)
```
</details>
</li>
</ul>
