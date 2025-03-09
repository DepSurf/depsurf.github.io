# Function: <code>aa_get_current_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582473286,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:184",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582517042,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:184",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_admin_capable",
        "security/apparmor/policy.c:aa_may_open_profiles"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582526619,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:184",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582542662,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:184",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582568726,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:184",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_audit",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_printk"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582698390,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:184",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582753064,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:184",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582764831,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:184",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582782662,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:184",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582810966,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:184",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582792102,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:184",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582848232,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:184",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582860111,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:184",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582878054,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:184",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582906678,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:184",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582883436,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:223",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_readlink",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582925957,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:223",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582937703,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:223",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582947405,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:223",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071582969928,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:223",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583042860,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:223",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_readlink",
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583085541,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:223",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583097959,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:223",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583111217,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:223",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583133174,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/context.h:223",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583244373,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:164",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583288608,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:164",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583301623,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:164",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583316634,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:164",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583338821,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:164",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583358469,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:180",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583406979,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:180",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583420103,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:180",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583433633,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:180",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583457461,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:180",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583545205,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583592979,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583605879,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583617701,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583643173,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583650885,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583699139,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583712055,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583723877,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583749461,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584011461,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584068007,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584084368,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584107547,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584137637,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct aa_ns * aa_get_current_ns()
```

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584131944,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ]
    },
    {
      "addr": 18446744071584186871,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584203728,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584225979,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584256085,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584130672,
      "name": "aa_get_current_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 402
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct aa_ns * aa_get_current_ns()
```

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584158440,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ]
    },
    {
      "addr": 18446744071584213591,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584230320,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584251547,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584281029,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584157824,
      "name": "aa_get_current_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct aa_ns * aa_get_current_ns()
```

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584542440,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ]
    },
    {
      "addr": 18446744071584598951,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584615968,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584637227,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584667109,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584541824,
      "name": "aa_get_current_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 394
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct aa_ns * aa_get_current_ns()
```

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585191297,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:163",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:p_start"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ]
    },
    {
      "addr": 18446744071585267648,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:163",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071585313744,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:163",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585189072,
      "name": "aa_get_current_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
    },
    {
      "addr": 18446744071585313744,
      "name": "aa_get_current_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct aa_ns * aa_get_current_ns()
```

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585920257,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:163",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:p_start"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ]
    },
    {
      "addr": 18446744071586002109,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:163",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586053232,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:163",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ]
    },
    {
      "addr": 18446744071586094880,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:163",
      "file": "security/apparmor/notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/notify.c:aa_new_listener",
        "security/apparmor/notify.c:aa_register_listener_proxy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585920912,
      "name": "aa_get_current_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
    },
    {
      "addr": 18446744071586053232,
      "name": "aa_get_current_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 476
    },
    {
      "addr": 18446744071586094880,
      "name": "aa_get_current_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct aa_ns * aa_get_current_ns()
```

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586152465,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:163",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:p_start"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ]
    },
    {
      "addr": 18446744071586235277,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:163",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586288272,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:163",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ]
    },
    {
      "addr": 18446744071586333040,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:163",
      "file": "security/apparmor/notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:aa_new_listener",
        "security/apparmor/notify.c:aa_register_listener_proxy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586153104,
      "name": "aa_get_current_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    },
    {
      "addr": 18446744071586288272,
      "name": "aa_get_current_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 472
    },
    {
      "addr": 18446744071586333040,
      "name": "aa_get_current_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 406
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
struct aa_ns * aa_get_current_ns()
```

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586401665,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:163",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:policy_get_link",
        "security/apparmor/apparmorfs.c:p_start"
      ],
      "caller_func": [
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ]
    },
    {
      "addr": 18446744071586488528,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:163",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071586544944,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:163",
      "file": "security/apparmor/label.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
      ]
    },
    {
      "addr": 18446744071586600048,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:163",
      "file": "security/apparmor/notify.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/notify.c:knotif_update_from_uresp_name",
        "security/apparmor/notify.c:aa_new_listener",
        "security/apparmor/notify.c:aa_register_listener_proxy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586402320,
      "name": "aa_get_current_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
    },
    {
      "addr": 18446744071586544944,
      "name": "aa_get_current_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
    },
    {
      "addr": 18446744071586600048,
      "name": "aa_get_current_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 412
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495445244,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495492552,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495505716,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495522104,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446603336495548948,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3228811404,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 3228860040,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 3228873272,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 3228888368,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 3228912616,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289489616,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289556628,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289575016,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289594852,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 13835058055289636708,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274635666,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274676458,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274687782,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274698764,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936274721226,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583619621,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583667875,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583680791,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583692613,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583718197,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583556677,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583604931,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583617847,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583629669,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583655253,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583603397,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583651651,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583664567,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583676389,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583701973,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "aa_get_current_ns",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583700805,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/apparmorfs.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/apparmorfs.c:p_start",
        "security/apparmor/apparmorfs.c:ns_revision_open"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583750055,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/policy.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/policy.c:policy_view_capable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583763209,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/procattr.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/procattr.c:aa_getprocattr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583775579,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/lsm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/lsm.c:apparmor_socket_post_create"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583802229,
      "name": "aa_get_current_ns",
      "external": false,
      "loc": "security/apparmor/include/cred.h:176",
      "file": "security/apparmor/label.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "security/apparmor/label.c:aa_label_printk",
        "security/apparmor/label.c:aa_label_seq_print",
        "security/apparmor/label.c:aa_label_audit"
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
struct aa_ns * aa_get_current_ns()
```
</details>
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
