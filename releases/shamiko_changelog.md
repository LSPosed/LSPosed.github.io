#### 0.3.0
1. Support whitelist (enable by creating an empty file `/data/adb/shamiko/whitelist`)
1. Always unshare (useful for old platforms and isolated processes in new platforms)
1. Request Magisk 23017+, which allows us to strip Java daemon and change denylist regardless of enforcement status
1. Temporarily disable showing status in module description (need to find a new way for it)
1. Support module update since Magisk 23017
