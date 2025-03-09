# Function: <code>security_compute_av</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void security_compute_av(u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582351376,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1084",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582351376,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 689
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
void security_compute_av(u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582572368,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1078",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582572368,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 710
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
void security_compute_av(u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582665568,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1078",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582665568,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 721
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
void security_compute_av(u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582758176,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1090",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582758176,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 711
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
void security_compute_av(u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582914192,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1095",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582914192,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 711
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1109",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583124620,
      "name": "security_compute_av.cold.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583112416,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 644
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1106",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583240770,
      "name": "security_compute_av.cold.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583228400,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1092",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583427803,
      "name": "security_compute_av.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583415088,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 671
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
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1092",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583533709,
      "name": "security_compute_av.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583520992,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 671
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
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1099",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583883076,
      "name": "security_compute_av.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583871360,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 419
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
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1108",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591366559,
      "name": "security_compute_av.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583992320,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 370
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
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1110",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591309505,
      "name": "security_compute_av.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071584018976,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 643
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
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1112",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592300125,
      "name": "security_compute_av.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071584388592,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 403
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
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1110",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594081634,
      "name": "security_compute_av.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    },
    {
      "addr": 18446744071585014464,
      "name": "security_compute_av",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1104",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596096762,
      "name": "security_compute_av.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585730416,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 474
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void security_compute_av(u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1095",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596619965,
      "name": "security_compute_av.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071585961232,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void security_compute_av(u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1095",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597525635,
      "name": "security_compute_av.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586210080,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 471
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
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495287968,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1092",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495287968,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 828
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
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228670348,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1092",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228670348,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 696
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
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289272112,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1092",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289272112,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1020
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
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274511234,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1092",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274511234,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 608
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1092",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583502445,
      "name": "security_compute_av.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583489728,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 671
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
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1092",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583439501,
      "name": "security_compute_av.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583426800,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 671
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
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1092",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583486221,
      "name": "security_compute_av.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583473504,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 671
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
void security_compute_av(struct selinux_state * state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision * avd, struct extended_perms * xperms)
```

```json
{
  "name": "security_compute_av",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "security_compute_av",
      "external": true,
      "loc": "security/selinux/ss/services.c:1092",
      "file": "security/selinux/ss/services.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/avc.c:avc_compute_av"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583582585,
      "name": "security_compute_av.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071583569664,
      "name": "security_compute_av",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 669
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_state * state</code>
</li>
<li>
<b>Param reordered. </b>
<code>ssid, tsid, orig_tclass, avd, xperms</code> ➡️ <code>state, ssid, tsid, orig_tclass, avd, xperms</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state * state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, ssid, tsid, orig_tclass, avd, xperms</code> ➡️ <code>ssid, tsid, orig_tclass, avd, xperms</code>
</li>
</ul>
</details>
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
