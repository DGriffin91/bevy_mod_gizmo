# bevy_mod_gizmos

## An external version of the [bevy_gizmos plugin](https://github.com/bevyengine/bevy/pull/6529) for bevy 0.10.
This crate will be deprecated and replaced by the included plugin in Bevy 0.11

If the gizmos plugin in the bevy main branch is updated, this plugin may also be updated. It is recommended to reference a specific commit when including in Cargo.toml.

```toml
[dependencies]
bevy_mod_gizmos = { git = "https://github.com/DGriffin91/bevy_mod_gizmo", commit = "81fe53caa1f777b3c0c9396d81b28ad166f3c6fe" }
bevy = "0.10"
```