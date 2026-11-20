# TextTransform Releases

Official Windows installers for TextTransform.

## Latest version: 1.0.17

[Download TextTransform for Windows](https://github.com/Doma-Sapiens/texttransform-releases/releases/latest/download/TextTransformSetup.exe)

[Release notes and SHA-256 checksums](https://github.com/Doma-Sapiens/texttransform-releases/releases/tag/v1.0.17)

Version 1.0.17 restores automatic selected-text replacement in editable Chromium/Electron fields, preserves the original clipboard after confirmed delivery, and avoids unnecessary previews when layout correction leaves the text unchanged. Keep the original field and selection while a command is processing.

Known issue: cold capture can still fail with InputSourceUnavailable. The failed installed cold-start check is recorded in the release validation report; physical Slack acceptance of this package remains pending.

System, Light and Dark appearance modes remain available. Recording stops automatically at the ten-minute limit, and the completed dictation result is also kept in the clipboard. Informational dialogs have one OK action.

Anonymous aggregate counts for completed setup, first launch and the first successful result can be disabled in General settings. No text, API keys, email or user/device identifiers are sent.

The release also includes TextTransformSetup-Yandex.exe: the same application/version with a shared campaign source label. The website chooses this variant for the matching advertising link. This label is identical for everyone using that installer; it is not an individual identifier.

Installers are unsigned while the app is in early release, so Windows or Chrome may show a warning. Previous releases remain available in the release history.
