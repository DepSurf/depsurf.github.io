# Function: <code>clear_opal_cmd</code>

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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583411360,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:959",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:gen_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583411360,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583590976,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:971",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:gen_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583590976,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583807840,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:988",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:gen_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583807840,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583890720,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:988",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:get_msid_cpin_pin",
        "block/sed-opal.c:get_lsp_lifecycle",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:generic_pw_cmd",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:get_active_key",
        "block/sed-opal.c:gen_key"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583890720,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584079648,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1019",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584079648,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584202336,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1018",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584202336,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584603247,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1020",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584722095,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1020",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584749471,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1020",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585177727,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1020",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585910704,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1020",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585910704,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586699088,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1060",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586699088,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586960016,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1068",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586960016,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587240272,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1185",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587240272,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496072008,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1018",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496072008,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229400220,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1018",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229400220,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290311136,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1018",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290311136,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936275148748,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1018",
      "file": "block/sed-opal.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584171072,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1018",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584171072,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584106320,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1018",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584106320,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584154832,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1018",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584154832,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void clear_opal_cmd(struct opal_dev * dev)
```

```json
{
  "name": "clear_opal_cmd",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584259216,
      "name": "clear_opal_cmd",
      "external": false,
      "loc": "block/sed-opal.c:1018",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:cmd_start"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584259216,
      "name": "clear_opal_cmd",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void clear_opal_cmd(struct opal_dev * dev)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void clear_opal_cmd(struct opal_dev * dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void clear_opal_cmd(struct opal_dev * dev)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void clear_opal_cmd(struct opal_dev * dev)
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
