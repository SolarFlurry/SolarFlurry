# hello...

i use nvim btw

programming languages i like
- Zig
- C
- TypeScript
- C++ (std too confusing, decades of accumulated mistakes)
- Rust (allocation unconscious, annoying `Box`'s, easy to write inefficient code)

what could i be doing right now...

- being lazy
- working on a programming language
- creating a game
- minecraft redstone computer
- making a discord bot
- learning complex & quaternions


my favourite license is GPLv3, i use it in basically all projects, sometimes MIT

```zig
const std = @import("std");

pub fn main(init: std.process.Init) !void {
  // dependency injection of a std.Io.Writer, this is a good practice
  var stdout = std.Io.File.stdout().writer(init.io, &.{});
  const writer = &stdout.interface;

  try writer.print("radnom zig code lol\n");
  try writer.print("also to whoever's reading this, please try zig, it's an amazing language not enough people know\n");
}
```

if only zig used `let` and `let mut` instead of `const` and `var`... thats why im making [this programming language](https://github.com/SolarFlurry/wyrm-lang/)!

read [this](https://zig.guide)

if you want to collaborate:
- [Discord](https://discord.com/channels/@me)
- [Scratch..?](https://scratch.mit.edu/users/SolarFlurry)

<!---
SolarFlurry/SolarFlurry is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
