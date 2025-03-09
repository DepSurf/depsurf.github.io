# Function: <code>verbose_linfo</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580733936,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:299",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580733936,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 363
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580811136,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:291",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580811136,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580862272,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:291",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580862272,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581003040,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:355",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_read",
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581003040,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581006112,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:359",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_read",
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581006112,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581012640,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:378",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581012640,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581230192,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:379",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581230192,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581517008,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:382",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581517008,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581878784,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:384",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581878784,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 419
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581974592,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:380",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581974592,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 373
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582275568,
      "name": "verbose_linfo",
      "external": true,
      "loc": "kernel/bpf/log.c:360",
      "file": "kernel/bpf/log.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_read_fixed_off",
        "kernel/bpf/verifier.c:check_stack_write_fixed_off"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582275568,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 385
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492187672,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:291",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492187672,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 404
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226084088,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:291",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226084088,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 356
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285403424,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:291",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285403424,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 424
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272340952,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:291",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_stack_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272340952,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 274
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580831072,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:291",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580831072,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580777248,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:291",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580777248,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580822320,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:291",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580822320,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```

```json
{
  "name": "verbose_linfo",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580880640,
      "name": "verbose_linfo",
      "external": false,
      "loc": "kernel/bpf/verifier.c:291",
      "file": "kernel/bpf/verifier.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:is_state_visited",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:push_insn",
        "kernel/bpf/verifier.c:check_mem_access",
        "kernel/bpf/verifier.c:check_mem_access"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580880640,
      "name": "verbose_linfo",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void verbose_linfo(struct bpf_verifier_env * env, u32 insn_off, const char * prefix_fmt, void (anon))
```
</details>
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
