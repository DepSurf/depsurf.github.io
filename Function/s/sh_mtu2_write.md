# Function: <code>sh_mtu2_write</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void sh_mtu2_write(struct sh_mtu2_channel * ch, int reg_nr, long unsigned int value)
```

```json
{
  "name": "sh_mtu2_write",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234093876,
      "name": "sh_mtu2_write",
      "external": false,
      "loc": "drivers/clocksource/sh_mtu2.c:167",
      "file": "drivers/clocksource/sh_mtu2.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_interrupt",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_start_stop_ch",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_start_stop_ch"
      ],
      "caller_func": [
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic",
        "drivers/clocksource/sh_mtu2.c:sh_mtu2_clock_event_set_periodic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234092092,
      "name": "sh_mtu2_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void sh_mtu2_write(struct sh_mtu2_channel * ch, int reg_nr, long unsigned int value)
```
</details>
</li>
</ul>
