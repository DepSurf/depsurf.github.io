# Function: <code>memchr_inv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void * memchr_inv(const void * start, int c, size_t bytes)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582981760,
      "name": "memchr_inv",
      "external": true,
      "loc": "lib/string.c:896",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "mm/vmstat.c:vmstat_shepherd",
        "mm/slub.c:check_bytes_and_report",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582981760,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void * memchr_inv(const void * start, int c, size_t bytes)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583270944,
      "name": "memchr_inv",
      "external": true,
      "loc": "lib/string.c:893",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583270944,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
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
void * memchr_inv(const void * start, int c, size_t bytes)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389712,
      "name": "memchr_inv",
      "external": true,
      "loc": "lib/string.c:893",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "security/integrity/ima/ima_policy.c:ima_parse_rule"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389712,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 267
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588290650,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/string.h:364",
      "file": "arch/x86/mm/init_64.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588244192,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579085523,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/string.h:399",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:validate_xstate_header",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:SyS_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588795616,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579090894,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/string.h:400",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:validate_xstate_header",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/syscall.c:bpf_btf_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_btf_load",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_prog_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_test_run",
        "kernel/bpf/syscall.c:bpf_prog_query",
        "kernel/bpf/syscall.c:bpf_prog_detach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_obj_get",
        "kernel/bpf/syscall.c:bpf_obj_pin",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589173760,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
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
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579096206,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/string.h:407",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:validate_xstate_header",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589403680,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 237
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579106622,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/string.h:414",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:validate_xstate_header",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589859680,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579108446,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/string.h:435",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:validate_xstate_header",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_create_info",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590085472,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579121600,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/string.h:461",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:validate_user_xstate_header",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pte_table",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_enable_stats",
        "kernel/bpf/syscall.c:bpf_link_get_fd_by_id",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_test_run",
        "kernel/bpf/syscall.c:bpf_prog_query",
        "kernel/bpf/syscall.c:bpf_prog_detach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_freeze",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_create_info",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/ethtool/bitset.c:ethnl_compact_sanity_checks"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083280,
      "name": "memchr_inv",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579121744,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/string.h:502",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:validate_user_xstate_header",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages",
        "arch/x86/mm/init_64.c:remove_pud_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pte_table",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:bpf_enable_stats",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_test_run",
        "kernel/bpf/syscall.c:bpf_prog_query",
        "kernel/bpf/syscall.c:bpf_prog_detach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_freeze",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_create_info",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:linereq_set_config",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/ethtool/bitset.c:ethnl_compact_sanity_checks"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585232448,
      "name": "memchr_inv",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579127968,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/fortify-string.h:250",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:validate_user_xstate_header",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/ethtool/bitset.c:ethnl_compact_sanity_checks"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585115312,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579152944,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/fortify-string.h:250",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_raw_tracepoint_open",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_check_uarg_tail_zero",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/ethtool/bitset.c:ethnl_compact_sanity_checks"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585564000,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 202
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
void * memchr_inv(const const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579195820,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/fortify-string.h:436",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_freeze",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_check_uarg_tail_zero",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/slub.c:slab_pad_check",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/landlock/fs.c:check_access_path_dual",
        "security/landlock/fs.c:check_access_path_dual",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_validate",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/ethtool/bitset.c:ethnl_compact_sanity_checks"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586718496,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void * memchr_inv(const const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579251907,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/fortify-string.h:674",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_check_uarg_tail_zero",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/slub.c:slab_pad_check",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/landlock/fs.c:is_access_to_paths_allowed",
        "security/landlock/fs.c:is_access_to_paths_allowed",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_validate",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/ethtool/bitset.c:ethnl_compact_sanity_checks",
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595880848,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void * memchr_inv(const const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579258387,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/fortify-string.h:744",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_freeze",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_check_uarg_tail_zero",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "mm/slub.c:slab_pad_check",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/verify.c:verify_data_block",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/landlock/fs.c:is_access_to_paths_allowed",
        "security/landlock/fs.c:is_access_to_paths_allowed",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_validate",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/ethtool/bitset.c:ethnl_compact_sanity_checks",
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596398080,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void * memchr_inv(const const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579288771,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/fortify-string.h:689",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:copy_uabi_to_xstate",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu",
        "arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:__sys_bpf",
        "kernel/bpf/syscall.c:bpf_prog_bind_map",
        "kernel/bpf/syscall.c:link_update",
        "kernel/bpf/syscall.c:link_create",
        "kernel/bpf/syscall.c:bpf_map_do_batch",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_map_get_fd_by_id",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_query",
        "kernel/bpf/syscall.c:bpf_prog_detach",
        "kernel/bpf/syscall.c:bpf_prog_attach",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_freeze",
        "kernel/bpf/syscall.c:map_lookup_and_delete_elem",
        "kernel/bpf/syscall.c:map_get_next_key",
        "kernel/bpf/syscall.c:map_delete_elem",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "kernel/bpf/syscall.c:bpf_check_uarg_tail_zero",
        "kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "kernel/bpf/bpf_struct_ops.c:check_zero_holes",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/slub.c:slab_pad_check",
        "mm/slub.c:check_bytes_and_report",
        "mm/page_poison.c:__kernel_unpoison_pages",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/policy.c:fscrypt_supported_v2_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_get_descriptor",
        "fs/verity/verify.c:verify_data_block",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "security/landlock/fs.c:scope_to_request",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/gpio/gpiolib-cdev.c:lineinfo_get",
        "drivers/gpio/gpiolib-cdev.c:linereq_create",
        "drivers/gpio/gpiolib-cdev.c:gpio_v2_line_config_validate",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/gpu/drm/drm_edid.c:edid_block_is_zero",
        "net/core/rtnetlink.c:rtnl_fill_ifinfo",
        "net/bpf/test_run.c:bpf_prog_test_run_sk_lookup",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/bpf/test_run.c:convert___skb_to_skb",
        "net/ethtool/bitset.c:ethnl_compact_sanity_checks",
        "net/ipv4/tcp.c:do_tcp_getsockopt"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597293312,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492142620,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/string.h:435",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_create_info",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503863296,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226038680,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/string.h:435",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_task_fd_query",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_create_info",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236490924,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285349404,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/string.h:435",
      "file": "kernel/bpf/syscall.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_create_info",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297721728,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void * memchr_inv(const void * start, int c, size_t bytes)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279760686,
      "name": "memchr_inv",
      "external": true,
      "loc": "lib/string.c:1030",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/crypto/policy.c:fscrypt_supported_policy",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_create_info",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279760686,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 226
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579108830,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/string.h:435",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:validate_xstate_header",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_create_info",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/nvme/host/core.c:nvme_alloc_ns_head",
        "drivers/nvme/host/core.c:nvme_alloc_ns_head",
        "drivers/nvme/host/core.c:nvme_ns_id_attrs_are_visible",
        "drivers/nvme/host/core.c:nvme_ns_id_attrs_are_visible",
        "drivers/nvme/host/core.c:wwid_show",
        "drivers/nvme/host/core.c:wwid_show",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589687728,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579041214,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/string.h:435",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:validate_xstate_header",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_create_info",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "drivers/nvme/host/core.c:nvme_alloc_ns_head",
        "drivers/nvme/host/core.c:nvme_alloc_ns_head",
        "drivers/nvme/host/core.c:nvme_ns_id_attrs_are_visible",
        "drivers/nvme/host/core.c:nvme_ns_id_attrs_are_visible",
        "drivers/nvme/host/core.c:wwid_show",
        "drivers/nvme/host/core.c:wwid_show",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589413520,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579108382,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/string.h:435",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:validate_xstate_header",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_create_info",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590131104,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void * memchr_inv(const void * p, int c, size_t size)
```

```json
{
  "name": "memchr_inv",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579113454,
      "name": "memchr_inv",
      "external": true,
      "loc": "include/linux/string.h:435",
      "file": "arch/x86/kernel/fpu/xstate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/xstate.c:validate_xstate_header",
        "arch/x86/mm/init_64.c:remove_pagetable",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "arch/x86/mm/init_64.c:remove_pmd_table",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:__do_sys_bpf",
        "kernel/bpf/syscall.c:bpf_obj_get_info_by_fd",
        "kernel/bpf/syscall.c:bpf_obj_get_next_id",
        "kernel/bpf/syscall.c:bpf_prog_load",
        "kernel/bpf/syscall.c:map_update_elem",
        "kernel/bpf/syscall.c:map_lookup_elem",
        "kernel/bpf/syscall.c:map_create",
        "mm/vmstat.c:need_update",
        "mm/vmstat.c:need_update",
        "mm/slub.c:check_bytes_and_report",
        "fs/crypto/keyring.c:fscrypt_ioctl_get_key_status",
        "fs/crypto/keyring.c:do_remove_key",
        "fs/crypto/keyring.c:fscrypt_ioctl_add_key",
        "fs/verity/enable.c:fsverity_ioctl_enable",
        "fs/verity/open.c:fsverity_create_info",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "fs/ext4/ioctl.c:ext4_ioc_getfsmap",
        "security/keys/dh.c:__keyctl_dh_compute",
        "crypto/dh_helper.c:crypto_dh_decode_key",
        "drivers/char/tpm/tpm2-cmd.c:tpm2_get_pcr_allocation",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_flow_dissector",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb",
        "net/bpf/test_run.c:bpf_prog_test_run_skb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590181488,
      "name": "memchr_inv",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void * p</code>
</li>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param removed. </b>
<code>const void * start</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t bytes</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const void * p</code> ➡️ <code>const const void * p</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void * start</code>
</li>
<li>
<b>Param added. </b>
<code>size_t bytes</code>
</li>
<li>
<b>Param removed. </b>
<code>const void * p</code>
</li>
<li>
<b>Param removed. </b>
<code>size_t size</code>
</li>
</ul>
</details>
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
