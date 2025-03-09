# Function: <code>aa_dfa_match</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582488096,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:377",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:match_mnt",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/mount.c:aa_pivotroot",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582488096,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582720944,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:381",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582720944,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582815600,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:381",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582815600,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 182
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582903360,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:381",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582903360,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583061472,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:381",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583061472,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583262528,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:444",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583262528,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583380384,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:444",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583380384,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583567120,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:440",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583567120,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672848,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:455",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672848,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584035584,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:479",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:leftmatch_fb",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584035584,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584154832,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:479",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:leftmatch_fb",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584154832,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584181888,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:479",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:leftmatch_fb",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584181888,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584566912,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:479",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:leftmatch_fb",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/file.c:profile_path_link",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584566912,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585212528,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:479",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/ipc.c:aa_profile_mqueue_perm",
        "security/apparmor/match.c:leftmatch_fb",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585212528,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585944624,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:479",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/ipc.c:aa_profile_mqueue_perm",
        "security/apparmor/match.c:leftmatch_fb",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585944624,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586177072,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:435",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/ipc.c:aa_profile_mqueue_perm",
        "security/apparmor/match.c:leftmatch_fb",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/notify.c:notification_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586177072,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586428352,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:435",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/ipc.c:aa_profile_mqueue_perm",
        "security/apparmor/match.c:leftmatch_fb",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_components_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/domain.c:label_compound_match",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_components_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/label.c:label_compound_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:profile_umount",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/mount.c:do_match_mnt",
        "security/apparmor/notify.c:notification_match"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586428352,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495467376,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:455",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495467376,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3228833960,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:455",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch",
        "security/apparmor/match.c:aa_dfa_leftmatch",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228833960,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055289521216,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:455",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch",
        "security/apparmor/match.c:aa_dfa_leftmatch",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289521216,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 392
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936274654724,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:455",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274654724,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583641584,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:455",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583641584,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583578640,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:455",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583578640,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583625360,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:455",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583625360,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
unsigned int aa_dfa_match(struct aa_dfa * dfa, unsigned int start, const char * str)
```

```json
{
  "name": "aa_dfa_match",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583723424,
      "name": "aa_dfa_match",
      "external": true,
      "loc": "security/apparmor/match.c:455",
      "file": "security/apparmor/match.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/match.c:aa_dfa_leftmatch",
        "security/apparmor/file.c:aa_str_perms",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/label.c:aa_label_match",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:build_pivotroot",
        "security/apparmor/mount.c:aa_umount",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/mount.c:match_mnt_path_str",
        "security/apparmor/af_unix.c:aa_unix_peer_perm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583723424,
      "name": "aa_dfa_match",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
