# Function: <code>bsearch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583030800,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:33",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:find_symbol_in_section",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "kernel/trace/trace_events.c:check_ignore_pid",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583030800,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583323264,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:33",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_symbol_in_section",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583323264,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583448176,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:33",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_symbol_in_section",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583448176,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583468832,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:33",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_symbol_in_section",
        "kernel/trace/ftrace.c:ftrace_free_init_mem",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583468832,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 127
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583649744,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:33",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583649744,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 130
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583867648,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:33",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "kernel/bpf/verifier.c:find_subprog",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583867648,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583952928,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:33",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_exported_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "kernel/bpf/verifier.c:find_subprog",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583952928,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584132816,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:poke_int3_handler",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_exported_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "kernel/bpf/verifier.c:find_subprog",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584132816,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584255216,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:poke_int3_handler",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_exported_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "kernel/bpf/verifier.c:find_subprog",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584255216,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, cmp_func_t cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584662976,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_exported_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:lookup_rec",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:check_max_stack_depth",
        "lib/extable.c:search_extable",
        "drivers/tty/vt/vt.c:do_con_write",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw",
        "drivers/base/regmap/regcache.c:regcache_sync_block_single",
        "drivers/base/regmap/regcache.c:regcache_default_sync",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584662976,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, cmp_func_t cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584780336,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_exported_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:lookup_rec",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:check_func_call",
        "kernel/bpf/verifier.c:check_max_stack_depth",
        "kernel/bpf/btf.c:btf_id_set_contains",
        "lib/extable.c:search_extable",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/base/regmap/regcache.c:regcache_sync_block_raw",
        "drivers/base/regmap/regcache.c:regcache_sync_block_single",
        "drivers/base/regmap/regcache.c:regcache_default_sync",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584780336,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, cmp_func_t cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584824432,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_exported_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:lookup_rec",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_max_stack_depth",
        "kernel/bpf/verifier.c:bpf_jit_find_kfunc_model",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/btf.c:btf_id_set_contains",
        "lib/extable.c:search_extable",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/base/regmap/regcache.c:regcache_default_sync",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584824432,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, cmp_func_t cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585242720,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_exported_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:lookup_rec",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_max_stack_depth",
        "kernel/bpf/verifier.c:bpf_jit_find_kfunc_model",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/btf.c:btf_id_set_contains",
        "lib/extable.c:search_extable",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/base/regmap/regcache.c:regcache_sync_block",
        "drivers/base/regmap/regcache.c:regcache_sync_block",
        "drivers/base/regmap/regcache.c:regcache_default_sync",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585242720,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, cmp_func_t cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586083632,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:find_exported_symbol_in_section",
        "kernel/module/kallsyms.c:module_get_kallsym",
        "kernel/module/kallsyms.c:module_get_kallsym",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:kallsyms_callback",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:lookup_rec",
        "kernel/trace/bpf_trace.c:bpf_get_attach_cookie_kprobe_multi",
        "kernel/bpf/syscall.c:bpf_map_kptr_off_contains",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_max_stack_depth",
        "kernel/bpf/verifier.c:bpf_jit_find_kfunc_model",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/btf.c:btf_kfunc_id_set_contains",
        "kernel/bpf/btf.c:btf_parse_kptrs",
        "lib/extable.c:search_extable",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/base/regmap/regcache.c:regcache_reg_needs_sync",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586083632,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, cmp_func_t cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587064768,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module/main.c:find_exported_symbol_in_section",
        "kernel/module/kallsyms.c:module_get_kallsym",
        "kernel/module/kallsyms.c:module_get_kallsym",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:kallsyms_callback",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:lookup_rec",
        "kernel/trace/bpf_trace.c:module_callback",
        "kernel/trace/bpf_trace.c:bpf_get_attach_cookie_kprobe_multi",
        "kernel/bpf/syscall.c:btf_record_find",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:do_misc_fixups",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_max_stack_depth",
        "kernel/bpf/verifier.c:bpf_jit_find_kfunc_model",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/btf.c:btf_kfunc_is_modify_return",
        "kernel/bpf/btf.c:btf_kfunc_id_set_contains",
        "kernel/bpf/btf.c:btf_kfunc_id_set_contains",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_check_and_fixup_fields",
        "kernel/bpf/btf.c:btf_parse_fields",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_is_trusted",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_find_cgroup_shim",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/base/regmap/regcache.c:regcache_default_sync",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587064768,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, cmp_func_t cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587322832,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_numa_find_nth_cpu",
        "kernel/module/main.c:find_exported_symbol_in_section",
        "kernel/module/kallsyms.c:module_get_kallsym",
        "kernel/module/kallsyms.c:module_get_kallsym",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:kallsyms_callback",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:lookup_rec",
        "kernel/trace/bpf_trace.c:bpf_get_attach_cookie_kprobe_multi",
        "kernel/bpf/syscall.c:btf_record_find",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:fixup_kfunc_call",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:do_check",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_max_stack_depth_subprog",
        "kernel/bpf/verifier.c:backtrack_insn",
        "kernel/bpf/verifier.c:bpf_jit_find_kfunc_model",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/verifier.c:bpf_get_kfunc_addr",
        "kernel/bpf/btf.c:__btf_kfunc_id_set_contains",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_check_and_fixup_fields",
        "kernel/bpf/btf.c:btf_parse_kptr",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_is_trusted",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_find_cgroup_shim",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/base/regmap/regcache.c:regcache_reg_needs_sync",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err",
        "net/core/filter.c:tracing_iter_filter",
        "net/core/xdp.c:bpf_dev_bound_kfunc_id",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587322832,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, cmp_func_t cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587605776,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sched/build_utility.c:sched_numa_find_nth_cpu",
        "kernel/module/main.c:find_exported_symbol_in_section",
        "kernel/module/kallsyms.c:module_get_kallsym",
        "kernel/module/kallsyms.c:module_get_kallsym",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:kallsyms_callback",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:lookup_rec",
        "kernel/trace/bpf_trace.c:bpf_get_file_xattr_filter",
        "kernel/trace/bpf_trace.c:bpf_get_attach_cookie_kprobe_multi",
        "kernel/bpf/syscall.c:btf_record_find",
        "kernel/bpf/verifier.c:check_attach_btf_id",
        "kernel/bpf/verifier.c:bpf_check_attach_target",
        "kernel/bpf/verifier.c:fixup_kfunc_call",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:jit_subprogs",
        "kernel/bpf/verifier.c:check_ld_imm",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_kfunc_call",
        "kernel/bpf/verifier.c:check_max_stack_depth_subprog",
        "kernel/bpf/verifier.c:backtrack_insn",
        "kernel/bpf/verifier.c:bpf_jit_find_kfunc_model",
        "kernel/bpf/verifier.c:add_kfunc_call",
        "kernel/bpf/verifier.c:__find_kfunc_desc_btf",
        "kernel/bpf/verifier.c:bpf_get_kfunc_addr",
        "kernel/bpf/btf.c:__btf_kfunc_id_set_contains",
        "kernel/bpf/btf.c:btf_struct_access",
        "kernel/bpf/btf.c:btf_check_and_fixup_fields",
        "kernel/bpf/btf.c:btf_parse_kptr",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_is_trusted",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_func_proto",
        "kernel/bpf/bpf_lsm.c:bpf_ima_inode_hash_allowed",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_verify_prog",
        "kernel/bpf/bpf_lsm.c:bpf_lsm_find_cgroup_shim",
        "fs/verity/measure.c:bpf_get_fsverity_digest_filter",
        "drivers/tty/vt/vt.c:vc_con_write_normal",
        "drivers/base/regmap/regcache.c:regcache_reg_needs_sync",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err",
        "net/core/filter.c:tracing_iter_filter",
        "net/core/xdp.c:bpf_dev_bound_kfunc_id",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587605776,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496133720,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/cpufeature.c:do_emulate_mrs",
        "arch/arm64/kernel/cpufeature.c:init_cpu_ftr_reg",
        "virt/kvm/kvm_main.c:kvm_io_bus_get_first_dev",
        "arch/arm64/kvm/sys_regs.c:find_reg",
        "virt/kvm/arm/vgic/vgic-mmio.c:vgic_get_mmio_region",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_exported_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "kernel/bpf/verifier.c:find_subprog",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496133720,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229457092,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_exported_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "kernel/bpf/verifier.c:find_subprog",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229457092,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290390832,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_exported_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "kernel/bpf/verifier.c:find_subprog",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290390832,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275191408,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_exported_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "kernel/bpf/verifier.c:find_subprog",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275191408,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 98
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584223952,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:poke_int3_handler",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_exported_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "kernel/bpf/verifier.c:find_subprog",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223952,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584159168,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:poke_int3_handler",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_exported_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "kernel/bpf/verifier.c:find_subprog",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584159168,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584207712,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:poke_int3_handler",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_exported_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "kernel/bpf/verifier.c:find_subprog",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584207712,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
void * bsearch(const void * key, const void * base, size_t num, size_t size, int (*)(const void *, const void *) cmp)
```

```json
{
  "name": "bsearch",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584312272,
      "name": "bsearch",
      "external": true,
      "loc": "lib/bsearch.c:31",
      "file": "lib/bsearch.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:poke_int3_handler",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:module_get_kallsym",
        "kernel/module.c:find_exported_symbol_in_section",
        "kernel/user_namespace.c:map_id_up",
        "kernel/user_namespace.c:map_id_range_down",
        "kernel/trace/ftrace.c:ftrace_free_mem",
        "kernel/trace/ftrace.c:ftrace_location_range",
        "kernel/bpf/verifier.c:find_subprog",
        "drivers/base/regmap/regcache.c:regcache_lookup_reg",
        "drivers/firmware/efi/efi.c:efi_status_to_str",
        "drivers/firmware/efi/efi.c:efi_status_to_err",
        "lib/extable.c:search_extable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312272,
      "name": "bsearch",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*)(const void *, const void *) cmp</code> ➡️ <code>cmp_func_t cmp</code>
</li>
</ul>
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
