# Function: <code>EVT_TO_HPET_DEV</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct hpet_dev * EVT_TO_HPET_DEV(struct clock_event_device * evtdev)
```

```json
{
  "name": "EVT_TO_HPET_DEV",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579250160,
      "name": "EVT_TO_HPET_DEV",
      "external": true,
      "loc": "arch/x86/kernel/hpet.c:57",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250160,
      "name": "EVT_TO_HPET_DEV",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 9
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "EVT_TO_HPET_DEV",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "EVT_TO_HPET_DEV",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:57",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "EVT_TO_HPET_DEV",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "EVT_TO_HPET_DEV",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:57",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "EVT_TO_HPET_DEV",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "EVT_TO_HPET_DEV",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:57",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "EVT_TO_HPET_DEV",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "EVT_TO_HPET_DEV",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:57",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "EVT_TO_HPET_DEV",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579282437,
      "name": "EVT_TO_HPET_DEV",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:58",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_set_periodic",
        "arch/x86/kernel/hpet.c:hpet_msi_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_msi_shutdown"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "EVT_TO_HPET_DEV",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579306389,
      "name": "EVT_TO_HPET_DEV",
      "external": false,
      "loc": "arch/x86/kernel/hpet.c:54",
      "file": "arch/x86/kernel/hpet.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/hpet.c:hpet_msi_next_event",
        "arch/x86/kernel/hpet.c:hpet_msi_resume",
        "arch/x86/kernel/hpet.c:hpet_msi_set_periodic",
        "arch/x86/kernel/hpet.c:hpet_msi_set_oneshot",
        "arch/x86/kernel/hpet.c:hpet_msi_shutdown"
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
struct hpet_dev * EVT_TO_HPET_DEV(struct clock_event_device * evtdev)
```
</details>
</li>
</ul>
