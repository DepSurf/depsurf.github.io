# Function: <code>bpf_patch_insn_data</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580501632,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:3513",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580501632,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580560128,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:4321",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580560128,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 259
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580643040,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:5237",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580643040,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580704880,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:6423",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580704880,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 317
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580806000,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8126",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580806000,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580857136,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8141",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580857136,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580984096,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:9255",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580984096,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580992656,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:10184",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580992656,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580999856,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11449",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999856,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 276
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581214240,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:11824",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581214240,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 644
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581498656,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:12883",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581498656,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 665
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581852624,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:14860",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:inline_bpf_loop",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581852624,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581979136,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:17077",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:inline_bpf_loop",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581979136,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 651
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582107424,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:18231",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:inline_bpf_loop",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582107424,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 628
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492182624,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8141",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492182624,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 464
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226079284,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8141",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226079284,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 436
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285396768,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8141",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285396768,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 620
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272336824,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8141",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272336824,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 426
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580825936,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8141",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580825936,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580772112,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8141",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580772112,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580817184,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8141",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580817184,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```

```json
{
  "name": "bpf_patch_insn_data",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580875568,
      "name": "bpf_patch_insn_data",
      "external": false,
      "loc": "kernel/bpf/verifier.c:8141",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:bpf_check",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses",
        "kernel/bpf/verifier.c:convert_ctx_accesses"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580875568,
      "name": "bpf_patch_insn_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 423
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
struct bpf_prog * bpf_patch_insn_data(struct bpf_verifier_env * env, u32 off, const struct bpf_insn * patch, u32 len)
```
</details>
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
