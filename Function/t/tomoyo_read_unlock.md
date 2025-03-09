# Function: <code>tomoyo_read_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595200155,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_load_builtin_policy",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_check_profile"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582446688,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path_number_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path2_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582455633,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582456412,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582461818,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582463469,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582653610,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582670597,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582677857,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582678652,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582683722,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582685709,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582746666,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582763653,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582770929,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582771724,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582776762,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582778749,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1107",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582839006,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1109",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582856167,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1109",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582863345,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1109",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582864586,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1109",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582869103,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1109",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582871280,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1109",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582995854,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1111",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583013111,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1111",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583020289,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1111",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583021258,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1111",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583026079,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1111",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583028256,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1111",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583196374,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1108",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583213560,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1108",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583220865,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1108",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583221627,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1108",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583226577,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1108",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583228674,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1108",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583312854,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1111",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583330504,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1111",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583337937,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1111",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583338699,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1111",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583343649,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1111",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583345805,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1111",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583500206,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583517915,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583525377,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583526606,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583531520,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583533333,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583606126,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583623803,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583631265,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583632494,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583637280,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583639093,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583962878,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583980811,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583988513,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583989758,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_inet_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583994608,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583996453,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584082734,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584100619,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584108193,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584109438,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_inet_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584114197,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584116037,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584110542,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584128219,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584135713,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584136958,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584141653,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584143493,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584491007,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584510407,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584518801,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584520769,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584525470,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584527317,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
void tomoyo_read_unlock(int idx)
```

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585126111,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control"
      ],
      "caller_func": [
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ]
    },
    {
      "addr": 18446744071585148280,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585157125,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585159300,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585164536,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585166813,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585100112,
      "name": "tomoyo_read_unlock",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585850571,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585873656,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585882933,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585885300,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585890872,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585893645,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586082555,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586105528,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586114885,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586117204,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586122760,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586125536,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1120",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586331659,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1118",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586354824,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1118",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586364181,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1118",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586366500,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1118",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry",
        "security/tomoyo/network.c:tomoyo_check_inet_address"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586372056,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1118",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586374832,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1118",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495389140,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495408104,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495417848,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495419552,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495425220,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495428148,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228761936,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 3228779288,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 3228787824,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 3228789340,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 3228795032,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 3228797460,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289411572,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289441484,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289454036,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289456136,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289464708,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289467960,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274591020,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274606370,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274614526,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274615826,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274620524,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274622854,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583574862,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583592539,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583600001,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583601230,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583606016,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583607829,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583511918,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583529595,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583537057,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583538286,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583543072,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583544885,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583558638,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583576315,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583583777,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583585006,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583589792,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583591605,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tomoyo_read_unlock",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583655710,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/common.c:tomoyo_check_profile",
        "security/tomoyo/common.c:tomoyo_write_control",
        "security/tomoyo/common.c:tomoyo_read_control",
        "security/tomoyo/common.c:tomoyo_load_builtin_policy"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583673483,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/file.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/file.c:tomoyo_path2_perm",
        "security/tomoyo/file.c:tomoyo_mkdev_perm",
        "security/tomoyo/file.c:tomoyo_path_perm",
        "security/tomoyo/file.c:tomoyo_check_open_permission",
        "security/tomoyo/file.c:tomoyo_path_number_perm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583680865,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/mount.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/mount.c:tomoyo_mount_permission"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583682094,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/network.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/network.c:tomoyo_unix_entry"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583686880,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/securityfs_if.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/tomoyo/securityfs_if.c:tomoyo_write_self"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583688693,
      "name": "tomoyo_read_unlock",
      "external": false,
      "loc": "security/tomoyo/common.h:1121",
      "file": "security/tomoyo/tomoyo.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void tomoyo_read_unlock(int idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void tomoyo_read_unlock(int idx)
```
</details>
</li>
</ul>
