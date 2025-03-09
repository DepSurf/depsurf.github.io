# Function: <code>bin2hex</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583045040,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:68",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/x509_public_key.c:x509_request_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583045040,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583338384,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:68",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583338384,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583463808,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:68",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583463808,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583486080,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:68",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "certs/load_uefi.c:uefi_blacklist_binary",
        "certs/load_uefi.c:uefi_blacklist_x509_tbs",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583486080,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583667120,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:69",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "certs/load_uefi.c:uefi_blacklist_binary",
        "certs/load_uefi.c:uefi_blacklist_x509_tbs",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583667120,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583884736,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:69",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "certs/load_uefi.c:uefi_blacklist_binary",
        "certs/load_uefi.c:uefi_blacklist_x509_tbs",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583884736,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583968944,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:69",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "certs/load_uefi.c:uefi_blacklist_binary",
        "certs/load_uefi.c:uefi_blacklist_x509_tbs",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583968944,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584150080,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:65",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584150080,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584272928,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:65",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584272928,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584681584,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:65",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_ksym_set_name",
        "kernel/bpf/syscall.c:bpf_link_show_fdinfo",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584681584,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584799248,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:66",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:add_build_id_vmcoreinfo",
        "kernel/bpf/core.c:bpf_prog_ksym_set_name",
        "kernel/bpf/syscall.c:bpf_link_show_fdinfo",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584799248,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584843440,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:66",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/crash_core.c:crash_save_vmcoreinfo_init",
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/syscall.c:bpf_link_show_fdinfo",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584843440,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585263360,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:66",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/syscall.c:bpf_link_show_fdinfo",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "security/integrity/evm/evm_crypto.c:dump_security_xattr",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585263360,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 69
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586107664,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:87",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/syscall.c:bpf_link_show_fdinfo",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:get_raw_hash",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "security/integrity/evm/evm_crypto.c:dump_security_xattr",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586107664,
      "name": "bin2hex",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587093152,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:87",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/syscall.c:bpf_link_show_fdinfo",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:get_raw_hash",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "security/integrity/evm/evm_crypto.c:dump_security_xattr",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587093152,
      "name": "bin2hex",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587353264,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:87",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/syscall.c:bpf_link_show_fdinfo",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:get_raw_hash",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587353264,
      "name": "bin2hex",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587639584,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:87",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_prog_kallsyms_add",
        "kernel/bpf/syscall.c:bpf_link_show_fdinfo",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:get_raw_hash",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "security/integrity/evm/evm_crypto.c:dump_security_xattr_l",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639584,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496157408,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:65",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496157408,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229477968,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:65",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229477968,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290420112,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:65",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290420112,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275209936,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:65",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275209936,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584241664,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:65",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584241664,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584176864,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:65",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584176864,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225424,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:65",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225424,
      "name": "bin2hex",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
char * bin2hex(char * dst, const void * src, size_t count)
```

```json
{
  "name": "bin2hex",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584330256,
      "name": "bin2hex",
      "external": true,
      "loc": "lib/hexdump.c:65",
      "file": "lib/hexdump.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/bpf/core.c:bpf_get_prog_name",
        "kernel/bpf/syscall.c:bpf_prog_show_fdinfo",
        "certs/blacklist.c:is_hash_blacklisted",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_packet_set",
        "fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet",
        "fs/ecryptfs/debug.c:ecryptfs_dump_auth_tok",
        "crypto/asymmetric_keys/asymmetric_type.c:find_asymmetric_key",
        "crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584330256,
      "name": "bin2hex",
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
