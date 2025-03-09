# Function: <code>bpf_tramp_image_put</code>

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
void bpf_tramp_image_put(struct bpf_tramp_image * im)
```

```json
{
  "name": "bpf_tramp_image_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581082496,
      "name": "bpf_tramp_image_put",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:213",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581082496,
      "name": "bpf_tramp_image_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void bpf_tramp_image_put(struct bpf_tramp_image * im)
```

```json
{
  "name": "bpf_tramp_image_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581101328,
      "name": "bpf_tramp_image_put",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:243",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581101328,
      "name": "bpf_tramp_image_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void bpf_tramp_image_put(struct bpf_tramp_image * im)
```

```json
{
  "name": "bpf_tramp_image_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581330960,
      "name": "bpf_tramp_image_put",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:245",
      "file": "kernel/bpf/trampoline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581330960,
      "name": "bpf_tramp_image_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void bpf_tramp_image_put(struct bpf_tramp_image * im)
```

```json
{
  "name": "bpf_tramp_image_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581635472,
      "name": "bpf_tramp_image_put",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:245",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581635472,
      "name": "bpf_tramp_image_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void bpf_tramp_image_put(struct bpf_tramp_image * im)
```

```json
{
  "name": "bpf_tramp_image_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582024048,
      "name": "bpf_tramp_image_put",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:327",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582024048,
      "name": "bpf_tramp_image_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void bpf_tramp_image_put(struct bpf_tramp_image * im)
```

```json
{
  "name": "bpf_tramp_image_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582216256,
      "name": "bpf_tramp_image_put",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:304",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582216256,
      "name": "bpf_tramp_image_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
void bpf_tramp_image_put(struct bpf_tramp_image * im)
```

```json
{
  "name": "bpf_tramp_image_put",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582371520,
      "name": "bpf_tramp_image_put",
      "external": false,
      "loc": "kernel/bpf/trampoline.c:304",
      "file": "kernel/bpf/trampoline.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/trampoline.c:bpf_trampoline_update",
        "kernel/bpf/trampoline.c:bpf_trampoline_update"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582371520,
      "name": "bpf_tramp_image_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 130
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void bpf_tramp_image_put(struct bpf_tramp_image * im)
```
</details>
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
