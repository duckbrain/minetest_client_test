# minetest_client_test

A minetest mod for testing the client-side mods being added to minetest

- The branch can be found [in my fork](https://github.com/duckbrain/minetest/tree/feature/client-mods).
- [Pull Reqest](https://github.com/minetest/minetest/pull/4577)
- You must enable the feature in **both the client *and* the server**
  - Settings
  - Advanced Settings
  - Client and Server
  - Advanced
  - Enable Client-side Mods
  - Edit
  - Enabled
  - Save

If it works you should get the following in your stdout.
  
```
Hello from the client side
It's so nice to be included
```
