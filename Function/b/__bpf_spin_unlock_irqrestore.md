# Function: <code>__bpf_spin_unlock_irqrestore</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __bpf_spin_unlock_irqrestore(struct bpf_spin_lock * lock)
```

```json
{
  "name": "__bpf_spin_unlock_irqrestore",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581267760,
      "name": "__bpf_spin_unlock_irqrestore",
      "external": false,
      "loc": "kernel/bpf/helpers.c:314",
      "file": "kernel/bpf/helpers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_start",
        "kernel/bpf/helpers.c:bpf_timer_set_callback",
        "kernel/bpf/helpers.c:bpf_timer_init",
        "kernel/bpf/helpers.c:copy_map_value_locked",
        "kernel/bpf/helpers.c:bpf_spin_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581267760,
      "name": "__bpf_spin_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void __bpf_spin_unlock_irqrestore(struct bpf_spin_lock * lock)
```

```json
{
  "name": "__bpf_spin_unlock_irqrestore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581562528,
      "name": "__bpf_spin_unlock_irqrestore",
      "external": false,
      "loc": "kernel/bpf/helpers.c:328",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_start",
        "kernel/bpf/helpers.c:bpf_timer_set_callback",
        "kernel/bpf/helpers.c:bpf_timer_init",
        "kernel/bpf/helpers.c:copy_map_value_locked",
        "kernel/bpf/helpers.c:bpf_spin_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581562528,
      "name": "__bpf_spin_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void __bpf_spin_unlock_irqrestore(struct bpf_spin_lock * lock)
```

```json
{
  "name": "__bpf_spin_unlock_irqrestore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581934880,
      "name": "__bpf_spin_unlock_irqrestore",
      "external": false,
      "loc": "kernel/bpf/helpers.c:344",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_list_head_free",
        "kernel/bpf/helpers.c:bpf_list_head_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_start",
        "kernel/bpf/helpers.c:bpf_timer_set_callback",
        "kernel/bpf/helpers.c:bpf_timer_init",
        "kernel/bpf/helpers.c:copy_map_value_locked",
        "kernel/bpf/helpers.c:bpf_spin_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581934880,
      "name": "__bpf_spin_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void __bpf_spin_unlock_irqrestore(struct bpf_spin_lock * lock)
```

```json
{
  "name": "__bpf_spin_unlock_irqrestore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582118048,
      "name": "__bpf_spin_unlock_irqrestore",
      "external": false,
      "loc": "kernel/bpf/helpers.c:345",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_rb_root_free",
        "kernel/bpf/helpers.c:bpf_list_head_free",
        "kernel/bpf/helpers.c:bpf_list_head_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_start",
        "kernel/bpf/helpers.c:bpf_timer_set_callback",
        "kernel/bpf/helpers.c:bpf_timer_init",
        "kernel/bpf/helpers.c:copy_map_value_locked",
        "kernel/bpf/helpers.c:bpf_spin_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582118048,
      "name": "__bpf_spin_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
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
void __bpf_spin_unlock_irqrestore(struct bpf_spin_lock * lock)
```

```json
{
  "name": "__bpf_spin_unlock_irqrestore",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582258384,
      "name": "__bpf_spin_unlock_irqrestore",
      "external": false,
      "loc": "kernel/bpf/helpers.c:351",
      "file": "kernel/bpf/helpers.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/helpers.c:bpf_rb_root_free",
        "kernel/bpf/helpers.c:bpf_list_head_free",
        "kernel/bpf/helpers.c:bpf_list_head_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel_and_free",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_cancel",
        "kernel/bpf/helpers.c:bpf_timer_start",
        "kernel/bpf/helpers.c:bpf_timer_set_callback",
        "kernel/bpf/helpers.c:bpf_timer_init",
        "kernel/bpf/helpers.c:copy_map_value_locked",
        "kernel/bpf/helpers.c:bpf_spin_unlock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582258384,
      "name": "__bpf_spin_unlock_irqrestore",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 68
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void __bpf_spin_unlock_irqrestore(struct bpf_spin_lock * lock)
```
</details>
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
