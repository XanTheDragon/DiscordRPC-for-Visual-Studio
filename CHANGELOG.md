# Changelog

## [v5.1] (23-6-2019)

**CHANGES**
- Code cleanup.
- Added Rust, TOML and Lua.
- Fixed icons being cut off.

**BUGS FIXED**
- Fixed extension crashing on Visual Studio 2017.

## [v5] (6-6-2019)

**CHANGES**
- Added language formatting, proper name will be shown as text.
- Code cleanup.
- Text document icon will now display instead of Visual Studio icon when editing a file that is not supported.

**BUGS FIXED**
- Visual Studio crashes on disable.

## [v4.14] (1-6-2019)

**CHANGES**
- Added cshtml and razor file types.

## [v4] (18-5-2019)

**CHANGES**
- Now using lachee's [Discord Rich Presence library](https://github.com/lachee/discord-rpc-csharp)!
- New improved icons.
- More file types.
- Optimized code.

## [v3.1] (15-5-2019)

**BUGS FIXED**
- Rich Presence timestamp will reset on settings change.

## [v3] (14-5-2019)

**CHANGES (COMPLETE REWRITE)**

- New settings window, for faster settings change.
- Project now initializes the rich presence for the current document on startup.
- Removed unnessesary assigning of null presence on startup.
- Made installer better.
- Added installer icon.
- Better presence icons.

**BUGS FIXED**

- Rich Presence will stop working after switching to a non-editor window.