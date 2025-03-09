# Function: <code>func_id_name</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580485742,
      "name": "func_id_name",
      "external": false,
      "loc": "kernel/bpf/verifier.c:200",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580503135,
      "name": "func_id_name",
      "external": false,
      "loc": "kernel/bpf/verifier.c:202",
      "file": "kernel/bpf/verifier.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580610222,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:24",
      "file": "kernel/bpf/disasm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/bpf/disasm.c:print_bpf_insn"
      ],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:do_check"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580609232,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580705552,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:55",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580705552,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580782128,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:55",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580782128,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580866944,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:47",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580866944,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580917904,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:47",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580917904,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581066976,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:47",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_map_func_compatibility"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581066976,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581080960,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:47",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_map_func_compatibility"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581080960,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581099392,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:54",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:check_map_func_compatibility"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581099392,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581328896,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:54",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_map_func_compatibility"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581328896,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581633264,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:54",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_map_func_compatibility"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581633264,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582020960,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:54",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:check_map_func_compatibility"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582020960,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582213216,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:54",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:__check_func_call",
        "kernel/bpf/verifier.c:check_map_func_compatibility",
        "kernel/bpf/verifier.c:check_reg_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582213216,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582362304,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:54",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:push_callback_call",
        "kernel/bpf/verifier.c:push_callback_call",
        "kernel/bpf/verifier.c:check_map_func_compatibility",
        "kernel/bpf/verifier.c:check_reg_type"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582362304,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492252672,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:47",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492252672,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226144328,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:47",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226144328,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285481376,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:47",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285481376,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272394016,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:47",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272394016,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580886704,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:47",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580886704,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580832768,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:47",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580832768,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580877952,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:47",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580877952,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
const char * func_id_name(int id)
```

```json
{
  "name": "func_id_name",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580936592,
      "name": "func_id_name",
      "external": true,
      "loc": "kernel/bpf/disasm.c:47",
      "file": "kernel/bpf/disasm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:fixup_bpf_calls",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call",
        "kernel/bpf/verifier.c:check_helper_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580936592,
      "name": "func_id_name",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
const char * func_id_name(int id)
```
</details>
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
