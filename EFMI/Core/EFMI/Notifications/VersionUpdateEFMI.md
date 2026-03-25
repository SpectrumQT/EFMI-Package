Compatibility Warning

Starting with XXMI DLL 0.8.5, the Region Hashes system has changed in a non-backwards compatible way:

- All [TextureOverride] sections using IB hashes must now include a `match_index_count` value.

To fix most mods automatically, run Gustav0's auto-patcher in your Mods folder:
- https://gamebanana.com/tools/22185

This change prevents overly broad hash matching to reduce CPU usage peaks by up to 100 times.

For mod creators: You can now view the index count of the selected IB in Shader Hunting Mode.

Press F10 to hide this message