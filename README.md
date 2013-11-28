Mockery Support for Sublime Text
================================

[Mockery](https://github.com/padraic/mockery) support for Sublime Text 2 and 3.

Author
------

- [Florian Eckerstorfer](http://florian.ec) ([Twitter](http://twitter.com/Florian_), [App.net](https://alpha.app.net/florian)).

Snippets
--------

- `usem⇥` → `use \Mockery as m;`
- `mm⇥` → `m::mock(✎);`
- `mc⇥` → `m::close();`
- `msr⇥` → `shouldReceive(✎)`
- `mw⇥` → `with(✎)`
- `mw2⇥` → `with(✎, ✎)`
- `mw3⇥` → `with(✎, ✎, ✎)`
- `mw?⇥` → `withAnyArgs()`
- `mw0⇥` → `withNoArgs()`
- `mo⇥` → `once()`
- `mtw⇥` → `twice()`
- `mz+⇥` → `zeroOrMoreTimes()`
- `mt⇥` → `times(✎)`
- `mal⇥` → `atLeast()`
- `mal1⇥` → `atLeast()->once()`
- `mal2⇥` → `atLeast()->twice()`
- `malt⇥` → `atLeast()->times(✎)`
- `mam⇥` → `atMost()`
- `mam1⇥` → `atMost()->once()`
- `mam2⇥` → `atMost()->twice()`
- `mamt⇥` → `atMost()->times(✎)`
- `mar⇥` → `andReturn(✎)`
- `mat⇥` → `andThrow(✎)`

### Combined Snippets

- `msroar⇥` → `shouldReceive(✎)->once()->andReturn(✎);`
- `msroat⇥` → `shouldReceive(✎)->>once()->andThrow(✎);`
- `msrtar⇥` → `shouldReceive(✎)->times(✎)->andReturn(✎);`
- `msrtat⇥` → `shouldReceive(✎)->times(✎)->andThrow(✎);`
- `msrw?o⇥` → `shouldReceive(✎)->withAnyArgs()->once()✎;`
- `msrw?oar⇥` → `shouldReceive(✎)->withAnyArgs()->once()->andReturn(✎);`
- `msrw?oat⇥` → `shouldReceive(✎)->withAnyArgs()->once()->andThrow(✎);`
- `msrw?t⇥` → `shouldReceive(✎)->withAnyArgs()->times(✎)✎;`
- `msrw?tar⇥` → `shouldReceive(✎)->withAnyArgs()->times(✎)->andReturn(✎);`
- `msrw?tat⇥` → `shouldReceive(✎)->withAnyArgs()->times(✎)->andThrow(✎);`
- `msrw0o⇥` → `shouldReceive(✎)->withNoArgs()->once()✎;`
- `msrw0oar⇥` → `shouldReceive(✎)->withNoArgs()->once()->andReturn(✎);`
- `msrw0oat⇥` → `shouldReceive(✎)->withNoArgs()->once()->andThrow(✎);`
- `msrw0t⇥` → `shouldReceive(✎)->withNoArgs()->times(✎)✎;`
- `msrw0tar⇥` → `shouldReceive(✎)->withNoArgs()->times(✎)->andReturn(✎);`
- `msrw0tat⇥` → `shouldReceive(✎)->withNoArgs()->times(✎)->andThrow(✎);`
- `msrwo⇥` → `shouldReceive(✎)->with(✎)->once()✎;`
- `msrwoar⇥` → `shouldReceive(✎)->with(✎)->once()->andReturn(✎);`
- `msrwoat⇥` → `shouldReceive(✎)->with(✎)->once()->andThrow(✎);`
- `msrwt⇥` → `shouldReceive(✎)->with(✎)->times(✎)✎;`
- `msrwtar⇥` → `shouldReceive(✎)->with(✎)->times(✎)->andReturn(✎);`
- `msrwtat⇥` → `shouldReceive(✎)->with(✎)->times(✎)->andThrow(✎);`
