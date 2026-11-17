Wind Client
Wind Client is a free Minecraft: Java Edition launcher and client for Windows, developed by Nyraa.
> Status: early development (prototype). Not yet released.
What it is
A launcher for Minecraft: Java Edition versions 1.8 to 26.3.
Support for Vanilla, Fabric, Forge, NeoForge and Quilt (in development).
Instance management, mod discovery and installation (in development).
Free and non-commercial.
Sign-in and security
Players sign in with their own Microsoft account, in a window that loads Microsoft's official sign-in page (OAuth 2.0 authorization code flow with PKCE). Wind Client never sees or stores passwords.
The app requests the `XboxLive.signin` scope to authenticate with Xbox Live and Minecraft services, then verifies through the official Minecraft services API that the account owns Minecraft: Java Edition.
No offline mode, no cracked accounts, no license bypass.
Refresh tokens are stored only in the Windows Credential Manager. Access tokens are kept in memory only. Logs never contain tokens.
Roadmap
Interface and launcher foundation — done (prototype)
Microsoft account sign-in — implemented, awaiting Minecraft API approval
Version management and game launching
Mod management and content browser
Instances
Later: updates, community, cosmetics
Contact
Developer: Nyraa
Application name: Wind Client
Wind Client is not an official Minecraft product and is not approved by or associated with Mojang or Microsoft.
