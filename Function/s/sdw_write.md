# Function: <code>sdw_write</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int sdw_write(struct sdw_slave * slave, u32 addr, u8 value)
```

```json
{
  "name": "sdw_write",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588027872,
      "name": "sdw_write",
      "external": true,
      "loc": "drivers/soundwire/bus.c:392",
      "file": "drivers/soundwire/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/soundwire/bus.c:sdw_handle_slave_status",
        "drivers/soundwire/bus.c:sdw_handle_slave_status",
        "drivers/soundwire/bus.c:sdw_handle_slave_status",
        "drivers/soundwire/bus.c:sdw_handle_slave_alerts",
        "drivers/soundwire/bus.c:sdw_configure_dpn_intr"
      ],
      "caller_func": [
        "drivers/soundwire/stream.c:sdw_program_params",
        "drivers/soundwire/stream.c:sdw_program_params",
        "drivers/soundwire/stream.c:sdw_program_params",
        "drivers/soundwire/stream.c:sdw_program_params",
        "drivers/soundwire/stream.c:sdw_program_params",
        "drivers/soundwire/stream.c:sdw_program_params",
        "drivers/soundwire/stream.c:sdw_program_params",
        "drivers/soundwire/stream.c:sdw_program_params",
        "drivers/soundwire/stream.c:sdw_program_params",
        "drivers/soundwire/stream.c:sdw_program_params",
        "drivers/soundwire/stream.c:sdw_prep_deprep_ports",
        "drivers/soundwire/stream.c:sdw_prep_deprep_ports"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588025664,
      "name": "sdw_write",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int sdw_write(struct sdw_slave * slave, u32 addr, u8 value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➖</summary>

```c
int sdw_write(struct sdw_slave * slave, u32 addr, u8 value)
```
</details>
</li>
</ul>
