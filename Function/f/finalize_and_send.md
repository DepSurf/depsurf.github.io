# Function: <code>finalize_and_send</code>

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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583412672,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1009",
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
      "addr": 18446744071583412672,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 952
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583592336,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1021",
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
      "addr": 18446744071583592336,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583809248,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1038",
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
      "addr": 18446744071583809248,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 977
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583892128,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1038",
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
      "addr": 18446744071583892128,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 972
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584082624,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1090",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584082624,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584205328,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1091",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584205328,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584601920,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1093",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:set_new_pw",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584601920,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584720768,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1093",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:set_new_pw",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584720768,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584748144,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1093",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:set_new_pw",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584748144,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 377
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585176400,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1093",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:set_new_pw",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585176400,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 371
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585912992,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1093",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:set_new_pw",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:revert_tper",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585912992,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586702720,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1133",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:set_new_pw",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586702720,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586964240,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1141",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr_ace",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:set_new_pw",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_columns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964240,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587244592,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1258",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:read_table_data",
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr_ace",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:set_new_pw",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:erase_locking_range",
        "block/sed-opal.c:revert_lsp",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_table_write_data",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_columns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587244592,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 381
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496076240,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1091",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496076240,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 676
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229405156,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1091",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229405156,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 744
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290315584,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1091",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290315584,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 884
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275146686,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1091",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:start_generic_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275146686,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 798
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584174064,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1091",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584174064,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584109312,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1091",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584109312,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584157824,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1091",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584157824,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
```

```json
{
  "name": "finalize_and_send",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584262208,
      "name": "finalize_and_send",
      "external": false,
      "loc": "block/sed-opal.c:1091",
      "file": "block/sed-opal.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/sed-opal.c:activate_lsp",
        "block/sed-opal.c:lock_unlock_locking_range_sum",
        "block/sed-opal.c:lock_unlock_locking_range",
        "block/sed-opal.c:add_user_to_lr",
        "block/sed-opal.c:write_shadow_mbr",
        "block/sed-opal.c:set_mbr_enable_disable",
        "block/sed-opal.c:set_mbr_done",
        "block/sed-opal.c:internal_activate_user",
        "block/sed-opal.c:start_auth_opal_session",
        "block/sed-opal.c:setup_locking_range",
        "block/sed-opal.c:gen_key",
        "block/sed-opal.c:generic_get_column"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584262208,
      "name": "finalize_and_send",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
int finalize_and_send(struct opal_dev * dev, cont_fn * cont)
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
