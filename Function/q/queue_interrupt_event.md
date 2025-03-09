# Function: <code>queue_interrupt_event</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot * p_slot, u32 event_type)
```

```json
{
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584335232,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584335232,
      "name": "queue_interrupt_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot * p_slot, u32 event_type)
```

```json
{
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584430496,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584430496,
      "name": "queue_interrupt_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot * p_slot, u32 event_type)
```

```json
{
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584626768,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584626768,
      "name": "queue_interrupt_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot * p_slot, u32 event_type)
```

```json
{
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584764464,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584764464,
      "name": "queue_interrupt_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585457264,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585457264,
      "name": "queue_interrupt_event.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585604576,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585604576,
      "name": "queue_interrupt_event.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585483568,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585483568,
      "name": "queue_interrupt_event.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585950208,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585950208,
      "name": "queue_interrupt_event.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587154304,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587154304,
      "name": "queue_interrupt_event.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588361952,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588361952,
      "name": "queue_interrupt_event.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588638032,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588638032,
      "name": "queue_interrupt_event.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588938352,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588938352,
      "name": "queue_interrupt_event.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot * p_slot, u32 event_type)
```

```json
{
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497029008,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497029008,
      "name": "queue_interrupt_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot * p_slot, u32 event_type)
```

```json
{
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275686776,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275686776,
      "name": "queue_interrupt_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot * p_slot, u32 event_type)
```

```json
{
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584713280,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584713280,
      "name": "queue_interrupt_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot * p_slot, u32 event_type)
```

```json
{
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584644048,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644048,
      "name": "queue_interrupt_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot * p_slot, u32 event_type)
```

```json
{
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584714624,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584714624,
      "name": "queue_interrupt_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int queue_interrupt_event(struct slot * p_slot, u32 event_type)
```

```json
{
  "name": "queue_interrupt_event",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584822208,
      "name": "queue_interrupt_event",
      "external": false,
      "loc": "drivers/pci/hotplug/shpchp_ctrl.c:28",
      "file": "drivers/pci/hotplug/shpchp_ctrl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_power_fault",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_presence_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_switch_change",
        "drivers/pci/hotplug/shpchp_ctrl.c:shpchp_handle_attention_button"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584822208,
      "name": "queue_interrupt_event",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int queue_interrupt_event(struct slot * p_slot, u32 event_type)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int queue_interrupt_event(struct slot * p_slot, u32 event_type)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int queue_interrupt_event(struct slot * p_slot, u32 event_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int queue_interrupt_event(struct slot * p_slot, u32 event_type)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
