# Function: <code>memdup_user_nul</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580698704,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:187",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_disable",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580698704,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580764512,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:187",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_disable",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764512,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800768,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:214",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/integrity/ima/ima_fs.c:ima_write_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800768,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580889472,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:214",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/integrity/ima/ima_fs.c:ima_write_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580889472,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581025216,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:236",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581025216,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581102736,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:229",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "drivers/media/cec/cec-core.c:cec_error_inj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581102736,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581167168,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:243",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/media/cec/cec-core.c:cec_error_inj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581167168,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581224960,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:250",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/media/cec/cec-core.c:cec_error_inj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224960,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581413952,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:250",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "lib/bitmap.c:bitmap_parse_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581413952,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581456800,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:251",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "lib/bitmap.c:bitmap_parse_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581456800,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581477744,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:251",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "lib/bitmap.c:bitmap_parse_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581477744,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581730144,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:251",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "lib/bitmap.c:bitmap_parse_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581730144,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582111152,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:252",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "lib/bitmap.c:bitmap_parse_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582111152,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582585456,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:252",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "lib/bitmap.c:bitmap_parse_user",
        "lib/string_helpers.c:parse_int_array_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582585456,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792752,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:275",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_disable",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "lib/bitmap.c:bitmap_parse_user",
        "lib/string_helpers.c:parse_int_array_user",
        "drivers/pinctrl/pinmux.c:pinmux_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792752,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582967776,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:275",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "kernel/trace/trace_events_inject.c:event_inject_write",
        "fs/fsopen.c:__do_sys_fsconfig",
        "fs/proc/base.c:timens_offsets_write",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_disable",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:handle_policy_update",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap-str.c:bitmap_parselist_user",
        "lib/bitmap-str.c:bitmap_parse_user",
        "lib/string_helpers.c:parse_int_array_user",
        "drivers/pinctrl/pinmux.c:pinmux_select",
        "drivers/gpu/drm/drm_debugfs_crc.c:crc_control_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582967776,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492615200,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:250",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "fs/fsopen.c:__arm64_sys_fsconfig",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/media/cec/cec-core.c:cec_error_inj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492615200,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226467016,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:250",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/media/cec/cec-core.c:cec_error_inj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226467016,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285930912,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:250",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/pseries/reconfig.c:ofdt_write",
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/media/cec/cec-core.c:cec_error_inj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285930912,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 276
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272640282,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:250",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "fs/fsopen.c:__se_sys_fsconfig",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/media/cec/cec-core.c:cec_error_inj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272640282,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581193808,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:250",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/media/cec/cec-core.c:cec_error_inj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193808,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581140560,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:250",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/media/cec/cec-core.c:cec_error_inj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581140560,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581185008,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:250",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/media/cec/cec-core.c:cec_error_inj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581185008,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void * memdup_user_nul(const void * src, size_t len)
```

```json
{
  "name": "memdup_user_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581248256,
      "name": "memdup_user_nul",
      "external": true,
      "loc": "mm/util.c:250",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/sysctl.c:proc_do_large_bitmap",
        "kernel/sysctl.c:__do_proc_doulongvec_minmax",
        "kernel/sysctl.c:__do_proc_douintvec",
        "kernel/sysctl.c:__do_proc_dointvec",
        "kernel/user_namespace.c:map_write",
        "kernel/trace/blktrace.c:blk_msg_write",
        "kernel/trace/trace_events.c:subsystem_filter_write",
        "kernel/trace/trace_events.c:event_filter_write",
        "kernel/trace/trace_events_trigger.c:event_trigger_write",
        "mm/page_alloc.c:numa_zonelist_order_handler",
        "fs/fsopen.c:__ia32_sys_fsconfig",
        "fs/fsopen.c:__x64_sys_fsconfig",
        "fs/proc/generic.c:proc_simple_write",
        "security/selinux/selinuxfs.c:sel_write_avc_cache_threshold",
        "security/selinux/selinuxfs.c:sel_commit_bools_write",
        "security/selinux/selinuxfs.c:sel_write_bool",
        "security/selinux/selinuxfs.c:sel_write_validatetrans",
        "security/selinux/selinuxfs.c:sel_write_checkreqprot",
        "security/selinux/selinuxfs.c:sel_write_enforce",
        "security/smack/smackfs.c:smk_write_relabel_self",
        "security/smack/smackfs.c:smk_write_syslog",
        "security/smack/smackfs.c:smk_write_onlycap",
        "security/smack/smackfs.c:smk_write_ambient",
        "security/smack/smackfs.c:smk_write_net6addr",
        "security/smack/smackfs.c:smk_write_net4addr",
        "security/tomoyo/securityfs_if.c:tomoyo_write_self",
        "security/safesetid/securityfs.c:safesetid_file_write",
        "security/lockdown/lockdown.c:lockdown_write",
        "security/integrity/ima/ima_fs.c:ima_write_policy",
        "security/integrity/evm/evm_secfs.c:evm_write_xattrs",
        "lib/bitmap.c:bitmap_parselist_user",
        "drivers/media/cec/cec-core.c:cec_error_inj_write"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581248256,
      "name": "memdup_user_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void * memdup_user_nul(const void * src, size_t len)
```
</details>
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
