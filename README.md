# StreamerBot_CSharp
Collection of functionality extensions I've created for Streamer.bot written in C#.

**Import Codes**

*Advanced OBS Clipper*

This leverages OBS Studio's ReplayBuffer feature to create high quality clips via a Streamer.bot sub-action. Using this function, your chat will be able to created clips directly from chat and their comment.

```!clip Fancy name for a clip``` becomes ```Fancy name for a clip (clipped by HYP3RSTRIKE).mkv```

Assign it to a command, and edit the two file location variables atop of the document.

```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```
