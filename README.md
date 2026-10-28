# hello...

i use nvim btw

you can view my dotfiles [here](https://github.com/SolarFlurry/dotfiles)

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
  try writer.print("hello, why are you even reading this? thanks for checking out my profile\n");
}
```

more active projects:
- [vacite scripting lang](https://github.com/SolarFlurry/vacite)!
- [wyrm programming lang](https://github.com/SolarFlurry/wyrm-lang/)!
- [fintui](https://github.com/fintui)!

<!---
SolarFlurry/SolarFlurry is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
