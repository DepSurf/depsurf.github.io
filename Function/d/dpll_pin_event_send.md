# Function: <code>dpll_pin_event_send</code>

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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int dpll_pin_event_send(enum dpll_cmd event, struct dpll_pin * pin)
```

```json
{
  "name": "dpll_pin_event_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594286368,
      "name": "dpll_pin_event_send",
      "external": false,
      "loc": "drivers/dpll/dpll_netlink.c:604",
      "file": "drivers/dpll/dpll_netlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_pin_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_parent_device_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_phase_adj_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_freq_set",
        "drivers/dpll/dpll_netlink.c:dpll_pin_change_ntf",
        "drivers/dpll/dpll_netlink.c:dpll_pin_delete_ntf",
        "drivers/dpll/dpll_netlink.c:dpll_pin_create_ntf"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594286368,
      "name": "dpll_pin_event_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
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
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int dpll_pin_event_send(enum dpll_cmd event, struct dpll_pin * pin)
```
</details>
</li>
</ul>
