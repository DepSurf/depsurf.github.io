# Function: <code>cgroup_dev_func_proto</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580624512,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:548",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580624512,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 89
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580753152,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:646",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580753152,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580817984,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:703",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580817984,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580908800,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:807",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580908800,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580961952,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:817",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580961952,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581126368,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1139",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581126368,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581160352,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1163",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581160352,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581174560,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1167",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581174560,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581415072,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1197",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581415072,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581743488,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1378",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581743488,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582159424,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1602",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582159424,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582356960,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1602",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582356960,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582523792,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:1617",
      "file": "kernel/bpf/cgroup.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582523792,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
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
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492307016,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:817",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492307016,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226194516,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:817",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226194516,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285545296,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:817",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285545296,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272437968,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:817",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272437968,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580930752,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:817",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580930752,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580876816,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:817",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580876816,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580922000,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:817",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922000,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id, const struct bpf_prog * prog)
```

```json
{
  "name": "cgroup_dev_func_proto",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580982272,
      "name": "cgroup_dev_func_proto",
      "external": false,
      "loc": "kernel/bpf/cgroup.c:817",
      "file": "kernel/bpf/cgroup.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580982272,
      "name": "cgroup_dev_func_proto",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
const struct bpf_func_proto * cgroup_dev_func_proto(enum bpf_func_id func_id)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_prog * prog</code>
</li>
</ul>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
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
