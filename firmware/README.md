# Firmware

This directory is reserved for the ESP32 firmware source code.

The original source file should be added after review. Before committing it:

1. Move Wi-Fi credentials, Firebase credentials, and other private values into a local secrets header (for example, `secrets.h`).
2. Commit only a sanitized example template such as `secrets.example.h`, containing placeholders.
3. Confirm that no passwords, tokens, private URLs, or personal data remain in the source or commit history.
4. Review sensor calibration constants, timeout behavior, relay logic, and electrical safety assumptions.
5. Record the board configuration and required Arduino libraries.

Do not upload real credentials to this repository.
