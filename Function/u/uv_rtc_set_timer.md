# Function: <code>uv_rtc_set_timer</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_rtc_set_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579472182,
      "name": "uv_rtc_set_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:211",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
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
int uv_rtc_set_timer(int cpu, u64 expires)
```

```json
{
  "name": "uv_rtc_set_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494224,
      "name": "uv_rtc_set_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:211",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494224,
      "name": "uv_rtc_set_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int uv_rtc_set_timer(int cpu, u64 expires)
```

```json
{
  "name": "uv_rtc_set_timer",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579476688,
      "name": "uv_rtc_set_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:201",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579476688,
      "name": "uv_rtc_set_timer",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
  "name": "uv_rtc_set_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579478761,
      "name": "uv_rtc_set_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:201",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
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
  "name": "uv_rtc_set_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579544827,
      "name": "uv_rtc_set_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:201",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_rtc_set_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579633528,
      "name": "uv_rtc_set_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:201",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_rtc_set_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579748136,
      "name": "uv_rtc_set_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:201",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_rtc_set_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579794683,
      "name": "uv_rtc_set_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:201",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_rtc_set_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579828363,
      "name": "uv_rtc_set_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:201",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "uv_rtc_set_timer",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579477510,
      "name": "uv_rtc_set_timer",
      "external": false,
      "loc": "arch/x86/platform/uv/uv_time.c:211",
      "file": "arch/x86/platform/uv/uv_time.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/platform/uv/uv_time.c:uv_rtc_next_event"
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
int uv_rtc_set_timer(int cpu, u64 expires)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int uv_rtc_set_timer(int cpu, u64 expires)
```
</details>
</li>
</ul>
