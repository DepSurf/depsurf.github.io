# Function: <code>xfer_to_guest_mode_work</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int xfer_to_guest_mode_work(struct kvm_vcpu * vcpu, long unsigned int ti_work)
```

```json
{
  "name": "xfer_to_guest_mode_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580139024,
      "name": "xfer_to_guest_mode_work",
      "external": false,
      "loc": "kernel/entry/kvm.c:6",
      "file": "kernel/entry/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580139024,
      "name": "xfer_to_guest_mode_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
  "name": "xfer_to_guest_mode_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580143887,
      "name": "xfer_to_guest_mode_work",
      "external": false,
      "loc": "kernel/entry/kvm.c:6",
      "file": "kernel/entry/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int xfer_to_guest_mode_work(struct kvm_vcpu * vcpu, long unsigned int ti_work)
```

```json
{
  "name": "xfer_to_guest_mode_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580287504,
      "name": "xfer_to_guest_mode_work",
      "external": false,
      "loc": "kernel/entry/kvm.c:6",
      "file": "kernel/entry/kvm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580287504,
      "name": "xfer_to_guest_mode_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 265
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
  "name": "xfer_to_guest_mode_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580460855,
      "name": "xfer_to_guest_mode_work",
      "external": false,
      "loc": "kernel/entry/kvm.c:6",
      "file": "kernel/entry/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
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
  "name": "xfer_to_guest_mode_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580708087,
      "name": "xfer_to_guest_mode_work",
      "external": false,
      "loc": "kernel/entry/kvm.c:6",
      "file": "kernel/entry/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
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
  "name": "xfer_to_guest_mode_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580785415,
      "name": "xfer_to_guest_mode_work",
      "external": false,
      "loc": "kernel/entry/kvm.c:6",
      "file": "kernel/entry/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
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
  "name": "xfer_to_guest_mode_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580874679,
      "name": "xfer_to_guest_mode_work",
      "external": false,
      "loc": "kernel/entry/kvm.c:6",
      "file": "kernel/entry/kvm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/entry/kvm.c:xfer_to_guest_mode_handle_work"
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
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int xfer_to_guest_mode_work(struct kvm_vcpu * vcpu, long unsigned int ti_work)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int xfer_to_guest_mode_work(struct kvm_vcpu * vcpu, long unsigned int ti_work)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int xfer_to_guest_mode_work(struct kvm_vcpu * vcpu, long unsigned int ti_work)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int xfer_to_guest_mode_work(struct kvm_vcpu * vcpu, long unsigned int ti_work)
```
</details>
</li>
</ul>
