# Function: <code>setup_APIC_eilvt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579185984,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:421",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185984,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 348
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
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579186256,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:429",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579186256,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579197760,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:430",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579197760,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 357
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
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579196016,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:432",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579196016,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 340
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
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579211168,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:423",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579211168,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 346
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
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579224176,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:424",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mcheck/mce_amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579224176,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579247856,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:430",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579247856,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:431",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266558,
      "name": "setup_APIC_eilvt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071579261872,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:431",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268211,
      "name": "setup_APIC_eilvt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071579263456,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:429",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579295910,
      "name": "setup_APIC_eilvt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071579290256,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:435",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591259662,
      "name": "setup_APIC_eilvt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071579296320,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 306
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:435",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591202715,
      "name": "setup_APIC_eilvt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071579298912,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 305
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:432",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592073711,
      "name": "setup_APIC_eilvt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579346400,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:441",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593839918,
      "name": "setup_APIC_eilvt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071579405856,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579486864,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:442",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:setup_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579486864,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
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
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579498928,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:444",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:setup_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579498928,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 533
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
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579528992,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:411",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu",
        "arch/x86/events/amd/ibs.c:perf_ibs_suspend",
        "arch/x86/events/amd/ibs.c:setup_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579528992,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 511
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:431",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579266915,
      "name": "setup_APIC_eilvt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071579262160,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:431",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579202336,
      "name": "setup_APIC_eilvt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071579197520,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:431",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579268115,
      "name": "setup_APIC_eilvt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071579263360,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```

```json
{
  "name": "setup_APIC_eilvt",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "setup_APIC_eilvt",
      "external": true,
      "loc": "arch/x86/kernel/apic/apic.c:431",
      "file": "arch/x86/kernel/apic/apic.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/events/amd/ibs.c:amd_ibs_init",
        "arch/x86/events/amd/ibs.c:clear_APIC_ibs",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/events/amd/ibs.c:force_ibs_eilvt_setup",
        "arch/x86/kernel/cpu/mce/amd.c:mce_amd_feature_init",
        "arch/x86/kernel/cpu/mce/amd.c:prepare_threshold_block"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273715,
      "name": "setup_APIC_eilvt.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071579268960,
      "name": "setup_APIC_eilvt",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 307
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int setup_APIC_eilvt(u8 offset, u8 vector, u8 msg_type, u8 mask)
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
