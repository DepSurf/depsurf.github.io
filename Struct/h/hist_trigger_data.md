# Struct: <code>hist_trigger_data</code>

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
struct hist_trigger_data {
    struct hist_field *[5] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[5] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[5] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[6] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct hist_field *[16] synth_var_refs;
    unsigned int n_synth_var_refs;
    struct field_var *[16] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[16] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[16] max_vars;
    unsigned int n_max_vars;
    unsigned int n_max_var_str;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[16] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[16] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[16] max_vars;
    unsigned int n_max_vars;
    unsigned int n_max_var_str;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[16] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[16] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[16] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[16] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[16] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[16] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[32] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[32] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[32] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int n_var_str;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[32] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[32] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[32] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int n_var_str;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[32] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[32] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[32] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int n_var_str;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[64] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[64] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[64] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int n_var_str;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[64] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[64] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[64] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int n_var_str;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[64] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[64] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[64] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int n_var_str;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[64] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[64] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[64] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int n_var_str;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[64] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[64] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[64] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
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
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[16] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[16] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[16] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
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
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[16] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[16] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[16] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
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
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[16] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[16] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[16] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[16] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[16] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[16] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[16] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[16] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[16] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[16] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[16] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[16] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
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
struct hist_trigger_data {
    struct hist_field *[5] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct hist_field *[5] fields</code> ➡️ <code>struct hist_field *[6] fields</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int n_vars</code>
</li>
<li>
<b>Field added. </b>
<code>bool enable_timestamps</code>
</li>
<li>
<b>Field added. </b>
<code>bool remove</code>
</li>
<li>
<b>Field added. </b>
<code>struct hist_field *[16] var_refs</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int n_var_refs</code>
</li>
<li>
<b>Field added. </b>
<code>struct action_data *[8] actions</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int n_actions</code>
</li>
<li>
<b>Field added. </b>
<code>struct hist_field *[16] synth_var_refs</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int n_synth_var_refs</code>
</li>
<li>
<b>Field added. </b>
<code>struct field_var *[16] field_vars</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int n_field_vars</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int n_field_var_str</code>
</li>
<li>
<b>Field added. </b>
<code>struct field_var_hist *[16] field_var_hists</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int n_field_var_hists</code>
</li>
<li>
<b>Field added. </b>
<code>struct field_var *[16] max_vars</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int n_max_vars</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int n_max_var_str</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct hist_field *[6] fields</code> ➡️ <code>struct hist_field *[22] fields</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field removed. </b>
<code>struct hist_field *[16] synth_var_refs</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int n_synth_var_refs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>struct field_var *[16] save_vars</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int n_save_vars</code>
</li>
<li>
<b>Field added. </b>
<code>unsigned int n_save_var_str</code>
</li>
<li>
<b>Field removed. </b>
<code>struct field_var *[16] max_vars</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int n_max_vars</code>
</li>
<li>
<b>Field removed. </b>
<code>unsigned int n_max_var_str</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct field_var *[16] field_vars</code> ➡️ <code>struct field_var *[32] field_vars</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct field_var_hist *[16] field_var_hists</code> ➡️ <code>struct field_var_hist *[32] field_var_hists</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct field_var *[16] save_vars</code> ➡️ <code>struct field_var *[32] save_vars</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>unsigned int n_var_str</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>struct field_var *[32] field_vars</code> ➡️ <code>struct field_var *[64] field_vars</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct field_var_hist *[32] field_var_hists</code> ➡️ <code>struct field_var_hist *[64] field_var_hists</code>
</li>
<li>
<b>Field type changed. </b>
<code>struct field_var *[32] save_vars</code> ➡️ <code>struct field_var *[64] save_vars</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[16] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[16] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[16] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
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
struct hist_trigger_data {
    struct hist_field *[22] fields;
    unsigned int n_vals;
    unsigned int n_keys;
    unsigned int n_fields;
    unsigned int n_vars;
    unsigned int key_size;
    struct tracing_map_sort_key[2] sort_keys;
    unsigned int n_sort_keys;
    struct trace_event_file * event_file;
    struct hist_trigger_attrs * attrs;
    struct tracing_map * map;
    bool enable_timestamps;
    bool remove;
    struct hist_field *[16] var_refs;
    unsigned int n_var_refs;
    struct action_data *[8] actions;
    unsigned int n_actions;
    struct field_var *[16] field_vars;
    unsigned int n_field_vars;
    unsigned int n_field_var_str;
    struct field_var_hist *[16] field_var_hists;
    unsigned int n_field_var_hists;
    struct field_var *[16] save_vars;
    unsigned int n_save_vars;
    unsigned int n_save_var_str;
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
