# Knighty's Bricks Analytics — update channel

This public repository is used only to distribute Windows application updates.
The application source code, Bricqer credentials, and inventory database remain
in the separate private source repository and on the user's computers.

Releases must contain the file `Knightys-Bricks-Analytics-Windows.zip`.
The app checks the latest GitHub Release and installs only when GitHub exposes a
SHA-256 digest for that asset. Updates replace only the application executable;
the Documents database, OneDrive snapshot, and Windows Credential Manager are
not modified.

Do not upload source code, inventory exports, API keys, or customer information.
