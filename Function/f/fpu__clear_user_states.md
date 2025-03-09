# Function: <code>fpu__clear_user_states</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void fpu__clear_user_states(struct fpu * fpu)
```

```json
{
  "name": "fpu__clear_user_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579115040,
      "name": "fpu__clear_user_states",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:348",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:do_signal",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579115040,
      "name": "fpu__clear_user_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void fpu__clear_user_states(struct fpu * fpu)
```

```json
{
  "name": "fpu__clear_user_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579115056,
      "name": "fpu__clear_user_states",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:388",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:arch_do_signal_or_restart",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579115056,
      "name": "fpu__clear_user_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void fpu__clear_user_states(struct fpu * fpu)
```

```json
{
  "name": "fpu__clear_user_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579121712,
      "name": "fpu__clear_user_states",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:388",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579121712,
      "name": "fpu__clear_user_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
void fpu__clear_user_states(struct fpu * fpu)
```

```json
{
  "name": "fpu__clear_user_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579146688,
      "name": "fpu__clear_user_states",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:372",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal",
        "arch/x86/kernel/fpu/signal.c:fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579146688,
      "name": "fpu__clear_user_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void fpu__clear_user_states(struct fpu * fpu)
```

```json
{
  "name": "fpu__clear_user_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579188032,
      "name": "fpu__clear_user_states",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:709",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal",
        "arch/x86/kernel/fpu/signal.c:fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579188032,
      "name": "fpu__clear_user_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void fpu__clear_user_states(struct fpu * fpu)
```

```json
{
  "name": "fpu__clear_user_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579244000,
      "name": "fpu__clear_user_states",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:706",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal",
        "arch/x86/kernel/fpu/signal.c:fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244000,
      "name": "fpu__clear_user_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void fpu__clear_user_states(struct fpu * fpu)
```

```json
{
  "name": "fpu__clear_user_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579250352,
      "name": "fpu__clear_user_states",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:706",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal",
        "arch/x86/kernel/fpu/signal.c:fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579250352,
      "name": "fpu__clear_user_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void fpu__clear_user_states(struct fpu * fpu)
```

```json
{
  "name": "fpu__clear_user_states",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579279776,
      "name": "fpu__clear_user_states",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:741",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/signal.c:handle_signal",
        "arch/x86/kernel/fpu/signal.c:fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579279776,
      "name": "fpu__clear_user_states",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void fpu__clear_user_states(struct fpu * fpu)
```
</details>
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
