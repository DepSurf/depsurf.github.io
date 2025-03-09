# Function: <code>pi_state_update_owner</code>

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
void pi_state_update_owner(struct futex_pi_state * pi_state, struct task_struct * new_owner)
```

```json
{
  "name": "pi_state_update_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580252736,
      "name": "pi_state_update_owner",
      "external": false,
      "loc": "kernel/futex.c:766",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:__fixup_pi_state_owner",
        "kernel/futex.c:__fixup_pi_state_owner",
        "kernel/futex.c:wake_futex_pi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580252736,
      "name": "pi_state_update_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void pi_state_update_owner(struct futex_pi_state * pi_state, struct task_struct * new_owner)
```

```json
{
  "name": "pi_state_update_owner",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580257920,
      "name": "pi_state_update_owner",
      "external": false,
      "loc": "kernel/futex.c:765",
      "file": "kernel/futex.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:__fixup_pi_state_owner",
        "kernel/futex.c:__fixup_pi_state_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580257920,
      "name": "pi_state_update_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pi_state_update_owner(struct futex_pi_state * pi_state, struct task_struct * new_owner)
```

```json
{
  "name": "pi_state_update_owner",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580409168,
      "name": "pi_state_update_owner",
      "external": false,
      "loc": "kernel/futex.c:823",
      "file": "kernel/futex.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex.c:futex_unlock_pi",
        "kernel/futex.c:__fixup_pi_state_owner",
        "kernel/futex.c:__fixup_pi_state_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580409168,
      "name": "pi_state_update_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
void pi_state_update_owner(struct futex_pi_state * pi_state, struct task_struct * new_owner)
```

```json
{
  "name": "pi_state_update_owner",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580632928,
      "name": "pi_state_update_owner",
      "external": false,
      "loc": "kernel/futex/pi.c:45",
      "file": "kernel/futex/pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:__fixup_pi_state_owner",
        "kernel/futex/pi.c:__fixup_pi_state_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580632928,
      "name": "pi_state_update_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void pi_state_update_owner(struct futex_pi_state * pi_state, struct task_struct * new_owner)
```

```json
{
  "name": "pi_state_update_owner",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580899328,
      "name": "pi_state_update_owner",
      "external": false,
      "loc": "kernel/futex/pi.c:45",
      "file": "kernel/futex/pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:__fixup_pi_state_owner",
        "kernel/futex/pi.c:__fixup_pi_state_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580899328,
      "name": "pi_state_update_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void pi_state_update_owner(struct futex_pi_state * pi_state, struct task_struct * new_owner)
```

```json
{
  "name": "pi_state_update_owner",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580983296,
      "name": "pi_state_update_owner",
      "external": false,
      "loc": "kernel/futex/pi.c:45",
      "file": "kernel/futex/pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:__fixup_pi_state_owner",
        "kernel/futex/pi.c:__fixup_pi_state_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580983296,
      "name": "pi_state_update_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void pi_state_update_owner(struct futex_pi_state * pi_state, struct task_struct * new_owner)
```

```json
{
  "name": "pi_state_update_owner",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581078816,
      "name": "pi_state_update_owner",
      "external": false,
      "loc": "kernel/futex/pi.c:46",
      "file": "kernel/futex/pi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/futex/pi.c:futex_unlock_pi",
        "kernel/futex/pi.c:__fixup_pi_state_owner",
        "kernel/futex/pi.c:__fixup_pi_state_owner"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581078816,
      "name": "pi_state_update_owner",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 191
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
void pi_state_update_owner(struct futex_pi_state * pi_state, struct task_struct * new_owner)
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
