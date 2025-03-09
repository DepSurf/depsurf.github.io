# Function: <code>aa_proxy_kref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582554336,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:57",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:aa_fs_seq_profile_release",
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582554336,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582794960,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:57",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir",
        "security/apparmor/apparmorfs.c:rawdata_release",
        "security/apparmor/apparmorfs.c:aa_fs_seq_profile_release",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582794960,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582890720,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:57",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:__aa_fs_profile_rmdir",
        "security/apparmor/apparmorfs.c:aa_fs_seq_profile_release",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582890720,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 67
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582961192,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:57",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582961088,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583122800,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:57",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583122800,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583328528,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:57",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583328528,
      "name": "aa_proxy_kref",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583446912,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:57",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583446912,
      "name": "aa_proxy_kref",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583631920,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583631920,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583738096,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583738096,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584125248,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_hash_open",
        "security/apparmor/apparmorfs.c:seq_profile_attach_open",
        "security/apparmor/apparmorfs.c:seq_profile_mode_open",
        "security/apparmor/apparmorfs.c:seq_profile_name_open",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:__label_insert",
        "security/apparmor/label.c:aa_label_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584125248,
      "name": "aa_proxy_kref",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584243968,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_hash_open",
        "security/apparmor/apparmorfs.c:seq_profile_attach_open",
        "security/apparmor/apparmorfs.c:seq_profile_mode_open",
        "security/apparmor/apparmorfs.c:seq_profile_name_open",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584243968,
      "name": "aa_proxy_kref",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584266896,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_hash_open",
        "security/apparmor/apparmorfs.c:seq_profile_attach_open",
        "security/apparmor/apparmorfs.c:seq_profile_mode_open",
        "security/apparmor/apparmorfs.c:seq_profile_name_open",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584266896,
      "name": "aa_proxy_kref",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584652912,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_hash_open",
        "security/apparmor/apparmorfs.c:seq_profile_attach_open",
        "security/apparmor/apparmorfs.c:seq_profile_mode_open",
        "security/apparmor/apparmorfs.c:seq_profile_name_open",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584652912,
      "name": "aa_proxy_kref",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585312816,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_hash_open",
        "security/apparmor/apparmorfs.c:seq_profile_attach_open",
        "security/apparmor/apparmorfs.c:seq_profile_mode_open",
        "security/apparmor/apparmorfs.c:seq_profile_name_open",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585312816,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586052272,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586052272,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586287360,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586287360,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586544016,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:aa_label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586544016,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336495537084,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495536816,
      "name": "aa_proxy_kref",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228902136,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/apparmorfs.c:seq_profile_open",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228901904,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055289620560,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/apparmorfs.c:seq_profile_open",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289620368,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936274711558,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/apparmorfs.c:seq_profile_open",
        "security/apparmor/policy.c:aa_replace_profiles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274711322,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583706832,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583706832,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583643888,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583643888,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583690608,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583690608,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
void aa_proxy_kref(struct kref * kref)
```

```json
{
  "name": "aa_proxy_kref",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583790496,
      "name": "aa_proxy_kref",
      "external": true,
      "loc": "security/apparmor/label.c:53",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/apparmorfs.c:create_profile_file",
        "security/apparmor/apparmorfs.c:seq_profile_release",
        "security/apparmor/policy.c:aa_replace_profiles",
        "security/apparmor/label.c:label_destroy",
        "security/apparmor/label.c:__proxy_share"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583790496,
      "name": "aa_proxy_kref",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
