# Struct: <code>hist_trigger_attrs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    bool pause;
    bool cont;
    bool clear;
    unsigned int map_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    bool pause;
    bool cont;
    bool clear;
    unsigned int map_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    bool pause;
    bool cont;
    bool clear;
    unsigned int map_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    bool pause;
    bool cont;
    bool clear;
    unsigned int map_bits;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    bool no_hitcount;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    bool no_hitcount;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    bool no_hitcount;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
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
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
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
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    bool pause;
    bool cont;
    bool clear;
    unsigned int map_bits;
}
```
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>char * clock</code>
</li>
<li>
<b>Field added. </b>
<code>bool ts_in_usecs</code>
</li>
<li>
<b>Field added. </b>
<code>char *[16] assignment_str</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int n_assignments</code>
</li>
<li>
<b>Field added. </b>
<code>char *[8] action_str</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int n_actions</code>
</li>
<li>
<b>Field added. </b>
<code>struct var_defs var_defs</code>
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
<details>
<summary>Changed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool no_hitcount</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct hist_trigger_attrs {
    char * keys_str;
    char * vals_str;
    char * sort_key_str;
    char * name;
    char * clock;
    bool pause;
    bool cont;
    bool clear;
    bool ts_in_usecs;
    unsigned int map_bits;
    char *[16] assignment_str;
    unsigned int n_assignments;
    char *[8] action_str;
    unsigned int n_actions;
    struct var_defs var_defs;
}
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
