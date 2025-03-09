# Function: <code>kmemdup_nul</code>

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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580800176,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:131",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580800176,
      "name": "kmemdup_nul",
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580888880,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:131",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/ss/services.c:security_context_to_sid_core"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580888880,
      "name": "kmemdup_nul",
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581024800,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:131",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581024800,
      "name": "kmemdup_nul",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581102320,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:124",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:__create_synth_event",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "drivers/pci/pci.c:pci_dev_str_match",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581102320,
      "name": "kmemdup_nul",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581166576,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:136",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "drivers/pci/pci.c:pci_dev_str_match",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581166576,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581224368,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:143",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "drivers/pci/pci.c:pci_dev_str_match",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581224368,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581411936,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:143",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "security/security.c:security_setprocattr",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "lib/parser.c:match_number",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581411936,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581454608,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:144",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "security/security.c:security_setprocattr",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "lib/parser.c:match_number",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581454608,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581475504,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:144",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "security/security.c:security_setprocattr",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "lib/parser.c:match_uint",
        "lib/parser.c:match_number",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581475504,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581729568,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:144",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "security/security.c:security_setprocattr",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "lib/parser.c:match_uint",
        "lib/parser.c:match_number",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581729568,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 78
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582109104,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:145",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "fs/ext4/super.c:parse_options",
        "security/security.c:security_setprocattr",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "lib/parser.c:match_uint",
        "lib/parser.c:match_number",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582109104,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582584992,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:145",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "fs/ext4/super.c:parse_options",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_strdup",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582584992,
      "name": "kmemdup_nul",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582792144,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:168",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "fs/ext4/super.c:parse_options",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_strdup",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582792144,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582967184,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:168",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_events_inject.c:parse_field",
        "kernel/trace/trace_events_synth.c:create_synth_event",
        "kernel/trace/trace_events_synth.c:create_or_delete_synth_event",
        "kernel/trace/trace_events_synth.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "kernel/trace/trace_fprobe.c:__trace_fprobe_create",
        "fs/fs_context.c:vfs_parse_fs_string",
        "fs/ext4/super.c:parse_options",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_strdup",
        "drivers/pci/pci.c:pci_dev_str_match_path",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582967184,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492612896,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:143",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "drivers/pci/pci.c:pci_dev_str_match",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492612896,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226464740,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:143",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_filter.c:append_filter_err",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt",
        "security/selinux/ss/services.c:security_context_to_sid_core",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "lib/parser.c:match_number",
        "drivers/pci/pci.c:pci_dev_str_match",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226464740,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285929792,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:143",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "drivers/pci/pci.c:pci_dev_str_match",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285929792,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272639902,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:143",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "fs/fs_context.c:vfs_parse_fs_string",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "drivers/pci/pci.c:pci_dev_str_match",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272639902,
      "name": "kmemdup_nul",
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581193216,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:143",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "drivers/pci/pci.c:pci_dev_str_match",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193216,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581139968,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:143",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "drivers/pci/pci.c:pci_dev_str_match",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139968,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581184416,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:143",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "drivers/pci/pci.c:pci_dev_str_match",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581184416,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
```

```json
{
  "name": "kmemdup_nul",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581247664,
      "name": "kmemdup_nul",
      "external": true,
      "loc": "mm/util.c:143",
      "file": "mm/util.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_events_filter.c:parse_pred",
        "kernel/trace/trace_events_hist.c:parse_synth_field",
        "kernel/trace/trace_probe.c:traceprobe_parse_probe_arg",
        "fs/fs_context.c:vfs_parse_fs_string",
        "security/selinux/hooks.c:selinux_sb_eat_lsm_opts",
        "security/selinux/hooks.c:selinux_add_mnt_opt",
        "security/smack/smack_lsm.c:smack_sb_eat_lsm_opts",
        "lib/parser.c:match_u64",
        "drivers/pci/pci.c:pci_dev_str_match",
        "net/dns_resolver/dns_query.c:dns_query"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581247664,
      "name": "kmemdup_nul",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
char * kmemdup_nul(const char * s, size_t len, gfp_t gfp)
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
