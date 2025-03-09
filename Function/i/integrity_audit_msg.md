# Function: <code>integrity_audit_msg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582606496,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:31",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582606496,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582851616,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:31",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582851616,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582947648,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:31",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582947648,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582997824,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:31",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582997824,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583161920,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:31",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583161920,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583367408,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:31",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583367408,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 480
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583486160,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:31",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583486160,
      "name": "integrity_audit_msg",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672256,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672256,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583779264,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583779264,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584169744,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:ima_file_mprotect",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584169744,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584289312,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:ima_file_mprotect",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584289312,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584323152,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:ima_file_mprotect",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584323152,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584710288,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:ima_file_mprotect",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_inode_setxattr",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr",
        "security/integrity/evm/evm_main.c:evm_protect_xattr",
        "security/integrity/evm/evm_main.c:evm_protect_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584710288,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585384080,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:ima_file_mprotect",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_inode_setxattr",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr",
        "security/integrity/evm/evm_main.c:evm_protect_xattr",
        "security/integrity/evm/evm_main.c:evm_protect_xattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585384080,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586135792,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:ima_file_mprotect",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_inode_setxattr",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586135792,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586373664,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:ima_file_mprotect",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_inode_setxattr",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586373664,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586638208,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:ima_file_mprotect",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_inode_setxattr",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr",
        "security/integrity/evm/evm_main.c:evm_inode_set_acl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586638208,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495581976,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495581976,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 436
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228943268,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228943268,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 488
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289679712,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289679712,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 572
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274747798,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274747798,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583748000,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583748000,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583685056,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583685056,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583731776,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583731776,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
void integrity_audit_msg(int audit_msgno, struct inode * inode, const unsigned char * fname, const char * op, const char * cause, int result, int audit_info)
```

```json
{
  "name": "integrity_audit_msg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583832656,
      "name": "integrity_audit_msg",
      "external": true,
      "loc": "security/integrity/integrity_audit.c:28",
      "file": "security/integrity/integrity_audit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/integrity/ima/ima_fs.c:ima_release_policy",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/ima/ima_queue.c:ima_add_template_entry",
        "security/integrity/ima/ima_init.c:ima_add_boot_aggregate",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_main.c:process_measurement",
        "security/integrity/ima/ima_api.c:ima_store_measurement",
        "security/integrity/ima/ima_api.c:ima_collect_measurement",
        "security/integrity/ima/ima_api.c:ima_add_violation",
        "security/integrity/ima/ima_api.c:ima_store_template",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_policy.c:ima_parse_add_rule",
        "security/integrity/ima/ima_template_lib.c:ima_eventdigest_init",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/ima/ima_appraise.c:ima_appraise_measurement",
        "security/integrity/evm/evm_main.c:evm_inode_setattr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583832656,
      "name": "integrity_audit_msg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
