# Function: <code>bpf_jit_add_poke_descriptor</code>

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
int bpf_jit_add_poke_descriptor(struct bpf_prog * prog, struct bpf_jit_poke_descriptor * poke)
```

```json
{
  "name": "bpf_jit_add_poke_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580918832,
      "name": "bpf_jit_add_poke_descriptor",
      "external": true,
      "loc": "kernel/bpf/core.c:766",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918832,
      "name": "bpf_jit_add_poke_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int bpf_jit_add_poke_descriptor(struct bpf_prog * prog, struct bpf_jit_poke_descriptor * poke)
```

```json
{
  "name": "bpf_jit_add_poke_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580914832,
      "name": "bpf_jit_add_poke_descriptor",
      "external": true,
      "loc": "kernel/bpf/core.c:762",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:jit_subprogs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580914832,
      "name": "bpf_jit_add_poke_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
int bpf_jit_add_poke_descriptor(struct bpf_prog * prog, struct bpf_jit_poke_descriptor * poke)
```

```json
{
  "name": "bpf_jit_add_poke_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580918560,
      "name": "bpf_jit_add_poke_descriptor",
      "external": true,
      "loc": "kernel/bpf/core.c:768",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_misc_fixups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580918560,
      "name": "bpf_jit_add_poke_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_jit_add_poke_descriptor(struct bpf_prog * prog, struct bpf_jit_poke_descriptor * poke)
```

```json
{
  "name": "bpf_jit_add_poke_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_jit_add_poke_descriptor",
      "external": true,
      "loc": "kernel/bpf/core.c:769",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_misc_fixups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592179968,
      "name": "bpf_jit_add_poke_descriptor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581121008,
      "name": "bpf_jit_add_poke_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_jit_add_poke_descriptor(struct bpf_prog * prog, struct bpf_jit_poke_descriptor * poke)
```

```json
{
  "name": "bpf_jit_add_poke_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_jit_add_poke_descriptor",
      "external": true,
      "loc": "kernel/bpf/core.c:772",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_misc_fixups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593953853,
      "name": "bpf_jit_add_poke_descriptor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581390064,
      "name": "bpf_jit_add_poke_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_jit_add_poke_descriptor(struct bpf_prog * prog, struct bpf_jit_poke_descriptor * poke)
```

```json
{
  "name": "bpf_jit_add_poke_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_jit_add_poke_descriptor",
      "external": true,
      "loc": "kernel/bpf/core.c:780",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_misc_fixups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596013271,
      "name": "bpf_jit_add_poke_descriptor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581738672,
      "name": "bpf_jit_add_poke_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_jit_add_poke_descriptor(struct bpf_prog * prog, struct bpf_jit_poke_descriptor * poke)
```

```json
{
  "name": "bpf_jit_add_poke_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_jit_add_poke_descriptor",
      "external": true,
      "loc": "kernel/bpf/core.c:781",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_misc_fixups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596533246,
      "name": "bpf_jit_add_poke_descriptor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071581898096,
      "name": "bpf_jit_add_poke_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int bpf_jit_add_poke_descriptor(struct bpf_prog * prog, struct bpf_jit_poke_descriptor * poke)
```

```json
{
  "name": "bpf_jit_add_poke_descriptor",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "bpf_jit_add_poke_descriptor",
      "external": true,
      "loc": "kernel/bpf/core.c:824",
      "file": "kernel/bpf/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_misc_fixups"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597434008,
      "name": "bpf_jit_add_poke_descriptor.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071582021984,
      "name": "bpf_jit_add_poke_descriptor",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 404
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
int bpf_jit_add_poke_descriptor(struct bpf_prog * prog, struct bpf_jit_poke_descriptor * poke)
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
