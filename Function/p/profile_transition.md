# Function: <code>profile_transition</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct aa_label * profile_transition(struct aa_profile * profile, const char * name, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582496080,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:490",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582496080,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2398
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582729728,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:490",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582729728,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3071
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582824464,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:490",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582824464,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3404
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582910912,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:488",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582910912,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2009
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583069216,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:509",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583069216,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2334
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583271680,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:617",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271680,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2242
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389552,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:617",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389552,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2270
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583576496,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:613",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583576496,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2138
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583682752,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:617",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583682752,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2148
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584046896,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:622",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584046896,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2403
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584166048,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:622",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584166048,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2494
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584192960,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:624",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584192960,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2479
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:624",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584578016,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2530
    },
    {
      "addr": 18446744071592305504,
      "name": "profile_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:623",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585225008,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2430
    },
    {
      "addr": 18446744071594086811,
      "name": "profile_transition.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
struct aa_label * profile_transition(const struct cred * subj_cred, struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585957648,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:629",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585957648,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2399
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
struct aa_label * profile_transition(const struct cred * subj_cred, struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586190416,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:629",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586190416,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2627
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
struct aa_label * profile_transition(const struct cred * subj_cred, struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586441840,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:636",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:apparmor_bprm_creds_for_exec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586441840,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 3103
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495477168,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:617",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495477168,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1976
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228843656,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:617",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228843656,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2148
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289535152,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:617",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289535152,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2676
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274663398,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:617",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274663398,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1718
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583651488,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:617",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583651488,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2148
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583588544,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:617",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583588544,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2148
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583635264,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:617",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583635264,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2148
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
struct aa_label * profile_transition(struct aa_profile * profile, const struct linux_binprm * bprm, char * buffer, struct path_cond * cond, bool * secure_exec)
```

```json
{
  "name": "profile_transition",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583733472,
      "name": "profile_transition",
      "external": false,
      "loc": "security/apparmor/domain.c:617",
      "file": "security/apparmor/domain.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:apparmor_bprm_set_creds",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec",
        "security/apparmor/domain.c:handle_onexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583733472,
      "name": "profile_transition",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2307
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
<summary>Changed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct linux_binprm * bprm</code>
</li>
<li>
<b>Param added. </b>
<code>char * buffer</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * name</code>
</li>
<li>
<b>Param reordered. </b>
<code>profile, name, cond, secure_exec</code> ➡️ <code>profile, bprm, buffer, cond, secure_exec</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cred * subj_cred</code>
</li>
<li>
<b>Param reordered. </b>
<code>profile, bprm, buffer, cond, secure_exec</code> ➡️ <code>subj_cred, profile, bprm, buffer, cond, secure_exec</code>
</li>
</ul>
</details>
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
