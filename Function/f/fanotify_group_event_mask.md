# Function: <code>fanotify_group_event_mask</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581977720,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:98",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582111953,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:147",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582189329,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:147",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
u32 fanotify_group_event_mask(struct fsnotify_group * group, struct fsnotify_iter_info * iter_info, u32 event_mask, const void * data, int data_type)
```

```json
{
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582426128,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:208",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582426128,
      "name": "fanotify_group_event_mask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 296
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
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582482834,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:226",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582510417,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:256",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582823104,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:256",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582823104,
      "name": "fanotify_group_event_mask.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 422
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
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583379504,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:292",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583379504,
      "name": "fanotify_group_event_mask.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 467
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
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583964640,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:292",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583964640,
      "name": "fanotify_group_event_mask.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:293",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188064,
      "name": "fanotify_group_event_mask.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
    },
    {
      "addr": 18446744071596580344,
      "name": "fanotify_group_event_mask.constprop.0.isra.0.cold",
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:287",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584402048,
      "name": "fanotify_group_event_mask.constprop.0.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 774
    },
    {
      "addr": 18446744071597484205,
      "name": "fanotify_group_event_mask.constprop.0.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493750552,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:147",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3227271556,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:147",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055287361796,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:147",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936273355502,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:147",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582158065,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:147",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582095505,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:147",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582148545,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:147",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "fanotify_group_event_mask",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582221793,
      "name": "fanotify_group_event_mask",
      "external": false,
      "loc": "fs/notify/fanotify/fanotify.c:147",
      "file": "fs/notify/fanotify/fanotify.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/notify/fanotify/fanotify.c:fanotify_handle_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
u32 fanotify_group_event_mask(struct fsnotify_group * group, struct fsnotify_iter_info * iter_info, u32 event_mask, const void * data, int data_type)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
u32 fanotify_group_event_mask(struct fsnotify_group * group, struct fsnotify_iter_info * iter_info, u32 event_mask, const void * data, int data_type)
```
</details>
</li>
</ul>
