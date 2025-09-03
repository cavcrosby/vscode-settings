# vscode-settings

Personal VSCode/VSCodium settings that are maintained using
<https://github.com/zokugun/vscode-sync-settings>.

## Usage

1. In VSCode/VSCodium, configure the `vscode-sync-settings` extension to use the
   following remote repository.

   > &gt; Sync Settings: Open the repository settings

   ```yaml
   ---
   profile: linux
   repository:
     type: git
     url: https://github.com/cavcrosby/vscode-settings.git
     branch: main
   ```

2. See <https://github.com/zokugun/vscode-sync-settings#readme> for how to
   download or upload VSCode/VSCodium settings.

## License

See LICENSE[^1].

[^1]: The `profiles/linux/data/additionals/~-.config-VSCodium-User-vsicons-custom-icons-folder_type_systemd.svg` and `profiles/linux/data/additionals/~-.config-VSCodium-User-vsicons-custom-icons-folder_type_systemd_opened.svg` files are licensed under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0) license. Credit goes to [Tobias Bernard](https://tobiasbernard.com/) for the `systemd` logo. Resized from the [original](https://brand.systemd.io/).
