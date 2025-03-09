# Function: <code>strnchr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582980672,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:422",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582980672,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583269888,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:422",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583269888,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583388656,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:422",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/lib.c:aa_splitn_fqname",
        "net/core/dev.c:__dev_alloc_name"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583388656,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588245168,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:422",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "net/core/dev.c:__dev_alloc_name",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588245168,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588796592,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:423",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588796592,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589174704,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:423",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589174704,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589404624,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:424",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/security.c:security_setprocattr",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589404624,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589860496,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:463",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/security.c:security_setprocattr",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589860496,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590085984,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:465",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/security.c:security_setprocattr",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590085984,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585083808,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:506",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:unknown_bootoption",
        "kernel/module.c:module_kallsyms_lookup_name",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/integrity/ima/ima_template_lib.c:ima_show_template_field_data",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083808,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585232976,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:503",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:unknown_bootoption",
        "kernel/module.c:module_kallsyms_lookup_name",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/integrity/ima/ima_template_lib.c:ima_show_template_field_data",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585232976,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585115856,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:503",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:unknown_bootoption",
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/integrity/ima/ima_template_lib.c:ima_show_template_field_data",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585115856,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585564544,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:504",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:unknown_bootoption",
        "kernel/module.c:module_kallsyms_lookup_name",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "drivers/spi/spi.c:__spi_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585564544,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586717168,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:465",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:unknown_bootoption",
        "kernel/module/kallsyms.c:module_kallsyms_lookup_name",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "lib/kobject_uevent.c:kobject_synth_uevent",
        "drivers/base/driver.c:driver_set_override",
        "drivers/spi/spi.c:__spi_register_driver"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586717168,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595879344,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:400",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:unknown_bootoption",
        "kernel/module/kallsyms.c:module_kallsyms_lookup_name",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "drivers/base/driver.c:driver_set_override",
        "drivers/spi/spi.c:__spi_register_driver",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595879344,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596396736,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:400",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:unknown_bootoption",
        "kernel/module/kallsyms.c:module_kallsyms_lookup_name",
        "kernel/bpf/verifier.c:check_func_arg",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "drivers/base/driver.c:driver_set_override",
        "drivers/spi/spi.c:__spi_register_driver",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596396736,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597291968,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:385",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:unknown_bootoption",
        "kernel/module/kallsyms.c:module_kallsyms_lookup_name",
        "kernel/bpf/verifier.c:check_reg_const_str",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "kernel/bpf/helpers.c:bpf_bprintf_prepare",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "drivers/base/driver.c:driver_set_override",
        "drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector",
        "drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector",
        "drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector",
        "drivers/gpu/drm/drm_modes.c:drm_mode_parse_command_line_for_connector",
        "drivers/gpu/drm/drm_modes.c:drm_mode_parse_cmdline_named_mode",
        "drivers/spi/spi.c:__spi_register_driver",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597291968,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503863760,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:465",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/security.c:security_setprocattr",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503863760,
      "name": "strnchr",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236491536,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:465",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/security.c:security_setprocattr",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "security/integrity/ima/ima_template_lib.c:ima_show_template_field_data",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236491536,
      "name": "strnchr",
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297722624,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:465",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/security.c:security_setprocattr",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297722624,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279759538,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:465",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/security.c:security_setprocattr",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279759538,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589688240,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:465",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/security.c:security_setprocattr",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589688240,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589414032,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:465",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/security.c:security_setprocattr",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589414032,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590131616,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:465",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/security.c:security_setprocattr",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590131616,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
char * strnchr(const char * s, size_t count, int c)
```

```json
{
  "name": "strnchr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590182000,
      "name": "strnchr",
      "external": true,
      "loc": "lib/string.c:465",
      "file": "lib/string.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/module.c:module_kallsyms_lookup_name",
        "mm/slub.c:kmem_cache_flags",
        "fs/binfmt_script.c:load_script",
        "security/security.c:security_setprocattr",
        "security/apparmor/lib.c:aa_splitn_fqname",
        "lib/kobject_uevent.c:kobject_synth_uevent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590182000,
      "name": "strnchr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
