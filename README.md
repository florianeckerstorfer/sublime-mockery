Mockery Support for Sublime Text 2
==================================

[Mockery](https://github.com/padraic/mockery) support for Sublime Text 3.

By [Florian Eckerstorfer](http://braincrafted.com) ([Twitter](http://twitter.com/braincrafted), [App.net](https://alpha.app.net/braincrafted)).

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

- `msrwo⇥` → `shouldReceive(✎)->with(✎)->once()✎;`
- `msrwoar⇥` → `shouldReceive(✎)->with(✎)->once()->andReturn(✎);`
- `msrwoat⇥` → `shouldReceive(✎)->with(✎)->once()->andThrow(✎);`
- `msrwt⇥` → `shouldReceive(✎)->with(✎)->times(✎)✎;`
- `msrwtar⇥` → `shouldReceive(✎)->with(✎)->times(✎)->andReturn(✎);`
- `msrwtat⇥` → `shouldReceive(✎)->with(✎)->times(✎)->andThrow(✎);`
- `msroar⇥` → `shouldReceive(✎)->once()->andReturn(✎);`
- `msroat⇥` → `shouldReceive(✎)->>once()->andThrow(✎);`
- `msrtar⇥` → `shouldReceive(✎)->times(✎)->andReturn(✎);`
- `msrtat⇥` → `shouldReceive(✎)->times(✎)->andThrow(✎);`
