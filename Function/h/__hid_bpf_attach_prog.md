# Function: <code>__hid_bpf_attach_prog</code>

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
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int __hid_bpf_attach_prog(struct hid_device * hdev, enum hid_bpf_prog_type prog_type, int prog_fd, __u32 flags)
```

```json
{
  "name": "__hid_bpf_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593356592,
      "name": "__hid_bpf_attach_prog",
      "external": true,
      "loc": "drivers/hid/bpf/hid_bpf_jmp_table.c:390",
      "file": "drivers/hid/bpf/hid_bpf_jmp_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog",
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593356592,
      "name": "__hid_bpf_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1230
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int __hid_bpf_attach_prog(struct hid_device * hdev, enum hid_bpf_prog_type prog_type, int prog_fd, struct bpf_prog * prog, __u32 flags)
```

```json
{
  "name": "__hid_bpf_attach_prog",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594110880,
      "name": "__hid_bpf_attach_prog",
      "external": true,
      "loc": "drivers/hid/bpf/hid_bpf_jmp_table.c:397",
      "file": "drivers/hid/bpf/hid_bpf_jmp_table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog",
        "drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_attach_prog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594110880,
      "name": "__hid_bpf_attach_prog",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1266
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
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
int __hid_bpf_attach_prog(struct hid_device * hdev, enum hid_bpf_prog_type prog_type, int prog_fd, __u32 flags)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog * prog</code>
</li>
<li>
<b>Param reordered. </b>
<code>hdev, prog_type, prog_fd, flags</code> ➡️ <code>hdev, prog_type, prog_fd, prog, flags</code>
</li>
</ul>
</details>
</li>
</ul>
