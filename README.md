# CiCe
CiCe is a C# library you can use to make your own programs that interact with the A/B feature experiment mechanism found in Windows 10 & newer.
Why CiCe? Because of the meme

The *FeatureManager* class should cover most feature management needs with the added benefit of some struct heavy lifting being done for you. Boot persistence and LKG management is offered exclusively by this class as it had to be reimplemented.

In case you'd like to talk to NTDLL exports directly, you can use *NativeMethods*.

# CiCeTool
CiCeTool is both an example of how to use CiCe, as well as a straightforward tool for power users which want to use the new APIs instantly.

[![Release downloads](https://img.shields.io/github/downloads/thebookisclosed/ViVe/total.svg)](https://GitHub.com/thebookisclosed/ViVe/releases/)

# Compatibility
In order to use CiCe, you must be running Windows 10 build 18963 or newer.

![ViVeTool Helpfile](https://i.imgur.com/PzCHEUQ.png)
