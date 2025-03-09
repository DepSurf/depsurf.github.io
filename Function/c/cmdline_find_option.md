# Function: <code>cmdline_find_option</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588815280,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:210",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588815280,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 494
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589193440,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:210",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589193440,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589434896,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:210",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589434896,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589892896,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:209",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589892896,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590118848,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:209",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590118848,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585122480,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:209",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_parse_early_param",
        "arch/x86/kernel/cpu/bugs.c:ssb_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/intel.c:split_lock_setup",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/crash.c:crash_reserve_low_1M",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585122480,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585273040,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:209",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/bugs.c:ssb_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/intel.c:split_lock_setup",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/crash.c:crash_reserve_low_1M",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585273040,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 465
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585156576,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:209",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation",
        "arch/x86/kernel/cpu/intel.c:sld_setup",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/kernel/crash.c:crash_reserve_low_1M",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585156576,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585609424,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:209",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/intel.c:sld_state_setup",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585609424,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586766112,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:209",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/intel.c:sld_state_setup",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586766112,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595930880,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:209",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/intel.c:sld_state_setup",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595930880,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596449200,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:211",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/intel.c:sld_state_setup",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596449200,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597344560,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:211",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/common.c:cpu_parse_early_param",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline",
        "arch/x86/kernel/cpu/bugs.c:spectre_v2_user_select_mitigation",
        "arch/x86/kernel/cpu/intel.c:sld_state_setup",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597344560,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589721104,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:209",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589721104,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589446880,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:209",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589446880,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590164480,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:209",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590164480,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```

```json
{
  "name": "cmdline_find_option",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590214992,
      "name": "cmdline_find_option",
      "external": true,
      "loc": "arch/x86/lib/cmdline.c:209",
      "file": "arch/x86/lib/cmdline.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/bugs.c:check_bugs",
        "arch/x86/kernel/cpu/tsx.c:tsx_init",
        "arch/x86/mm/pti.c:pti_check_boottime_disable",
        "arch/x86/mm/mem_encrypt_identity.c:sme_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590214992,
      "name": "cmdline_find_option",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 464
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
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int cmdline_find_option(const char * cmdline, const char * option, char * buffer, int bufsize)
```
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
